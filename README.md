# deploy-Laravel


La idea de este archivo, es que sirva de respaldo, para el que quiera leerlo.

Por lo tanto, lo primero que se tiene que crear es un VPS o servidor.ç
Uno siempre puede elegir, entre CentOs, Ubuntu, Windows, por preferencia, creo que uno de los mejores es ocupar Ubuntu.

Dentro de Ubuntu, se pueden manejar diferentes versiones, pero la idea es siempre estar con las más actualizadas, que tengan
su respectiva documentación y cuenten con respaldo.

Por ejemplo, para la fecha en que va a ser creado este documento, se tienen las distribuciones de Ubuntu:

- Ubuntu 16.04
- Ubuntu 18.04
- Ubuntu 20.04

Para nuestra comodidad, vamos a ocupar Ubuntu 16.04, pero lo ideal sería realizar el tutorial en las 3 distribuciones, de manera
que se abarquen todos los problemas que pudiera tener una persona al querer subir sus servidores a la web.


Aquí, se muestra una pequeña lista de cuales podrían ser los distintos proveedores de servidores, los cuales van a quedar a elección de
cada persona, ya que cada proyecto nos proveerá de distintas limitaciones económicas, que nos permitirán cambiar de servidores.

<ul>
<li>www.opencloud.cl</li>
<li>www.digitalocean.com</li>
<li>amazon.com</li>
<li>ibmcloud.com</li>
<li>googlecloud</li>

</ul>


El servidor que se va a comprar va a ser el más barato, el cual tiene un precio de $2500 +IVA ($2.975).- ésto es en pesos chilenos.
Si convertimos ésto a dólares, se convierte en casi 4 dólares.

Entonces, recibimos un correo de parte de nuestro proveedor, el cual nos indica las claves del servidor.

<h2>Hora de Comenzar a revisar este servidor </h2>

<h3> Conexión al Servidor</h3>

Por lo tanto, nos vamos a poder conectar de muchas formas a nuestro servidor.
- Mediante Putty si estás en Windows
- Mediante la consola de Windows, aunque es recomendable ocupar Power Shell.
(Si quieres una mejor experiencia en la Terminal, es recomendable que instales la consola de Ubuntu en Windows )

- Si estás en Linux, sólo es conectarte mediante la Consola.
- Si estás en Mac, también debes realizarlo por la Consola.

Entonces, lo importante es que despliegues la consola, sin importar en que carpeta te encuentres situado.

Ahora, debemos iniciar con una conexión SSH a nuestro servidor.

Para conectarnos, debemos hacer lo siguiente:

ssh root@"ip" aquí en ip, se reemplaza por la ip que te entregue tu proveedor de servidores.
Después simplemente se debe dar enter y completar la contraseña.



<h2>Caso Para Macintosh</h2>

Conexión para Macintosh, los que tengan Mojave o superior:
http://www.yellow-bricks.com/2018/11/26/ssh-broken-pipe-osx/


<h2>Comandos para moverse en el servidor</h2>
Comandos para moverse dentro de los servidores : 
https://www.hostinger.com/tutorials/ssh/basic-ssh-commands