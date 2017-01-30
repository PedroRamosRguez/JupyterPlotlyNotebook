# JupyterPlotlyNotebook
[![Binder](http://mybinder.org/badge.svg)](http://mybinder.org/repo/alu0100505078/jupyterplotlynotebook)

Ejemplo de uso del Notebook creado sobre plotly y python mostrandolo en un enlace realizado por **mybinder** en el que 
muestra el resultado del notebook, como si se estuviese realizando el notebook por un usuario mismo.

[Enlace del notebook mediante myBinder](http://mybinder.org/repo/alu0100505078/jupyterplotlynotebook)


## Pasos para usar Jupyter sin usar Anaconda

Para utilizar Jupyter sin tener que usar **Anaconda** y usar los paquetes instalados localmente hay que seguir los siguientes paso:

* `pip3 install --upgrade pip` para Python 3 ó `pip install --upgrade pip` en caso de usar Pythos 2.7
* `pip3 install jupyter` ó `pip install jupyter`
* Lo siguiente será  añadir la pestaña de cluster para utilizar el cluster propio mediante el comando
  * `pip install ipyparallel`
* Para activar la pestaña una vez se ha instalado el paquete es mediante el siguiente comando
  * `ipcluster nbextension enable`
* Para desactivarla nuevamente es mediante el comando
  * `ipcluster nbextension disable`
Una vez realizados estos pasos, instalar de manera local los paquetes que se vayan a utilizar en el notebook pertinente mediante el comando:
* `pip install <NombrePaquete>` ó `pip3 install <NombrePaquete>`
