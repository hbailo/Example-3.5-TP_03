# Utilización de clases BusIn/BusOut y PortIn/PortOut
En este trabajo práctico solo se utiliza únicamente BusIn porque los botones se hallan en puertos diferenetes y por lo tanto es inconveniente usar PortIn (hay que agrupar para cada puerto). Debajo se escriben las ventajas y desventajas de usar BusIn o PortIn

## Ventajas
* Escritura simultánea.
* Simplificación del código.
* Agrupación de salidas o entradas que comparten funciones similares

## Desventajas
* Limitación en la cantidad de pines.
* Requiere de uso detallado de de máscaras
