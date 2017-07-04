<section>

# Actividad Presencial 1 de Jquery.

https://github.com/DesafioLatam/Blearning-Frontend-E14CP1A1

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
	$('document').ready(function(){

	});
	~~~

## Ejercicios de desarrollo

Para realizar estos ejercicios entra a: https://jsfiddle.net/1fk5fyLc/7/
Recuerda documentar todos los pasos en un archivo llamado tunombre.md para que puedas subir tus respuestas a la plataforma.

- Pon tu nombre al atributo value del campo first name
- Pon el valor a la pregunta Favorite Day of Week a Monday
- Cambia la etiqueta de First name a 'Tu nombre'
- Obtén el valor del atributo 'name' del campo Favorite Day of The Week
- Escoge la opción Female de la pregunta de género.
- Encuentra la primera form del documento y pon el atributo name = personal_info
- Encuentra la primera form del documento y pon el atributo name = job_info
- Agrega un título h1 a cada una de las formas que diga 'Entrevista personal', 'Entrevista de trabajo' respectivamente
- Agrega un título a la pregunta Male/Female 'Gender'
- Agrega una pregunta Email: con un input de tipo texto después de last name
- Agrega la clase form a ambas for- </section>
