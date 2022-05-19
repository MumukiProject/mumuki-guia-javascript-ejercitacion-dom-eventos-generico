Queremos crear un programa que genere un número aleatorio entre 0 y 9. Cuando se presiona un número en el teclado, el programa debe mostrar en el documento `html` un mensaje mediante un `span`:

- si el número seleccionado es más grande que el número aleatorio generado, debe mostrar `El número es más chico`;
- si el número seleccionado es más chico que el número aleatorio generado, debe mostrar `El número es más grande`;
- si el número seleccionado es igual al número aleatorio generado, debe mostrar `Adivinaste`.

En todos los casos el mensaje también debe incluir el número ingresado (por ejemplo, `Número ingresado: 3`). 

Por ejemplo:

```
Número aleatorio: 7 (No se muestra)
El número presionado fue 3
"El número es más grande. Número ingresado: 3"
El número presionado fue 9
"El número es más chico. Número ingresado: 9"
El número presionado fue 7
"Adivinaste. Número ingresado: 7"
```

El `span` inicialmente debe decir `¡Nueva partida! Presione un número.`. El documento también debe tener un botón que diga `Reiniciar`, que genere un nuevo número aleatorio y reinice el texto del `span` a su contenido inicial. 

> Creá el código HTML y JavaScript que acabamos de describir.