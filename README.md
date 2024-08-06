# Análisis de Votaciones Venezuela 2024

Este proyecto realiza un análisis de anomalías en los datos públicos de las elecciones en Venezuela 2024. El objetivo es identificar posibles irregularidades en los resultados electorales utilizando técnicas estadísticas.

## Contenido del Repositorio

- `RESULTADOS_2024_CSV_V1.csv` y `RESULTADOS_2024_CSV_V2.csv`: Datos electorales utilizados en el análisis.
- Jupyter Notebooks para el análisis:
  - `VENEZUELA LIBRE.ipynb`: Análisis general de los datos.
  - `analisis_votos_anomalos.ipynb`: Identificación de mesas con resultados anómalos.
  - `anomalias_nm.ipynb`: Análisis específico de posibles fraudes.
  - `top_10_anomalias.ipynb`: Análisis de las 10 mesas con mayores anomalías.

## Requisitos

- Python 3.x
- Pandas
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

Puedes instalar los requisitos usando:
```bash
pip install pandas numpy scipy matplotlib jupyter
```

```bash
cd analisis-votaciones-venezuela-2024
```

```bash
jupyter notebook
```

## Metodología

El análisis se basa en los siguientes pasos:

1. **Carga de Datos**: Se cargan los datos electorales desde archivos CSV.
2. **Cálculo del Porcentaje de Participación**: Se calcula el porcentaje de participación en cada mesa.
3. **Cálculo del Z-Score**: Se calcula el z-score para identificar mesas con participaciones anómalas.
4. **Comparación de Votos**: Se comparan los votos de mesas anómalas con mesas normales.
5. **Visualización**: Se generan gráficos para visualizar los resultados y detectar posibles fraudes.

## Contribuciones

¡Las contribuciones son bienvenidas! Por favor, abre un issue o envía un pull request para discutir cualquier cambio importante.
