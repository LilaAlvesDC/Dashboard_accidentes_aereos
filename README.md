# Análisis de accidentes de avión desde inicios de siglo XX 

La  **Organización de Aviación Civil Internacional (OACI)**, organismo de la Organización de las Naciones Unidas, quiere investigar en profundidad los accidentes producidos desde inicios del siglo XX. Para ello, les solicita la elaboración de un informe y un dashboard interactivo que recopile tal información.

La OACI únicamente cuenta con un dataset sobre datos de accidentes de aviones, pero insta a la consultora de datos -de la que forman parte- que intente cruzar esta información con otras fuentes de su interés. Esto con el objetivo de obtener mayor claridad y consistencia en los fundamentos del estudio.

## Investigación preliminar 

### **Sobre la OACI**

Organismo especializado de las Naciones Unidas, la OACI fue creada en 1944 para promover el desarrollo seguro y ordenado de la aviación civil internacional en el mundo entero. Formula las normas y reglamentos necesarios para la seguridad operacional, protección, eficiencia y capacidad de la aviación, así como para la protección del medio ambiente, entre muchas otras prioridades. Constituye un foro para la cooperación en todos los campos de la aviación civil entre sus 193 Estados miembros.

### **Definición: Accidente de aviación** 
El Anexo 13 del  _Convenio sobre Aviación Civil Internacional_, que contiene las normas y métodos recomendados para la  _Investigación de accidentes e incidentes de aviación_, define un accidente como todo suceso relacionado con la utilización de una aeronave:

> - en que cualquier persona sufre lesiones mortales o graves;  
> - en que la aeronave sufre daños o roturas estructurales que exigen reparación;  
> - tras el que la aeronave se considera desaparecida.

*Nota:* Asumimos que los datos proporcionados por la OACI solo incluye sucesos que cumplan con los criterios definidos en el anexo 13 del  _Convenio sobre Aviación Civil Internacional_. 

**Objetivo de la investigación de accidentes aéreos** 
El único objetivo de la investigación de accidentes en virtud del Anexo 13 es generar datos e información sobre seguridad operacional para ayudar a prevenir accidentes e incidentes semejantes en el futuro. Las investigaciones llevadas a cabo en virtud del Anexo 13 _no_ se ocupan de determinar la culpa o la responsabilidad.

## **Enfoques del análisis de los accidentes aéreos** 

El análisis de los accidentes aéreos se abordó desde cuatro enfoques, que son: 

 1. **Ubicaciones:** contrastamos las ubicaciones geográficas donde
    ocurriendo los accidentes  
 2. **Rutas:** contrastamos las diferentes rutas de viajes para explorar aquellas con mayores accidentes 
 3.  **Temporalidad:** exploramos la proporción y tendencia de las cantidad de accidentes ocurridos en diversas temporalidades (anual, mensual, semanal, diario) 
 4.  **Tipos de aeroplanos:** contrastamos los diversos aeroplanos con las cantidad de accidentes 

## **Reporte de análisis de datos de accidentes aéreos** 

En virtud de la misión de la Organización de Aviación Civil Internacional de generar datos e información sobre seguridad operacional para ayudar a prevenir accidentes e incidentes semejantes en el futuro, ponemos a disposición el siguiente reporte que pretende poner a disposición los casos en los que hubo mayor número de personas con lesionales mortales. 

#### Ubicaciones 
Los países donde ocurrieron hubo mayor cantidad de personas con lesiones mortales fueron: 

 1. Estados Unidos (193.110 víctimas)
 2. Rusia (83.690 víctimas)
 3. Brazil  (31.880 víctimas) 

![Ubicaciones con mayor cantidad de accidentes aéreos](https://github.com/LilaAlvesDC/Dashboard_accidentes_aereos/blob/main/_str/Pa%C3%ADses%20con%20mayores%20v%C3%ADctimas%20por%20accidentes%20de%20aviaci%C3%B3n.png?raw=true)

Uno de los primeros planeadores modernos fue construido en *Estados Unidos* en el año 1883 de manera los registros analizados reflejan que durante los años 1908 y 1922 todas las victimas por accidentes aéreos fueron de Estados Unidos. 

Por otro lado, Rusia registró su primera victima en el año 1923, siendo el año 1973 el año con mayor cantidad de Víctimas que coincide con el período de la existencia de la Unión Soviética, la Guerra Fría y la Guerra de Vietnam. 

Finalmente, el año que Brazil registró la mayor cantidad de víctimas por accidentes aéreos fue entre 2006 y 2009, período en el se registró el accidente más mortal de Air France en la historia, donde fallecieron 12 tripulantes y 216 pasajeros. 
 
#### Rutas
Las principales rutas con mayor cantidad de personas con lesiones mortales provenientes de las ciudades: 

1. Moscow, Rusia (21.300víctimas)
2. París, Francia (19.940 víctimas)
3. Nueva York, Estados Unidos (19.260 víctimas) 

De la misma manera, las principales rutas con mayor cantidad de personas con lesiones mortales provenientes de las ciudades: 

 1. New York, Estados Unidos (17.640 víctimas)
 2. París, Francia (15.630 víctimas)
 3. Londres, Inglaterra (14.290 víctimas)

#### Temporalidad
En relación a la temporalidad identificamos los años con mayor cantidad de personas con lesiones mortales fueron: 

 1. 1972 (27.960 victimas) 
 2. 1985 (25.900 victimas) 
 4. 1973 (23.230 victimas) 

![Año con mayor cantidad de accidentes aereos](https://github.com/LilaAlvesDC/Dashboard_accidentes_aereos/blob/main/_str/A%C3%B1o%20con%20m%C3%A1s%20v%C3%ADctimas%20por%20accidentes%20de%20aviaci%C3%B3n.png?raw=true)

#### Tipos de aeroplanos
En relación a los tipos de aeroplanos identificamos los años con mayor cantidad de personas con lesiones mortales fueron: 

 1. Douglas DC-3 (47.250 víctimas)
 2. Antonov AN-26(12.250 víctimas) 
 3. Douglas C-47 (10.590 víctimas)

![Tipos de aeroplanos con mas accidentes](https://github.com/LilaAlvesDC/Dashboard_accidentes_aereos/blob/main/_str/Aeronaves%20con%20m%C3%A1s%20v%C3%ADctimas%20por%20accidentes%20de%20aviaci%C3%B3n.png?raw=true )

## Conclusiones 

En general principales causas que ocasionan accidentes aéreos son las siguientes: 
1. Error de piloto 
2. Fallos mecánicos 
3. Meteorología adversa 
4. Sabotaje 
5. Error humano de controlador aéreo o persona en tierra 

En nuestro análisis identificamos que los períodos, regiones y tipo de aeronaves con mayor cantidad de víctimas por accidentes áereos en la historia coinciden con períodos de conflictos bélicos. Con lo cual hay una destacada tendencia negativa que inició en el año 1972, mismo año que registró el mayor número de victimas, hasta la actualidad donde la cantidad de víctimas se ha reducido en un 94%. 

Por último, en el año 2019 se registraron mas de 39 millones de vuelos de los cuales se registraron apenas 13 accidentes aéreos, con lo cual podemos concluir que en la actualidad las probabilidades de morir en un accidentes aéreo es 1 / 3 millones o 0,00003%. 

 ## Registro técnico del análisis de datos 

### **Análisis exploratorio de los datos y transformaciones**

Los datos proporcionados contamos con 5008 y con 17 columnas, como sigue: 

	1  fecha
	2  HORA declarada  
	3  Ruta  
	4  OperadOR  
	5  flight_no  
	6  route 
	7  ac_type
	8  registration  
	9  cn_ln  5008
	10  all_aboard
	11  PASAJEROS A BORDO  
	12  crew_aboard  
	13  cantidad de fallecidos  
	14  passenger_fatalities  
	15  crew_fatalities  
	16  ground  
	17  summary  
	dtypes: int64(1), object(17)

En el análisis exploratorio identificamos datos faltantes, inconsistentes y errores que fueron subsanados siguiendo los siguientes criterios: 

 1. Las filas cuyo único carácter era '?' fueron reemplazados por un campo vacío. 
 2. Los nombres de las columnas fueron renombrados en español 
 3. La columna de horas fue uniformada y transformada de formato militar a formato regular
 4. Extrajimos las palabras clave de las descripciones de los accidentes 
 5. Creamos una columna de sobrevivientes como resultado de la ecuación 'Total pasajeros a bordo' menos 'Total Fallecidos'
 6. A partir de la columna 'Fecha' fueron creadas las columnas año, mes y día
 7. A partir de la columna 'Ruta' fueron creadas las columnas 'Ciudad de Origen' y 'Ciudad destino' 
 8. A partir de la columna 'Ubicación accidente' fuer creada y transformada la columna 'País'

Luego de este proceso de análisis y transformación cargamos los datos en una base de datos para ser consultados por la plataforma de visualización. 
