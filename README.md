# GELIPAY, Tu seguridad es nuestra prioridad!

## Índice

* [1. Resumen del proyecto](#1-resumen-del-proyecto)
* [2. Imagen final del proyecto](#2-imagen-final-del-proyecto)
* [3. Investigación UX (Diseño de experiencia de usuario)](#3-investigación-ux-(diseño-de-experiencia-de-usuario))
* [4. Notas](#4-notas)

***

### 1. Resumen del proyecto

Este proyecto permite _validar_ el número de una tarjeta de crédito y devolver dicho número
ocultando todos los dígitos excepto los últimos 4, sin importar la longitud del número validado.

```js
maskify('4556364607935616') === '############5616'
maskify(     '64607935616') ===      '#######5616'
maskify(               '1') ===                '1'
maskify(               '')  ===                ''
```

***

### 2. Imagen final del proyecto


![imagen final proyecto](https://www.101computing.net/wp/wp-content/uploads/Luhn-Algorithm.png)

***

### 3. Investigación UX (Diseño de experiencia de usuario)

Este proyecto esta destinado para aquellas personas que prefieren realizar sus compras
de supermercado por internet, a través de una página segura y sin tener que compartir
su información financiera en cada sitio web que ingresen.

En **GELIPAY** podrás `validar` tu tarjeta de crédito y registrarla para realizar tus compras
de forma rápida y segura al momento de pagar en el sitio web del supermercado
de tu preferencia, evitando de igual forma demoras o problemas al realizar tu
pago web, ya que lo estarías realizando a traves de nuestra página.


##### Primer Sketch :pencil:

![Alt text](/relative/path/to/img.jpg?raw=true "Optional Title")

##### Primer Prototipo en Invision :joy:

![Alt text](/relative/path/to/img.jpg?raw=true "Optional Title")

##### Feedback primer Prototipo :hand: :traffic_light: :computer:

Los puntos más relevantes implementados a partir del _feedback_ recibido estaban relacionados
mayormente a la redacción de los `labels` para indicar al usuario donde ingresar el número de
la tarjeta de crédito, asi como en los nombres que debían llevar los botones por página y la
redacción de los mensajes de **Tarjeta Válida** Y **Tarjeta No Válida**. Principalmente apuntaban a
dejar la información más _clara_ al usuario, para evitar confusiones.


##### Prototipo Final :heart:

![Alt text](/relative/path/to/img.jpg?raw=true "Optional Title")


***

### 4. Notas :book:

Como tip para la realización de este proyecto, puedes revisar el Algoritmo de Luhn y los siguientes links con Recursos
para entender este proyecto:

* [Blog: cómo funciona el algoritmo de Luhn](http://www.quobit.mx/asi-funciona-el-algoritmo-de-luhn-para-generar-numeros-de-tarjetas-de-credito.html)
* [Valores, tipos y operadores](https://eloquentjavascript.net/01_values.html)
* [Expresiones y Operadores - MDN](https://developer.mozilla.org/es/docs/Web/JavaScript/Guide/Expressions_and_Operators)
* [Estructura del Programa (Variables, Control de flujo)](https://eloquentjavascript.net/02_program_structure.html)
* [Test Unitarios (Unit Texting)](https://martinfowler.com/bliki/UnitTest.html)
* [Npm funcionamiento](https://docs.npmjs.com/)

***

:computer: por Genesis y Eliana con :heart:
