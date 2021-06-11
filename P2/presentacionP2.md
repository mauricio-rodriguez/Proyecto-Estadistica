Impacto del proceso de vacunación contra el Covid-19
========================================================
author: 
date: 
autosize: true

Importancia
=========================================================
El estudio busca sensibilizar e informar a la población sobre los efectos generados por el proceso de vacunación contra la Covid-19 en las regiones del Perú, por lo que se considera un tema de interés público debido al contexto actual.
<div align="center">
<img src="imgs/imagenVacunas.jpg" width=600 height=400>
</div>

Obtención de los datos
========================================================
Plataforma Nacional de Datos Abiertos
- [Datos sobre vacunados](https://www.datosabiertos.gob.pe/dataset/vacunaci%C3%B3n-contra-covid-19-ministerio-de-salud-minsa-0): 
  - Datos faltantes:  127931 -> 0
  - Observaciones completas: 2671786 -> 4571604
  - Porcentaje de observaciones incompletas: 4.57 -> 0
- [Datos sobre fallecidos](https://www.datosabiertos.gob.pe/dataset/fallecidos-por-covid-19-ministerio-de-salud-minsa/resource/4b7636f3-5f0c-4404-8526):
  - Datos faltantes: 0 -> 1
  - Observaciones completas: 66770 -> 187157
  
  
Clasificación de las variables del estudio
========================================================
Datos sobre fallecidos por Covid-19

Variable | Tipo de variable | Restricciones
------------- | ------------- | -------------
EDAD | Numérica Discreta | Entero Positivo 
SEXO | Categórica Nominal | Masculino, Femenino
DEPARTAMENTO | Categórica Nominal | Departamentos del Perú
FECHA_FALLECIDO | | 

Clasificación de las variables del estudio
========================================================
Datos sobre proceso de vacunación de covid-19

Variable | Tipo de variable | Restricciones
------------- | ------------- | -------------
GRUPO_RIESGO | C. Nominal | Grupos de riesgo incluidos para el proceso de vacunacion(PNP)   
EDAD | N. Discreta | Entero mayor a 17
SEXO | C. Nominal | Masculino, Femenino
FECHA_VACUNACION | |
DOSIS | C. Nominal | 1,2
Fabricante | C. Nominal | SINOPHARM, PFIZER, ASTRAZENECA
DEPARTAMENTO | C. Nominal | Departamentos del Perú


Figuras de Mérito
========================================================
Tabla Fallecidos: 









