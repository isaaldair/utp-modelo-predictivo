# Análisis de Satisfacción de Pasajeros en Aerolíneas ✈️

## Descripción del proyecto
Este proyecto aplica modelos predictivos para analizar los factores que influyen en la satisfacción de los pasajeros de aerolíneas, utilizando un dataset obtenido de Kaggle. La investigación se desarrolla en el contexto de la asignatura **Modelos Predictivos**, combinando herramientas como **Weka**, **KNIME** y **Jupyter Notebook** para el análisis de datos, visualización y modelado.

---

## Objetivo
Construir modelos de clasificación que permitan predecir si un pasajero está satisfecho o no con su experiencia de vuelo, a partir de variables demográficas, operativas y de percepción del servicio.

---

## Dataset
- Nombre: `Airline Passenger Satisfaction`
- Fuente: Kaggle
- Registros: 129.880 pasajeros
- Variables: 23 columnas (ID, edad, género, tipo de cliente, tipo de viaje, clase, retrasos, puntuaciones de servicio, etc.)
- Variable objetivo: `Satisfaction` (`Satisfied` / `Neutral or unsatisfied`)

---

## Herramientas utilizadas
- **Weka**: para el entrenamiento y prueba rápida de modelos de clasificación.
- **KNIME**: para análisis visual y aplicación de flujos predictivos sin programación.
- **Python (Jupyter Notebook)**: para limpieza, exploración de datos y visualización.
- **Excel / Google Sheets**: para organización y validación de valores.

---

## Pasos del proyecto

1. **Selección del dataset** y revisión de su estructura.
2. **Análisis descriptivo**:
   - Estadísticas generales.
   - Distribución de variables.
   - Detección de valores nulos, outliers y ceros no aplicables.
3. **Exploración visual en Python**.
4. **Pruebas de modelos en Weka**:
   - Árboles de decisión (J48)
   - Random Forest
   - Naive Bayes, entre otros.
5. **Evaluación en KNIME** usando flujos de clasificación.
6. **Análisis de resultados y comparación de modelos**.
7. **Reflexión personal y documentación del proceso**.

---

## Descubrimientos principales
- Existen factores clave que influyen en la satisfacción, especialmente relacionados con el servicio y la puntualidad.
- Algunos aspectos, como la clase del asiento o el tipo de viaje, tienen mayor peso de lo que se pensaba.
- El uso de herramientas visuales permitió enfocarse en el análisis más que en la programación.

---

## Lecciones aprendidas
- Comprender el origen y significado de los datos es tan importante como analizarlos.
- Las herramientas como Weka y KNIME facilitan mucho el inicio en Machine Learning.
- Validar y comparar modelos ayuda a tomar decisiones con más fundamento.

---

## Recomendaciones y trabajos futuros
- Probar más modelos (como redes neuronales o boosting).
- Usar validación cruzada y métricas más avanzadas.
- Trabajar con datos reales o combinarlos con información operativa interna.
- Aplicar técnicas de procesamiento de texto si se dispone de comentarios abiertos de los pasajeros.
- Crear dashboards para facilitar la visualización de resultados.

---

## Autor
**Isaac Avila**  
Estudiante de Modelos Predictivos  
Año: 2025  
Modelos predictivos
