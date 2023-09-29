# NN_CANCER_PYTORCH
Una aplicación de red neuronal para datos tabulares con PyTorch

# Implementación de una Red Neuronal para la Detección de Cáncer con PyTorch

# Observaciones sobre el Rendimiento del Modelo

Basándonos en los resultados proporcionados durante el entrenamiento del modelo, podemos hacer las siguientes observaciones:

1. **Pérdida Promedio por Época**:
   - La pérdida promedio disminuye gradualmente a medida que aumenta el número de épocas.
   - Inicialmente, la pérdida es alta, pero se observa una tendencia a la disminución. Esto sugiere que el modelo está aprendiendo de los datos de entrenamiento.

2. **Precisión por Época**:
   - La precisión muestra un patrón diferente al de la pérdida.
   - Inicialmente, la precisión es baja (alrededor del 36.70%), lo que indica que el modelo está realizando predicciones aleatorias.
   - A medida que progresa el entrenamiento, la precisión mejora significativamente, alcanzando alrededor del 69.89% en la época 11.
   - Luego, la precisión se estabiliza en alrededor del 63.30% y no parece mejorar más.

3. **Número de Épocas**:
   - Se realizaron 99 épocas de entrenamiento.

El modelo inicialmente tiene dificultades para aprender los patrones en los datos y realiza predicciones aleatorias. Sin embargo, a medida que se aumenta el número de épocas, el modelo comienza a aprender y mejora su precisión. Sin embargo, después de alrededor de 11 épocas, la mejora se estabiliza y la precisión parece mantenerse en alrededor del 63.30%. Esto podría indicar que el modelo ha alcanzado su capacidad de aprendizaje en los datos de entrenamiento y no se beneficia significativamente de más épocas de entrenamiento.

Evaluar el modelo de manera más completa, es importante realizar pruebas en un conjunto de datos de prueba separado y considerar otras métricas de evaluación, como la matriz de confusión y el área bajo la curva ROC, para comprender mejor su rendimiento en la detección de cáncer de mama.

# Referencia de Inspiración

Gran parte del código y la estructura de este proyecto se basaron en el trabajo previamente realizado por [Alejandro Puig](https://github.com/puigalex/Pytorch_churn). Este recurso proporcionó valiosa orientación y ejemplos que sirvieron como punto de partida para el desarrollo de este proyecto.

Agradecemos al autor del repositorio original por su contribución a la comunidad de aprendizaje de PyTorch y por compartir su conocimiento.
