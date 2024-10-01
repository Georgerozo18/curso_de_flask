# Opción 1: Correr el servidor
```bash
flask --app main run
```

# Opción 2: Configurar variable de entorno `FLASK_APP`
```bash
$env:FLASK_APP="main"
flask run
```

# Opción 3: Utilizar un archivo .env 
```bash
pip install python-dotenv
```
Crear un archivo `.env` en la raiz del proyecto con el siguiente contenido:

```bash
FLASK_APP=main
```