# Tarea 2: Marketing Analytics - Caso N°3: Fintual.
Repositorio para la Tarea 2 de Marketing Analytics, correspondiente al Caso N°3: Fintual.

## Integrantes:
- Javier Aguilera Trincado
- Matías Garín Avendaño
- Matías Olea Thomsen

## Paso a paso:
1. Ejecutar en consola:
```bash
pip install -r requirementsvenv.txt
virtualenv .venv
```
2. Activar entorno virtual:
- Si estás en Linux:
```bash
source .venv/bin/activate
```
- Si estás en Windows, abre Powershell y ejecuta el path completo hacia el script 'activate' del entorno virtual:
```bash
C:\Users\TuUsuario\Ruta\Hacia\El\Proyecto\.venv\Scripts\activate
```
3. Instalar las dependencias ya dentro del entorno virtual:
```bash
pip install -r requirements.txt
```
4. Escoger el entorno virtual dentro del notebook `./notebooks/Marketing_Analytics_Caso_3_Fintual.ipynb`.
5. Ejecutar el notebook `./notebooks/Marketing_Analytics_Caso_3_Fintual.ipynb` en Visual Studio Code o en Jupyter Notebook.

## Descripción del proyecto:
El proyecto consiste en un análisis de marketing para Fintual, una plataforma de inversión en línea. El objetivo es identificar oportunidades de crecimiento y optimización en sus estrategias de marketing digital mediante el análisis de datos históricos y la aplicación de técnicas de machine learning. Se utilizan diversas librerías de Python para la manipulación de datos, visualización y modelado predictivo.

## Estructura del repositorio:
- `data/`: Contiene los conjuntos de datos utilizados en el análisis.
- `notebooks/`: Contiene el notebook principal con el análisis y resultados.
- `outputs/`: Carpeta destinada para guardar gráficos, tablas y otros resultados generados.
- `requirements.txt`: Lista de dependencias necesarias para ejecutar el proyecto, dentro del entorno virtual.
- `requirementsvenv.txt`: Lista de dependencias necesarias para crear el entorno virtual.
- `README.md`: Documentación del proyecto y guía de uso.