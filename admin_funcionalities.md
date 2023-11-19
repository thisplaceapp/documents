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

La función de administración del lugar confiere al usuario administrador un control total sobre la representación visual del lugar en la aplicación. Desde la descripción general hasta la identidad visual a través del logo, el administrador puede personalizar la primera impresión que los usuarios tienen al acceder a This Place App. Esta capacidad de adaptación es esencial para garantizar que la aplicación se alinee de manera efectiva con la identidad y los valores específicos de cada lugar.

### Administración de Mapas

Un administrador tendrá la opciones de Leer, Crear, Modificar y Eliminar "Mapas", que pueden representar una nueva área dentro del lugar que utiliza la licencia, ya sean distintos pisos o enfoques a distintas áreas que el lugar quiera definir.

Estos mapas tienen un Nombre, un número de piso, una url de tiles (la cual se utiliza para definir contornos personalizados) y un área que debe cubrir todos los lugares donde se podrían agregar pines.

En caso de que un administrador desee utilizar los contornos personalizados (url de tiles), deberá entregar una imagen a escala del lugar o en su defecto solicitar una a This Place App por un costo adicional acorde al tamaño y diversidad del lugar.

La gestión de mapas no se limita simplemente a la creación de representaciones visuales; va más allá al permitir la definición de áreas específicas dentro del lugar licenciado. Los administradores tienen la capacidad de crear experiencias de usuario más ricas y detalladas. Esta función es especialmente valiosa al representar áreas complejas o distintos niveles dentro del lugar, brindando a los usuarios una navegación clara y precisa.

### Administración de Caminos

Un administrador podrá Leer, Crear, Modificar y Eliminar "Caminos". Los cuales podrán ser utilizados para mostrar los lugares por los cuales los usuarios pueden caminar. Estos podrán ser utilizados para calcular el mejor camino entre la ubicación por GPS del usuario y una "Ubicación".

Cada camino tiene:

* Nombre: Usado por el administrador para distinguir entre caminos.
* Ancho y Color: Los cual definen que tan ancho es un camino y el color que tendrá al mostrarse en la aplicación.
* Conjunto de nodos: Son referencias de puntos geográficos por los que pasa el camino.

Para facilitar que los caminos estén correctamente referenciados geográficamente, en lugar de crear el camino manualmente se da la opción de subir un archivo gpx que contenga todos los nodos iniciales del camino. Debido a que el gps al momento de mapear el camino no siempre es preciso y para mejorar la fluidez de visualizar el mapa por los usuarios, se recomienda editar los caminos subidos de esta forma, para dejar solamente los nodos que se estimen convenientes.

La administración de caminos no solo se trata de trazar rutas en el mapa, sino de ofrecer una experiencia de usuario fluida y precisa. Al permitir la creación y modificación de caminos, los administradores pueden definir no solo la apariencia visual de las rutas, sino también los puntos geográficos exactos por los que pasan. La opción de subir archivos GPX añade una capa adicional de precisión, asegurando que los caminos estén perfectamente alineados con la topografía del lugar.

### Administración de Pines

Un administrador tendrá la opción de Leer, Crear, Modificar y Eliminar "Puntos de Interés". Estas pueden ser utilizadas como referencia de un conjunto de pines ("Ubicaciones") que comparten una misma descripción, logo y horarios (ej: baños o una atracción que quieres que aparezca en varios mapas).

Por cada "Punto de Interés", un administrador tendrá la opción de:

* Leer, Crear, Modificar y Eliminar "Ubicaciones", los cuales representan un "pin" en el mapa seleccionado. Cada uno de estas "ubicaciones" podrá tener un nombre especifico, una ubicación en las coordenadas seleccionadas dentro del mapa, una prioridad (la cual representa con cuanto zoom se podrá ver el pin), varias imágenes y un "Pin personalizado" (el cual se refiere a un icono especifico que representará el pin).

La capacidad de asociar imágenes, nombres específicos y pines personalizados a cada ubicación mejora significativamente la experiencia del usuario al proporcionar información visualmente rica y detallada

### Personalización de Pines

Un administrador tendrá la opción de Leer, Crear, Modificar y Eliminar "Pines personalizados". Los cuales pueden ser utilizados para hacer que las "ubicaciones" tengan distintos iconos que representen el pin en el mapa.

Cada pin personalizado está compuesto por un Nombre y una Imagen. El nombre proporciona una referencia exclusiva para que el administrador pueda identificar fácilmente el pin al utilizarlo. En contraste, la imagen asociada al pin debe ser de tamaño reducido, priorizando la agilidad de uso para los usuarios. Estas imágenes están diseñadas de manera que su centro apunte al punto medio de la zona inferior, proporcionando una referencia visual clara para las coordenadas de la "ubicación" que utilice dicho pin. Esta cuidadosa consideración en el diseño garantiza una experiencia intuitiva y eficiente tanto para los administradores como para los usuarios finales.

### Administración de Horarios

Un administrador tendrá la opción de Leer, Crear, Modificar y Eliminar "Horarios", los cuales debieran representar las horas en que los usuarios pueden visitar el pin y éste se encuentre operativo.

Estos horarios tienen una hora de inicio, una hora de termino y un dia de la semana por lo que será necesario crear al menos uno por cada dia de la semana que la "punto de interés".

La gestión de horarios es crucial para la operatividad eficiente de cada "punto de interés". Al establecer horarios específicos para cada día de la semana, los administradores garantizan que los usuarios tengan información actualizada sobre cuándo pueden visitar cada ubicación. Esta función no solo mejora la experiencia del usuario al proporcionar información precisa, sino que también optimiza la operación del lugar al garantizar la disponibilidad y funcionalidad en momentos específicos.

### Administración de Notificaciones

Un administrador podrá Leer, Crear, Modificar y Eliminar "Notificaciones", las cuales pueden ser utilizadas para mostrar informaciones o advertencias recientes que puedan ser relevantes para los usuarios que están en el lugar.

Una notificación tiene Nombre, Descripción y si está activa. Donde los usuarios solo podrán ver nombre y descripción de las notificaciones activas.

Estas notificaciones, son una herramienta valiosa para mantener a los usuarios informados sobre eventos, cambios en la operatividad del lugar o cualquier otra información pertinente. La capacidad de activar o desactivar notificaciones agrega flexibilidad al sistema, asegurando que solo la información más relevante esté disponible para los usuarios en un momento dado.
