# TÍTULO DEL PROYECTO A SOLICITAR
Diseño e Implementación de comercio electrónico a nivel nacional 

## PROBLEMA
El comercio electrónico no es algo nuevo en el mundo, ni es el futuro ni una revolución que marca la diferencia, sin embargo la falta de compañías de comercio electrónico a nivel nacional es  notable, puesto que cuando se realiza una compra en línea de un producto, la entrega del mismo suele tardar como 10 dias mínimamente desde el momento de la compra , por lo que opta por tener una compañía de  comercio electrónico de compra y venta nacional haciendo que las entregas de productos sean razonables.

Recurriendo a esto se deja de depender de sistemas externos como ser amazon o ebay de tal forma que se tenga como opción utilizar recurrir a los otros sistemas en caso de estar buscando algún producto internacional o así mismo recurrir al sistema planteado y hacer la comercializacion mas cómoda y mucho mas rapida.

Por otro lado al tener este tipo de servicio a nivel nacional ayudaría a generar más comunidad entre los usuarios de cada departamento. 

## PROPUESTA GENERAL DE SOLUCIÓN
La empresa "electronic sales" desea implementar un sistema de compra y venta electrónico, para ello se propone diseñar e implementar un sistema que cumpla con los requerimientos descritos en el documento. 

## VALOR PARA EL NEGOCIO

### TANGIBLE
 - Evitará costos altos de envío entre departamentos.
 - Permitirá tener el producto que se adquirió en un tiempo razonable.
 
### INTANGIBLE

- Se generará una comunidad de usuarios a nivel nacional. 
- Brindará mayor confianza al realizar una compra en linea. 
- La ganancia se haría por cobros de comisión dependiendo del costo del producto a vender y se   tendrán inicialmente 3 categorías para el cobro de comision que seran las siguientes:
Si el producto cierra entre Bs 0 y Bs 175 se cobrará al vendedor un 5% del valor final de venta.
Si el producto cierra entre Bs 176 y Bs 7.000 se cobrará al vendedor un 5.% sobre los Bs 176 iniciales más 3% sobre el balance restante. 
Si el producto cierra a más de Bs 7.000 se cobrará al vendedor un 5% sobre los Bs 175 iniciales más 3% sobre el balance entre Bs 175 y Bs 7.000 y 1.5% sobre el balance restante. 


## FACTIBILIDAD (ANÁLISIS DE RIESGOS)

### ECONOMICA
- Inicialmente se requerirían unos 50 servidores para el almacenamiento del sistema y toda la información necesaria hasta verificar si el usuario final tiene la aceptación del sistema y así poder aumentar a la necesidad
- El sistema costará Bs. 22940 a razón de 2 programadores y 1 servidor web para 5 años.
 
### TECNICA
   - El sistema puede ser realizado sin mucho inconveniente tratándose del aspecto técnico pero con la excepción de que los usuarios están acostumbrados a utilizar tanto Amazon como Ebay para este tipo de transacciones por lo que el factor del cambio puede ser algo muy crítico al momento de la aceptación del sistema por parte del usuario y siga optando por usar otros comercios electrónicos.
 -

### ORGANIZACIONAL
    - Hará que las operaciones de intercambio de productos tenga menores tiempos de entrega
 - Fomentara la venta de productos nacionales.
 
# LISTADO REQUERIMIENTOS.
- 1 [El sistema debe ser una plataforma web que sea soportado en Safari y Chrome] (https://github.com/LauraPereyra/rfp/issues/1)
- 2 [Se debe permitir pagos con tarjeta de crédito o débito en la plataforma. (PayPal opcional)] (https://github.com/LauraPereyra/rfp/issues/4)
- 3  [Cada  usuario debe tener un perfil para tener un historial de las compras y ventas que hizo en su debido tiempo y así mismo se tenga puntuaciones de usuario (puntuación en base a la especificación del producto a vender o en relación a la cantidad de compras realizadas utilizando el sistema)] (https://github.com/LauraPereyra/rfp/issues/2)
- 4 [Un usuario puede tener el rol comprador y vendedor, dependiendo de las necesidades] (https://github.com/LauraPereyra/rfp/issues/6)
- 5 [El usuario con rol de comprador deberá tener la opción para calificar a los vendedores] (https://github.com/LauraPereyra/rfp/issues/3)
- 6 [Se podrá realizar búsquedas según a categorías de productos] (https://github.com/LauraPereyra/rfp/issues/7)
- 7 [Debe existir un carrito de compras, al cual se pueden añadir, eliminar o modificar productos] (https://github.com/LauraPereyra/rfp/issues/5)
- 8 [Se debe tener un desglose por producto, es decir, de cada producto se debe tener el detalle de precio, cantidades vendidas y cantidades restantes] (https://github.com/LauraPereyra/rfp/issues/8)

# Observaciones

## Explicar en detalle el proceso de entrega. 
Puesto que la empresa se caracteriza por ser C2C, el proceso de entrega será tercerizado, es decir que la empresa relaciona al comprador con el vendedor y la actividad comercial se lleva a cabo entre ambos. Cabe destacar que  en la descripción de cada artículo debe redactarse como se realizará la entrega. 

## Agregar a la factibilidad el detalle de cómo se maneja la seguridad.
La seguridad se terciarizará con respecto al pago por stripe/pay-me por lo que la única información que se maneja sería la información personal del usuario y los productos mostrados en venta mas no algún tipo de información delicada o que pueda comprometer en algún momento al usuario. 

## Dar soporte a todos lo navegadores desde IE 8
- 1 [Dar soporte a todos lo navegadores desde IE 8] (https://github.com/LauraPereyra/rfp/issues/1)

## Agregar información de PayME 
Optar por utilizar como plataforma de pago pay-me o stripe para simular pagos.

### Pay-me 
Red Enlace S.A. es una empresa especializada en la gestión de medios de pago electrónico. Esta empresa nos ofrece “Pay-me”, un servicio que permite recibir pagos con tarjetas de débito, crédito y prepago por internet, mediante una plataforma segura certificada bajo protocolo 3D-Secure. 

El proceso de compra con pay-me es el siguiente:
El comprador ingresa al sitio web de comercio electrónico.
El comprador llena el carrito de compras y luego ingresa sus datos dando inicio al proceso de pago (pay-me).
El comprador llena el formulario de pago e ingresa los datos de su tarjeta en un entorno totalmente seguro y certificado.
La tarjeta debe estar habilitada para compras por internet.
Finaliza el pago y la transacción es procesada.
Importante: El banco emisor de la tarjeta programa 3D secure, se pedirá al comprador registrar una clave que será enviada a su teléfono celular, para la autenticación.

(https://www.youtube.com/watch?v=o0u5CkCyqSs)

### Stripe 
Stripe desarrolla las herramientas más avanzadas y flexibles para el comercio electrónico. Las API’s de Stripe te ayudan a crear el mejor producto posible para tus usuarios: servicio de suscripción, marketplace "on demand", un establecimiento de comercio electrónico o una plataforma de microfinanciación. Miles de las empresas de tecnología más innovadoras del mundo crecen con más rapidez y eficiencia gracias a la integración de Stripe.

La forma más fácil de integrar Stripe es a través de Checkout, una herramienta integrada que se encarga de crear un formulario HTML, validar la entrada de los usuarios y asegurar los datos de la tarjeta de sus clientes. Usando Checkout, la información sensible de la tarjeta de crédito se envía directamente a Stripe, y no toca su servidor. Stripe vuelve a su sitio una representación simbólica de la tarjeta, y este símbolo puede ser utilizado en una solicitud de carga.

Stripe permite realizar pruebas en vivo y entrar en modo de prueba. Los modos de prueba y pruebas en vivo fueron diseñadas para funcionar casi idénticamente, con algunas diferencias necesarias:

- En el modo de prueba, las transacciones con tarjetas de crédito no se procesan a través de las redes de tarjetas reales y solo se pueden usar los números de tarjeta de prueba que proporciona stripe.

- El modo de prueba permite tener un balance de stripe para probar pagos.
- Las disputas también tienen un flujo más matizado en el modo en vivo, y un proceso de prueba más simple.

[Stripe] (https://stripe.com/es)

## Explicar cómo se gestiona el tema de los puntos y para qué sirve.
El tema de los puntos está plasmado con el siguiente cálculo siendo una propuesta inicial para la reducción de las comisiones:

  |Cantidad de ventas en caso de obtener 5 estrellas	   | 0  | 200  | 400  | 600  | 800  | 1000 |
  |-------------------------------------------------------|---|---|---|---|---|---|
  |Puntos 					  	   | 0  | 1000 | 2000 | 3000 | 4000 | 5000 |
  |Costo					  	   | 50 | 50   |  50  | 50   | 50   | 50   |
  |Disminución de la tasa de comisión  	   	   | 0  | 0.05 | 0.08 | 0.05 | 0.10 | 0.15 |
  |Total descuento 				   	   | 0  | 2.5  |  4   |  5   | 6.5  | 7.5  |

## ¿cómo van a gestionar disputas? 
Las disputas únicamente se harán entre comprador y vendedor ofreciendo un enlace por correo electrónico para que ambos arreglen el envío y recepción debido a que el modelo de negocio planteado sería C2C por lo que nos liberaremos de la responsabilidad en caso de reembolsos y/o extravíos.
Casos de disputas:
Artículos no recibidos → Una vez realizado el pago y en caso de no haber recibido el producto en el plazo previsto, debe comunicarse con el vendedor para que el mismo haga el seguimiento del paquete.
Artículos muy distintos a la descripción → si el producto adquirido no coincide con la descripción, debe comunicarse con el vendedor para acordar la devolución del mismo y el reembolso.
En caso de que el comprador no pueda de ninguna forma ponerse en contacto con el vendedor, la empresa proporcionará un número de contacto.




	

