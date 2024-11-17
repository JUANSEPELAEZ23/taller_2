# Universidad de los Andes
## MINE-4101: Ciencia de Datos Aplicada
### Taller 2
  
**Integrantes:**  
- Juan Sebastián Peláez Pardo y Nicolás Tibatá
  

  **Resumen / conclusiones:**  
 El análisis de los dos modelos implementados resalta la importancia de la optimización en la
 arquitectura y los hiperparámetros para mejorar la capacidad de generalización. Aunque el
 modelo 1 mostró un desempeño adecuado en el conjunto de entrenamiento, su rendimiento en
 el conjunto de prueba disminuyó significativamente, evidenciando problemas de sobreajuste.
 Por el contrario, el modelo 2, optimizado mediante búsqueda de hiperparámetros, demostró un
 desempeño superior, con un incremento notable en métricas clave como precisión (47% frente
 a 38% en promedio) y recall (40% frente a 38% en promedio). Esto confirma que el modelo 2
 no solo identifica con mayor exactitud las imágenes en cada clase, sino que también clasifica
 correctamente una mayor proporción de los datos de prueba, consolidándose como la solución
 más robusta para el problema planteado. Desde el punto de vista del impacto económico, el modelo ofrece un ahorro significativo en el
 tiempo de registro de productos, estimado en 14.5 horas mensuales, lo que equivale a
 $146,000 de ahorro mensual. Si bien el desarrollo del modelo requirió una inversión inicial, el
 retorno de la misma se alcanzará en aproximadamente 16 meses, demostrando su viabilidad
 económica a largo plazo. En conclusión, la implementación del modelo 2 no solo mejora la
 eficiencia técnica en la clasificación de imágenes, sino que también representa una inversión
 estratégica con beneficios tangibles en productividad y costos operativos.

**Dependencias:**  
-pandas - Para análisis y manipulación de datos tabulares.

-numpy - Para manipulación de arreglos y matrices multidimensionales.

-scikit-learn - Para clasificación, regresión y evaluación de modelos de machine learning.

-tensorflow - Para desarrollo y ejecución de modelos de deep learning.

-keras-tuner - Para optimización de hiperparámetros en modelos de deep learning.

-matplotlib - Para creación y visualización de gráficos.

-Pillow (PIL) - Para manipulación y procesamiento de imágenes.

-os - Para manejo de rutas y operaciones del sistema operativo.

**Instrucciones de ejecución:**  
1. **Requisitos previos**:
   - Asegúrate de haber instalado las dependencias listadas en la sección de dependencias.

2. **Ejecutar el script**:
   Para ejecutar el proyecto, utiliza el siguiente comando:
   ```bash
   python Taller_2_Ciencia_de_datos.ipynb
