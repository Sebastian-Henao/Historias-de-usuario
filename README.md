# Historias-de-usuario

## Historia 1


**Prioridad:** Alta

**Atributo de calidad:** Escalabilidad

**Cuando:** La aplicación tenga un incremento en el número de usuarios o mensajes enviados.

**Dado que:** El sistema se encuentra en sobrecargado

**Yo como:** Usuario del sistema.

**Quiero:** Que la aplicación funcione sin retrasos ni interrupciones, sin importar cuántos usuarios estén activos o cuántos mensajes se estén enviando simultáneamente.

**Y debe suceder:** La aplicación deberá soportar al menos un 30% más de carga de usuarios y mensajes de forma eficiente.

## Historia 2


**Prioridad:** Baja

**Atributo de calidad:** Creación y gestión de grupos de chat

**Cuando:** El usuario quiera crear o gestionar un grupo de chat.

**Dado que:** El sistema se encuentra en estado normal.

**Yo como:** Usuario del sistema.

**Quiero:** Crear un grupo de chat donde pueda agregar o eliminar miembros, asignar administradores, cambiar el nombre y la imagen del grupo de forma sencilla.

**Y debe suceder:** Cuando cree un grupo, este deberá estar disponible en la lista de chats para cada miembro del grupo. Los cambios en el grupo (agregar/eliminar miembros o actualizar información) deberán reflejarse en tiempo real para todos los miembros.