# Modelo TCP/IP
## 1. Responde a las siguientes cuestiones:
### a. ¿cuál es la IP de www.iesgrancapitan.org? ¿qué web encontramos en la IP 172.217.17.3?
**nslookup www.iesgrancapitan.org**

Address:  89.248.100.49

**nslookup 172.217.17.3**

Servidor:  apis.dptoinformatica.iesfuengirola1.net
### b. ¿cuál es la dirección de la red en la que está el dispositivo 11.11.11.11/11?
Para  11.11.11.11/11 serí 11.0.0.0
### c. ¿Cuántos equipos podemos conectar en una red con máscara 255.255.255.128?
2^7 - 2 = 126
### d. Busca un protocolo de cada capa del modelo TCP/IP e indica para que sirve
Capa de aplicación: HTTP (Protocolo de Transferencia de Hipertexto) - Sirve para la transferencia de documentos hipertexto, es el protocolo utilizado para la web.

Capa de transporte: TCP (Protocolo de Control de Transmisión) - Proporciona una comunicación fiable y orientada a la conexión entre aplicaciones.

Capa de Internet: IP (Protocolo de Internet) - Proporciona la base para el enrutamiento de paquetes y la entrega de datos entre redes.

Capa de enlace de datos: Ethernet - Define las reglas para la comunicación en la capa física de la red, incluyendo la estructura de tramas y la resolución de direcciones MAC.
### e. Resume al máximo la IP 2000:0F0F:0000:0000:0000:0000:0000:0F0F . Indica al completo la IP 2100:2::2000:202
se puede resumir como 2000:F0F:0:0:0:0:0:F0F.

Y se puede escribir en su forma completa como 2100:0002:0000:0000:0000:0000:2000:0202.
## 2. Realizar los siguientes cálculos numéricos:
### a. Pasar la IP 200.201.202.203 a binario y a hexadecimal
Binario: 11001000.11001001.11001010.11001011
Hexadecimal: C8.C9.CA.CB
### b. Pasar la MAC 88:99:00:AA:BB:CC a binario y decimal
Binario: 10001000.10011001.00000000.10101010.10111011.11001100
Decimal: 136.153.0.170.187.204
### c. Resultado en hexadecimal de la resta de hexadecimales: ABCD – 1111
La resta en hexadecimal sería: ABCD - 1111 = ABBC
### d. Resultado en binario de sumar los números binarios 1111111111 + 1
La suma binaria sería: 1111111111 + 1 = 10000000000
### e. Pasar 6543 (en base 7) a decimal
6*7^3 + 5*7^2 + 4*7^1 + 3*7^0 = 1715

### f. Pasar el decimal 1234 a base 14
1234 / 14 = 88 con residuo 2
  88 / 14 = 6 con residuo 4
   6 / 14 = 0 con residuo 6

Por lo tanto, 1234 en base 14 es igual a 6462.
## 3. Realiza en Packet Tracert una pequeña red mínima con dos PCs de forma que puedan comunicar por IPv4 e IPv6. Indica en el mismo archivo con la herramienta de texto como has comprobado ambas comunicaciones. Llama al fichero tarea1_3.pkt y envíalo junto con el archivo de respuestas en un archivo comprimido.
Para esto, puedes diseñar una red simple con dos PCs conectados a un switch, y el switch conectado a un router que soporte IPv4 e IPv6. Luego, puedes asignar manualmente direcciones IPv4 e IPv6 a las interfaces correspondientes, y probar la conectividad utilizando comandos de ping desde las terminales de los PCs.

## 4. En un instituto hay 1000 PCs para alumnos y 22 servidores para profesores y todos tienen conexión a internet a través de un router de fibra. Se pide configurar la red de todos los dispositivos indicando los siguientes parámetros:
4. Configuración de red para 1000 PCs y 22 servidores
a. Máscara de red, identificación de red, dirección de broadcast, IPs asignadas
Para configurar la red de acuerdo a los requisitos, necesitarías calcular la máscara de red para alojar a 1000 PCs y 22 servidores. Esto implicaría determinar el número mínimo de bits de subred necesarios para acomodar todos los dispositivos, y luego asignar las direcciones IP en función de la identificación de red y la dirección de broadcast.

Comandos para el CMD
Para conocer la IP de un dominio: nslookup www.ejemplo.com
Para encontrar el dominio asociado a una IP: nslookup IP
Para verificar la conectividad de red: ping IP_o_nombre_de_host
Para verificar la ruta que sigue un paquete hacia un destino: tracert IP_o_nombre_de_host
Para mostrar la configuración de red: ipconfig
### a. Máscara de red teniendo en cuenta que el tamaño de la red sea el mínimo necesario (indicar la máscara en formato binario, decimal por octetos y CIDR)

### b. Identificación de la red

### c. Dirección de broadcast

### d. IPs asignadas a los dispositivos
