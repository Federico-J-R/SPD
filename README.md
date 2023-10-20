## Integrantes 
- Federico Javier Rodriguez


## Proyecto: Contador binario.
![Tinkercad](./img/Parte1.png)


## Descripción
Diseñar un contador de 0 a 99 utilizando dos displays de 7 segmentos y tres botones para
controlar la cuenta. Debes implementar la técnica de multiplexación para mostrar los dígitos
en los displays. El contador debe comenzar en 0 y debe ser capaz de aumentar o disminuir
su valor en una unidad con los botones.

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

## Link al proyecto
- [proyecto Parte 1](https://www.tinkercad.com/things/cPZRakO8v8l?sharecode=4zw4omYo43QWZ-cez5j4xP895Vi6cKD3WPHlrawGe_s)

- [proyecto Parte 2.1](https://www.tinkercad.com/things/8SHYNW3vZca?sharecode=UxRMu7hsoRyqP1zi-bpJfc38KqyYmoQy4ftVkYA3EmE)

- [proyecto Parte 2.2](https://www.tinkercad.com/things/dAmwa2TJFZ8?sharecode=Z9OxSiw9o3XoiCG8D6WIGtDXGqcfqlGiPRuVMMkt_aU)
  
- [proyecto Parte 3](https://www.tinkercad.com/things/iMcCFf0yZyk?sharecode=-OHlYV-KR3sQyBG7x9PNRmm_n5a-KCH74JQI4oLUq_A)

