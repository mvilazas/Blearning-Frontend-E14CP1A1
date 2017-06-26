<section>

# Actividad Presencial 1 de Jquery.

## Ejercicios de repaso de javascript y jquery

Para realizar estos ejercicios escribir dentro de un archivo .md

- ¿Qué se muestra en pantalla?

	~~~js
	a = 2
	a + 1
	console.log(a)
	~~~
- ¿Qué se muestra en pantalla?

	~~~js
	a = "2"
	a += 1
	console.log(a)
	~~~
- ¿Qué se muestra en pantalla?

	~~~js
	console.log( 2 + 3 * 5)
	~~~

	- ¿Por qué es relevante esta pregunta?
	- Cómo podríamos hacer para cambiar el orden de la operación
- ¿Qué se muestra en pantalla?

	~~~js
	function saludar(a){
		console.log("hola");
	}

	saludar
	~~~
	- ¿Qué hay que agregar para que el llamado a la función muestre en pantalla "hola"?
	- Hay algo en este código que está sobrando, ¿qué es?
- ¿Cuál es el error?

	~~~js
	var calcularIMC = function(peso, estatura){
		return peso / (estatura * estatura);
	}

	var interpretarIMC = function(peso, estatura){
		var imc = calcularIMC(peso, estatura);
		if (imc > 24){
			return "sobrepeso";
		} else if (imc > 19) {
			return "ok";
		} else {
			return "bajo peso";
		}
	}

	resultado = InterpretarIMC(95);
	console.log(resultado);
	~~~

- Qué hace?

	~~~js
	$( ".b1" ).html("html")
	~~~
- Qué hace?

	~~~js
	var text = $('.b1').html()
	~~~
- ¿Qué hace?

	~~~js
	$('.btn').on('click', function(){
		alert('dont click me');
	}
	~~~
- ¿Cuál es la utilidad del siguiente código?

	~~~js
	$('document').on('load', function(){
	}
	~~~

##Ejercicios de desarrollo
- Crear un input donde el usuario escribirá un color en inglés y un botón. El usuario al presionar el botón se debe cambiar el color de la página al color especificado.

- Crear dos input y un botón, el usuario debe ingresar su altura en uno de los inputs y el peso en el otro, se debe mostrar un mensaje con IMC resultante, si es normal, mostrar en verde, si es alto o bajo mostrar en rojo.

- Crear un input, un botón y otro input. El usuario debe ingresar un valor númerico en el primero, y al presionar el botón en el segundo input debe aparecer de forma automática el valor más el IVA (incremento del 19%)

- Crear tres inpus y un botón, los dos primeros inputs son para que el usuario ingrese su nombre y su apellido, al presionar el boton el texto del tercer input debe ser remplazado por la concatenación de los dos primeros.
	-  Cambiar el código anterior para que el texto del tercer input se modifique automáticamente cada vez que alguien escriba en los inputs sin necesidad de presionar algún botón.

- Crear dos inputs y un botón, el usuario debe ingresar un ancho en un input y un alto en el segundo, al presionar el botón se debe dibujar un cuadrado (para dibujarlo se debe utilizar CSS)

- Crear una página que tiene 2 columnas, en la columna izquierda se muestran productos donde cada producto tiene nombre, precio y un link agregar, cada vez que se presione alguno de los links se debe agregar el nombre del producto a la columna derecha.


</section>
