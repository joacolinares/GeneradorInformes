# Generador de Informes Automáticos con OpenAI

Este script permite generar informes en formato Word automáticamente a partir de un tema ingresado por el usuario. 

##  Instalación

1. Clonar el repositorio:
git clone https://github.com/joacolinares/GeneradorInformes  

2. Crear un entorno virtual y activarlo:

# Linux/macOS
python -m venv venv
source venv/bin/activate

# Windows
python -m venv venv
venv\Scripts\activate

3. Instalar dependencias:

pip install -r requirements.txt


## Uso

Ejecutar el siguiente comando:

python main.py --tema "Tema a elección"

Esto generará un archivo Word con el informe.

##  Requisitos

- Python 3.x
- API Key de OpenAI (se debe configurar en `main.py`)
