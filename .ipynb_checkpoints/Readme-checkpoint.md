{
 "cells": [
  {
   "cell_type": "markdown",
   "id": "e22c9fb2",
   "metadata": {},
   "source": [
    "<div style=\"text-align: center;\">\n",
    "  <span style=\"font-size: 30px;\"><strong>PREDICCIÓN DE TENDENCIAS EN LA MOVILIDAD EN CABA</strong></span>\n",
    "</div>"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "8a4e6509",
   "metadata": {},
   "source": [
    "<div style=\"float: right; margin: 0px 200px 0px 0px\">\n",
    "  <img src=\"Ingenias Logo.png\" alt=\"Ingenias\" width=\"100\"/>\n",
    "</div>\n",
    "\n",
    "<div style=\"text-align: center;\">\n",
    "  <p><strong>STRAWBERRY TEAM - Ingenias Data Science</strong></p>\n",
    "</div>\n",
    "\n",
    "<table style=\"margin-left: 0;\">\n",
    "  <tr>\n",
    "    <td style=\"text-align:center\">Ludmila Yerfino</td>\n",
    "    <td style=\"text-align:center\">Ingeniera Industrial</td>\n",
    "    <td style=\"text-align:center\">Malargüe - Mendoza - Argentina</td>\n",
    "  </tr>\n",
    "  <tr>\n",
    "    <td style=\"text-align:center\">Marcela Luciana Tobes</td>\n",
    "    <td style=\"text-align:center\">Licenciada en Economía</td>\n",
    "    <td style=\"text-align:center\">La Plata - Buenos Aires - Argentina</td>\n",
    "  </tr>\n",
    "  <tr>\n",
    "    <td style=\"text-align:center\">Marcela Karina Salas</td> \n",
    "    <td style=\"text-align:center\">Industria del Petróleo</td>\n",
    "    <td style=\"text-align:center\">Comodoro Rivadavia - Chubut - Argentina</td>\n",
    "  </tr>\n",
    "  <tr>\n",
    "    <td style=\"text-align:center\">Marcela Adriana Salvattore</td>\n",
    "    <td style=\"text-align:center\">Abogada</td>\n",
    "    <td style=\"text-align:center\">Corrientes - Corrientes - Argentina</td>\n",
    "</table>\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "84a431c2",
   "metadata": {},
   "source": [
    "\n",
    "## Objetivo\n",
    "Analizar las tendencias en la movilidad en la Ciudad de Buenos Aires para con esa información poder, mediante la aplicación de modelos predictivos, establecer la proyección para la definición de los flujos de movimiento y en base a ello, diseñar estrategias de abordaje desde la política pública."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "f001fafe",
   "metadata": {},
   "source": [
    "## Fuentes de Información\n",
    "Se tomó la Encuesta de Movilidad Domiciliaria 2018 generada por la Subsecretaría de Planificación de la Movilidad, de la Dirección General de Planificación, Uso y Evaluación, dependiente de la Gerencia Operativa del Observatorio de Movilidad y Seguridad Vial del Gobierno de la Ciudad de Buenos Aires.\n",
    "\n",
    "Esta encuesta incluye las bases de hogares, personas, viajes, etapas, un diccionario de registros y el cuestionario utilizado.\n",
    "\n",
    "[Encuesta de Movilidad Domiciliaria 2018](https://data.buenosaires.gob.ar/dataset/encuesta-movilidad-domiciliaria)\n",
    "<div style=\"float: left; margin: 10px 10px 10px 10px\">\n",
    "  <img src=\"BA Data Logo.png\" alt=\"BA Data\" width=\"200\"/>\n",
    "</div>\n"
   ]
  },
  {
   "cell_type": "markdown",
   "id": "e9905e29",
   "metadata": {},
   "source": [
    "## Requerimientos técnicos\n",
    "Para poder trabajar en la base de datos que creamos a partir de la fusión de las 3 bases que contenía la encuesta, utilizamos un entorno Anaconda, con Jupyter Notebook como interfaz y debimos hacer uso de las siguientes librerías: Pandas, NumPy, Seaborn, Matplotlib y Scikit-Learn."
   ]
  },
  {
   "cell_type": "markdown",
   "id": "cb70dd1e",
   "metadata": {},
   "source": [
    "## Tabla de Contenidos\n",
    "Dentro del Repositorio principal, encontrarán 2 carpetas o directorios: \"Datos\", en la que hemos alojado las Bases de Datos con las que hemos trabajado; y \"Notebooks\", donde alojamos los archivos en los que hemos desarrollado el análisis, las visualizaciones y el modelo predictivo.\n",
    "Por fuera, además de éste detalle introductorio, encontrarán el Diccionario para comprender las nomenclaturas que se utilizaron."
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3 (ipykernel)",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.11.4"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 5
}
