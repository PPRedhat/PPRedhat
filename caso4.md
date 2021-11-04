# Caso No. 4

![Ref](Images/red-hat-logo.png)

# DESCRIPCIÓN DEL CASO 4

Una empresa del sector automotriz perteneciente al portafolio de clientes de Nexsys requiere implementar una infraestructura de TI. 

A continuación, se relacionan los retos a resolver para dicho propósito:

# ACTIVIDADES A REALIZAR

1.	La información importante de la empresa se encuentra en máquinas locales, los procedimientos no están documentados y su base de datos se encuentra en archivos de Excel, actualmente buscan implementar buenas prácticas en este sentido y desean que su sistema utilice el entorno GNU/Linux. Exponga mediante argumentos porque debería utilizar estas distribuciones y qué beneficios obtendría a nivel tecnológico.

2.	Configure un bloqueo automático de inactividad en la consola web.

3.	En una futura apertura de sedes, el administrador de sistemas deberá configurar servidores en diferentes países. Mediante el uso del comando tzselect, encuentre la zona horaria correcta de Costa Rica, Taiwán, Estados Unidos - Pacifico, Reino Unido (UK) y las Maldivas.

4.	Como parte del entrenamiento a los administradores en una futura implementación del protocolo IPV6, se necesita que compacte las siguientes direcciones siguiendo las dos reglas que existen para este fin:

a)	2001:0db8:3c4d:0015:0000:0000:1a2f:1a2b

b)	3FFE  :  0000  :  0654  :  FEDA  :  1245  :  0098  :  3210  :  0002

c)	3FFE  :  0000  :  0000  :  0000  :  1245  :  0098  :  3210  :  0002

5.	Muestre la IP pública de su máquina (Nota: usar el comando curl, instalar si se requiere)

6.	Muestre mediante el uso de la herramienta vmstat, la memoria activa e inactiva de la máquina y explique la información que muestra cada columna al ejecutar este comando.

7.	Usando el comando nmcli muestre el estado de todos los dispositivos de red de la máquina.

8.	Se requiere visualizar en pantalla las últimas 10 líneas del diario (journal) del sistema y que continúe proporcionando entradas nuevas a medida que se escriben.
	
9.	Se requiere eliminar el vínculo padre-hijo de 2 procesos, en este caso el proceso 1 es el terminal y el proceso 2 un editor de texto. Demuestre cómo lo realizaría usando el comando nohub.
	
10.	Mediante el comando logger, cree un log tipo info que se llame “local0.info” y que contenga el mensaje “Ha creado un log de información”.

# INSTRUCCIONES

Los casos de uso pueden ser aplicados sobre sistema operativos Red Hat, RHEL7, RHEL8 o CentOS7, CentOS8

Como recomendación principal es contar con un sistema de máquinas virtuales en su equipo de mesa o portátil y/o laboratorio local, le recomendamos realizar la instalación desde cero de la imagen del Sistema operativo elegido, como se indica en el punto número 1.

La imagen del Sistema operativo RHEL8 se encuentra en esta ruta, https://developers.redhat.com/download-manager/file/rhel-8.1-x86_64-dvd.iso. 

Adicionalemente instalamos la aplicacion Virtual Box desde el siguiente Link, https://www.virtualbox.org/wiki/Downloads, aqui encontraremos las versiones para el SO de preferencia en el apartado "VirtualBox 6.1.22 platform packages".

Es muy importante que antes de realizar las instalaciones, se debe activar la Virtualizacion del equipo, esto se realiza principalmente desde la configuracion de la BIOS.

En caso de no poder contar con dicho laboratorio, puede realizar el 90% de los puntos en este link:

https://www.katacoda.com/courses/centos/playground

Para ingresar a esta plataforma, se requiere registro, es rapido, con la limitación que este ambiente únicamente puede durar 10 minutos y en caso que el trabajo sea constante puede durar hasta 1 hora (NO MAS DE ESTO), asi que deberia sacar las evidencias de los resultados durante este tiempo, dicha terminal deja copiar y pegar entre pantallas.

# CALIFICACIONES
Para calificar hay 1 opcion de envio de resultados.

## Recopilacion de resultados de forma Manual
En cada uno de los pasos mencionados anteriormente enviar la salida de los comandos que permite ver la evidencia que el punto fue desarrollado, por medio de la herramienta de su preferencia, sea Word con imagenes descriptivas, presentaciones, archivos txt, Etc.

[Caso No. 1](Caso1.md)

[Caso No. 2](Caso2.md)

[Caso No. 3](caso3.md)

[Volver](README.md)
