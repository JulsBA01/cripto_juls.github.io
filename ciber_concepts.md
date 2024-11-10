---
layout: default
---

# Ciberseguridad


**Seguridad Computacional:** Es la protección otorgada a un sistema de información automatizada para alcanzar los objetivos de preservar la integridad, disponibilidad y confidencialidad de los recursos del sistema.

Gracias a la definición de seguridad computacional podemos ver los objetivos principales de la ciberseguridad a los cuales se les conoce como la _triada de la CIA_.

## Triada de la CIA
>
>### Confidencialidad:
>Se busca asegurar que los datos del sistema de información no llegue a usuarios no autorizados.
>
>### Integridad:
>Se busca asegurar que los datos del sistema de información no sea alterada por usuarios no autorizados, la idea es que cada cambio en los datos del sistema de información >sean unicamente hechos por usuarios autorizados y que cada cambio sea monitoreado.
>
>### Disponibilidad:
>Se busca asegurar que el sistema funcione adecuadamente y que los datos no sean denegados a usuarios autorizados.
>
## Modelo OSI
>El modelo OSI divide el sistema de comunicación de red en 7 capas que nos ayudan a identificar dónde ocurre un problema en la red. Este modelo permite que diversos sistemas >de comunicaciones de conecten usando estas capas como un estándar.
>
>### Capa 7: Capa de aplicación:
>La capa de aplicación es responsable de los protocolos y la manipulación de datos de los que depende el software para presentar datos significativos al usuario. Es la única >capa que interactúa directamente con los datos del usuario.
>
>### Capa 6: Capa de presentación:
La capa de presentación es responsable de la traducción, el cifrado y la compresión de los datos. También es la encargada de comprimir los datos que recibe de la capa de aplicación antes de ser enviados a la capa 5.
 
### Capa 5: Capa de sesión:
Es la responsable de la apertura y cierre de comunicaciones entre dos dispositivos. Ese tiempo que transcurre entre la apertura de la comunicación y el cierre de esta se conoce como sesión. La capa de sesión garantiza que la sesión permanezca abierta el tiempo suficiente como para transferir todos los datos que se están intercambiando y luego que se cierre inmediatamente la sesión para evitar el desaprovechamiento de recursos. También sincroniza la transferencia de datos utilizando puntos de control.
 
### Capa 4: Capa de transporte:
Es responsable de las comunicaciones de extremo a extremo entre dos dispositivos. Antes de enviar los datos a capa 3, toma datos de la capa de sesión y los fragmenta en trozos más pequeños llamados segmentos. También es responsable del control de flujo y el control de errores. 

### Capa 3: Capa de red:
Es responsable de la transferencia de datos entre 2 redes distintas. Toma los segmentos de la capa de transporte y los divide en partes más pequeñas llamados paquetes en el dispositivo del emisor y une los paquetes en segmentos en el dispositivo del receptor. Esta capa también es la encargada de buscar la mejor ruta física para que los datos lleuen al destino(enrutamiento).

### Capa 2: Capa de enlace de datos:
Facilita la transferencia de datos dentro de la misma red. La capa toma paquetes de la capa de red y los divide en partes más pequeñas llamados tramas. Esta capa también es resposable del control de flujo y controles de comunicaciones dentro de la misma red.

### Capa 1: Capa física:
Esta capa incluye el equipo físico implicado en la transferencia de datos. En esta capa los datos se convierten en bits.
[back](./) 
