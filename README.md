# Tabla de contenido de la Guía de uso de OnToology


1. [Primer paso: registrar un repositorio](#registrar-un-repositorio)
2. [Configuración de repositorio](#)
3. [Administración del entorno de trabajo](#administración-del-entorno-de-trabajo)
4. [Sugerencia de flujo de trabajo](#)

## Registrar un repositorio

Para utilizar OnToology debes contar previamente con una cuenta de [Github](http://github.com) en la que posterioremente podrás crear repositorios en los que albergar tu(s) ontología(s). Debes fijarte que en tu perfil de Github tienes escrito tu Nombre y que tu correo eléctronico sea de **acceso público** pues de no serlo OnToology no podrá acceder a tu cuenta.

Para que OnToology haga un seguimiento de tus ontologías (o mejor dicho los ficheros .ttl, .owl and .rdf que haya en tu repositorio) debe introducir en [OnToology](http://ontoology.linkeddata.es/) el nombre de tu repositorio "usuario/nombreDeRepositorio" y presionar el botón "Watch this Repo" (véase figura a continuacin).

![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso1.png)


A continuación Github te redireccionará para solicitarte que autorices a OnToology para que tenga acceso a tu repositorio, tendrás que dar click en el botón "Authorize application"

![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso2.png)

En tu repositorio tendrás que actualizar tu ontología y hacer un "Push", tras lo cual OnToology generará una "Pull Request", al acceder a ella te encontrarás con "OnToology Update" a la que debes darle click para ingresar en su detalle

![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso3.png)

Luego dar click en el botón "Merge Pull Request"

![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso4.png)


Finalmente necesitas confirmar la acción para lo cual debes dar click en el botón "Confirm merge"

![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso4_1.png)


Tras estos pasos tendrás en tu repositorio una carpeta llamada "OnToology" en la que se depositan todos los archivos generados por la herramienta.

![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/paso5.png)


## Administración del entorno de trabajo

Una vez que se ha enlazado el repositorio con OnToology puedes expandirlo al hacer click en el ícono de la izquierda

![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/admin.png)

A continuación podrás ver las ontologías que tengas en tu repositorio y varios íconos que te permitirán realizar diferentes acciones

![](https://github.com/paoespinozarias/ManualOnToology/blob/master/imagenes/admin1.png)

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
