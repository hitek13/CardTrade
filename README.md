# CardTrade
Online Shop project


Estructura (los nombres pueden variar):

index.php "Página de bienvenida, novedades, buscador y log-in de usuarios"
	
	buscador.php "Pagina con consula SQL mostrando resultados, busqueda de nombre"
	
	avcbuscador.php "Página con busqeuda avanzada: ediccion, habilidades, coste, precio... etc"
	
	carta.php "Página de una carta concreta y sus ofertas"
	
	vendedor.php "Página del vendedor y sus cartas en venta + valoraciones de usuarios"
	
	login.php "Página de registro"
	
	mipagina.php "Página donde el usuario puede cambiar sus datos o borrar su cuenta"
	
Base de datos s(los nombres pueden variar):

Tabla 1: 	Usuarios (idUsuario, Nick, Pass, Correo, Direccion, FecNac, Otros)

Tabla2:	  	Cartas (idCarta, Nombre, Imágen, Edicion, AtrEspeciales, Otros?)

Tabla3:	  	Usuarios-Cartas (idCarta, idUsuario, Precio, Foil, FullArt, Texture, Estado, Idioma, Cantidad)

Tabla4:	  	Atributos? (idAtributo, Nombre, Descripcion, Otros?)

Tabla5: 	Atributos-Carta (idCarta, idAtributos, Otros?)

	
	