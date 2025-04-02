# Multimodalidad

## Índice

- [LLMs](#multimodalidad)
  - [Papers](#papers)
  - [Recursos](#recursos)

## Papers

* **Image-to-LaTeX Converter for Mathematical Formulas and Text** (7 ago 2024 – Saarland University)  
  [arXiv](https://arxiv.org/abs/2408.04015)  | [GitHub](https://github.com/d-gurgurov/im2latex?tab=readme-ov-file)  
  **Keywords**: Multimodalidad, Imagen, Texto, OCR, *transformers*, LoRA  
  **Descripción**: En este proyecto se entrena un modelo encoder-decoder de visión para generar código LaTeX a partir de imágenes que contienen fórmulas matemáticas y texto. Se desarrollan dos versiones: una base, que utiliza un encoder basado en Swin Transformer y un decodificador basado en GPT-2 entrenado con imágenes generadas automáticamente, y otra afinada mediante Low-Rank Adaptation (LoRA) entrenada con fórmulas manuscritas. Se evalúa la calidad de la conversión mediante la métrica BLEU y se comparan los resultados con modelos similares, como Pix2Text, TexTeller y Sumen. El proyecto aporta modelos de código abierto y código desde cero para la construcción de estos sistemas con entrenamiento distribuido y optimización en GPU.

## Recursos

### OCR
* **im2latex** (7 ago 2024 – GitHub)  
  [GitHub](https://github.com/d-gurgurov/im2latex?tab=readme-ov-file)  
  **Descripción**: Repositorio que contiene código y documentación para un convertidor de imágenes a LaTeX, facilitando la transformación de fórmulas matemáticas y texto a código LaTeX mediante técnicas de visión por ordenador.

* **TexTeller** (6 jun 2024 – GitHub)  
  [GitHub](https://github.com/OleehyO/TexTeller)  
  **Descripción**: Repositorio que ofrece un sistema de reconocimiento de fórmulas en imágenes, permitiendo convertir imágenes a código LaTeX con alta precisión y robustez, basado en modelos end-to-end y técnicas avanzadas de OCR.

* ⚠️**Pix2Text** (15 jul 2024 – GitHub) ⭐⭐⭐  
  [GitHub](https://github.com/breezedeus/Pix2Text)  
  **Descripción**: Repositorio que proporciona un modelo para convertir imágenes en texto. Basado en técnicas de OCR y aprendizaje profundo, destaca por su capacidad de generalización y precisión en la extracción de contenido visual.