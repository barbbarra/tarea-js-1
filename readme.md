Identifica por qué el archivo javascript no se carga

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
    <script href="javascript.js"> </script>
  </head>
  <body>
  </body>
</html>

Respuesta:

linea 8 debiese ser src= no href


2 ¿Qué valor da la siguiente variable? ¿Por qué da ese valor?

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    <script>
     	var = a;
    	alert(a);
    </script>
  </body>
</html>

Respuesta:

No se ha definido el nombre de la variable y no se le ha puesto las '' en alert('a')



3---¿Cuál es el valor de la siguiente suma?

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    <script>
     	var miNumero = 3 + "3";
    	console.log(miNumero);
    </script>
  </body>
</html>

respuesta:
33 pq está sumando un número con un string


4---Descubre cúales eson los errores en el siguiente código:

<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    <script>
      Var Mis Vacaciones = "me faltan" + " " + 45 + "días para las vacaciones";
    </script>
  </body>
</html>

respuesta:

Var Mis Vacaciones = "me faltan" + " " + 45 + "días para las vacaciones";
var con minúscula y misVacaciones no puede haber espacios


5----<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>
    <script type="text/javascript">
    a = prompt("ingresa un número");
    b = prompt("ingresa otro número");
    alert("la suma es " + a + b );
    </script>
  </body>
</html>

Respuesta:

Se suman string y no numeros para pasar a números se debe

a = prompt("ingresa un número");
b = prompt("ngresa otro número");
alert(parseInt(a)+parseInt(b));
