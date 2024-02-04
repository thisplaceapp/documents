# Documentación Funcionalidades del Administrador

## 1. Aclaraciones

### Funcionalidades actuales

La siguiente Documentación representa las funcionalidades que contiene This Place App hasta Noviembre de 2023.

### Permisos de usuario

Las funcionalidades descritas a continuación serán las funcionalidades completas que tendría un usuario sin restricciones de permisos.

Cada usuario de la aplicación tendrá sus propios permisos definidos por los administradores de This Place App, los cuales pueden ser consultados al momento de firmar el CONTRATO DE LICENCIA DE USO DE SOFTWARE.

Todas las funcionalidades descritas a continuación serán exclusivamente para ser utilizadas en el 'lugar' que firmó el CONTRATO DE LICENCIA DE USO DE SOFTWARE, donde se asumirá que el administrador ya tiene acceso a una cuenta con todos los permisos correspondientes.

## 2. Funcionalidades

### Administración del lugar

Un administrador tendrá la opción de Leer y Modificar el lugar para el que se definió el contrato. En el lugar, el administrador podrá modificar la Descripción y el Logo que se mostrará a los clientes en la vista inicial de la aplicación.

La función de administración del lugar confiere al usuario administrador un control total sobre la representación visual del lugar en la aplicación. Desde la descripción general hasta la identidad visual a través del logo, el administrador puede personalizar la primera impresión que los usuarios tienen al acceder a This Place App. Esta capacidad de adaptación es esencial para garantizar que la aplicación se alinee de manera efectiva con la identidad y los valores específicos de cada lugar.

#### Modo de uso

* **Editar**
  1. En la barra lateral, seleccionar "Editar".
  2. *Debieran aparecer campos de edición para la descripción y logo*.
  3. Modificar los campos correspondientes y seleccionar "Guardar".
  4. *Las modificaciones debieran verse reflejadas en la aplicación una vez que un usuario vuelva a abrirla*.

### Administración de Mapas

Un administrador tendrá la opción de Leer, Crear, Modificar y Eliminar "Mapas", que pueden representar una nueva área dentro del lugar que utiliza la licencia, ya sea en distintos pisos o enfoques a diversas áreas que el lugar desee definir.

Estos mapas tienen un Nombre, un número de piso, una url de tiles (la cual se utiliza para definir contornos personalizados) y un área que debe cubrir todos los lugares donde se podrían agregar pines.

En caso de que un administrador desee utilizar los contornos personalizados (url de tiles), deberá entregar una imagen a escala del lugar o en su defecto solicitar una a This Place App por un costo adicional acorde al tamaño y diversidad del lugar.

La gestión de mapas no se limita únicamente a la creación de representaciones visuales; va más allá al permitir la definición de áreas específicas dentro del lugar licenciado. Los administradores tienen la capacidad de crear experiencias de usuario más ricas y detalladas. Esta función es especialmente valiosa al representar áreas complejas o distintos niveles dentro del lugar, brindando a los usuarios una navegación clara y precisa.

#### Modo de uso

* **Leer (listado de mapas)**
  1. En la barra lateral, seleccionar "Mapas".
  2. *Debiera aparecer un listado con los mapas creados previamente*.
* **Crear**
  1. Ir al listado de mapas.
  2. Seleccionar "+ Crear".
  3. *Debieran aparecer campos de edición de un mapa*.
  4. Modificar los campos correspondientes y seleccionar "Guardar".
  5. *Debiera redirigir a la lista de mapas*.
* **Editar**
  1. Ir al listado de mapas.
  2. Seleccionar el botón de un "lápiz amarillo (editar)" en las acciones de un mapa.
  3. Repetir los pasos 3, 4 y 5 de la creación.
* **Eliminar**
  1. Ir al listado de mapas.
  2. Seleccionar el botón de un "basurero rojo (eliminar)" en las acciones de un mapa.
  3. Seleccionar "Si" a la pregunta de seguridad.
  4. *Debiera borrarse el mapa que se seleccionó*.

### Administración de Caminos

Un administrador podrá Leer, Crear, Modificar y Eliminar "Caminos". Los cuales se pueden usar para mostrar los lugares por los que los usuarios pueden caminar. Estos podrán ser utilizados para calcular el mejor camino entre la ubicación por GPS del usuario y una "Ubicación".

Cada camino tiene:

* Nombre: Usado por el administrador para distinguir entre caminos.
* Ancho y Color: Los cual definen que tan ancho es un camino y el color que tendrá al mostrarse en la aplicación.
* Conjunto de nodos: Son referencias de puntos geográficos por los que pasa el camino.

Para facilitar que los caminos estén correctamente referenciados geográficamente, en lugar de crear el camino manualmente se da la opción de subir un archivo gpx que contenga todos los nodos iniciales del camino. Debido a que el GPS al mapear el camino no siempre es preciso y para mejorar la fluidez de visualizar el mapa por los usuarios, se recomienda editar los caminos subidos de esta forma, para dejar solamente los nodos que se estimen convenientes.

La administración de caminos no solo se trata de trazar rutas en el mapa, sino de ofrecer una experiencia de usuario fluida y precisa. Al permitir la creación y modificación de caminos, los administradores pueden definir no solo la apariencia visual de las rutas, sino también los puntos geográficos exactos por los que pasan. La opción de subir archivos GPX añade una capa adicional de precisión, asegurando que los caminos estén perfectamente alineados con la topografía del lugar.

#### Modo de uso

* **Leer (listado de caminos de un mapa)**
  1. En la barra lateral, seleccionar "Mapas".
  2. *Debiera aparecer un listado con los mapas creados previamente*.
  3. Seleccionar el botón de un "camino azul (caminos)" en las acciones del mapa.
  4. *Debiera aparecer un listado con los caminos del mapa creados previamente*.
* **Crear un camino desde un archivo**
  1. Ir al listado de caminos de un mapa.
  2. Seleccionar "Subir archivo".
  3. *Debieran aparecer campos de edición de un camino y un campo para seleccionar el archivo .gpx*.
  4. Modificar los campos correspondientes, subir el archivo y seleccionar "Guardar".
  5. *Debiera redirigir a la lista de caminos del mapa*.
* **Crear manualmente un camino**
  1. Ir al listado de caminos de un mapa.
  2. Seleccionar "+ Crear".
  3. *Debieran aparecer campos de edición de un camino y un mapa para agregar/editar los nodos*.
  4. Modificar los campos correspondientes y seleccionar "Guardar".
  5. *Debiera redirigir a la lista de caminos del mapa*.
* **Editar**
  1. Ir al listado de caminos de un mapa.
  2. Seleccionar el botón de un "lápiz amarillo (editar)" en las acciones de un mapa.
  3. Repetir los pasos 3, 4 y 5 de la creación manual de un camino.
* **Eliminar**
  1. Ir al listado de caminos de un mapa.
  2. Seleccionar el botón de un "basurero rojo (eliminar)" en las acciones de un mapa.
  3. Seleccionar "Si" a la pregunta de seguridad.
  4. *Debiera borrarse el mapa que se seleccionó*.

### Administración de Pines

Un administrador tendrá la opción de Leer, Crear, Modificar y Eliminar "Puntos de Interés". Estas pueden ser utilizadas como referencia de un conjunto de pines ("Ubicaciones") que comparten una misma descripción, logo y horarios (ej: baños o una atracción que quieres que aparezca en varios mapas).

Cada "Punto de Interés" también tendrá la opción de agregar descripciones dinámicas e infografías, las cuales ayudarán a enriquecer la información de los pines utilizando imágenes, videos que podrá verse por el usuario en el detalle luego de seleccionar y abrir un pin.

Por cada "Punto de Interés", un administrador tendrá la opción de:

* Leer, Crear, Modificar y Eliminar "Ubicaciones", los cuales representan un "pin" en el mapa seleccionado. Cada una de estas "ubicaciones" podrá tener un nombre especifico, una ubicación en las coordenadas seleccionadas dentro del mapa, una prioridad (la cual representa con cuanto zoom se podrá ver el pin), una o varias imágenes y un "Pin personalizado" (el cual se refiere a un icono especifico que representará el pin).

La capacidad de asociar imágenes, nombres específicos y pines personalizados a cada ubicación mejora significativamente la experiencia del usuario al proporcionar información visualmente rica y detallada.

#### Modo de uso

##### Puntos de Interés

Enfocado en todos los puntos de interés de el lugar, es decir, tiendas, atracciones, baños, etc. Que puedan tener mas de una única ubicación (pin) entre los mapas.

* **Leer (listado de puntos de interés)**
  1. En la barra lateral, seleccionar "Puntos de interés".
  2. *Debiera aparecer un listado con todos los puntos de interés del lugar*.
* **Crear**
  1. Ir al listado de puntos de interés.
  2. Seleccionar "+ Crear".
  3. *Debieran aparecer campos de edición de un punto de interés*.
  4. Modificar los campos correspondientes y seleccionar "Guardar".
  5. *Debiera redirigir a la lista de puntos de interés.
* **Editar**
  1. Ir al listado de puntos de interés.
  2. Seleccionar el botón de un "lápiz amarillo (editar)" en las acciones de un punto de interés.
  3. Repetir los pasos 3, 4 y 5 de la creación de un punto de interés.
* **Eliminar**
  1. Ir al listado de puntos de interés.
  2. Seleccionar el botón de un "basurero rojo (eliminar)" en las acciones de un punto de interés.
  3. Seleccionar "Si" a la pregunta de seguridad.
  4. *Debiera borrarse el mapa que se seleccionó*.

##### Ubicaciones

Al enfocarse en todas las ubicaciones de un mapa, es decir, los pines que se mostrarán en ese mapa, la mejor forma de administrar las ubicaciones/pines es:

* **Leer (listado de ubicaciones de un mapa)**
  1. En la barra lateral, seleccionar "Mapas".
  2. *Debiera aparecer un listado con los mapas creados previamente*.
  3. Seleccionar el botón de un "pin azul (ubicaciones)" en las acciones del mapa.
  4. *Debiera aparecer un listado con las ubicaciones existentes del mapa*.
* **Crear**
  1. Ir al listado de ubicaciones de un mapa.
  2. Seleccionar "+ Crear".
  3. *Debieran aparecer 2 opciones:*
     1. **Seleccionar punto de interés**: En este caso se deberá seleccionar un punto de interés ya existente en el lugar y seleccionar Guardar.
     2. **Crear punto de interés**: En este caso, aparecerán los campos de creación de un punto de interés que deberán ser completados y seleccionar Guardar.
  4. *Debieran aparecer campos de edición de una ubicación*.
  5. Modificar los campos correspondientes y seleccionar "Guardar".
  6. *Debiera redirigir a la lista de ubicaciones del mapa*.
* **Editar**
  1. Ir al listado de ubicaciones de un mapa.
  2. Seleccionar el botón de un "lápiz amarillo (editar)" en las acciones de un mapa.
  3. Repetir los pasos 4, 5 y 6 de la creación de una ubicación.
* **Eliminar**
  1. Ir al listado de ubicaciones de un mapa.
  2. Seleccionar el botón de un "basurero rojo (eliminar)" en las acciones de un mapa.
  3. Seleccionar "Si" a la pregunta de seguridad.
  4. *Debiera borrarse la ubicación que se seleccionó*.

EXTRA: Las mismas funcionalidades de Leer/Crear/Editar/Eliminar una ubicación se pueden realizar desde la perspectiva de los "Puntos de Interés", de forma que sea mas fácil gestionar todas las ubicaciones que tiene cada punto de interés.

* **Leer (listado de ubicaciones de un punto de interés)**
  1. En la barra lateral, seleccionar "Puntos de interés".
  2. *Debiera aparecer un listado con los puntos de interés creados previamente*.
  3. Seleccionar el botón de un "pin azul (ubicaciones)" en las acciones del punto de interés.
  4. *Debiera aparecer un listado con las ubicaciones existentes del punto de interés*.
* **Crear**
  1. Ir al listado de ubicaciones de un punto de interés.
  2. Seleccionar "+ Crear".
  3. *Debieran aparecer campos de edición de una ubicación*.
  4. Modificar los campos correspondientes y seleccionar "Guardar".
  5. *Debiera redirigir a la lista de ubicaciones del punto de interés*.
* **Editar**
  1. Ir al listado de ubicaciones de un punto de interés.
  2. Seleccionar el botón de un "lápiz amarillo (editar)" en las acciones de un punto de interés.
  3. Repetir los pasos 3, 4 y 5 de la creación de una ubicación.
* **Eliminar**
  1. Ir al listado de ubicaciones de un punto de interés.
  2. Seleccionar el botón de un "basurero rojo (eliminar)" en las acciones de un punto de interés.
  3. Seleccionar "Si" a la pregunta de seguridad.
  4. *Debiera borrarse la ubicación que se seleccionó*.

### Administración de Horarios

Un administrador tendrá la opción de Leer, Crear, Modificar y Eliminar "Horarios", los cuales debieran representar las horas en que los usuarios pueden visitar el pin y éste se encuentre operativo.

Estos horarios tienen una hora de inicio, una hora de termino y un dia de la semana por lo que será necesario crear al menos uno por cada dia de la semana que la "punto de interés".

La gestión de horarios es crucial para la operatividad eficiente de cada "punto de interés". Al establecer horarios específicos para cada día de la semana, los administradores garantizan que los usuarios tengan información actualizada sobre cuándo pueden visitar cada ubicación. Esta función no solo mejora la experiencia del usuario al proporcionar información precisa, sino que también optimiza la operación del lugar al garantizar la disponibilidad y funcionalidad en momentos específicos.

#### Modo de uso

* **Leer (listado de horarios de un punto de interés)**
  1. En la barra lateral, seleccionar "Puntos de interés".
  2. *Debiera aparecer un listado con los puntos de interés creados previamente*.
  3. Seleccionar el botón de un "calendario azul (horarios)" en las acciones del punto de interés.
  4. *Debiera aparecer un listado con las horarios existentes del punto de interés*.
* **Crear**
  1. Ir al listado de horarios de un punto de interés.
  2. Seleccionar "+ Crear".
  3. *Debieran aparecer campos de edición de un horario*.
  4. Modificar los campos correspondientes y seleccionar "Guardar".
  5. *Debiera redirigir a la lista de horarios del punto de interés*.
* **Editar**
  1. Ir al listado de horarios de un punto de interés.
  2. Seleccionar el botón de un "lápiz amarillo (editar)" en las acciones de un punto de interés.
  3. Repetir los pasos 3, 4 y 5 de la creación de un horario.
* **Eliminar**
  1. Ir al listado de horarios de un punto de interés.
  2. Seleccionar el botón de un "basurero rojo (eliminar)" en las acciones de un punto de interés.
  3. Seleccionar "Si" a la pregunta de seguridad.
  4. *Debiera borrarse el horario que se seleccionó*.

### Contornos de Pines

Un administrador tendrá la opción de Editar una "Ubicación" de un "Punto de Interés" para definir contornos de la ubicación. Estos pueden ser utilizados para demarcar una zona geográfica que tenga cierta relación con la ubicación en cuestión, es decir, el área que pueda cubrir el punto de interés.

Cada ubicación tendrá la opción de personalizar el color de el contorno o dejar el color por defecto de la aplicación.

Gracias a esto, se podrá mejorar la experiencia de usuario de manera que cuando éste seleccione un pin, se demarque el área que tiene relación con el mismo.

#### Modo de uso

* **Usar en una ubicación**
  * Ir a Editar una Ubicación (descrita en la sección de *"Administración de Pines"*).
  * *Abajo de seleccionar una Prioridad, debiera aparecer un mapa que permite agregar vectores*.
  * En la zona superior izquierda del mapa, seleccionar "Draw Polygons".
  * Formar un polígono cerrado en el mapa, el cual demarcará el contorno que tendrá el pin cuando un usuario lo seleccione.
  * Hacer click en "color del contorno del pin" y seleccionar un color de preferencia acorde al pin.
  * Seleccionar "Guardar".

### Personalización de Pines

Un administrador tendrá la opción de Leer, Crear, Modificar y Eliminar "Pines personalizados". Los cuales pueden ser utilizados para hacer que las "ubicaciones" tengan distintos iconos que representen el pin en el mapa.

Cada pin personalizado está compuesto por un nombre y una imagen. El nombre proporciona una referencia exclusiva para que el administrador pueda identificar fácilmente el pin al utilizarlo. En contraste, la imagen asociada al pin debe ser de tamaño reducido, priorizando la agilidad de uso para los usuarios. Estas imágenes están diseñadas de manera que su centro apunte al punto medio de la zona inferior, proporcionando una referencia visual clara para las coordenadas de la "ubicación" que utilice dicho pin. Esta cuidadosa consideración en el diseño garantiza una experiencia intuitiva y eficiente tanto para los administradores como para los usuarios finales.

#### Modo de uso

* **Leer (listado de pines personalizados)**
  1. En la barra lateral, seleccionar "Pines personalizados".
  2. *Debiera aparecer un listado con los pines personalizados creados previamente*.
* **Crear**
  1. Ir al listado de pines personalizados.
  2. Seleccionar "+ Crear".
  3. *Debieran aparecer campos de edición Nombre e Imagen*.
  4. Modificar los campos correspondientes, subir una imagen (de tamaño aproximado a 160px*160px) y seleccionar "Guardar".
  5. *Debiera redirigir a la lista de pines personalizados*.
* **Editar**
  1. Ir al listado de pines personalizados.
  2. Seleccionar el botón de un "lápiz amarillo (editar)" en las acciones de un pin personalizado.
  3. Repetir los pasos 3, 4 y 5 de la creación.
* **Eliminar**
  1. Ir al listado de pines personalizados.
  2. Seleccionar el botón de un "basurero rojo (eliminar)" en las acciones de un pin personalizado.
  3. Seleccionar "Si" a la pregunta de seguridad.
  4. *Debiera borrarse el pin personalizado que se seleccionó*.
* **Usar en una ubicación**
  * Ir a Editar una Ubicación (descrita en la sección de *"Administración de Pines"*).
  * Hacer click en "Pin personalizado" y seleccionar uno de los pines personalizados existentes.
  * Seleccionar "Guardar".

### Administración de Notificaciones

Un administrador podrá Leer, Crear, Modificar y Eliminar "Notificaciones", las cuales pueden ser utilizadas para mostrar información o advertencias recientes que puedan ser relevantes para los usuarios que están en el lugar.

Una notificación tiene Nombre, Descripción y si está activa. Donde los usuarios solo podrán ver nombre y descripción de las notificaciones activas.

Estas notificaciones, son una herramienta valiosa para mantener a los usuarios informados sobre eventos, cambios en la operatividad del lugar o cualquier otra información pertinente. La capacidad de activar o desactivar notificaciones agrega flexibilidad al sistema, asegurando que solo la información más relevante esté disponible para los usuarios en un momento dado.

#### Modo de uso

* **Leer (listado de notificaciones)**
  1. En la barra lateral, seleccionar "Notificaciones para visitantes".
  2. *Debiera aparecer un listado con las notificaciones creadas previamente*.
* **Crear**
  1. Ir al listado de notificaciones.
  2. Seleccionar "+ Crear".
  3. *Debieran aparecer campos de edición de una notificación*.
  4. Modificar los campos correspondientes y seleccionar "Guardar".
  5. *Debiera redirigir a la lista de notificaciones*.
* **Editar**
  1. Ir al listado de notificaciones.
  2. Seleccionar el botón de un "lápiz amarillo (editar)" en las acciones de un pin personalizado.
  3. Repetir los pasos 3, 4 y 5 de la creación.
* **Eliminar**
  1. Ir al listado de notificaciones.
  2. Seleccionar el botón de un "basurero rojo (eliminar)" en las acciones de un pin personalizado.
  3. Seleccionar "Si" a la pregunta de seguridad.
  4. *Debiera borrarse el pin personalizado que se seleccionó*.
