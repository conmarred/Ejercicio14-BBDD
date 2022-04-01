# Configuracion

1. Primero debemos de crear el esquema "bbdd" en nuestro MySQL

2. A continuacion lanzar la siguiente instruccion sql

	CREATE TABLE `coches` (
	  `id` int(11) NOT NULL AUTO_INCREMENT,
	  `matricula` varchar(7) DEFAULT NULL,
	  `marca` varchar(20) DEFAULT NULL,
	  `modelo` varchar(20) DEFAULT NULL,
	  `numkilometros` int(20) DEFAULT NULL,
	  PRIMARY KEY (`id`)
	);


