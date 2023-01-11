# LMSGI-E08-Quiditch

![Logo de Team](https://github.com/ana-polo/LMSGI02-E01/blob/main/LMSGI.gif "Team logo")

## Table of Contents

1. Información General.
2. Tecnologias.
3. Definition del problema.

&nbsp;

### 1. Información General

***

Ejemplo de código XML y DTD para el módulo de Lenguajes de Marcas y Sistemas de Gestión de Información (LMSGI) del grado superior de Administración de Sistemas Informáticos en Red.

&nbsp;

### 2. Tecnologías

***

- *XML*

- *DTD*

- *XML Schema*

&nbsp;

### 3. Descripción del problema

<details>
	<summary>Leer las condiciones del problema</summary>
		En el mundo mágico el principal deporte es el Quiditch, que se desarrolla mientras 14 jugadores, 
		7 de cada equipo, vuelan en escobas al tiempo que esquivan las bludgers ( tipo de pelota hechizada 
		que persigue a los jugadores de forma indiscriminada ). En cada equipo hay siete jugadores:

			&nbsp;
			- Tres son cazadores, su cometido es lanzar la quaffle ( pelota especial ) e intentar que entre 
			por uno de los aros de gol. Obtienen diez puntos cada vez que la quaffle pasa por un aro. 

			&nbsp;
			- El guardián, vuela alrededor de los aros de gol y detiene los lanzamientos del otro equipo.

			&nbsp;
			- Dos golpeadores, cuyo trabajo es proteger a su equipo de las bludgers y desviarlas hacia el equipo contrario. 

			&nbsp;
			- El buscador, vuela entre cazadores, golpeadores, la quaffle y las bludgers, intentando atrapar la snitch 
			 dorada ( una pelota pequeña con alas que vuela muy rápido y es difícil de coger, ya que está hechizada para 
			no dejarse atrapar ) antes de que la coja el otro buscador, porque cada vez que un buscador la atrapa, su 
			equipo gana ciento cincuenta puntos extra.

		&nbsp;
		Un partido de quidditch sólo termina cuando se atrapa la snitch, así que puede durar muchísimo ( el record 
		son 3 meses 2 días y 3minutos ). 

		&nbsp;
		El colegio de magia y hechicería Hogwarts celebra todos los cursos un campeonato de Quidditch entre las 
		cuatro casas del colegio, Gryffinfor, Ravenclaw, Hufflepuff y Slytherin. Los cuatro equipos compiten 
		entre sí para luchar por la Copa del colegio.

		&nbsp;
		Para agilizar la gestión de los datos del campeonato, Albus Dumbledor, director del colegio de magia y 
		hechicería Hogwarts, ha contratado a los mejores especialistas en lenguajes de marcas, los alumnos muggles 
		del 1er curso de ASIR del IES Alisal, para hacer una aplicación xml que valide los documentos XML con la información 
		sobre cada uno de los partidos que tienen lugar. 

		&nbsp;
		Estos ficheros XML han de contener la siguiente información sobre el partido:

		&nbsp;	
			- Equipos que lo juegan. ( Sólo pueden ser los equipos de las casas de Hogwarts ).

			&nbsp;
			- Fecha del encuentro. 

			&nbsp;
			- Duración del mismo. 

			&nbsp;
			- Ganador. ( Su valor será el nombre del equipo ganador ). 

			&nbsp;
			- Arbitro. Pueden ser la profesora. Hooch o el profesor Snape.

			&nbsp;
			- Código de identificación del partido. Está formado por las iniciales de los equipos contrincantes, en mayúsculas, seguidas de un guión y cuatro cifras que representan el año del partido.

		&nbsp;
		Sobre cada equipo se guardará la siguiente información:

			&nbsp;
			- Nombre.

			&nbsp;
			- Agrupar los jugadores que ocupan cada uno de los puestos. Hay que guardar, si es el caso, los goles que ha metido cada uno de los cazadores, las paradas del guardián y si el buscador ha capturado o no la snicht dorada. 

			&nbsp;
			- Puntos conseguidos. 

			&nbsp;
			- Código que lo identifica, se formará por las 3 primeras letras del nombre, en minúsculas, seguido de tres cifras. 

		&nbsp;
		La información que queremos guardar de cada uno de los jugadores es:

			&nbsp;

			- Nombre. 

			&nbsp;

			- Número de faltas cometidas, si las hay. 

			&nbsp;

			- Código identificador, que coincide con el expediente académico. Está compuesto de 8 Caracteres alfanuméricos. 

			&nbsp;

			- Número de cursos que lleva formando parte del equipo.

</details>
&nbsp;

👀 **¡Atención!**

- Prestar cuidado al uso de las marcas para tener un documento XML bien formado en todos los casos.

&nbsp;
