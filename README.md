#  MARS-ROVER-PHOTOS - API
Este es un proyecto de ejemplo utilizando Flask para crear una aplicación web que interactúa con la API Mars Rover Photos de la NASA.

## Requisitos

Antes de ejecutar esta aplicación, asegúrate de tener instalado Python y pip en tu sistema. También, se recomienda crear y activar un entorno virtual para el proyecto. Si usas Linux debes tener python3-venv instalado.

```bash
sudo apt-get install python3-venv
```

### Entorno virtual

1. Clona el repositorio
```bash
git clone https://github.com/Uma347/mars-rover-photos-api.git
```
2. `cd` ingresa en el nuevo directorio
```bash
cd mars-rover-photos-api
```
3. Crea un nuevo entorno virtual `env` en el directorio
```bash
python -m venv venv
```
4. Activa en nuevo entorno en Windows 
```bash
.\venv\Scripts\Activate
```
   En Linux
```bash
source venv/bin/activate
```
5. Instala las dependencias en el entorno
```bash
pip install -r requirements.txt
```
6. Copia las variables de entorno
```bash
cp .env.sample .env
```
7. Cambia el valor de API_KEY en el archivo .env, si no lo tienes lo puedes conseguir [aqui](https://api.nasa.gov/)

8. Corre la aplicación
```bash
python app.py
