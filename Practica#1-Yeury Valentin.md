# Practica#1-Yeury Valentin



#### Este es un script en batch que hice para ver rápido cómo anda mi red. Nada muy loco, solo junta comandos útiles que aprendí en clase.



ipconfig

Muestra tu dirección IP, máscara de subred y puerta de enlace. Es lo primero que uso cuando no tengo internet. 



ipconfig /all

Da toda la info de red: IP, DNS, MAC, DHCP, y si estás conectado por Wi-Fi o cable. Muy útil para ver detalles. 



ipconfig /release

Libera tu dirección IP actual. El equipo deja de tener IP, como si se desconectara un momento. 



ipconfig /renew

Pide una nueva IP al router. Va bien si tenés problemas para conectarte, después de un release. 



ipconfig /flushdns

Limpia la caché de DNS. Sirve si un sitio no carga o te lleva a otro lugar. Como "refrescar" las direcciones. 



tracert google.com

Muestra el camino que recorre la señal desde tu PC hasta Google. Sirve para ver dónde se traba la conexión. 



nslookup google.com

Consulta el DNS para ver a qué IP pertenece un nombre. Ideal para ver si el problema es de resolución de nombres. 



netstat -ano

Lista todas las conexiones activas del equipo. Muestra puertos abiertos y el ID del proceso. Bueno para ver qué apps usan internet. 



arp -a

Muestra los dispositivos que tu PC conoce en la red local, con sus IPs y direcciones MAC. Como una libreta de contactos de red. 



route print

Muestra la tabla de enrutamiento. Dice cómo se envían los paquetes y por dónde. Útil para redes más avanzadas. 



getmac

Muestra la dirección MAC de tu tarjeta de red. Es única, como una huella dactilar del equipo. 



netsh interface ip show config

Muestra cómo está configurada cada interfaz de red. Sirve para ver si usás IP manual o automática. 



netsh advfirewall show allprofiles

Te dice si el firewall está activo en red privada, pública o de dominio. Bueno para ver si bloquea algo.



netsh advfirewall set allprofiles state off

Desactiva el firewall de Windows. Útil para pruebas, pero no lo dejes así mucho tiempo. 



netsh advfirewall set allprofiles state on

Vuelve a activar el firewall. Lo uso después de probar algo con él desactivado.



net use

Muestra o conecta unidades de red compartidas. Ideal si trabajás en una oficina o red local con carpetas compartidas. 



hostname

Muestra el nombre de tu equipo en la red. Así sabés cómo te ven los demás dispositivos. 





