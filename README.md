# Sistemas de Inteligencia Artificial

Trabajos de la materia Sistemas de Inteligencia Artificial de la Tecnicatura en Análisis de Datos e Inteligencia Artificial: redes neuronales desde sus fundamentos en NumPy hasta su implementación con Keras/TensorFlow.

## Notebooks

| Notebook | Contenido |
|----------|-----------|
| [SIA_Grupo3_TrabajoIntegrador.ipynb](notebooks/SIA_Grupo3_TrabajoIntegrador.ipynb) | Trabajo integrador grupal (Grupo 3): red neuronal para clasificación/regresión sobre el dataset Iris, con descripción del problema, exploración, modelo, evaluación y conclusiones. |
| [Ejercicio1_Red_Neuronal_Numpy.ipynb](notebooks/Ejercicio1_Red_Neuronal_Numpy.ipynb) | Red neuronal implementada a mano con NumPy: inicialización de pesos y sesgos, propagación hacia adelante y operaciones base. |
| [Ejercicio2_Retropropagacion_AND.ipynb](notebooks/Ejercicio2_Retropropagacion_AND.ipynb) | Actividad de retropropagación (backpropagation) aplicada al problema lógico AND: tabla de verdad, gradiente descenso y entrenamiento paso a paso. |
| [Ejercicio5_Keras_Mnist.ipynb](notebooks/Ejercicio5_Keras_Mnist.ipynb) | Clasificación de dígitos (MNIST) con redes neuronales en Keras/TensorFlow: definición del modelo, compilación, entrenamiento y métricas. |
| [SIA_Trabajo_Practico1.ipynb](notebooks/SIA_Trabajo_Practico1.ipynb) | Trabajo Práctico 1. |
| [ejercicio2_raices.ipynb](notebooks/ejercicio2_raices.ipynb) | Ejercicio 2: búsqueda de raíces. |
| [clase3/](notebooks/clase3/) | Material de la clase 3. |
| [clase4_5/](notebooks/clase4_5/) | Material de las clases 4 y 5. |
| [clase6/](notebooks/clase6/) | Material de la clase 6. |

Todos los notebooks se publican ejecutados, con sus salidas y gráficos, y se pueden leer directamente en GitHub.

## Datos

No se requieren archivos locales: los datasets (Iris, MNIST) se descargan automáticamente desde scikit-learn y Keras.

## Cómo ejecutarlos

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
jupyter notebook notebooks/SIA_Grupo3_TrabajoIntegrador.ipynb
```

## Temas cubiertos

- Perceptrón y redes neuronales desde cero
- Propagación hacia adelante y retropropagación
- Funciones de activación y descenso de gradiente
- Redes densas con Keras/TensorFlow
- Clasificación multiclase (Iris) y de dígitos (MNIST)
- Evaluación de modelos: accuracy, matrices de confusión

## Licencia

MIT
