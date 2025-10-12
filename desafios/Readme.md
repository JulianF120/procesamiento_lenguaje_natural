# Desafíos de Procesamiento del Lenguaje Natural (PLN)

Este repositorio contiene las soluciones a 4 desafíos prácticos realizados durante la cursada de la materia "Procesamiento del Lenguaje Natural", en el marco de la Especialización en Inteligencia Artificial de la Universidad de Buenos Aires (UBA).

Los desafíos están diseñados para seguir una progresión de complejidad, cubriendo desde conceptos fundamentales hasta la implementación de modelos avanzados.

---
## Desafíos

A continuación se detalla la temática de cada uno de los desafíos.

### Desafío 1: Clasificación de Documentos
Implementación de un modelo para **clasificar documentos por temática**. En este desafío se exploran técnicas de **vectorización** de texto (como TF-IDF), cálculo de **similitud de coseno** y el entrenamiento de un clasificador para asignar categorías a nuevos documentos.

### Desafío 2: Embeddings y Similitud de Palabras
Entrenamiento de un modelo de ***word embeddings*** con la librería **Gensim**. El objetivo es que, a partir de una palabra dada, el modelo sea capaz de encontrar los términos semánticamente más similares, demostrando su capacidad para capturar relaciones contextuales en el lenguaje.

### Desafío 3: Modelo de Lenguaje a Nivel de Caracteres
Creación de un **modelo de lenguaje a nivel de caracteres** utilizando redes recurrentes (**RNN** y **LSTM**). El modelo, entrenado con el texto de *Don Quijote*, es capaz de generar nuevo texto a partir de una secuencia de entrada. Se implementan y comparan estrategias de decodificación como ***Greedy Search*** y ***Beam Search*** para la predicción.

### Desafío 4: Traductor Neuronal (Inglés-Español)
Desarrollo de un traductor automático neuronal para los idiomas inglés y español. Se implementa un modelo ***Sequence-to-Sequence*** (Seq2Seq) con un mecanismo de atención en **PyTorch** para abordar la tarea de traducción automática.
