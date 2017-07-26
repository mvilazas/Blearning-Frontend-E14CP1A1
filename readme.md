<section>

# Actividad Presencial 1 de Jquery.

https://github.com/DesafioLatam/Blearning-Frontend-E14CP1A1

## Ejercicios de repaso de javascript y jquery

Para realizar estos ejercicios escribir dentro de un archivo .md

###Respuesta 1
~~~js

			var calcularIMC = function(peso, estatura){
		return peso / (estatura * estatura);
	}

	var interpretarIMC = function(peso, estatura){
		var imc = calcularIMC(peso, estatura);
		if (imc > 40){
			return "sobrepeso";
		} else if (imc >= 18) {
			return "ok";
		} else {
			return "bajo peso";
		}
	}

	resultado = interpretarIMC(70 , 1.70);
	alert(resultado);
	</script>	
~~~

## Ejercicios de desarrollo

Para realizar estos ejercicios entra a: https://jsfiddle.net/1fk5fyLc/7/
Recuerda documentar todos los pasos en un archivo llamado tunombre.md para que puedas subir tus respuestas a la plataforma.

- Pon tu nombre al atributo value del campo first name
~~~js
$('input[name ="firstname"]').val("maximiliano")
~~~
- Pon el valor a la pregunta Favorite Day of Week a Monday
~~~js
$('select[name="fav_day"]').val("Monday")
~~~
- Cambia la etiqueta de First name a 'Tu nombre'
~~~js
$('label[name="first_name_label"]').text("Tu nombre")
~~~
- Obtén el valor del atributo 'name' del campo Favorite Day of The Week
~~~js
var fav_day = $('select[name="fav_day"]').val()
~~~
- Escoge la opción Female de la pregunta de género.
~~~js
$('input:radio[value="female"]').prop("checked",true)
~~~
- Encuentra la primera form del documento y pon el atributo name = personal_info
~~~js
$('form').first().attr("name=personal_info")
~~~
- Encuentra la primera form del documento y pon el atributo name = job_info
~~~js
$('form').first().attr("name=job_info")
~~~
- Agrega un título h1 a cada una de las formas que diga 'Entrevista personal', 'Entrevista de trabajo' respectivamente
- Agrega un título a la pregunta Male/Female 'Gender'
- Agrega una pregunta Email: con un input de tipo texto después de last name
- Agrega la clase form a ambas for- </section>
