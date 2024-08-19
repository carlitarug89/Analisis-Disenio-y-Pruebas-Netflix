# Netflix


Netflix: se trata de una plataforma con una amplia variedad en películas, series y documentales. Los usuarios una vez suscriptos, tienen acceso ilimitado a todo el contenido disponible a través de sus dispositivos. Pueden crear distintos perfiles de usuario y personalizar el contenido que recomienda la plataforma dependiendo de sus preferencias.

## Análisis y Diseño

### Captura de Requerimientos


Para la aplicación seleccionada, Netflix, se capturarán requerimientos. En un primer momento, haremos una lista de requerimientos candidatos y luego los diferenciaremos entre requerimientos funcionales y requerimientos no funcionales. Para finalizar, seleccionaremos una lista definitiva de al menos 6 requerimientos funcionales y al menos 4 requerimientos no funcionales para la continuación del desarrollo de la resolución.<br> <br>

Lista de Requerimientos Candidatos

•	Suscribir a un plan

•	Iniciar sesión

•	Cerrar sesión

•	Crear perfiles de usuario

•	Ingresar a perfil de usuario

•	Buscar contenido

•	Agregar contenido a la categoría “Mi lista”

•	Reproducir contenido

•	Generar historial de reproducción

•	Personalizar recomendaciones

•	Descargar contenido

•	Calificar contenido

•	Generar subtítulos

•	Elegir idioma de reproducción

•	Visualizar notificaciones de novedades

•	Buscar contenido por categorías

•	Buscar contenido por idiomas

•	Generar tops de contenido por cantidad de reproducciones por país y mundiales

•	Generar categoría de contenido previamente reproducido con el nombre “volver a ver”

•	Seguridad

•	Interfaz de usuario

•	Velocidad

•	Escalabilidad

•	Protección de datos

•	Calidad

•	Disponibilidad

•	Rendimiento<br> <br>



División entre requerimientos funcionales y requerimientos no funcionales a partir de la lista de requerimientos candidatos:<br> <br>

Requerimientos Funcionales:

•	Iniciar sesión

•	Cerrar sesión

•	Crear perfiles de usuario

•	Personalizar perfil de usuario

•	Buscar contenido

•	Agregar contenido a “Mi lista”

•	Reproducir contenido

•	Generar historial de reproducción

•	Personalizar recomendaciones

•	Descargar contenido

•	Calificar contenido

•	Generar Subtítulos

•	Elegir idioma de reproducción

•	Generar notificaciones de novedades

•	Buscar contenido por categorías

•	Buscar contenido por idiomas

•	Generar tops de contenido por cantidad de reproducciones por país y mundiales

•	Generar categoría de contenido previamente reproducido con el nombre “volver a ver” <br> <br>


Requerimientos No Funcionales:

•	Seguridad

•	Interfaz de usuario

•	Velocidad

•	Escalabilidad

•	Protección de datos

•	Calidad

•	Disponibilidad

•	Rendimiento<br> <br>


Listado de requerimientos definitivos:<br> <br>

Requerimientos Funcionales:

RF01-Iniciar sesión: cada vez que el usuario desee acceder a la plataforma, deberá iniciar sesión. Para esto, se desplazará al botón iniciar sesión. En esta sección introducirá el correo electrónico o teléfono con el que se registró y la contraseña creada. El sistema validará los datos ingresados. Si son correctos, le permitirá acceder a todo el contenido de la plataforma.

RF02-Crear perfiles de usuario: el usuario podrá crearse distintos perfiles dentro de su propia cuenta. El límite es hasta 5 perfiles. En esta opción podrá personalizar la foto de perfil, con una selección de imágenes relacionadas al contenido disponible en la propia plataforma. Cada perfil podrá tener su propio nombre y también editar el contenido que se va a ver disponible para la persona relacionada a su edad (Todos los públicos/7+/10+/13+/16+/18+). 

RF03-Buscar contenido: el usuario dispondrá de un buscador para poder buscar la película o serie que desee. Este contenido puede buscarse dirigiéndose a la opción con el ícono lupa e introducir mediante teclado el nombre del contenido que desea reproducir o también puede introducir el nombre de un actor para ver su contenido subido a la plataforma. Por otro lado, se puede buscar a partir de las distintas categorías por género que se brinda.

RF04-Reproducir contenido: una vez que el usuario ha encontrado el contenido deseado para reproducir, el usuario puede dar “play” (reproducir) al contenido para comenzar su reproducción, podrá pausarlo y también salir. Por otro lado, podrá desplazarse a distintos momentos de la reproducción a través de la línea de tiempo de reproducción, o los íconos de atrasar y adelantar 10 segundos. 
Durante la reproducción del contenido elegido, se puede seleccionar la generación de subtítulos. Para esto, el usuario se dirigirá al ícono globo de conversación, que se encuentra entre las opciones que están en el borde inferior derecho. Dentro de la opción de Subtítulos puede desactivar o activarlos eligiendo el idioma en el que quiere que se muestren.
Durante la reproducción, también se puede el idioma de audio. Para esto, el usuario se dirigirá al ícono globo de conversación, que se encuentra entre las opciones que están en el borde inferior derecho. Dentro de la opción de Audio puede elegir de la lista desplegada el idioma en el que quiere reproducirlos.
Con cada reproducción, el sistema generará un historial de reproducciones para que quede guardado. Los datos que almacenará son el contenido reproducido, la fecha y hora de reproducción y la duración o tiempo de reproducción. De este modo, el usuario podrá continuar la reproducción desde el momento en que la detuvo.

RF05-Personalizar recomendaciones: el sistema personalizará distintas recomendaciones de películas y series dependiendo de las preferencias del usuario teniendo en cuenta su contenido reproducido y calificaciones realizadas.

RF06-Descargar contenido: el usuario, mientras tenga conexión a internet, podrá descargar contenido de la plataforma para poder reproducirlo luego de forma offline en sus dispositivos.

RF07-Calificar contenido: el usuario podrá calificar el contenido que reproduce dependiendo de su experiencia. También podrá visualizar las calificaciones para elegir a partir de ellas lo que desea ver.<br> <br>


Requerimientos No Funcionales:

RNF01-Seguridad: se deberán proteger los datos del usuario y los datos de pago.

RNF02-Interfaz de usuario: la interfaz utilizada deberá ser predecible, y debe poder adaptarse a distintos dispositivos. Estos dispositivos pueden ser celulares, computadoras y televisores.

RNF03-Escalabilidad: se debe tener en cuenta la conexión de gran cantidad de usuarios en forma consecutiva priorizando no perder la calidad de rendimiento.

RNF04-Calidad: la calidad de transmisión del contenido debe ser óptima adaptándose a las distintas resoluciones de pantalla y a la velocidad de conexión.

RNF05-Disponibilidad: el uso de la plataforma debe estar disponible todo el tiempo para que los usuarios puedan acceder cuando lo necesiten. Esto es, 24 horas al día.

### Diagrama de Casos de Uso

![image](https://github.com/user-attachments/assets/8e1994f6-127c-48db-80a8-7f121d83843e)

<br> <br>Este diagrama está conformado por 10 casos de uso y 2 actores que establecen relaciones entre sí:

Actores: Usuario, Sistema.

Casos de uso: Iniciar sesión, Crear perfil de usuario, Descargar contenido, Buscar contenido, Calificar contenido, Reproducir contenido, Generar subtítulos, Elegir idioma de reproducción, Generar historial de reproducción, Personalizar recomendaciones.

Utilización de include: Es utilizado en 3 casos: el usuario reproduce contenido en la plataforma. Esto incluye que el sistema genere un historial de reproducción. Por otro lado, el actor al reproducir contenido y al calificar contenido, incluye la personalización de las recomendaciones de contenido en la plataforma por parte del sistema conforme a sus preferencias.


Utilización de extend: Es utilizado en 2 casos: El usuario al reproducir el contenido elegido, tiene 2 acciones opcionales. Por un lado, puede generar subtítulos, activándolos, desactivándolos, escogiendo el idioma de la lista desplegada; por otro lado, puede escoger o cambiar el idioma en el que se reproduce el audio del contenido.

### Mapa de Trazabilidad

| ID Requerimiento | Requerimiento               | ID Caso de Uso | Caso de Uso                  | Comentario                                                                                         |
|------------------|-----------------------------|----------------|------------------------------|----------------------------------------------------------------------------------------------------|
| RF01             | Iniciar sesión               | CU01           | Iniciar sesión                | -El usuario inicia sesión <br> -El sistema verifica el inicio de sesión                             |
| RF02             | Crear perfiles de usuario    | CU02           | Crear perfiles de usuario     | -El usuario puede crear de 1 a 5 perfiles de usuario con contenido personalizado                    |
| RF03             | Buscar contenido             | CU03           | Buscar contenido              | -El usuario busca el contenido que desea reproducir mediante teclado o por categorías               |
| RF04             | Reproducir contenido         | CU04           | Reproducir contenido           | -El usuario puede reproducir el contenido que escoge                                                |
| RF04             | Reproducir contenido         | CU05           | Generar subtítulos            | -El usuario puede elegir si desea generar subtítulos                                                |
| RF04             | Reproducir contenido         | CU06           | Elegir idioma de reproducción | -El usuario puede elegir el idioma del audio en el que se va a reproducir el contenido elegido      |
| RF04             | Reproducir contenido         | CU07           | Generar historial de reproducción | -El sistema guarda lo reproducido por el usuario generando el historial de reproducción del usuario |
| RF05             | Personalizar recomendaciones | CU08           | Personalizar recomendaciones  | -El sistema puede personalizar las recomendaciones a partir de las calificaciones hechas por el usuario y de su contenido reproducido |
| RF06             | Descargar contenido          | CU09           | Descargar contenido           | -El usuario puede descargar contenido en sus dispositivos para luego reproducirlo de manera offline |
| RF07             | Calificar contenido          | CU10           | Calificar contenido           | -El usuario puede calificar el contenido con un sistema de opciones: “No es para mi”, “Me gusta” o “Me encanta” |

### Especificación

Las funcionalidades elegidas para realizar la especificación son:

•	Crear perfiles de usuario

•	Reproducir contenido<br> <br>

Crear perfiles de usuario:


| **Caso de Uso**                     | **Crear perfiles de usuario**                                                                                                                                                                                                                                                                                                                                 |
|-------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Actores**                         | Usuario, Sistema                                                                                                                                                                                                                                                                                                                                              |
| **Descripción**                     | Permite al usuario crear de 1 a 5 perfiles de usuario diferentes, en los cuales cada uno podrá personalizar el contenido con sus preferencias. También le dará un nombre, una imagen de perfil y se seleccionará el rango de edad al que pertenece el usuario.                                                                                                  |
| **Precondición**                    | - El usuario debe estar registrado a la plataforma <br> - El usuario debe iniciar sesión                                                                                                                                                                                                                                                                        |
| **Flujo Principal**                 | 1. El usuario debe dirigirse a la opción “Añadir perfil”. <br> 2. El usuario debe ingresar por teclado el nombre que le dará a su perfil. <br> 3. Se selecciona el idioma. <br> 4. El usuario seleccionará una imagen para personalizar el perfil. El sistema le ofrece imágenes relacionadas al contenido que hay dentro de la plataforma. <br> 5. El usuario selecciona su rango de edad. <br> 6. El usuario selecciona 3 opciones, entre contenido aleatorio o de su preferencia. |
| **Flujo Alternativo**               | En caso de que el usuario sea un menor: <br> - Al añadir un nuevo perfil y darle un nombre, el usuario debe seleccionar la casilla infantil en caso de tener menos de 13 años para que los contenidos se adecuen a su edad.                                                                                                                                      |
| **Postcondición**                   | El sistema muestra contenido dentro de cada perfil de usuario relacionado a la preferencia y edad del usuario.                                                                                                                                                                                                                                                  |
| **Excepciones**                     | Ninguna                                                                                                                                                                                                                                                                                                                                                        |


<br> <br>Reproducir contenido:



| **Caso de Uso**     | **Reproducir Contenido**                                                                                           |
|---------------------|---------------------------------------------------------------------------------------------------------------------|
| **Actores**         | Usuario, Sistema                                                                                                    |
| **Descripción**     | Permite al usuario reproducir el contenido que desea visualizar desde su dispositivo, en caso de tener conexión a internet o tenerlo descargado. |
| **Precondición**    | - El usuario debe iniciar sesión.<br>- El usuario debe haber creado un perfil de usuario.<br>- El usuario debe ingresar a uno de los perfiles creados. |
| **Flujo Principal** | - Una vez que el usuario elige que desea reproducir puede seleccionarlo.<br>- El usuario selecciona “play” para comenzar la reproducción del contenido.<br>- El usuario puede pausar la reproducción.<br>- El usuario puede moverse a distintos momentos de la reproducción desplazando la línea de tiempo reproducido.<br>- El usuario puede adelantar la reproducción con el ícono de adelantar 10 segundos.<br>- El usuario puede volver la reproducción con el ícono de atrasar 10 segundos.<br>- El usuario puede salir de la reproducción. |
| **Flujo Alternativo** | - El usuario puede elegir o cambiar el idioma de la reproducción.<br>- El usuario puede elegir si quiere utilizar subtítulos.<br>- El usuario dispone de un ícono dentro de la plataforma donde puede modificar el volumen.<br>- El usuario puede modificar la velocidad de reproducción. |
| **Postcondición**   | - El sistema guarda lo reproducido en el historial de reproducción. Con esto, el usuario puede continuar su reproducción a partir de cuando lo dejó.<br>- El sistema genera contenido personalizado de recomendaciones a partir de las reproducciones del usuario. |
| **Excepciones**     | - La reproducción del contenido online no se llevará a cabo en caso de falta o falla de internet. Se mostrará el mensaje: “Sin internet”.<br>- El contenido no podrá reproducirse en caso de tener abierto en más de una pantalla el mismo perfil de usuario. Se mostrará el mensaje: “Disculpa la interrupción. Parece que estás viendo Netflix desde más de un navegador o pestaña. Cierra los navegadores o las pestañas adicionales y vuelve a cargar la página. Si el problema no se soluciona, es posible que debas reiniciar el ordenador”. |


### Modelo de Dominio

![image](https://github.com/user-attachments/assets/a5d58b37-aa0c-4e5a-9c7d-bfe43983f1f9)

En el modelo de dominio podemos identificar la distintas entidades, atributos y relaciones que existen entre ellas.

Por ejemplo, podemos ver las siguientes interacciones:

- Un Sistema contiene a sus usuarios. 
-Un usuario puede iniciar sesión con su dirección de correo electrónico o teléfono y contraseña. El sistema se encarga de validar los datos para dar acceso a la plataforma.
- Un usuario puede crear un perfil de usuario. El sistema es capaz de generar desde 1 hasta 5 perfiles de usuario por cuenta.
- Un usuario puede buscar desde 1 a muchos contenidos dentro de la plataforma, también puede descargarlos, reproducir uno que elija y calificarlo. 
- Cada reproducción reproduce un contenido a la vez. Tiene como atributos play, pausa, salida, idioma y subtítulos. El usuario puede reproducir, pausar, salir del contenido, elegir el idioma de reproducción de audio y elegir los subtítulos. También puede desplazarse a distintos momentos del contenido, con los iconos de adelantar o atrasar 10 segundos y con la línea de desplazamiento.
- El sistema genera para el usuario un historial de reproducción a partir de las reproducciones hechas por el usuario.
- El sistema genera recomendaciones, las cuales son personalizadas a partir del historial de reproducción y las calificaciones. Luego esas recomendaciones llegan al usuario.

### Diagrama de Clases de Análisis

![image](https://github.com/user-attachments/assets/0822e721-4cf5-4e82-a32e-14d6e6455070)

En este diagrama de clases de análisis desarrollamos el requerimiento funcional Reproducir Contenido (RF04). Este requerimiento funcional, guiándonos por el mapa de trazabilidad, incluye los casos de uso Reproducir Contenido (CU04), Generar Subtítulos (CU05), Elegir idioma de reproducción (CU06), y Generar Historial de Reproducción (CU07). Para un mejor desarrollo, trazabilidad y entendimiento, se nombra otra entidad, la cual es Recomendaciones, que sugiere a otro requerimiento funcional relacionado (Personalizar Recomendaciones – RF05).<br> <br>

Podemos encontrar en el diagrama los siguientes elementos:

•	Clase de Interfaz: VentanaReproducción.

•	Clase de Entidad: Categorías, Contenido, Historial y Recomendaciones.

•	Clase de Control: ControladorReproduccion<br> <br>

Cada una de ellas con sus respectivos atributos y métodos. Todos los objetos de análisis interactúan mediante enlaces como instancias de asociación.


### Descripción del Paquete de Análisis y Arquitectura

![image](https://github.com/user-attachments/assets/95f0f0c6-8c9b-4aa6-bac7-9c2ef7444953)

Para la realización del paquete de análisis y arquitectura se plantea un paquete de análisis denominado “Gestión de Contenido”. Este paquete, contiene a su vez, tres paquetes los cuales son “Gestión de Recomendaciones”, “Gestión de Historial”, y “Gestión de Reproducción”. De esta manera, logramos graficar dependencias entre subsistemas.

El paquete “Gestión de Reproducción”, contiene al objeto interfaz llamado “VentanaReproduccion”, al objeto entidad “Categorías”, y al objeto entidad “ContenidoTitulos”.

### Diagrama de Colaboración

![image](https://github.com/user-attachments/assets/649cfb59-f951-4c58-8830-21187f166322)

Un diagrama de colaboración destaca la organización de los objetos que participan en una interacción. Los objetos que participan en dicha interacción, aparecen como nodos. 
En nuestro caso, serán el usuario, el objeto de interfaz Ventana Reproducción, el objeto de entidad Contenido y el objeto de Control llamado Control Contenido.

Podemos ver enlaces en el diagrama que representan una asociación entre los objetos, y también mensajes asociados a dichos enlaces, los cuales transmiten información a la espera de que se desencadene determinada actividad. De este modo, podemos visualizar de forma clara todo un circuito de mensajes y actividades que representan al requerimiento funcional de Reproducir Contenido.

### Diagrama de Secuencia

![image](https://github.com/user-attachments/assets/ad9c2994-38fa-4c59-b6c1-ddfcce92e19b)

En este diagrama podemos ver las interacciones entre objetos a medida que transcurre el tiempo. 
En nuestro caso, los objetos que intervienen en la interacción son: Usuario, Interfaz InicioSesión, Control Verificación, BaseDatos InicioSesion, Interfaz Reproducción, Control Contenido y BaseDatos Contenido. Luego, en el eje y podemos ver el tiempo transcurrido y los mensajes. 

Nuestro diagrama de secuencia actúa del siguiente modo:

En un primer momento, el usuario ingresa los datos para el inicio de sesión en la interfaz de inicio de sesión. Desde la interfaz de inicio de sesión se envía la solicitus para verificar los datos ingresados al control de verificación. Este control consulta y verifica en la base de datos que sea correcto. La base de datos de inicio de sesión devuelve el resultado al control de verificación y da por iniciada la sesión si los datos son correctos. En un segundo momento, el usuario busca contenido que desee reproducir en la interfaz de reproducción. Desde esta interfaz se envía la solicitud de la búsqueda realizada por el usuario al control de contenido. El control de contenido consulta y verifica en la base de datos de contenidos que lo que busca el usuario se encuentre o exista en la plataforma. La base de datos devuelve el resultado al control de contenido. Si el contenido se encuentra disponible, el control de contenido lo muestra en la interfaz de reproducción. Una vez hecho este proceso, el usuario puede reproducir el contenido en dicha interfaz.

### Diagrama de Clases del Diseño

![image](https://github.com/user-attachments/assets/483fd28c-0948-4a1b-b26f-4bd1cdedbef0)


En este diagrama de clases de diseño desarrollamos el requerimiento funcional Reproducir Contenido (RF04). Está conformado por seis clases, cada una con sus atributos, métodos y enlaces entre ellas. Estas clases son las siguientes:


CuentaUsuario: esta clase se relaciona con las categorías de contenido que ofrece la plataforma. El usuario a la hora de querer reproducir algún contenido, lo primero que va a hacer es buscar entre las categorías (consultarCategoria()). Relación: un usuario puede consultar de una a muchas categorías.

Categorias: esta clase representa a cada categoría de contenido de la plataforma, donde el usuario buscará lo que desea reproducir. Dado esto, esta clase se relaciona directamente con la clase Contenido. 

Relación: una categoría (o cada categoría) tiene de uno a muchos contenidos.

Contenido: esta clase y sus enlaces siguen la lógica del requerimiento funcional que se pretende representar. Aquí, se encuentran los principales métodos al momento de reproducir un contenido ya encontrado. En el diagrama se encuentra relacionado en dirección a la clase Historial. Relación: un contenido (o cada contenido) reproducido, puede guardarse en un historial

Historial: esta clase se relaciona con la clase Recomendaciones. Relación: un historial genera de una a más recomendaciones. Con esta relación se logra la personalización del contenido para el usuario.

Recomendaciones: esta clase está afectada por la clase Historial. Este historial determinará las recomendaciones que irán surgiendo, teniendo en cuenta el tipo de contenido reproducido hasta el momento. La clase Recomendaciones se asocia con la clase CuentaUsuario.
Relación: de una a muchas recomendaciones llegan a una cuenta de usuario de modo personalizado.

### Prototipos de Interfaz

Diseñados con Figma.

A partir de distintos elementos, como imágenes, formas y textos, se formaron los siguientes prototipos de interfaz correspondientes a la plataforma Netflix, intentando representar distintos casos de uso a los que puede acceder el usuario a través de ella:<br><br>

Prototipo de inicio de sesión:


Correspondiente al requerimiento RF01 (Iniciar sesión) y caso de uso CU01 (Iniciar sesión).
![image](https://github.com/user-attachments/assets/dc85ea6e-3c1b-4233-80a2-03915e35aeda)

Para acceder a los contenidos de la plataforma, el usuario deberá ingresar el correo electrónico o el número de teléfono, y contraseña con los que se ha registrado previamente. Puede tildar la opción Recuérdame para que la plataforma recuerde sus datos de inicio de sesión. Cada vez que el usuario introduzca sus datos de inicio de sesión, el sistema validará que estos sean correctos. En caso de que los datos sean incorrectos, el usuario puede ir a la opción “¿Necesitas ayuda?”.<br><br>

Prototipo de contenido de la plataforma:


Correspondiente al requerimiento RF03 (Buscar contenido) y caso de uso CU03 (Buscar contenido) y al requerimiento RF05 (Personalizar recomendaciones) y caso de uso CU08 (Personalizar recomendaciones).

![image](https://github.com/user-attachments/assets/ff86f31a-f95d-4e61-a7c6-6c95214c3c33)


El usuario al entrar a la plataforma, puede ver los contenidos en distintas categorías. Otra forma de encontrar contenido, es dirigirse al ícono de la lupa donde mediante la introducción por teclado, puede buscar el contenido que desea. Por su parte, el sistema, va a brindarle al usuario una categoría especial con una serie de recomendaciones determinadas por sus preferencias. Estas recomendaciones se personalizarán dependiendo del contenido previamente reproducido por parte del usuario y por las calificaciones que haya realizado.<br><br>



Prototipo de reproducción de contenido


Correspondiente al requerimiento RF04 y caso de uso CU04 (Reproducir contenido), al requerimiento RF04 y caso de uso CU05 (Generar subtítulos) y al requerimiento RF04 y caso de uso CU06 (Elegir idioma de reproducción).
![image](https://github.com/user-attachments/assets/d8217020-d1e5-4c98-8fbf-ca25cd90e41b)

Una vez que el usuario elige el contenido que desea ver, puede reproducirlo. En la pantalla de reproducción, tendrá distintos íconos con distintas funcionalidades. Con estos íconos podrá poner en marcha la reproducción, pausarla, o salir de ella. También podrá desplazarse a distintos momentos de la reproducción, a partir de la línea de tiempo de reproducción como también con los íconos de atrasar y adelantar 10 segundos. Puede manejar el volumen, la velocidad de reproducción, elegir el idioma de audio y los subtítulos. También puede saltar al siguiente episodio o siguiente contenido con el ícono ⊳|.


### Estrategia y Plan de Pruebas

Estrategias a seguir que nos permitirán validar el sistema:<br><br>

Niveles de pruebas y técnicas a evaluar<br> <br>

Nivel: Prueba de Unidad

Técnica: Prueba de Caja Negra: se utiliza cuando el único interés de una prueba es si una aplicación o parte de ella proporciona la salida adecuada, se prueba que cumpla cada requerimiento al usar la entrada apropiada. Las pruebas de caja negra pueden ser suficientes si se puede asegurar que agotan todas las combinaciones de entrada. Esto probaría al cliente que todos los requerimientos se satisfacen. Con esto, se podrá comprobar si las funcionalidades (casos de uso) hacen lo esperable, por ejemplo, si al pausar un contenido en reproducción, éste se pausa.

Nivel: Prueba de Integración: la verificación se reducirá a confirmar que se están uniendo justo los componentes que se planeó ensamblar, justo en la forma que se planeó ensamblarlos. Con esto, se podrá evaluar, por ejemplo, que la búsqueda de contenido para reproducir en la plataforma, se integre adecuadamente con la base de datos.

Nivel: Prueba de Sistemas: busca determinar si el sistema en su globalidad opera satisfactoriamente. Las funciones del sistema son ejercitadas y el programa es estresado para descubrir las limitaciones y medir los topes de capacidades. 

Pruebas de Aceptación de Usuario: Cuando las pruebas de sistema se completaron, comienzan las pruebas de aceptación. Tienen como propósito darle al cliente o al usuario final la confianza y la seguridad de que el sistema está listo para ser utilizado, por lo que encontrar defectos no tiene que ser el foco principal. Los sets de pruebas se arman con casos de las pruebas de sistemas. Incluyen transacciones y escenarios típicos del negocio. Frecuentemente, se hacen de manera informal y los registros se mantienen en función de cómo fueron los resultados.

Prueba No Funcional: Prueba de Interfaz de Usuario: En la actualidad, los sistemas cuentan con interfaces gráficas de usuario (GUI) cada vez más complejas. Es crucial que estas interfaces sean amigables y fáciles de usar. Esta prueba implica revisar el estado de los objetos, los modos de ventana, los menús, asegurándose de que los controles tengan un tamaño estándar, así como la revisión de la redacción y ortografía de los mensajes y cualquier otro texto que aparezca en pantalla.<br><br>

Especificación de casos de prueba.<br><br>

Caso de Uso: CU04 – Reproducir Contenido<br><br>


| **ID Caso de Prueba** | **Tipo de prueba**          | **Entrada**                                                                 | **Objetivo de la Prueba**                                                  | **Comportamiento esperado**                                               | **Comportamiento del Sistema**                                            |
|-----------------------|-----------------------------|-----------------------------------------------------------------------------|------------------------------------------------------------------------------|------------------------------------------------------------------------------|------------------------------------------------------------------------------|
| 001                   | Caja Negra                  | El usuario selecciona un contenido a reproducir.                            | Comprobar si al seleccionar un contenido para reproducir, éste se reproduce. | El contenido seleccionado por el usuario se reproduce correctamente.       | El sistema comienza la reproducción del contenido seleccionado por el usuario. |
| 002                   | Prueba de Integración        | El usuario selecciona un contenido a reproducir.                            | Comprobar que se integra el contenido con la base de datos.                  | El contenido seleccionado por el usuario es encontrado en la base de datos y se reproduce correctamente. | El sistema comienza correctamente la reproducción del contenido seleccionado por el usuario. |
| 003                   | Caja Negra                  | El usuario pausa la reproducción                                             | Comprobar que el contenido se pausa cuando elige hacerlo el usuario.        | Cuando el usuario pausa el contenido reproducido, éste se pausa correctamente. | El sistema pausa el contenido reproducido.                                 |
| 004                   | Caja Negra                  | El usuario se desplaza a distintos momentos de reproducción                  | Comprobar que el usuario puede desplazarse a distintos momentos de la reproducción. | El contenido reproducido puede desplazarse al momento seleccionado por el usuario. | El sistema le devuelve al usuario el momento exacto en la reproducción al que decide desplazarse y sigue su reproducción a partir de ahí. |
| 005                   | Caja Negra                  | El usuario detiene la reproducción                                          | Corroborar que la reproducción se puede detener.                             | El contenido reproducido se detiene.                                        | El sistema detiene el contenido cuando el usuario lo elige.                 |
| 006                   | Caja Negra                  | El usuario cambia el idioma de reproducción de inglés a español              | Comprobar que el idioma de reproducción de audio cambie de inglés a español. | El audio del contenido reproducido por el usuario cambia de inglés a español. | El sistema cambia el idioma del audio del contenido reproducido de inglés a español. |
| 007                   | Caja Negra                  | El usuario activa la generación de subtítulos en español                     | Comprobar que se activen los subtítulos en español.                          | Durante la reproducción del contenido se reproducen subtítulos en español.  | El sistema muestra por la pantalla de reproducción los subtítulos en español de lo que se está reproduciendo. |
| 008                   | Prueba de Interfaz de Usuario | El usuario adelanta 10 segundos en la reproducción con la selección del botón adelantar 10 segundos | Comprobar que el botón de adelantar 10 segundos funciona correctamente.      | El contenido reproducido se adelanta 10 segundos.                           | El sistema comprueba el correcto funcionamiento del botón de adelantar 10 segundos. Se adelanta 10 segundos la reproducción. |
| 009                   | Prueba de Interfaz de Usuario | El usuario retrasa 10 segundos en la reproducción con la selección del botón retrasar 10 segundos | Comprobar que el botón de retrasar 10 segundos funciona correctamente.       | El contenido reproducido se retrasa 10 segundos.                            | El sistema comprueba el correcto funcionamiento del botón de retrasar 10 segundos. Se retrasa 10 segundos la reproducción. |
| 010                   | Prueba de Interfaz de Usuario | El usuario selecciona la flecha salir, para salir de la reproducción del contenido. | Comprobar que el botón de salir funciona correctamente.                      | Se sale del contenido reproducido.                                          | El sistema comprueba el correcto funcionamiento del botón de salir. Se sale de la reproducción. Se sale de la interfaz de reproducción. |


### Documentos completos para el soporte de ejecución de la prueba

Nombre de Caso de Uso: CU04 - Reproducir Contenido<br><br>

Procedimiento de Prueba:<br><br>

1.	El usuario elige de la lista lo que desea reproducir.
2.	El sistema verifica que el contenido existe en la base de datos.
3.	El usuario selecciona lo que desea reproducir.
4.	El sistema accede al contenido desde la base de datos.
5.	El usuario selecciona “play” para comenzar la reproducción del contenido.
6.	El sistema verifica el correcto funcionamiento del botón “play”
7.	El sistema reproduce el contenido escogido por el usuario.
8.	El usuario cambia el idioma de reproducción de inglés a español.
9.	El sistema cambia el idioma de audio de inglés a español.
10.	El usuario activa la generación de subtítulos en español.
11.	El sistema muestra por la pantalla de reproducción los subtítulos en español de lo que se está reproduciendo.
12.	El usuario pausa la reproducción.
13.	El sistema verifica el correcto funcionamiento del botón “pausar”
14.	El sistema pausa el contenido reproducido por el usuario.
15.	El usuario se desplaza a distintos momentos de la reproducción.
16.	El sistema le devuelve al usuario el momento exacto en la reproducción al que decide desplazarse.
17.	El sistema continúa la reproducción del contenido a partir del punto desplazado.
18.	El usuario presiona el botón de adelantar 10 segundos el contenido en reproducción.
19.	El sistema comprueba el correcto funcionamiento del botón de adelantar 10 segundos.
20.	El sistema adelanta 10 segundos la reproducción.
21.	El usuario presiona el botón de retrasar 10 segundos el contenido en reproducción.
22.	El sistema comprueba el correcto funcionamiento del botón de retrasar 10 segundos.
23.	El sistema retrasa 10 segundos la reproducción.
24.	El usuario presiona el botón de salir de reproducción.
25.	El sistema sale de la reproducción del contenido.
26.	Salida de la interfaz de reproducción.
















