# Entrega de la práctica 2 de VC
## Descripción de la tarea
En este repositorio se encuentran las soluciones de las tareas solicitadas en el [fichero](https://github.com/otsedom/otsedom.github.io/blob/6378dcb759dee6f7c9dde1fe4555801f92b51969/VC/P2/VC_P2.ipynb) del [repositorio suministrado](https://github.com/otsedom/otsedom.github.io.git) por el profesor.
### Tarea 1
#### Enunciado
"TAREA: Realiza la cuenta de píxeles blancos por filas (en lugar de por columnas). Determina el valor máximo de píxeles blancos para filas, maxfil, mostrando el número de filas y sus respectivas posiciones, con un número de píxeles blancos mayor o igual que 0.90*maxfil."
### Tarea 2
#### Enunciado
"TAREA: Crear una imagen estilo Mondrian (un ejemplo https://www3.gobiernodecanarias.org/medusa/ecoescuela/sa/2017/04/17/descubriendo-a-mondrian/ ) con las funciones de dibujo de OpenCV"
### Tarea 3
#### Enunciado
"TAREA: Modifica de forma libre los valores de un plano de la imagen"
### Tarea 4
#### Enunciado
"TAREA: Pintar círculos en las posiciones del píxel más claro y oscuro de la imagen ¿Si quisieras hacerlo sobre la zona 8x8 más clara/oscura?"
## Dependencias
Para que este código se ejecute correctamente son necesarios los siguientes requisitos:
- [Anaconda o miniconda](https://www.anaconda.com/download)
- [VS Code](https://code.visualstudio.com/) o similar con el plugin de python y de jupyter notebooks
- Un kernel de python con  los paquetes "opencv-python" y "matplotlib"
## Instrucciones de instalación de dependencias y ejecución
### Windows
1. Abrir una "anaconda prompt" e introducir 
```cmd
conda create --name ENV_NAM python=3.11.5
conda activate ENV_NAM
pip install opencv-python
pip install matplotlib
conda install -n ENV_NAM ipykernel --update-deps --force-reinstall
```
2. Abrir [VS Code](https://code.visualstudio.com/) e instalarr los siguientes paquetes:
    - https://marketplace.visualstudio.com/items?itemName=ms-python.python
    - https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter
3. Clonar este repositorio
4. Abrir el fichero [Entrega1.ipynb](./Entrega1.ipynb)
5. Asignar el kernel "ENV_NAM" creado antes al fichero.
6. Ejecutar
### MacOS/Linux
1. Abrir una terminal e introducir 
```bash
anaconda
conda create --name ENV_NAM python=3.11.5
conda activate ENV_NAM
pip install opencv-python
pip install matplotlib
conda install -n ENV_NAM ipykernel --update-deps --force-reinstall
```
2. Abrir [VS Code](https://code.visualstudio.com/) e instalarr los siguientes paquetes:
    - https://marketplace.visualstudio.com/items?itemName=ms-python.python
    - https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter
3. Clonar este repositorio
4. Abrir el fichero [Entrega1.ipynb](./Entrega1.ipynb)
5. Asignar el kernel "ENV_NAM" creado antes al fichero.
6. Ejecutar
## Herramientas Externas
Para el desarrollo de estos ejercicios hemos hecho uso de la herramienta de inteligencia artificial copilot integrada en vs code para preguntar sobre los erroresque nos iban surgiendo
## Incidencias
En macOS funciona correctamente todo pero cada vez que se intenta cerrar la cámara, el kernel crashea. Parece ser que al cerrar el programa, la memoria no se libera.
## Creadores
-   Nicolás Rey Alonso
-   Wafa Azdad Triki