# TENDENCIAS EN LA MOVILIDAD EN CABA
## GRUPO 6 - FRUTILLITAS - Ingenias Data Science
![INGENIAS](https://github.com/ludmilayerfino/initial-project/blob/main/Datos/Ingenias%20Logo.png)

| Nombre| Formación de Base|Origen|
|-------|------------------|------|
|Ludmila Yerfino|Ingeniera Industrial|Malargüe - Mendoza - Argentina|
|Marcela Luciana Tobes|Licenciada en Economía|La Plata - Buenos Aires - Argentina|
|Marcela Karina Salinas|Industria del Petróleo|Comodoro Rivadavia - Chubut - Argentina|
|Marcela Adriana Salvattore|Abogada|Corrientes - Corrientes - Argentina|

## Objetivo
Analizar las tendencias en la movilidad en la Ciudad de Buenos Aires para con esa información poder, mediante la aplicación de modelos de clasificación y más adelante, predictivos, establecer la proyección de los flujos de movimiento y en base a ello, diseñar estrategias de abordaje desde la política pública.

## Fuentes de Información
Se tomó la Encuesta de Movilidad Domiciliaria 2018 generada por la Subsecretaría de Planificación de la Movilidad, de la Dirección General de Planificación, Uso y Evaluación, dependiente de la Gerencia Operativa del Observatorio de Movilidad y Seguridad Vial del Gobierno de la Ciudad de Buenos Aires.

Esta encuesta incluye las bases de hogares, personas, viajes, etapas, un diccionario de registros y el cuestionario utilizado.

[Encuesta de Movilidad Domiciliaria](https://data.buenosaires.gob.ar/dataset/encuesta-movilidad-domiciliaria)

![BA DATA](https://github.com/ludmilayerfino/initial-project/blob/main/Datos/BA%20Data%20Logo.png)

## Requerimientos técnicos
Para poder trabajar en la base de datos que creamos a partir de la fusión de las 3 bases que contenía la encuesta, utilizamos un entorno Anaconda, con Jupyter Notebook como interfaz y debimos hacer uso de las siguientes librerías: Pandas, NumPy, Seaborn, Matplotlib, Scikit-Learn y Scipy.

## Tabla de Contenidos
Dentro del Repositorio principal, encontrarán 2 carpetas o directorios: "Datos", en la que hemos alojado las Bases de Datos con las que hemos trabajado; y "Notebooks", donde alojamos los archivos en los que hemos desarrollado el análisis, las visualizaciones y el modelo predictivo. Por fuera, además de éste detalle introductorio, encontrarán el Diccionario para comprender las nomenclaturas que se utilizaron.

| CAMPO | DESCRIPCIÓN | CÓDIGO - VALOR |
|----------|------------|--------------|
|<span style="background-color: #0000FF; padding: 2px 4px; border-radius: 4px; box-shadow: 2px 2px 2px rgba(0, 0, 0, 0.4);">Vivienda</span> |Tipo de vivienda particular (observación)|<li>1. Casa</li><li>2. Rancho</li><li>3. Casilla</li><li>4. Departamento PH</li><li>5. Pieza en Inquilinato o Conventillo</li><li>6. Pieza de Hotel Familiar y/o Pensión</li><li>7. Construcción no destinada a vivienda</li><li>22. Otro</li>|
|Tiene Vehículos Motorizados|Sin incluir motos o ciclomotores ¿Tiene este hogar vehículo/s motorizado?|<li>1. Sí</li><li>2. No</li>|
|Tiene Motos|¿Tiene este hogar motos o ciclomotores? (que se encuentran en funcionamiento)|<li>1. Sí</li><li>2. No</li>|
|Tiene Bicis|¿Tiene bicicletas en el hogar?|<li>1. Sí</li><li>2. No</li>|
|Modo_Desplazamiento|Indica el tipo de viaje según un agrupamiento de los modos utilizados|<li>1. Una etapa en bicicleta</li><li>2. Una etapa a pie</li><li>3. Una etapa en taxi o remisse</li><li>4. Una etapa en transporte público (colectivo, tren o subte/premetro)</li><li>5. Una etapa en automóvil particular o moto/ciclomotor (conductor o acompañante)</li><li>6. Una etapa chárter/combi, bus de la empresa o transporte escolar</li><li>7. Dos o más etapas combinando transporte público (colectivo, tren y/o subte/premetro) y otro modo</li><li>8. Dos o más etapas en transporte público (colectivo, tren y/o subte/premetro)</li><li>9. Otros modo o dos o más etapas combinando modos que excluyen el transporte público (colectivo, tren y/o subte/premetro)</li>

### WARNINGS
Se encontrarán notas de alerta en aquellas líneas de código en las que consideramos debemos reveer, ya sea en su planteo, ya en su explicación.
