# Curso de aprendizaje automatizado, PCIC-UNAM
Notas, diapositivas, tareas y código de ejemplo del curso de aprendizaje automatizado impartido en el PCIC de la UNAM

## Configuración del ambiente

Los ejemplos del curso se pueden seguir usando:
 * Google Colab: recomendado para aquellos poco familiarizados programación y el entorno Python en general.
 * Local/Anaconda: para aquellos que deseen crear un ambiente para correr los ejemplos en su equipo.

### Google Colab

Google Colab es un servicio gratuito que permite ejecutar libretas de Jupyter que se encuentren almacenadas en una cuenta de Google Drive. Usarlo es sencillo, habiendo entrado previamente a tu cuenta de Drive, abre al libreta `1_mlp.ipynb` dentro del directorio `notebooks` y presiona sobre el icono:

![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)

esto importará la libreta en tu Drive. Ahora, en el menu "Runtime -> Change runtime type" seleccionamos Python 3 y GPU, y guardamos. Finalmente corremos la libreta en "Runtime -> Run all".

### Local/Anaconda

Para crear el ambiente se provee el archivo `enviroment.yml`. Seguir la [documentación](https://docs.anaconda.com/anaconda/navigator/tutorials) para más detalles.
