# Entrega de la práctica 2 de VC
## Descripción de la tarea
En este repositorio se encuentran las soluciones de las tareas solicitadas en el [fichero](https://github.com/otsedom/otsedom.github.io/blob/main/VC/P2/VC_P2.ipynb) del [repositorio suministrado](https://github.com/otsedom/otsedom.github.io.git) por el profesor.
### Tarea 1
#### Enunciado
"TAREA: Realiza la cuenta de píxeles blancos por filas (en lugar de por columnas). Determina el valor máximo de píxeles blancos para filas, maxfil, mostrando el número de filas y sus respectivas posiciones, con un número de píxeles blancos mayor o igual que 0.90*maxfil."
### Tarea 2
#### Enunciado
"TAREA: Aplica umbralizado a la imagen resultante de Sobel (convertida a 8 bits), y posteriormente realiza el conteo por filas y columnas similar al realizado en el ejemplo con la salida de Canny de píxeles no nulos. Calcula el valor máximo de la cuenta por filas y columnas, y determina las filas y columnas por encima del 0.90*máximo. Remarca con alguna primitiva gráfica dichas filas y columnas sobre la imagen del mandril. ¿Cómo se comparan los resultados obtenidos a partir de Sobel y Canny?."
### Tarea 3
#### Enunciado
"TAREA: Proponer un demostrador que capture las imágenes de la cámara, y les permita exhibir lo aprendido en estas dos prácticas ante quienes no cursen la asignatura. Es por ello que además de poder mostrar la imagen original de la webcam, permita cambiar de modo, incluyendo al menos dos procesamientos diferentes como resultado de aplicar las funciones de OpenCV trabajadas hasta ahora."
### Tarea 4
#### Enunciado
"TAREA: Tras ver los vídeos [My little piece of privacy](https://www.niklasroy.com/project/88/my-little-piece-of-privacy), [Messa di voce](https://youtu.be/GfoqiyB1ndE?feature=shared) y [Virtual air guitar](https://youtu.be/FIAmyoEpV5c?feature=shared) proponer un demostrador reinterpretando la parte de procesamiento de la imagen, tomando como punto de partida alguna de dichas instalaciones."
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
4. Abrir el fichero [Entrega_2.ipynb](./Entrega_2.ipynb)
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
4. Abrir el fichero [Entrega_2.ipynb](./Entrega_2.ipynb)
5. Asignar el kernel "ENV_NAM" creado antes al fichero.
6. Ejecutar
## Herramientas Externas
Para el desarrollo de estos ejercicios hemos hecho uso de la herramienta de inteligencia artificial copilot integrada en vs code para preguntar sobre los erroresque nos iban surgiendo
## Incidencias
En macOS funciona correctamente todo pero cada vez que se intenta cerrar la cámara, el kernel crashea. Parece ser que al cerrar el programa, la memoria no se libera.
## Creadores
-   Nicolás Rey Alonso
-   Wafa Azdad Triki