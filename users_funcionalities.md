# Documentación Funcionalidades usuarios de la app

## 1. Aclaraciones

### Funcionalidades actuales

La siguiente Documentación representa las funcionalidades que contienen los usuarios de la aplicación mobile This Place App hasta Enero de 2024.

### Permisos de usuario

Las funcionalidades descritas a continuación serán las funcionalidades completas que tendría un usuario sin restricciones de permisos.

Cada usuario de la aplicación tendrá sus propios permisos definidos por los administradores de cada lugar, por lo que en cada lugar, y acorde a si se está usando o no una cuenta de usuario puedes o no tener alguna de las funcionalidades mencionadas.

## 2. Funcionalidades

<!-- ### Registro de usuario -->

<!-- ### Login de usuario -->

### Selección de lugares

La selección de lugares es esencial para que los usuarios encuentren rápidamente los destinos asociados con This Place App. Esta función ofrece una vista inicial con una lista ordenada por distancia (solo si el usuario habilitó el permiso de ubicación), facilitando la elección del lugar más cercano. Además, permite a los usuarios explorar todos los lugares antes de llegar, brindando una experiencia más informada y personalizada.

Esta funcionalidad beneficia a los usuarios al proporcionar acceso rápido a destinos cercanos y mejorar la planificación de visitas a lugares específicos, aumentando la eficiencia y satisfacción del usuario.

#### Modo de uso

* Entrar a This Place App.
* (Opcional) Hacer click en la barra de búsqueda y escribir el nombre (o parte del nombre) del lugar que deseas.
* Hacer click en la imagen o descripción para seleccionar el lugar que deseas ver.
* *Debiera entrar al mapa por defecto del lugar seleccionado*

### Selección de mapas/pisos

En ciertos lugares, la opción de seleccionar el 'piso' proporciona una experiencia más detallada. Los administradores pueden definir mapas y pines específicos para cada piso, ofreciendo a los usuarios una vista enriquecida de los diferentes sectores del lugar. Esto permite una orientación más precisa y eficiente dentro del espacio, mejorando la experiencia de navegación del usuario.

Esta funcionalidad beneficia a los usuarios al proporcionar información detallada y específica de cada piso, facilitando la exploración y comprensión del lugar.

#### Modo de uso

* Seleccionar el lugar (debe tener habilitado mas de un piso).
* Hacer click en el icono blanco de la esquina inferior derecha, que dice Nv.0
* Seleccionar el nivel que deseas ver.
* *Debieran aparecer distintos caminos o pines acorde al piso seleccionado.*

### Búsqueda de pines

La búsqueda de pines permite a los usuarios encontrar rápidamente tiendas, atracciones o puntos de interés en un lugar. Si un usuario busca algo no visible en el mapa, esta función le permite localizar y seleccionar el pin deseado. Facilita la exploración y descubrimiento de lugares, ofreciendo una experiencia más completa.

Esta funcionalidad beneficia a los usuarios al proporcionar una herramienta de búsqueda eficiente, mejorando la accesibilidad y la capacidad de descubrimiento en el lugar.

#### Modo de uso

* Seleccionar el lugar
* Hacer click en el "icono de lupa" en la esquina superior derecha
* (Opcional) Hacer click en la barra de búsqueda y escribir el nombre (o parte del nombre) del lugar que deseas.
* Hacer click en el Pin que deseas encontrar.
* (Opcional) En caso de que el pin esté en multiples pisos, seleccionar el nivel donde se encuentra
* *Debiera aparecer el mapa en el nivel correspondiente y centrado en la ubicación del pin*

### Notificaciones

La función de notificaciones permite a los administradores enviar mensajes importantes a los usuarios que ingresan al lugar. Los usuarios pueden acceder a estos mensajes en cualquier momento, proporcionando información relevante, como eventos programados, cambios en los horarios de atención o alertas. Esta característica mejora la comunicación entre administradores y usuarios, garantizando una experiencia más informada y segura.

Esta funcionalidad beneficia a los usuarios al mantenerlos actualizados sobre eventos y cambios importantes en el lugar, mejorando la experiencia general de la visita.

#### Modo de uso

* Seleccionar el lugar.
* Hacer click en el "icono de campana" en la esquina superior derecha.
* *Debieran aparecer todas las notificaciones activas que los administradores tengan para informar a los usuarios, separados en distintas tarjetas.*

### Muestra de pines según zoom

La importancia de los pines varía según el zoom del usuario, garantizando una experiencia de mapa clara y no saturada. Al ingresar al lugar, los usuarios ven solo los pines esenciales, lo que evita la sobrecarga visual. Esta función mejora la navegación al proporcionar información relevante según la proximidad del usuario a los puntos de interés.

Esta funcionalidad beneficia a los usuarios al optimizar la visualización del mapa, ofreciendo información precisa y útil en momentos específicos durante su visita.

#### Modo de uso

* Seleccionar el lugar
* Alejar o acercar el zoom de una zona del mapa seleccionado
* *Debieran ir apareciendo pines al acercar el zoom y desapareciendo pines al alejar el zoom (de forma de que mientras mas lejano sea el zoom, solo se vean los pines de mayor relevancia)*

### Selección de un pin

En la vista principal de un lugar, los usuarios pueden explorar georeferenciadamente todos los pines disponibles. Al seleccionar un pin, se muestran el nombre y el logo del punto de interés, facilitando la búsqueda y identificación de lugares específicos.

Esta funcionalidad beneficia a los usuarios al proporcionar una manera fácil y rápida de encontrar puntos de interés en el mapa, mejorando la eficiencia y la experiencia de navegación.

#### Modo de uso

* Seleccionar el lugar
* Buscar un pin en el mapa y hacerle click
* *Debiera aparecer al menos el nombre y logo del punto de interés en un cuadro de la parte inferior de la pantalla*

### Detalles de un pin

Después de seleccionar un pin, los usuarios pueden acceder a información detallada, como descripciones, infografías, imágenes y horarios proporcionados por los administradores. Esto ofrece una comprensión más completa del punto de interés, mejorando la toma de decisiones del usuario.

Esta funcionalidad beneficia a los usuarios al proporcionar detalles específicos sobre los puntos de interés, mejorando la experiencia de exploración y permitiendo decisiones más informadas.

#### Modo de uso

* Seleccionar el lugar
* Seleccionar el pin
* Arrastrar el cuadro inferior hacia la zona superior de la pantalla
* *Debiera agrandarse la zona donde se muestra la información importante del punto de interés, en la cual se debiera poder navegar para ver texto, imágenes, horarios, etc. Acorde a lo que los administradores han agregado.*

<!-- ### Comentarios en un pin -->

<!-- Dentro de los detalles de un pin, cuando un usuario cree una cuenta, existirá la opción de realizar comentarios sobre el punto de interés.

Gracias a esto, los administradores y el resto del publico serán capaces de visualizar la opinion general del publico sobre el punto de interés y tomar las medidas correspondientes que crean necesarias -->
