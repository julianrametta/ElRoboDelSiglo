# ElRoboDelSiglo
Este proyecto contiene el desarrollo de un proyecto de ciencia de datos basado en detección de sitios web fraudulentos de la Argentina.

## Requerimientos

* Instalar miniconda *latest* version

    * ▶️ En Windows:
    1. Ir a la página oficial: https://docs.conda.io/en/latest/miniconda.html

    2. Descargar y ejecutar instalador para Windows (64-bit .exe)

    3. En opciones de instalacion
        a. Elegir “Just Me"
        b. Seleccionar "Add Miniconda to PATH" si no usás otra terminal como Anaconda Prompt.

    5. Abrir terminal Powershell y chequear instalacion:
        ```powershell
        conda --version
        ```
    6. Inicializar conda en Powershell:
        ```powershell
        conda init powershell
        ```
* Extensiones de Visual Studio Code:
    1. Jupyter
    2. Python

## Setup

1. Abrir terminal Powershell

2. Crear conda environment:
   ```powershell
   conda env create -f environment.yml
   ```
3. Abrir jupyter notebook [deteccion-sitios-web-fraudulentos.ipynb](deteccion-sitios-web-fraudulentos.ipynb)

4. Seleccionar como kernel de tipo Python Environment el entorno virtual conda *el-robo-del-siglo-env*