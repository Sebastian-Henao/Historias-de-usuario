***Aplicacion pensada: App de mensajeria, tipo WhatsApp***

***Historia 1***

**Prioridad:** Alta

**Atributo de calidad:** Confiabilidad 

**Cuando:** El usuario intente enviar o recibir un mensaje

**Dado que:** El sistema se encuentra en estado normal

**Yo como:** Usuario del sistema

**Quiero:** Enviar o recibir mensajes sin fallos ni perdida de informacion

**Y debe suceder:** Cuando yo o el otro usuario (quien me envia el mensaje a mi), presionemos el boton de enviar mensaje, debera llegar sin fallos ni perdida de informacion en los proximos 2 segundos (debe haber una conexion a internet)


***Historia 2***

**Prioridad:** Media

**Atributo de calidad:** Autenticacion de usuario (login)

**Cuando:** El usuario intente acceder a la aplicacion

**Dado que:** El sistema se encuentra en estado normal

**Yo como:** Usuario del sistema

**Quiero:** Una ventana en la cual se me permita iniciar sesion con usuario y contraseña de forma rapida, facil y segura

**Y debe suceder:** Cuando se ingresen mis credenciales y presione el boton iniciar sesion, el sistema debera permitirme o negarme el acceso, segun corresponda, en maximo 3 segundos (debe haber una conexion a internet)


***Historia 3***


**Prioridad:** Alta

**Atributo de calidad:** Escalabilidad

**Cuando:** La aplicación tenga un incremento en el número de usuarios o mensajes enviados.

**Dado que:** El sistema se encuentra en sobrecargado

**Yo como:** Usuario del sistema.

**Quiero:** Que la aplicación funcione sin retrasos ni interrupciones, sin importar cuántos usuarios estén activos o cuántos mensajes se estén enviando simultáneamente.

**Y debe suceder:** La aplicación deberá soportar al menos un 30% más de carga de usuarios y mensajes de forma eficiente.

***Historia 4***

**Prioridad:** Baja

**Atributo de calidad:** Creación y gestión de grupos de chat

**Cuando:** El usuario quiera crear o gestionar un grupo de chat.

**Dado que:** El sistema se encuentra en estado normal.

**Yo como:** Usuario del sistema.

**Quiero:** Crear un grupo de chat donde pueda agregar o eliminar miembros, asignar administradores, cambiar el nombre y la imagen del grupo de forma sencilla.

**Y debe suceder:** Cuando cree un grupo, este deberá estar disponible en la lista de chats para cada miembro del grupo. Los cambios en el grupo (agregar/eliminar miembros o actualizar información) deberán reflejarse en tiempo real para todos los miembros.

***Historia 5***

**Prioridad**: Alta.

**Atributo de calidad**: Rendimiento.

**Cuando**: El usuario envíe o reciba múltiples mensajes en una conversación activa.

**Dado que**: El sistema se encuentra en estado normal.

**Yo como**: Usuario del sistema.

**Quiero**: Que los mensajes se envíen y reciban de manera instantánea sin retrasos perceptibles.

**Y debe suceder**: Que al enviar o recibir un mensaje en una conversación activa, el sistema lo procese y lo muestre en pantalla en menos de 1 segundo, asegurando una experiencia fluida (debe haber una conexión a internet).

***Historia 6***

**Prioridad**: Media.

**Atributo de calidad**: Búsqueda de mensajes.

**Cuando**: El usuario intente buscar un mensaje específico en una conversación.

**Dado que**: El sistema se encuentra en estado normal.

**Yo como**: Usuario del sistema.

**Quiero**: Poder encontrar mensajes antiguos rápidamente mediante una barra de búsqueda.

**Y debe suceder**: Que al escribir palabras clave en la barra de búsqueda, los resultados relevantes aparezcan en un tiempo máximo de 2 segundos, permitiéndome navegar fácilmente entre los mensajes encontrados.

