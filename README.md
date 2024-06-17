# tresCapasPhp
Muestra una aplicación web interpretada en un servidor local, 
desarrollada en capas y codificada en **lenguaje php**.

```bash
tresCapasPhp
├── credenciales.php
└── index.php
	├─modelo
	├─controlador
	└─vista
Diagrama 1. Modelo por capas.
```

# Desarrollo.
Muestra una aplicación web desarrollada por capas, codificada con un mismo lenguaje 
con distintas responsabilidades y fuertemente acopladas. 
Es una estructura de código *monolítco*. Es una práctica 
recurrente en aplicaciones básicas y, o sencillas, como se muestra en el 
Diagrama 1.

Tiene las siguientes prácticas de desarrollo:
     <ul> 
	 <li> 1. La aplicación es construida en sus elementos con la misma tecnología de lenguaje.</li>
	 <li> 2. La aplicación principal es autosuficiente, contiene y comparte 
			 los componentes, memoria, recursos y códigos distribuidos en clases y archivos
			 en una unidad cohesiva de código.</li>
	 <li> 3. Su ámbito son escenarios donde existe un _sistema informático 
			 autónomo_. Es decir, no existe una dependencia con servicios externos, 
			 para ejecutar su tarea principal; por ejemplo, una _computadora embebida_
			 para soporte de respiración asistida, un _sistema de inyección electrónico_ de 
			 combustible en un vehiculo. Su ámbito de operación es por sí 
			 mismo y no depende de nadie al ejecutar su tarea.</li>	
	 <li> 4. **NO** es apropiado para aplicaciones medianas a grandes,
			 donde conviven otras tecnológias de software.</li> 
	 <li> 5. **NO** se recomienda que el código php, renderize la capa de vista.</li> 
	 <li> 6. **NO** cumple con el principio de responsabilidad única [1]. </li>			 
	 <li> 7. El método _divide y venceras_  es difícil de aplicar, dado el nivel de 
			 complegidad y amplitud del proyecto. </li>
     <li> </li>
	 <li> </li> 			
	 <li> </li> 			
     </ul>
     
![capasModeloVistaControlador](/img/capasModeloVistaControlador.jpg "modelo en capascon Php")

Figura 1. Capas en aplicación web.

# Glosario. 
<ol>
<li>Php</li>
<li>Credenciales de acceso</li>
<li>capa de código</li>
<li>Renderizar</li>
<li>Principio de responsabilidad</li>
</ol>

| Palabra técnica| Definición | 
|:-------------- |:----------:| 
| Php            | Cell 2     | 
| Row 1          | Cell 2     | 
| Row 1          | Cell 2     | 
| Row 1          | Cell 2     | 
# Referencias.

[1]: https://es.wikipedia.org/wiki/SOLID 

     [1]: Ingeniería de software.
     Disponible en:<https://https://es.wikipedia.org/wiki/SOLID/> "Título"
     Consultado:04Jun24.


