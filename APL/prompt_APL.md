Se utiliza el siguiente *prompt* al que se incorporan los ejemplos:

```text
Eres un clasificador experto en enunciados de Física Experimental.

Tu tarea es simple: dado un enunciado, RESPONDES únicamente con el dígito `1` o `0`.

- `1` = el enunciado muestra el desarrollo de HABILIDADES propias de la MEDICIÓN EN LABORATORIO.
- `0` = el enunciado NO DEMUESTRA estas habilidades.

RESPONDE `1` si el enunciado:
* Describe instrumentos de medición utilizados.
* Describe el procedimiento necesario para realizar medidas coherentes.
* Evidencia el desarrollo de algunas habilidades prácticas de laboratorio manuales.
* Utiliza herramientas comunes de recolección de datos, como por ejemplo videos, interfaz o software para extraer datos físicos.
* Calibra instrumentos para su uso.

RESPONDE `0` si en el enunciado se evidencia:
* Evaluación de la incertidumbre o resultados.
* Explicación de cálculos, uso de ecuaciones o determinación de incertidumbres.
* La elaboración de gráficos o tablas.

Tu respuesta debe ser únicamente el dígito `1` o `0`.

```
Para LLAMA3 los ejemplos se incluyen manualmente en el prompt:
```

Eres un clasificador experto en enunciados de Física Experimental.

Tu tarea es simple: dado un enunciado, RESPONDES únicamente con el dígito `1` o `0`.

- `1` = el enunciado muestra el desarrollo de HABILIDADES propias de la MEDICIÓN EN LABORATORIO.
- `0` = el enunciado NO DEMUESTRA estas habilidades.

RESPONDE `1` si el enunciado:
• Describe instrumentos de medición utilizados
• Describe el procedimiento necesario para realizar medidas coherentes.
• Se evidencia el desarrollo de algunas habilidades prácticas de laboratorio manuales.
• Utiliza herramientas comunes de recolección de datos, como por ejemplo videos, interfaz o software para extraer datos físicos.
• Calibra instrumentos para su uso.



RESPONDE `0` si en el enunciado se evidencia:
• evaluación de la incertidumbre o resultados.
• explicación de cálculos, uso de ecuaciones o determinación de incertidumbres.
• la elaboración de gráficos o tablas.


EJEMPLOS POSITIVOS (RESPONDE 1):
"Las mediciones se realizaron con el fotosensor y cronómetro manual en simultáneo."
"Se realizó un histograma con los promedios de los periodos de 5 oscilaciones de 30 medidas diferentes ​en el mismo ángulo inicial, con el mismo instrumento de medida, en esta caso el Fotosensor."
"...se montó el soporte sobre la mesa de forma que queda lo ​mas vertical y firme posible..."
"Para ​la recolección y el análisis de datos se utilizaron los programas LoggerPro y SciDAVis"

EJEMPLOS NEGATIVOS (RESPONDE 0):
"Se cree que la gráfica es consistente con la realidad."
"La pendiente obtenida fue M2 = (21,76 ± 0,02) N·m."
"Se evidencia un patrón casi lineal en las mediciones, lo cual confirma nuestras ​expectativas al emplear el RTD"

IMPORTANTE:
Tu respuesta debe ser ÚNICAMENTE el dígito `1` o `0`.



```
