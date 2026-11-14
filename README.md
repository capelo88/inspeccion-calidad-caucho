# Sistema inteligente de inspección de calidad de láminas de caucho

## Descripción
Proyecto académico de visión artificial y aprendizaje automático orientado a la inspección de calidad de láminas de caucho utilizadas en superficies deportivas.

El sistema analiza imágenes para clasificar las piezas como **conformes o defectuosas**, considerando características visuales como color, apariencia y posibles alteraciones superficiales.

## Metodología
Se desarrolló una solución simulada utilizando:

- **Python:** lenguaje de programación.
- **OpenCV:** procesamiento y análisis de imágenes.
- **NumPy y Matplotlib:** procesamiento y visualización de datos.
- **Scikit-learn:** implementación del clasificador Decision Tree.

Se construyó un conjunto de 100 imágenes sintéticas, distribuidas en piezas conformes y defectuosas. El modelo se entrenó y evaluó utilizando una división de datos del 70 % para entrenamiento y 30 % para prueba.

## Resultados
El modelo obtuvo una exactitud del **93,33 %** sobre el conjunto de prueba.

La simulación contempla una línea de inspección en la que las piezas clasificadas como defectuosas son separadas mediante un mecanismo de desviación lateral.

## Estructura del proyecto
- `data/`: imágenes utilizadas para el entrenamiento y las pruebas.
- `notebooks/`: desarrollo del procesamiento y clasificación.
- `resultados/`: gráficas, matriz de confusión y resultados de la simulación.

## Ejecución
1. Clonar o descargar el repositorio.
2. Instalar las dependencias:

   `pip install -r requirements.txt`

3. Abrir el notebook `notebooks/inspeccion_calidad.ipynb` en Jupyter Notebook o Visual Studio Code.
4. Ejecutar las celdas en orden.

## Alcance y limitaciones
El proyecto corresponde a una simulación académica. Los resultados se obtuvieron con imágenes sintéticas derivadas de una imagen de referencia, por lo que no representan todavía una validación industrial con piezas reales ni una implementación física del sistema robótico.

## Autor
Proyecto desarrollado para la asignatura **Sistemas de Percepción en Robótica**, de la Maestría en Automatización y Robótica.

**Universidad Europea – 2026**
