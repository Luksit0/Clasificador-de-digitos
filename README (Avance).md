# Clasificador de dígitos con redes neuronales convolucionales (CNN)

Proyecto de **Fundamentos de Inteligencia Artificial** — Centro Universitario de Ciencias Exactas e Ingenierías (CUCEI), Universidad de Guadalajara.
Profesor: Dr. Robin Fernando Conchas Cedano.

## Integrantes

- Jose Luis Leal Cardenas
- _(nombre del compañero)_

## Descripción

Se diseña, entrena y evalúa una red neuronal convolucional con **TensorFlow/Keras** para clasificar imágenes de dígitos del conjunto de datos **MNIST** (60,000 imágenes de entrenamiento y 10,000 de prueba, de 28×28 píxeles y 10 clases). Después se prueba la red con dígitos dibujados a mano por el equipo.

## Requisitos

- **Python 3.10, 3.11 o 3.12** (TensorFlow no funciona con versiones más nuevas de Python; con 3.13 o superior puede dar errores de instalación).
- Las librerías de `requirements.txt` (TensorFlow, NumPy, Matplotlib, scikit-learn, Pillow).

## Instalación (Windows)

```powershell
# 1. Crear un entorno virtual con Python 3.12 (instálalo antes si no lo tienes)
py -3.12 -m venv .venv

# 2. Activarlo
.venv\Scripts\activate

# 3. Instalar las librerías
pip install -r requirements.txt
```

## Uso

1. Abrir `modelo_clasificador.ipynb` en Visual Studio Code.
2. Seleccionar como kernel el intérprete del entorno `.venv`.
3. Ejecutar las celdas en orden, de arriba hacia abajo.

También puede ejecutarse en Google Colab, que ya incluye TensorFlow.

## Avance del proyecto

- [x] Parte 1: Preparación del dataset (carga, normalización y visualización)
- [x] Parte 2: Arquitectura de la red neuronal
- [x] Parte 3: Entrenamiento del modelo y gráficas de accuracy y loss
- [ ] Parte 4: Evaluación (accuracy, f1-score, matriz de confusión y predicciones)
- [ ] Parte 5: Clasificación de dígitos dibujados a mano
- [ ] Reporte en formato IEEE
