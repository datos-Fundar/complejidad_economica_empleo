# Guía práctica para analizar la Complejidad Económica de una provincia

En este repositorio se comparten los cálculos que se han utilizado para la **Guía práctica para analizar la Complejidad Económica de una provincia** [^1]. Contiene también las bases de datos que se han utilizado para generar los análisis presentados en el documento. Las fuentes de datos son los datos de [empleo registrado por actividad y departamento](https://datos.gob.ar/dataset/produccion-distribucion-geografica-establecimientos-productivos) publicados por el Ministerio de Economía, Secretaría de Industria, Dirección Nacional de Estudios para la Producción (CEP XXI). Los cálculos se encuentran basados en aquellos realizados para el proyecto de Complejidad Económica Verde que se encuentran en el siguiente [repositorio](https://github.com/datos-Fundar/complejidad-economica).

[^1]: [Luvini, P. (2024). Guía práctica para analizar la Complejidad Económica de una provincia. Fundar.](https://fund.ar/publicacion/mapa-politicas-sociales-2023/)


**Cita Sugerida:**
```
Luvini, P. (2024). Guía práctica para analizar la Complejidad Económica de una provincia. Fundar.

Bibtex:

@report{luvini2024calculos,
  author    = {Luvini, P.},
  title     = {Cálculos de la Guía práctica para analizar la Complejidad Económica de una provincia},
  year      = {2024},
  institution = {Fundar},
  type      = {Document}
}

```

## Organización del proyecto:

En [`datasets`](./datasets/) se encuentran los datos de empleo publicados por CEP XXI junto con el correspondiente diccionario de códigos y sectores de actividad.

En [`outputs`](./outputs/) se encuentran los resultados del código que procesa los indicadores. 

En [`maps`](./maps/) se encuentran los shapefile y archivos necesarios para graficar mapas, que se obtienen del del Instituto Nacional de Estadísticas y Censos [aquí](https://www.indec.gob.ar/indec/web/Institucional-Indec-Codgeo).

El análisis está repartido entre las siguientes Jupyter Notebooks:
  - `procesa_indicadores.ipynb` presenta los cálculos de los índices e indicadores de Complejidad Económica.
  - `analiza_resultados.ipynb` contiene el análisis de los resultados obtenidos anteriormente, tanto a nivel provincia como actividad.
  - `selecciona_sectores.ipynb` contiene los criterios de selección de actividades a recomendar para cada provincia.


<div>&nbsp;</div>
<div>&nbsp;</div>
<div>
  &nbsp;
  <a href="https://fund.ar">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://github.com/datos-Fundar/fundartools/assets/86327859/6ef27bf9-141f-4537-9d78-e16b80196959">
    <source media="(prefers-color-scheme: light)" srcset="https://github.com/datos-Fundar/fundartools/assets/86327859/aa8e7c72-4fad-403a-a8b9-739724b4c533">
    <img src="fund.ar"></img>
  </picture>
</a>

</div>