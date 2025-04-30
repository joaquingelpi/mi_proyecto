# mi_proyecto
 
Este proyecto demuestra cómo estructurar un proyecto de Python, usar funciones con estructuras de control y ejecutar código. 

## Objetivos

- Aplicar funciones personalizadas en Python, usando estructuras de control como for e if.

- Separar la lógica del programa principal, organizando funciones reutilizables en módulos.

- Probar funciones desde un script (main.py) y desde un notebook.

- Gestionar el proyecto con Git y GitHub, incluyendo inicialización, seguimiento de cambios y publicación del repositorio.

- Ignorar archivos no deseados mediante .gitignore para mantener limpio el repositorio.

- Clonar y ejecutar el proyecto en editores de código, facilitando el acceso y uso del código en la nube.

## Estructura del proyecto

mi_proyecto/
│
├── README.md
├── requirements.txt
├── main.py
├── .gitignore
├── src/
│   ├── _init_.py
│   └── operaciones.py
└── notebooks/
    └── uso_funciones.ipynb

## Requisitos 
Python 3.11.9

## ¿Cómo funciona el proyecto?

Este proyecto muestra cómo se pueden usar funciones definidas en un archivo separado (operaciones.py). Luego, se realiza una prueba importando esas funciones en main.py, y ejecutando el programa desde la terminal con el comando python main.py.

Finalmente, también se utiliza un notebook llamado uso_funciones.ipynb, donde se importan las mismas funciones y se pueden usar directamente dentro del entorno del notebook.

Este enfoque permite mantener el proyecto más ordenado, ya que las funciones están definidas aparte en un archivo  .py, evitando que el notebook quede cargado o desorganizado.