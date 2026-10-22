# Python y pandas para ciencia de datos

Material del curso presencial de MBIT (10 horas en 2 días, más 1 hora de tutoría): fundamentos de Python y pandas, con los pasajeros del Titanic, la pandemia en España y 45.000 canciones de Spotify.

## Cuadernos

Se abren directamente en Google Colab. Guardad **vuestra copia** (Archivo → Guardar una copia en Drive) antes de empezar.

| Cuaderno | Contenido | Abrir |
|---|---|---|
| Día 1 | Fundamentos de Python · el DataFrame · seleccionar y filtrar | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clriesco/python-ciencia-datos/blob/main/cuadernos/PythonPandas_Dia1_alumno.ipynb) |
| Día 2 | Transformar · agrupar · combinar tablas y fechas · gráficos · proyecto Spotify | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clriesco/python-ciencia-datos/blob/main/cuadernos/PythonPandas_Dia2_alumno.ipynb) |
| Tutoría | Caza de errores · repaso con FIFA 24 · reto para casa | [![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/clriesco/python-ciencia-datos/blob/main/cuadernos/PythonPandas_Tutoria_alumno.ipynb) |

Los cuadernos del profesor (resueltos y ejecutados) se comparten al terminar cada día.

## Datos

Los cuadernos leen los ficheros de la carpeta `data/` de este repositorio por URL; no hace falta descargar nada.

| Fichero | Qué es |
|---|---|
| `titanic.csv` | 1313 pasajeros del Titanic: nombre, clase, edad, sexo y supervivencia |
| `covid_confirmed.csv`, `covid_deaths.csv`, `covid_recovered.csv` | Covid en España, cifras acumuladas por día (covid19api.com, hasta el 14/09/2022) |
| `covid_summary.csv` | Totales de Covid de 197 países |
| `tracks.json` | 45.128 canciones de Spotify: título, álbum, artista, duración y géneros |
| `fifa24.csv` | 19.397 jugadores de FIFA 24 |

Si en el aula no hay red, se pueden subir los ficheros a Colab a mano y cambiar en las celdas de carga la URL por `data/`.
