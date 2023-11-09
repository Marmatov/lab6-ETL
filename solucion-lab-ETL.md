SELECT *
FROM Cities
INNER JOIN Concentrations USING(city)
ORDER BY 	Cities ."Total Population" DESC 
LIMIT 10;

SELECT *
FROM Cities
INNER JOIN Concentrations USING(city)
ORDER BY 	Cities ."Total Population" ASC 
LIMIT 10;

SELECT *
FROM Cities
INNER JOIN Concentrations USING(city)
ORDER BY 	Concentrations ."overall_aqi" DESC 
LIMIT 10;

estas fueron las querys que emplee para la base de datos para encontrar en la ciudades con mas poblacion y aquellas con menos poblacion

realmente en el analisis no se puede encontrar una relacion entre la calidad del aire dado que muchas de las ciudades no tiene una alta poblacion, incluso la poblacion no alcanza los 250.000 y tenian una de las peores calidades se deberia enfocar en cual es la industria principal de la ciudades