Aplicacion pensada: App de mensajeria, tipo WhatsApp

**Historia 1**

**Prioridad:** Alta

**Atributo de calidad:** Confiabilidad 

**Cuando:** El usuario intente enviar o recibir un mensaje

**Dado que:** El sistema se encuentra en estado normal

**Yo como:** Usuario del sistema

**Quiero:** Enviar o recibir mensajes sin fallos ni perdida de informacion

**Y debe suceder:** Cuando yo o el otro usuario (quien me envia el mensaje a mi), presionemos el boton de enviar mensaje, debera llegar sin fallos ni perdida de informacion en los proximos 2 segundos (debe haber una conexion a internet)


**Historia 2**

**Prioridad:** Media

**Atributo de calidad:** Autenticacion de usuario (login)

**Cuando:** El usuario intente acceder a la aplicacion

**Dado que:** El sistema se encuentra en estado normal

**Yo como:** Usuario del sistema

**Quiero:** Una ventana en la cual se me permita iniciar sesion con usuario y contraseña de forma rapida, facil y segura

**Y debe suceder:** Cuando se ingresen mis credenciales y presione el boton iniciar sesion, el sistema debera permitirme o negarme el acceso, segun corresponda, en maximo 3 segundos (debe haber una conexion a internet)
