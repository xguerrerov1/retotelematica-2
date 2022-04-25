Segundo reto de topicos de telematica

Instrucciones

Para este proyecto se necesitara EC2, para este reto su uso aws academy en su defecto.

Crearemos una maquina virtual ubunto a la cual le asignaremos una ip elastica a la cual le instalaremos Docker, MongoDB y dentro del la base de datos Wordpress todo esto se podra consulta facilmente en internet su instalcion (de preferencia hacer la busqueda del tutorial en ingles)

Ahora bien necesitaremos adquirir un dominio para el cual usaremos Freenom, es importante configurar adecuadamente nuestro dominio y haber asignado la ip elastica como se indico anteriormente para asignar dicha a nuestro dominio

Como se habia indicado debemos certificar nuestro sitio, con la herramienta de NGINX podremos realizarlo, primero la instalaremos y de esto hecho se correra el siguiente comando 

sudo certbot --nginx certonly -d *dominio* -d www.*dominio*


Bien ahora todo esta hecho y podemos usar nuestra pagina

loland.tk

![image](https://user-images.githubusercontent.com/88469900/165006594-db75b338-2339-4795-aa22-f85724422946.png)
