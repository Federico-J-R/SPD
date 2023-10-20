## Integrantes 
- Federico Javier Rodriguez


## Proyecto: Contador binario.
![Tinkercad](./img/Parte1.png)


## Descripción
En este parrafo deberan describir que funcion cumple su proyecto. Que solucion esta ofreciendo.

## Función principal
La funcion se basa en las funciones prenderDigito(), la cual se encarga de encender y apagar los displays de 7 pines para alternar
que numero se muestra (Unidad y decena) y en la funcion prenderNumero(), la cual recibe como parametro un numero para mostrar por display.
En el caso de la decena se utiliza la operacion de division para mostrar el numero correspondiente a dicho display, mientras que para la unidad, se utiliza
la funcion modulo. Esta logica esta limitada para mostrar solamente numero con un maximo de dos digitos.

~~~ C (lenguaje en el que esta escrito)
void mostrarNumero(int numero){
{
  // PRENDER NUMERO DECENA
  prenderDigito(APAGADO);
  prenderNumero(numero/10);
  prenderDigito(DECENA);
  // PRENDER NUMERO UNIDAD
  prenderDigito(APAGADO);
  prenderNumero(numero%10);
  prenderDigito(UNIDAD);
}
~~~

## :robot: Link al proyecto
- [proyecto](https://www.tinkercad.com/things/aOYiibnDjWu)
## :tv: Link al video del proceso
- [video](https://www.youtube.com/watch?v=VyGjE8kx-O0)

---
### Fuentes
- [Consejos para documentar](https://www.sohamkamani.com/how-to-write-good-documentation/#architecture-documentation).

- [Lenguaje Markdown](https://markdown.es/sintaxis-markdown/#linkauto).

- [Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet).

- [Tutorial](https://www.youtube.com/watch?v=oxaH9CFpeEE).

- [Emojis](https://gist.github.com/rxaviers/7360908).

---
