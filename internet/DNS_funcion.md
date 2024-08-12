# ¿Que es un DNS y como funciona?
El DNS, o sistema de nombres de dominio, traduce los nombres de dominios aptos para lectura humana (por ejemplo, www.amazon.com) a direcciones ip aptas para lectura por parte de máquinas (por ejemplo, 192.0.2.44).

Todas los equipos con Internet, desde su teléfono inteligente o portátil a los servidores con contenido de sitios web de venta minorista masiva, se buscan y comunican entre sí mediante el uso de números. Estos números se conocen como direcciones IP. Cuando abre un navegador web y visita un sitio, no necesita recordar e ingresar un número largo. En su lugar, puede ingresar un nombre de dominio, como ejemplo.com, y de este modo también puede llegar al lugar correcto.

**Tipos de servicio de DNS**

* **DNS autoritativo:** un servicio de DNS autoritativo proporciona un mecanismo de actualización que los desarrolladores utilizan para administrar los nombres de DNS públicos. De esta forma, responde a las consultas DNS al convertir los nombres de dominio en direcciones IP para que los equipos se puedan comunicar entre sí. El DNS autoritativo tiene la autoridad final sobre el dominio y es responsable de brindar respuestas a servidores de DNS recurrente con la información de la dirección IP. Amazon Route 53 es un sistema de DNS autoritativo.

* **DNS recurrente:** los clientes normalmente no realizan consultas directamente a los servicios de DNS autoritativo. En su lugar, generalmente se conectan con otro tipo de servicio de DNS conocido como solucionador o un servicio de DNS recurrente. Un servicio de DNS recurrente funciona como el conserje de un hotel: si bien no es dueño de los registros DNS, funciona como un intermediario que obtiene la información del DNS por usted. Si un DNS recurrente tiene una referencia de DNS en caché o almacenada durante un período, entonces responde la consulta de DNS mediante el suministro de la información IP o la fuente. De lo contrario, pasa la consulta a uno o más servidores de DNS autoritativo para encontrar la información.

# ¿Como los navegadores cargan un sitio web?

![Como funciona un DNS](/img/dns-función.jpg)
