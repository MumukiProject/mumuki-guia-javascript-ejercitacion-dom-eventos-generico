Queremos crear una página que nos permita hacer interacciones con números :1234:, se espera que la misma:

- tenga 10 botones con números del 0 al 9;
- abajo de esos 10 botones, uno para reiniciar, que diga `Reiniciar`;
- como último botón una para borrar, que diga `Borrar`;
- tenga un `span`;
- cuando se presionan los botones de números, se tienen que ir agregando los números en el `span`. Por ejemplo, si se presiona el 1 y después el 3, se tiene que mostrar `13`;
- no se permite ingresar más de 6 dígitos, en caso de ingresar 6 números y clickear un nuevo número, no debe pasar nada;
- el botón de reiniciar debe borrar todos los dígitos del `span`;
- el botón de borrar debe borrar el último dígito del elemento de texto. Por ejemplo, si el pin ingresado es `2544` y se presiona la tecla para borrar, debe quedar en `254`.

> Creá el código HTML y JavaScript para lograr el comportamiento que acabamos de describir.