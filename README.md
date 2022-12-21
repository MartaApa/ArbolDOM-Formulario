# ArbolDOM-Formulario

## Requerimiento 1

Página web completamente por **JavaScript**, modificando el **árbol DOM**. La página web solo tiene un contenedor (DIV) y sobre dicho contenedor y por medio de JavaScript se añaden elementos a dicho contenedor. La temática de la web simula "*una agencia de viajes*". 
En este caso no fue necesario usar CSS, si no que la función principal fue usar funciones propias para modificar el árbol DOM y no usar innerHTML.

Se añadió los siguientes elementos HTML al formulario:
- Campos de texto donde poner el DNI, el nombre y los apellidos, la dirección y el teléfono.
- Dos radio button, con 4 opciones a elegir
- Cinco checkbox diferentes
- 2 imágenes
- Un campo select
- Un text area


## Requerimiento 2

**Formulario completo**, sin envío al servidor, que sirve para **dar de alta un pedido de una pizza** dentro de una web de una pizzería.

Los campos del formulario son los siguientes:
- Nombre
- Dirección
- Teléfono
- Email
- Un radio button con el tamaño de la pizza, pudiendo ser pequeña, mediana o grande
- 4 Checkbox con los diferentes ingredientes de la pizza
- Un botón de procesar el pedido

**Todos los campos** tienen que estar rellenos de tipo texto deben de estar **rellenos para que sean válidos**, además debe de **elegir obligatoriamente un tamaño** de la pizza y **al menos un ingrediente** para ella.

Al pulsar el *botón de procesar el pedido, se mostrará el precio total* del pedido calculándolo en base a los siguientes parámetros:

- 5€ para la pizza pequeña
- 10€ para la pizza mediana
- 15€ para la pizza grande
- Cada ingrediente elegido tendrá un valor de 1€
