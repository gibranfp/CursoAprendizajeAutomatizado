# Curso de aprendizaje automatizado 2022-2, PCIC-UNAM
Este repositorio contiene las diapositivas, libretas y demás material del curso de aprendizaje automatizado, impartido en el [Posgrado en Ciencia e Ingeniería de la Computación](http://www.mcc.unam.mx/) de la [UNAM](https://www.unam.mx/).


## Temario
1. Clasificador bayesiano ingenuo
2. Métodos lineales de regresión y clasificación
3. Selección de modelos
4. Modelos gráficos probabilísticos
5. Modelos de variales latentes
6. Máquinas de vectores de soporte y kernels
7. Ensambles

## Clonar rama
Este repositorio contiene el material de cursos anteriores y puede ser algo pesado clonarlo completamente. Para clonar únicamente la rama del curso 2022-1, debes hacerlo con el siguiente comando:

```
git clone --branch 2022-2 --single-branch https://github.com/gibranfp/CursoAprendizajeAutomatizado.git
```

## Ambiente de programación

Para ejecutar los ejercicios y las libretas de este repositorio se tienen dos opciones:

* Google Colab
* Ambiente local

### Google Colab

[Google Colab](https://colab.research.google.com) es un servicio para crear, editar, alojar y ejecutar libretas en la nube. Ofrece ambientes con CPU, GPU y TPU de forma gratuita, aunque con un tiempo máximo de ejecución. Puedes crear una nueva libreta (*notebook*) desde Colab, subir una existente desde tu computadora o importarla de Google Drive o GitHub.

### Ambiente local
Para instalar el ambiente en nuestra computadora primero debemos instalar Anaconda siguiendo las [instrucciones](https://docs.anaconda.com/anaconda/install/) oficiales. Después, desde una terminal creamos el ambiente con el archivo de dependencias:

```
conda env create --file environment.yml
```

Enseguida, activamos el ambiente:

```
conda activate caa
```

Posteriormente, para comenzar a trabajar con las libretas ejecutamos:

```
jupyter notebook
```

Este comando abrirá una pestaña o ventana en tu navegador web, como se muestra en la siguiente captura de pantalla:

![](https://github.com/gibranfp/CursoAprendizajeProfundo/blob/2022-1/figs/jupyter_notebook.png)

Aquí puedes crear una nueva libreta seleccionando el botón `New` y posteriormente `Python 3`. También puedes cargar una existente seleccionando un archivo con extensión `.ipynb` dentro del directorio donde se lanzó el comando. Con `Upload` agregas archivos que se encuentran en otra parte de tu computadora a este directorio. Para salir, simplemente presiona el botón `Quit` y cierra la pestaña o ventada correspondiente.

Para desactivar el ambiente

```
conda deactivate
```
