# QuarkChain
Translation whitepaper by @dblama


https://1drv.ms/w/s!AsoS-5SCUvPxhqdvCVJGngEIn6FTlw

You can check the translation on this link and here:

Resumen ejecutivo
Recientemente, se han distribuido tecnologías de registro – cadenas de bloques descentralizadas y verificadas( Bitcoin, Ethereum), empezaron reconduciendo la naturaleza de nuestra economía actual, comunicaciones y conocimiento. Debido al crecimiento del volumen de transaciones financieras globales en todos los productos electrónicos, la baja capacidad de las cadenas de bloques actuales y las redes basadas en estas, no se puede cubrir las necesidades del comercio mundial siempre. Sin embargo, una simple búsqueda para mejorar la escalabilidad normalmente sacrifica la descentralización y seguridad. Por lo tanto, la meta de la cadena bloque es mejorar la escalabilidad lo máximo posible mientras se mantenga la seguridad y la descentralización en un nivel apropiado.
Quarchain es una novedosa arquitectura de cadena de bloques con el objetivo de convertirse en el estándar comercial a nivel global. Ella provee una cadena de bloques segura, descentralizada y escalable para realizar 1.000.000+ transacciones por segundo (TPS). Las características principales de QuarChain son:
-	Cadena de bloques de 2 capas reutilizables: QuarkChain consiste en 2 capas de cadenas de bloques. Nosotros aplicamos una cadena de bloques con fragmentación elástica como primera capa, y una cadena de bloques raíz como segunda capa que confirma los bloques de la primera capa. La segunda capa es flexible para ser refragmentada si es necesario sin cambiar la capa raíz.
-	Garantizar la seguridad en la conducción del mercado con la minería colaborativa: para asegurar la seguridad de todas las transacciones, un marco de juego teorico esta diseñado para intentivar, donde al menos el 50% del poder total de hash esta localizado en la cadena raíz para prevenir ataques de doble envio en cualquier transacción.
-	Escalabilidad horizontal anticentralizacion: En cualquier red de cadena de bloques con un alto TPS, un super nodo puede ser extremadamente caro, lo que fomenta centralización. En contraste, QuarckChain permite multiples económicos nodos formando un cluster para remplazar el super nodo completo.
-	Transacciones efeccientes de fragmentación cruzada: Las transacciones de fragmentación cruzada en QuarkChain pueden ser resueltas en cualquier tiempo y confirmadas en minutos. La velocidad de las transacciones de fragmentación cruzada incrementan linealmente asi como el numero del fragmentos aumenta.
-	Gestion de cuentas simple: Solo se necesita una cuenta para todas las cadenas de bloques(fragmentos) en QuarkChain. Todas las crytomonedas de diferentes fragmentos están guardados en una Smart wallet.

 
Tabla de contenidos
1.	Motivacion y visión
a.	Vision general de la cadena de bloques
b.	Las generaciones de la tecnología de cadena de bloques
c.	Vision de QuarkChain
2.	Los desafíos de las cadenas de bloques
a.	Problemas de seguridad
b.	Problema de descentralización
c.	Problema de escalabilidad
d.	Compensaciones
3.	Tecnologia de QuarkChain
a.	Principio de diseño
b.	Arquitectura del sistema
c.	Mineria colaborativa
d.	Rapida verificación de la red QuarkChain
4.	QuarkChain posicionándose en la socidad de las cadenas de bloques
a.	Relacicones de QuarkChain con sistemas simples de cadenas de bloques o sistemas compuestos de cadenas de bloques.
b.	Posicion en seguridad, descentralizaccion y escalabilidad de QuarkChain
5.	Principales características de QuarkChain
a.	Expansion de la escalabilidad horizontal anti-centralizada
b.	Transacciones de fragmentación cruzada seguras y eficientes
c.	Manejo simple de cuentas
d.	Transaccion de cadenas cruzadas
6.	Aspectos operacionales del sistema QuarkChain
a.	Transacciones en la cadena y fuera de la cadena
b.	Contratos inteligentes
c.	Gestion de cuentas
d.	Cartera inteligente
7.	Ecosistema QuarkChain
a.	Economia de los tokens
b.	Desarrollo de negocio
c.	Desarrollo de aplicaciones
d.	Colaboradores de QuarkChain
8.	Carrera y línea del tiempo.
9.	Equipo de desarrollo
 
1.	Motivacion y visión

1.1	Vision general de la cadena de bloques

En los años 90, Kevin Kelly también advirtió al mundo sobre la llegada de la expansión de la encriptación – “Crypto-anarquia: la encriptación siempre gana.” “Varios criminales y elementos extranjeros serán usuarios activos de la CryptoNet. Pero eso no detendrá la difusión de la crypto anarquía” dicho por Tim May, un físico retirado de Intel(Citado por Out of Control). Tal y como May y Kelly predijeron, desde que la palabra “Blockchain” (Cadena de bloques) fue acuñada en el código fuente del Bitcoin en 2008, la crypto-epoca se inicio.

En los últimos 2 años, muchas compañías se han fijado en la tecnología de la cadena de bloques. Casi todas las mayores instituciones del mundo están haciendo investigaciones sobre la cadena de bloques en este momento. Por ejemplo, en 2016, la división educacional de Sony Global, desarrolló una tecnología que utilizaba las cadenas de bloques para almacenar datos educacionales que pueden ser fragmentados de manera segura con sevicios de terceras partes. Fig.1 muestra como desde finales de 2017, hay un increíble salto en el numero de solicitudes de transacciones en el sistema Ethereum. Esta demanda actualmente se mantiene en crecimiento desde que mas y mas aplicaciones están y serán desarolladas en un futuro próximo.

1.2	Las generaciones de la tecnología de cadena de bloques

Bitcoin es el primer y mayor experimento de moneda de la cadena de bloques. A pesar de que su capitalización de mercado maneja alrededor de 166M de dólares, está siendo utilizado por millones de personas para pagos y comercio de remesas. La tecnología de cadena de bloques bajo el Bitcoin es llamada como la primera generación.

La segunda generación de la tecnología de la cadena de bloques esta otorgada a Ethereum. Ethereum desarolló “contratos inteligentes” los cuales hacen que la cadena de bloques no solo permita el efectico como tokens sino también como instrumentos financieros, como prestamos o vinculaciones. La plataforma de contratos inteligentes de Etherum ahora tiene una capitalización de mercado de cerca de 84M de dólares.

Otro punto de corte en la innovación de la cadena de bloques es la llamada “prueba de participación (PoS)”. Actualmente la generación de la cadena de bloques esta asegurada por “prueba de trabajo (PoW)” la cual requiere de una cantidad significativa de poder de Hash(con su consecuente electricidad) lo cual en esta época, no energéticamente eficiente. A diferencia el sistema PoS asigna la recompensa de bloque a los propietarios de los tokens proporcionalmente, lo que reduce significativamente la cantidad de energía necesaria para minar un bloque lo cual es mucho mas eficiente económicamente.

Con el aumento de demanda, que hemos visto en la figura 1, otro de los problemas que tiene la cadena de bloques es la escalabilidad. Al principio, en en mundo de las cadenas de bloques, cada computadora en la red procesaba cada transacción. 

PAGINA 7


