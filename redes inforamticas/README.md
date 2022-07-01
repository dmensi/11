—  ¿Qué es una red informática?
Es un conjunto de computadoras conectadas entre sí compartiendo información, recursos como CD-ROM, impresoras, grabadoras de DVD y servicios como e-mail, Chat, conexiones a Internet, juegos, etc.
—  ¿Cuál es el objetivo de una red informática?
compartir , información u otros recursos
—  ¿Qué elementos se necesitan para hacer una red informática?
Equipo de computo, sistema operativo, modem, bridges, concentradores ,ruteadores , conectores, cables ya se de fibra óptica, cable par trenzado, cable coaxial ,tarjeta de red , Hub o Switch.
—  Elementos de red que puede estar incluido en las computadoras cuando se adquieren o se puede adaptar y que permite conecta alas computadoras en una red local que tiene un puerto rj45:
Modem      
  

Hub o Switch.
Tarjeta de red

Cables ya se de fibra óptica, cable par trenzado, cable coaxial
—  Elemento que sirve como concentrador al cual se conectan todas los cables de las computadoras en una red local, dicho componente puede tener 8,16,24,y 32 puertos para conectores rj45
 Switch o hub, Modem, Router ,Tarjeta de red.
·         Tipos de redes mas comunes que existen:
Redes de Área Amplia o WAN
Redes de Área Metropolitana o MAN
Redes de Área Local o LAN
—  Topologías de redes mas comunes que existen:
Topología de estrella
Topología de malla
Topología de árbol
Topología de bus
Topología de anillo

—  Se refiere ala forma física como se conectan las computadoras en una red informática
Las topologías o los tipos de redes
—  Se refiere al lugar geográfico en donde se ubica y la que abarca la red informática
Las topologías o los tipos de redes y  la forma en como están conectados los equipos.
—  Tipos de cables mas comunes que se utilizan en una red informática:
El cable coaxial
Cable par trenzado(utp o stp)
Fibra optica
·         Son nuevas tecnologías de comunicación en la época actual a través de dispositivos informáticos.
Las redes inalambricas, bluetooh, wireless internet, intranet ip, ups intranet.
—  Es el tipo de red que cubre un área de máxima a 100 m y que por lo general se utiliza en un edificio, es el tipo de área mas común:
La red de área local (LAN)
—  Es un tipo de red que cubre varios redes locales, que se puede cubrir una ciudad o un pueblo:
Redes de Área Metropolitana o MAN
—  Es la topología mas utilizada en la actualidad y es donde existe un concentrador y a el se le conectan los demás dispositivos para su comunicación:
Arbol
Bus
Anillo
estrella
—  Esta topología consiste en conectar las computadoras o nodos a un medio único y en el cual viaja la información pero si un nodo o PC se desconecta se cae toda la red:
La topología en estrella
—  3 características principales de una red informática:
Seguridad
flexibilidad,
confiabilidad
—  Nombre con el que se conocen las redes locales:
Red (LAN)
—  Es la red de redes, millones de computadoras conectadas entre si:
Redes de Área Metropolitana o MAN
—  Es un código que se le asigna ala tarjeta de red de cada equipo, cuando se conecta en red y cuyo código es único en toda la red ala que esta conectado:
¿Cómo se llama dicho código?
dirección MAC
IP o TCP
HTTP, SMTP, SSH y FTP.
rj45
—  Tipo de conector para el cable utp:
categoría 5
—  ¿Qué es modelo osi y para que sirve?
Es el modelo de redes estructurados en capas o niveles, cada nivel se desarrolla sobre el interior de tal forma que recibe una serie de servicios sin conocer los detalles de cómo se realizan dichos servicios.
sirve como marco de referencia para reducir la complejidad implícita en el estudio y diseño de las redes (LAN/WAN). El proceso de comunicación se describe como una jerarquía de siete capas o niveles. Cada capa tiene un propósito bien definido: brindar servicios de red a la capa superior, utilizando los servicios que le brinda la capa inferior. La capa de un nodo establece una comunicación virtual con la capa de otro nodo.


protocolo arp


También hay que mencionar que la caché ARP no es infinita, sino todo lo contrario. Tiene un tamaño limitado y además las direcciones solo permanecen en caché durante un tiempo. Esto es así para poder liberar espacio y también para evitar ataques cibernéticos que puedan robar o falsificar las direcciones. Si sabemos que un determinado equipo siempre va a tener la misma dirección IP-MAC, entonces podríamos añadir esta entrada en la tabla ARP como estática, no obstante, si por algún motivo este equipo cambia de IP, no podremos comunicarnos con él, porque nuesta tabla ARP no está actualizada.


En qué consiste el protocolo ARP

ARP son las siglas de Address Resolution Protocol. En español lo podemos traducir como Protocolo de resolución de direcciones. Es un protocolo de comunicaciones muy importante, ya que se encarga de vincular una dirección MAC o dirección física, con una dirección IP o dirección lógica. Este protocolo se desarrolló en la década de 1980 y hoy en día sigue siendo fundamental para el buen funcionamiento de las redes.

    La dirección IP se trata de un número que se le asigna y hace referencia a un equipo en una red. Tiene como fin el facilitar que estos se distingan dentro de la misma. Puede ser pública o privada. En cuanto a la primera, es la que nos facilita nuestro proveedor de internet (ISP), y que nos identifica en Internet. Por otro lado, la privada es la que se establece en los dispositivos dentro de nuestra red doméstica.
    En cuanto a la dirección MAC, es el número que identifica un componente de un equipo. En este caso, la tarjeta de red. Pueden ser utilizadas para permitir o denegar el acceso a internet de un equipo.

Se encarga de permitir que un dispositivo conectado a una red pueda obtener una ruta MAC de otro equipo que está conectado a esa misma red, es decir, se encarga de «localizar» donde están los demás dispositivos cableados o inalámbricos en la red, preguntando por la dirección MAC de cada uno de ellos enviando un paquete a la dirección de broadcast que es FF:FF:FF:FF:FF:FF. Permite transmitir datos a través de una trama, ya que este protocolo se encuentra a nivel de capa de enlace. Es importante ya que la longitud de las direcciones IP y MAC no son iguales. La primera tiene una longitud de 32 bits y la segunda de 48 bits.

Por tanto, lo que hace el protocolo ARP en el procedimiento de mapeo es traducir para que los sistemas puedan reconocerse entre sí. Hoy en día la resolución de direcciones IPv4 es la más utilizada, de ahí que este protocolo sea importante. ARP se encarga de «traducir» la dirección de 32 bits a 48 bits y viceversa, realmente lo que hace este protocolo es crear una tabla con una pareja IP-MAC donde posteriormente fijarse para poder transmitir todos los datos correctamente.
Cuál es el funcionamiento de ARP

Entonces, ¿cómo funciona exactamente el protocolo ARP? ¿Qué pasos son necesarios? Pongamos que hemos conectado un nuevo ordenador o cualquier dispositivo a la red. Ese equipo, para poder vincularse al router, va a recibir una dirección IP única. Esto es imprescindible para comunicarse y poder identificarse. Los paquetes de datos van a ir dirigidos a un host en particular. La puerta de enlace o el hardware de una red va a permitir que los datos fluyan y va a solicitar al protocolo ARP que encuentre una dirección MAC que coincida con esa dirección IP.

Hay que tener en cuenta que esta información se almacena en caché, por lo que ese paso se realiza la primera vez. A partir de ahí, la caché ARP mantiene una lista con las diferentes direcciones IP y direcciones MAC correspondientes, es decir, existe una tabla ARP que ya tiene guardada toda la información necesaria para que este proceso no sea necesario realizarlo continuamente.

Como dato a añadir, el propio usuario puede crear una tabla ARP estática donde almacenar esas direcciones IP y MAC. Pero de forma dinámica, esa caché ARP se almacena en los sistemas operativos en una red Ethernet IPv4. En cuanto un dispositivo va a solicitar la dirección MAC para enviar datos a cualquier otro equipo que esté conectado en esa red, se va a verificar la caché ARP. En caso de que exista, no sería necesario realizar una nueva solicitud.




ARP Spoofing

También se conoce como suplantación de ARP. Básicamente consiste en enviar ARP falsos. Puede asociar la dirección MAC de un atacante con una dirección IP. De esta forma podría recopilar información que se envía a través de una dirección IP y controlar el tráfico.

Este tipo de ataque permite que un pirata informático pueda robar datos importantes de cualquier usuario particular o empresa en caso de un ataque exitoso. Lo pueden llevar a cabo a través de un dispositivo que previamente han atacado y controlado o incluso el suyo propio si está conectado a la red local.

Esta amenaza se podría prevenir a través de tablas ARP estáticas. Esto evita que haya caché dinámica, aunque no es algo viable en la mayoría de casos. En estos casos tendríamos que mantener una inspección constante para evitar la suplantación. Para que este tipo de ataques puedan ocurrir es necesario que el ciberdelincuente utilice ciertas herramientas como pueden ser Arpspoof o Driftnet.

También podemos relacionar esto con los ataques Man in the Middle. Lo que hace el atacante es interceptar todo lo que se envía, como pueden ser contraseñas o datos. Si la red está desprotegida, puede llegar a suplantar la identidad y obtener cierta información confidencial. Lo que hace el atacante literalmente es estar en medio de la comunicación, escuchando todo lo que se envía y recibe.
