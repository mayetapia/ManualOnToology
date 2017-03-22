# Tabla de contenido de la Guía de uso de OnToology


1. [Primer paso: registrar un repositorio](#registrar-un-repositorio)
2. [Funcionamiento de OnToology](#funcionamiento-de-ontoology)
3. [Administración del entorno de trabajo](#administración-del-entorno-de-trabajo)

[//]: # "4. [Sugerencia de flujo de trabajo](#)"

## Registrar un repositorio

Para utilizar [OnToology](http://ontoology.linkeddata.es/) debes contar previamente con una cuenta de [Github](http://github.com) en la que posterioremente podrás crear repositorios en los que albergar tu(s) ontología(s). Debes fijarte que en tu perfil de Github tienes escrito tu Nombre y que tu **correo eléctronico sea de acceso público** pues de no serlo OnToology no podrá acceder a tu cuenta.

Para que OnToology haga un seguimiento de tus ontologías (o mejor dicho los ficheros .ttl, .owl and .rdf que haya en tu repositorio) debes introducir en [OnToology](http://ontoology.linkeddata.es/) el nombre de tu repositorio "usuario/nombreDeRepositorio" y presionar el botón "Watch this Repo" (véase figura a continuación).

[//]: # "![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso1.png)"
<img src="https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso1.png" width="800">


A continuación Github te redireccionará para solicitarte que autorices a OnToology para que tenga acceso a tu repositorio, tendrás que dar click en el botón "Authorize application"

[//]: # "![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso2.png)"
<img src="https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso2.png" width="700" align="center">


Si tu repositorio ya contenía algún fichero .owl, .ttl o .rdf OnToology lanzará los procesos de generación de reportes de evaluación, documentación y diagramas y a continuación generará una **Pull request** para incorporar los recursos generados a tu repositorio.

En otro caso OnToology no lanzará ningún proceso ya que **solo se activa con la modificación de ficheros .owl, .ttl o .rdf.**

## Funcionamiento de OnToology

Como ya hemos comentado OnToology se activa cuando uno o más ficheros del repositorio que contengan ontologías son añadidos o modificados. Cuando OnToology detecte que un fichero de ontología ha sido añadido o modificado tras un **Push** al repositorio en GitHub, [los procesos configurados en OnToology serán ejecutados](#administración-del-entorno-de-trabajo). 

Al finalizar, OnToology generará una **Pull request** al repositorio en cuestión para incorporar los recursos generados. Esto es debido a que OnToology hace un **fork** del repositorio sobre el que se trabaja para generar los nuevos recursos. Al acceder a la información del pull request en tu repositorio de GitHub (esta pull request no aparece en el interfaz de OnToology) encontrarás un "OnToology Update" a la que podrás acceder para ver el detalle como en la siguiente secuencia de imágenes.

[//]: # (En tu repositorio tendrás que actualizar tu ontología y hacer un "Push", tras lo cual OnToology generará una "Pull Request", al acceder a ella te encontrarás con "OnToology Update" a la que debes darle click para ingresar en su detalle)

Lista de pull request de tu reposortio (vista en GitHub):

[//]: # "![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso3.png)"
<img src="https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso3.png" width="700" align="center">


[//]: # (Luego dar click en el botón "Merge Pull Request")

Detalle de la pull request:

[//]: # "![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso4.png)"
<img src="https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso4.png" width="700" align="center">


Finalmente, si deseas incorporar los recursos generados por OnToology a tu repositorio, necesitas confirmar la acción para lo cual debes dar click en el botón **Confirm merge**. 

[//]: # "![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso4_1.png)"
<img src="https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso4_1.png" width="700" align="center">


Tras estos pasos tendrás en tu repositorio una carpeta llamada "OnToology" en la que se depositan todos los archivos generados por la herramienta.

[//]: # "![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso5.png)"
<img src="https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso4_1.png" width="700" align="center">

La siguiente imagen muestra la estructura de carpetas creada por OnToology.

<img src="https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/folders.png" width="700" align="center">

## Administración del entorno de trabajo

Una vez que se ha enlazado el repositorio con OnToology puedes expandirlo al hacer click en el ícono de la izquierda

[//]: # "![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/admin.png)"
<img src="https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/admin.png" width="700" align="center">

A continuación podrás ver las ontologías que tengas en tu repositorio y varios íconos que te permitirán realizar diferentes acciones

[//]: # "![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/admin1.png)"
<img src="https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/admin1.png" width="700" align="center">

Las acciones que puedes realizar con cada ícono son las siguientes:

| Ícono | Acción |
| ---------- | ---------- |
| ![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/icon1.png)   | Ir a tu repositorio en Github   |
| ![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/icon2.png)   | Obtener la configuración de tus ontologías en este repositorio  |
| ![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/icon3.png)   | Generar la documentación, diagramas y evaluación de tus ontologías   |
| ![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/icon4.png)   | Reanudar la previsualiación   |
| ![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/icon6.png)   | Publicar la ontología   |
| ![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/icon7.png)   | Descargar un paquete con la documentación, diagramas, evaluación y el .htaccess  | 


La acción del botón "Update Configuration" permite actualizar en el repositorio de Github los cambios que se realizan en el entorno de OnToology, esto ocasiona que se genere una "Pull Request" que tendremos que administrar de la misma forma que se indicó previamente en la sección de Primeros Pasos.

Finalmente el botón "Stop Watching" permite ocultar el repositorio de tal forma que no aparecerá en OnToology, cabe destacar que esta acción no cambia la configuraciones que se realizaron previamente, y que cuando se desee volver a visualizarlo bastará con colocar los datos de nuestra cuenta y el repositorio (miusario/mirepositorio) y dar click en el botón "Whatch this Repo".

