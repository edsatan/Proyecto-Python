# Análisis de violencia en México
<img src="./img_readme/dontCross.png">

## Equipo 9 :robot:
- Santiago Ramírez Iturbide
- Fernando Valdez Espinosa
- Juan Manuel Castro Ascencio
- Jaime Rodrigo González Rodríguez
- Eduardo Marcelino López Santamaría

---
## Métricas de evaluación BEDU :memo:
1. Identificación del problema: identificar y escoger un problema (justificar su elección). Presentar investigación preliminar completa del tema. Presentar información previa sobre las soluciones al problema.

2. Planteamiento de preguntas: Las son correctamente respondidas. La entrega tiene al menos 5 preguntas pertinentes sobre el problema.
3. Colección de datos: Obtener una colección de datos completa y no previamente procesada que usará para los siguientes pasos. Los datos recopilados pueden responder completamente las preguntas planteadas anteriormente.
4. Análisis exploratorio de los datos: Convertir de forma adecuada su colección de Datos (en JSON, CSV, etc…) en un DataFrame de Pandas. Realizar un análisis exploratorio de estos datos a través del uso correcto de Pandas.
5. Limpieza de datos: El nuevo Dataset no contiene ningún NaN. El Dataset está correctamente indexado (en orden y sin índices incoherentes).Las columnas están correctamente nombradas. Se aplicaron agregaciones al Dataset para poder comenzar a responder algunas preguntas planteadas en la sesión 2.
6. Transformación de datos: Todos los datos de cada columna tienen un valor correcto dependiendo del tipo de dato (fechas, objetos, ints, floats).Todas las columnas de texto están manipuladas para estar en el formato correcto. Hay nuevas columnas con nuevos datos resultantes del procesamiento de una o más columnas originales. Se crearon otros datasets/subconjuntos/series que presentan información relevante para una pregunta específica, o simplemente para exploraciones más profundas.
7. Ordenamiento de código: Entregar un Jupyter Notebook ordenado y limpio que contiene todos los pasos llevados a cabo para el preprocesamiento de datos.El Notebook hace uso de las diversas técnicas aprendidas a través de las clases para la exploración y procesamiento de datos.El Notebook contiene el código (nombrado correctamente) de todas las sesiones pasadas.
8. Opcional uso de APIs
---
## Identificación del problema :speech_balloon:
<p style="text-align: justify;">
Una de las principales preocupaciones de la ciudadanía es la violencia que azota nuestro país. De hecho, podríamos clasificarla como una pandemia silenciosa que hemos normalizado y convivimos con ella a diario de muy variadas formas.

La OMS define la violencia como el uso intencional de la fuerza o el poder físico contra uno mismo, otra persona o un grupo o una comunidad; que cause o tenga muchas probabilidades de causar lesiones, muerte o daños psicológicos.

Consideramos que un primer acercamiento desde el punto de vista estadístico permite clarificar el problema, clasificando los delitos podemos segmentar y analizar si la violencia del país es la misma en todos los estados o si ciertos delitos se dan con mayor frecuencia en ciertas regiones del país. Entendemos que en México hasta la denuncia es un privilegio, y que los sectores más desprotegidos no siempre tienen al alcance un abogado o la asesoría adecuada para poder exigir a la autoridad la impartición de justicia o el resarcimiento del daño.

En este grupo de trabajo confiamos en que un análisis preciso y científico de los datos, contribuirá en aportar elementos que ayuden a clarificar las incidencias de los tipos de delitos y con ello se pueda conocer más del origen del problema y a su vez, su posible solución.
</p>

---

## Planteamiento de preguntas :dart:
Con el repositorio de datos pretendemos contestar las siguientes preguntas:
- ¿Cómo se comporta la incidencia delictiva de 2015 a 2021?
- ¿Cuál es el comportamiento por tipo de delito en cada estado?
- ¿En qué estados existen más homicidios?
- ¿Qué estados son los más violentos?
- ¿Cuál es el tipo de delito más común?
- ¿Cuál es el comportamiento de los delitos de orden sexual en nuestro país?
---
## Código Colab :gear:
El Google colab del código se puede encontrar en el siguiente enlace https://colab.research.google.com/drive/1m8gxsei8xS6hXvCMA0kUWSoLLOf6LAew?authuser=3#scrollTo=-8UZLujGo0pM

## Código local :computer:
Si desea correr el código de manera local, clona este repositorio y tendrá una estructura como la siguiente...
```
Proyecto-Python/
├─ codes/
|   ├─ requirements.txt
|   ├─ equipo_9_violencia_en_mexico.py
|   └─ Equipo_9_Violencia_en_Mexico.ipynb
|
├─ Data/
|   └─ IDEFC_NM_jun2021.csv
|
└─ img_readme/
    └─ ...    
```
Instala los paquetes necesarios para ejecutar el código
```
pip install -r codes/requirements.txt
```
Ejecuta el código demo
```
python equipo_9_violencia_en_mexico.py
```