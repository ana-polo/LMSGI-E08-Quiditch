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
		<br />
		<br />
		
			En el mundo mágico el principal deporte es el Quiditch, que se desarrolla mientras 14 jugadores, 
			7 de cada equipo, vuelan en escobas al tiempo que esquivan las bludgers ( tipo de pelota hechizada 
			que persigue a los jugadores de forma indiscriminada ). En cada equipo hay siete jugadores:
		
			<br />
					- Tres son cazadores, su cometido es lanzar la quaffle ( pelota especial ) e intentar que entre 
					por uno de los aros de gol. Obtienen diez puntos cada vez que la quaffle pasa por un aro. 
					<br />

					- El guardián, vuela alrededor de los aros de gol y detiene los lanzamientos del otro equipo.
					<br />

					- Dos golpeadores, cuyo trabajo es proteger a su equipo de las bludgers y desviarlas hacia el equipo contrario. 

					<br />
					- El buscador, vuela entre cazadores, golpeadores, la quaffle y las bludgers, intentando atrapar la snitch 
					 dorada ( una pelota pequeña con alas que vuela muy rápido y es difícil de coger, ya que está hechizada para 
					no dejarse atrapar ) antes de que la coja el otro buscador, porque cada vez que un buscador la atrapa, su 
					equipo gana ciento cincuenta puntos extra.
					<br />
		
			Un partido de quidditch sólo termina cuando se atrapa la snitch, así que puede durar muchísimo ( el record 
			son 3 meses 2 días y 3minutos ). 
			<br />

			El colegio de magia y hechicería Hogwarts celebra todos los cursos un campeonato de Quidditch entre las 
			cuatro casas del colegio, Gryffinfor, Ravenclaw, Hufflepuff y Slytherin. Los cuatro equipos compiten 
			entre sí para luchar por la Copa del colegio.
			<br />
		
			Para agilizar la gestión de los datos del campeonato, Albus Dumbledor, director del colegio de magia y 
			hechicería Hogwarts, ha contratado a los mejores especialistas en lenguajes de marcas, los alumnos muggles 
			del 1er curso de ASIR del IES Alisal, para hacer una aplicación xml que valide los documentos XML con la información 
			sobre cada uno de los partidos que tienen lugar. 
			<br />
		
			Estos ficheros XML han de contener la siguiente información sobre el partido:
			<br />
		
				- Equipos que lo juegan. ( Sólo pueden ser los equipos de las casas de Hogwarts ).
				<br />

				- Fecha del encuentro. 
				<br />

				- Duración del mismo. 
				<br />

				- Ganador. ( Su valor será el nombre del equipo ganador ). 
				<br />
			
				- Arbitro. Pueden ser la profesora. Hooch o el profesor Snape.
				<br />
			
				- Código de identificación del partido. Está formado por las iniciales de los equipos contrincantes, en mayúsculas, seguidas de un guión y cuatro cifras que representan el año del partido.
				<br />

			Sobre cada equipo se guardará la siguiente información:
			<br />
		
				- Nombre.
				<br />
			
				- Agrupar los jugadores que ocupan cada uno de los puestos. Hay que guardar, si es el caso, los goles que ha metido cada uno de los cazadores, las paradas del guardián y si el buscador ha capturado o no la snicht dorada. 
				<br />
			
				- Puntos conseguidos. 
				<br />
			
				- Código que lo identifica, se formará por las 3 primeras letras del nombre, en minúsculas, seguido de tres cifras. 
				<br />

			La información que queremos guardar de cada uno de los jugadores es:
			<br />

				- Nombre. 
				<br />

				- Número de faltas cometidas, si las hay. 
				<br />

				- Código identificador, que coincide con el expediente académico. Está compuesto de 8 Caracteres alfanuméricos. 
				<br />

				- Número de cursos que lleva formando parte del equipo.
				<br />

</details>
&nbsp;

👀 **¡Atención!**

- Prestar cuidado al uso de las marcas para tener un documento XML bien formado en todos los casos.

&nbsp;
