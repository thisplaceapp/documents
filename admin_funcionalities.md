# Documentación Funcionalidades del Administrador

## 1. Aclaraciones

### Funcionalidades actuales

La siguiente Documentación representa las funcionalidades que contiene This Place App hasta Noviembre de 2023.

### Permisos de usuario

Las funcionalidades descritas a continuación serán las funcionalidades completas que tendría un usuario sin restricciones de permisos.

Cada usuario de la aplicación tendrá sus propios permisos definidos por los administradores de This Place App, los cuales pueden ser consultados al momento de firmar el CONTRATO DE LICENCIA DE USO DE SOFTWARE.

Todas las funcionalidades descritas a continuación serán exclusivamente para ser utilizadas en el "lugar" al cual se firmó el CONTRATO DE LICENCIA DE USO DE SOFTWARE.

## 2. Funcionalidades

### Administración del lugar

Un administrador tendrá la opción de Leer y Modificar el lugar para el que se definió el contrato. En el lugar se podrá modificar la Descripción y el Logo que se mostrará a los clientes en la vista inicial de la aplicación.

### Administración de Mapas

Un administrador tendrá la opciones de Leer, Crear, Modificar y Eliminar "Mapas", que pueden representar una nueva área dentro del lugar que utiliza la licencia, ya sean distintos pisos o enfoques a distintas áreas que el lugar quiera definir.

Estos mapas tienen un Nombre, un número de piso, una url de tiles (la cual se utiliza para definir contornos personalizados) y un área que debe cubrir todos los lugares donde se podrían agregar pines.

### Administración de Caminos

Un administrador podrá Leer, Crear, Modificar y Eliminar "Caminos". Los cuales podrán ser utilizados para mostrar los lugares por los cuales los usuarios pueden caminar. Estos podrán ser utilizados para calcular el mejor camino entre la ubicación por GPS del usuario y una "Ubicación".

Cada camino tiene:

* Nombre: Usado por el administrador para distinguir entre caminos.
* Ancho y Color: Los cual definen que tan ancho es un camino y el color que tendrá al mostrarse en la aplicación.
* Conjunto de nodos: Son referencias de puntos geográficos por los que pasa el camino.

Para facilitar que los caminos estén correctamente referenciados geográficamente, en lugar de crear el camino manualmente se da la opción de subir un archivo gpx que contenga todos los nodos iniciales del camino. Debido a que el gps al momento de mapear el camino no siempre es preciso y para mejorar la fluidez de visualizar el mapa por los usuarios, se recomienda editar los caminos subidos de esta forma, para dejar solamente los nodos que se estimen convenientes.

### Administración de Pines

Un administrador tendrá la opción de Leer, Crear, Modificar y Eliminar "Tiendas/Atracciones". Estas pueden ser utilizadas como referencia de un conjunto de pines ("Ubicaciones") que comparten una misma descripción, logo y horarios (ej: baños o una atracción que quieres que aparezca en varios mapas).

Por cada "Tienda/Atracción", un administrador tendrá la opción de:

* Leer, Crear, Modificar y Eliminar "Ubicaciones", los cuales representan un "pin" en el mapa seleccionado. Cada uno de estas "ubicaciones" podrá tener un nombre especifico, una ubicación en las coordenadas seleccionadas dentro del mapa, una prioridad (la cual representa con cuanto zoom se podrá ver el pin), varias imágenes y un "Pin personalizado" (el cual se refiere a un icono especifico que representará el pin).

### Administración de Horarios

Un administrador tendrá la opción de Leer, Crear, Modificar y Eliminar "Horarios", los cuales debieran representar las horas en que los usuarios pueden visitar el pin y éste se encuentre operativo.

Estos horarios tienen una hora de inicio, una hora de termino y un dia de la semana por lo que será necesario crear al menos uno por cada dia de la semana que la "tienda/atracción".

### Administración de Notificaciones

Un administrador podrá Leer, Crear, Modificar y Eliminar "Notificaciones", las cuales pueden ser utilizadas para mostrar informaciones o advertencias recientes que puedan ser relevantes para los usuarios que están en el lugar.

Una notificación tiene Nombre, Descripción y si está activa. Donde los usuarios solo podrán ver nombre y descripción de las notificaciones activas.
