# 01-7DaysOfCode

<h2><b>#7DaysOfCode</b> - Lógica JS 1/7: Operaciones Booleanas</h2>

<p>
  <b>Enviado por Alura Latam</b></br>
  Jose Gonzalez</br>
  Instructor Front-End en Alura Latam
</p>

<p>¡Llegó la hora, ! Vas a comenzar tu jornada en el #7DaysOfCode ;)</p>

<p>Este primer día es muy importante. Al final de él, tendrás un nuevo conocimiento que es esencial para los próximos desafíos.
Existe una situación muy común para quienes usan Javascript: problemas con los tipos de variables al comparar los valores de dos variables entre sí. ¡A mí me ha pasado mucho!
En lenguajes de programación compilados, como Java y C#, este problema se detecta en tiempo de compilación, y tienes un aviso claro del error mientras desarrollas el código.
En JavaScript, estos errores pasan desapercibidos, ya que el código no pasa por un compilador. Es decir, los errores solo aparecen en tiempo de ejecución.
La parte más confusa para quienes están comenzando a aprender lógica con JavaScript es la operación de igualdad entre valores. Dependiendo de cómo escribas tu código, JavaScript hará una conversión de tipo a un tipo booleano de manera implícita (automática), y esto afectará a variables que eran Strings, Numbers, Object, etc.</p>

<p>Esto causa algunos comportamientos extraños, como todos estos ejemplos a continuación que retornan true:</p>

<ul>
<li>console.log( false == '0' );</li>

<li>console.log( null == undefined );</li>

<li>console.log( " \t\r\n" == 0 );</li>

<li>console.log( ' ' == 0 );</li>
</ul>

<p>Lo cual no tiene necesariamente mucho sentido.</p>

** Este día 1 de actividad/desafío implica reescribir un código (codigoSugerido.js) para que funcione de forma correcta.
