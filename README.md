# Aplicacion pensada: App de mensajeria, tipo WhatsApp

## Historia 1

- **Prioridad:** Alta

- **Atributo de calidad:** Confiabilidad 

- **Cuando:** El usuario intente enviar o recibir un mensaje

- **Dado que:** El sistema se encuentra en estado normal

- **Yo como:** Usuario del sistema

- **Quiero:** Enviar o recibir mensajes sin fallos ni perdida de informacion

- **Y debe suceder:** Cuando yo o el otro usuario (quien me envia el mensaje a mi), presionemos el boton de enviar mensaje, debera llegar sin fallos ni perdida de informacion en los proximos 2 segundos (debe haber una conexion a internet)


## Historia 2


- **Prioridad:** Media

- **Atributo de calidad:** Autenticacion de usuario (login)

- **Cuando:** El usuario intente acceder a la aplicacion

- **Dado que:** El sistema se encuentra en estado normal

- **Yo como:** Usuario del sistema

- **Quiero:** Una ventana en la cual se me permita iniciar sesion con usuario y contraseña de forma rapida, facil y segura

- **Y debe suceder:** Cuando se ingresen mis credenciales y presione el boton iniciar sesion, el sistema debera permitirme o negarme el acceso, segun corresponda, en maximo 3 segundos (debe haber una conexion a internet)


## Historia 3


- **Prioridad:** Alta

- **Atributo de calidad:** Escalabilidad

- **Cuando:** La aplicación tenga un incremento en el número de usuarios o mensajes enviados.

- **Dado que:** El sistema se encuentra en sobrecargado

- **Yo como:** Usuario del sistema.

- **Quiero:** Que la aplicación funcione sin retrasos ni interrupciones, sin importar cuántos usuarios estén activos o cuántos mensajes se estén enviando simultáneamente.

- **Y debe suceder:** La aplicación deberá soportar al menos un 30% más de carga de usuarios y mensajes de forma eficiente.


## Historia 4


- **Prioridad:** Baja

- **Atributo de calidad:** Creación y gestión de grupos de chat

- **Cuando:** El usuario quiera crear o gestionar un grupo de chat.

- **Dado que:** El sistema se encuentra en estado normal.

- **Yo como:** Usuario del sistema.

- **Quiero:** Crear un grupo de chat donde pueda agregar o eliminar miembros, asignar administradores, cambiar el nombre y la imagen del grupo de forma sencilla.

- **Y debe suceder:** Cuando cree un grupo, este deberá estar disponible en la lista de chats para cada miembro del grupo. Los cambios en el grupo (agregar/eliminar miembros o actualizar información) deberán reflejarse en tiempo real para todos los miembros.


## Historia 5


- **Prioridad**: Alta.

- **Atributo de calidad**: Rendimiento.

- **Cuando**: El usuario envíe o reciba múltiples mensajes en una conversación activa.

- **Dado que**: El sistema se encuentra en estado normal.

- **Yo como**: Usuario del sistema.

- **Quiero**: Que los mensajes se envíen y reciban de manera instantánea sin retrasos perceptibles.

- **Y debe suceder**: Que al enviar o recibir un mensaje en una conversación activa, el sistema lo procese y lo muestre en pantalla en menos de 1 segundo, asegurando una experiencia fluida (debe haber una conexión a internet).


## Historia 6


- **Prioridad**: Media.

- **Atributo de calidad**: Búsqueda de mensajes.

- **Cuando**: El usuario intente buscar un mensaje específico en una conversación.

- **Dado que**: El sistema se encuentra en estado normal.

- **Yo como**: Usuario del sistema.

- **Quiero**: Poder encontrar mensajes antiguos rápidamente mediante una barra de búsqueda.

- **Y debe suceder**: Que al escribir palabras clave en la barra de búsqueda, los resultados relevantes aparezcan en un tiempo máximo de 2 segundos, permitiéndome navegar fácilmente entre los mensajes encontrados.


## Historia 7


- **Prioridad:** Alta  

- **Atributo de calidad:** Confidencialidad y protección de datos  

- **Cuando:** Un usuario inicie sesión o envíe un mensaje  

- **Dado que:** Los datos personales y mensajes deben estar protegidos  

- **Yo como:** Usuario de la aplicación  

- **Quiero:** Que mis conversaciones estén cifradas de extremo a extremo  

- **Y debe suceder:** Que solo el remitente y el destinatario puedan acceder al contenido de los mensajes, evitando que terceros puedan interceptarlos.  


## Historia 8


- **Prioridad:** Alta

- **Atributo de calidad:** Rendimiento y disponibilidad  

- **Cuando:** Un usuario envíe un mensaje de texto  

- **Dado que:** La comunicación debe ser rápida y confiable  

- **Yo como:** Usuario de la aplicación  

- **Quiero:** Que los mensajes se envíen y entreguen de manera inmediata  

- **Y debe suceder:** Que el sistema procese y entregue los mensajes en menos de un segundo, incluso en condiciones de red inestables.  


## Historia 9: Compatibilidad entre dispositivos


- **Prioridad:** Alta

- **Atributo de calidad:** Compatibilidad

- **Cuando:** Un usuario utilice la aplicación en diferentes dispositivos o sistemas operativos.

- **Dado que:** La aplicación debe ser funcional en múltiples plataformas.

- **Yo como:** Usuario de la aplicación.

- **Quiero:** Poder acceder a mis mensajes y conversaciones desde cualquier dispositivo sin perder datos ni funcionalidades.

- **Y debe suceder:** Que al iniciar sesión en otro dispositivo, mis conversaciones y configuraciones se sincronicen correctamente, sin errores ni pérdida de información, manteniendo la misma experiencia de usuario en diferentes sistemas operativos (Android, iOS, Windows, macOS, web).


## Historia 10: Notificaciones en tiempo real


- **Prioridad:** Alta

- **Atributo de calidad:** Disponibilidad y tiempo de respuesta

- **Cuando:** Un usuario reciba un mensaje o una actualización importante en la aplicación.

- **Dado que:** El usuario debe ser notificado inmediatamente de nuevos mensajes o eventos relevantes.

- **Yo como:** Usuario de la aplicación.

- **Quiero:** Recibir notificaciones instantáneas cuando alguien me envíe un mensaje o interactúe conmigo en la aplicación.

- **Y debe suceder:** Que las notificaciones push o internas se entreguen en menos de 1 segundo después de que el mensaje haya sido enviado, incluso cuando la aplicación esté en segundo plano o cerrada, asegurando que no haya retrasos perceptibles en la recepción de avisos.  


## Historia 11


- **Prioridad:** Media

- **Atributo de calidad:** Accesibilidad

- **Cuando:** Un usuario con discapacidades visuales o motoras intente utilizar la aplicación.

- **Dado que:** El sistema debe ser inclusivo y accesible para todos los usuarios.

- **Yo como:** Usuario con discapacidad visual o motriz.

- **Quiero:** Que la aplicación sea compatible con lectores de pantalla y permita comandos de voz o accesos rápidos para enviar y recibir mensajes.

- **Y debe suceder:** Que los textos de los mensajes, botones y notificaciones sean correctamente leídos por lectores de pantalla, y que existan accesos rápidos o comandos de voz para enviar mensajes sin dificultad.


## Historia 12


- **Prioridad:** Alta

- **Atributo de calidad:** Compartición de archivos

- **Cuando:** Un usuario intente enviar imágenes, videos o audios a través del chat.

- **Dado que:** La aplicación debe permitir el intercambio de archivos de forma rápida y eficiente.

- **Yo como:** Usuario de la aplicación.

- **Quiero:** Poder enviar y recibir imágenes, videos y audios sin pérdida de calidad y sin largos tiempos de espera.

- **Y debe suceder:** Que al seleccionar y enviar un archivo multimedia, este se cargue y se envíe en menos de 3 segundos en condiciones de red normales, asegurando una experiencia fluida sin afectar la calidad del archivo.
