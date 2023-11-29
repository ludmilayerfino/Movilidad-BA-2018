<h1 align="center">MOVILIDAD EN EL AMBA CON PERSPECTIVA DE GÉNERO</h1>

<p align="center">
  <img src="https://github.com/ludmilayerfino/initial-project/blob/main/Datos/Fondo%20Mujer.png" alt="Texto alternativo" width="400"/>
</p>

<h1 align="center">PROGRAMA INGENIAS - Data Science - Grupo 6</h1> 

| Nombre| Formación de Base|Origen|
|-------|------------------|------|
|Ludmila Yerfino|Ingeniera Industrial|Malargüe - Mendoza - Argentina|
|Marcela Luciana Tobes|Licenciada en Economía|La Plata - Buenos Aires - Argentina|
|Marcela Karina Salinas|Industria del Petróleo|Comodoro Rivadavia - Chubut - Argentina|
|Marcela Adriana Salvattore|Abogada|Corrientes - Corrientes - Argentina|

## Objetivo
Analizar las tendencias en la movilidad en el Área Metropolitana de Buenos Aires, desglosando las variables con la mirada de género para poder proponer líneas de acción que hagan foco en las mujeres como usuarias con patrones específicos de movilidad.

## Fuentes de Información
Se tomó la Encuesta de Movilidad Domiciliaria 2018 generada por la Subsecretaría de Planificación de la Movilidad, de la Dirección General de Planificación, Uso y Evaluación, dependiente de la Gerencia Operativa del Observatorio de Movilidad y Seguridad Vial del Gobierno de la Ciudad de Buenos Aires.

Esta encuesta incluye las bases de hogares, personas, viajes, etapas, un diccionario y el cuestionario utilizado.

## Estructura de las bases de datos trabajadas
La muestra se basa en 16.667 hogares, 59.452 viajes y 49.271 personas, de las cuales el 51,3% son mujeres.

[Encuesta de Movilidad Domiciliaria](https://data.buenosaires.gob.ar/dataset/encuesta-movilidad-domiciliaria)

![BA DATA](https://github.com/ludmilayerfino/initial-project/blob/main/Datos/BA%20Data%20Logo.png)

## Tabla de Contenidos
Dentro del Repositorio principal, encontrarán 2 carpetas o directorios: "Datos", en la que hemos alojado las Bases de Datos con las que hemos trabajado; y "Notebooks", donde alojamos los archivos en los que hemos desarrollado el análisis, las visualizaciones y los modelos predictivos. Por fuera, además de éste detalle introductorio, encontrarán el Diccionario para comprender las nomenclaturas que se utilizaron y que por su extensión, se conservaron en un archivo .xlsx, no obstante lo cual, se clarifica lo siguiente:

|CONCEPTO| DESCRIPCIÓN|
|--------|------------|
|VIAJE| Es un desplazamiento de una persona que tiene un motivo, origen y destino, y se compone de etapas|
|MOTIVO| Es el objetivo del viaje: <li>2. Lugar de Trabajo</li><li>3. Asunto laboral </li><li>4. Estudios (lugar donde cursa)</li><li>5. Estudios (otros lugares)</li><li>6. Salud</li><li>7. Compras</li><li>8. Social</li><li>9. Familia</li><li>10. Deportes</li><li>11. Recreación</li><li>12. Personal</li><li>13. Trámite personal</li><li>14. Ir a buscar empleo</li><li>15. Dejar/ buscar o acompañar a un miembro del hogar a centro educativo</li><li>16. Dejar/ buscar o acompañar a un miembro del hogar a lugar distinto del centro educativo</li><li>17. Dejar/ buscar o acompañar a un NO miembro del hogar</li><li>22. Otro</li>| 
|ORIGEN y DESTINO| Son los puntos donde comienza y termina el viaje: del hogar a un establecimiento educativo, del trabajo al hogar, etc|
|SEXO|<li>1. Varón</li><li>2. Mujer</li>|

[DICCIONARIO EXTENDIDO](https://github.com/ludmilayerfino/Movilidad-BA-2018/blob/main/Diccionario.xlsx)

## Requerimientos técnicos
Para poder trabajar en la base de datos que creamos a partir de la fusión de las 2 bases de interés para los análisis que queríamos realizar, PERSONAS y VIAJES, utilizamos un entorno Anaconda, con Jupyter Notebook como interfaz y debimos hacer uso de las siguientes librerías: Pandas, NumPy, Seaborn, Matplotlib, Scikit-Learn y Scipy.
