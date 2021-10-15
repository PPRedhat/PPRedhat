# Caso No. 3

![Ref](Images/red-hat-logo.png)

# DESCRIPCIÓN DEL CASO 3
El administrador del departamento de sistemas de uno de los grupos de comercio al detal más reconocido del país comunica a la mesa de ayuda de NEXSYS el siguiente requerimiento:

## ACTIVIDADES A REALIZAR
1.	Se necesita efectuar el procedimiento de suscripción del sistema operativo Red Hat Enterprise Linux 8 del servidor principal.
2.	La empresa necesita añadir un banner a la página de inicio de sesión en la consola web de RHEL con el mensaje:

 “Welcome. All connections are monitored and recorded. Please, ¡disconnect IMMEDIATELY if you are not an authorized user!”

3.	El departamento de Tecnología tiene un directorio llamado “info_tech” en el cual se encuentra información importante que debe estar actualizada. Descargue del siguiente enlace: 
https://drive.google.com/file/d/18t21wcU01ChE1h7JFM57it2xconDLfrK/view?usp=sharing
el directorio mencionado, realice modificaciones en su contenido y demuestre como realizaría de forma remota la sincronización de los cambios realizados usando el comando “rsync”.

4.	Se necesita que el envío de ficheros entre los miembros del equipo de trabajo se realice con cifrado hashing. Indique el procedimiento correcto para realizar este envío y verificar la integridad de los archivos.
5.	Se requiere encriptar con cifrado simétrico un directorio llamado “Datos”.
6.	Por medio de la generación de una llave pública y privada, demuestre el ingreso sin solicitud de credenciales de una máquina a otra.
7.	Muestre los procesos del sistema con información detallada de los mismos.
8.	Con el fin de monitorear la memoria libre y usada del sistema, se necesita una línea de comandos que al ejecutarla muestre en pantalla la siguiente información:
a.	La memoria libre y usada por el sistema
b.	Espere 5 segundos
c.	Mostrar el directorio actual
d.	Espere 5 segundos
e.	Limpiar la pantalla.
9.	Establecer los permisos por defecto del archivo de texto “Ventas” y del directorio “Finanzas” a solo r--r--r-- (es decir, solo la lectura para el propietario, grupo y los otros).
10.	La empresa tendrá un usuario importante llamado sysadmin, para el cual se requiere lo siguiente:

a.	Cambiar la fecha de expiración de la cuenta al día 2022-01-28 al usuario llamado sysadmin	
b.	Establecer en 45 días el cambio de contraseña para el usuario sysadmin, es decir, podrá tener la misma contraseña 45 días.
c.	Establecer la advertencia de caducidad de contraseña para avisar al usuario sysadmin durante 10 días antes de que caduque su contraseña



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

[Volver](README.md)
