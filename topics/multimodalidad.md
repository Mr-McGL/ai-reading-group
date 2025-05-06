# Multimodalidad

## Índice

- [Multimodalidad](#multimodalidad)
  - [Papers](#papers)
  - [Recursos](#recursos)
    - [Repositorios de artículos](#repositorios-de-artículos)
    - [Frameworks](#Frameworks)
    - [OCR](#ocr)

## Papers

* **LLaMA-Mesh: Unifying 3D Mesh Generation with Language Models** (14 nov 2024 – NVIDIA)  
  [arXiv](https://arxiv.org/abs/2411.09595)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), generación de mallas 3D, integración de modalidades, conocimiento espacial, tokenización de mallas  
  **Descripción**: Este estudio explora la ampliación de las capacidades de los *LLMs* entrenados en texto para generar mallas 3D. Se propone representar las coordenadas de los vértices y las definiciones de las caras como texto, lo que permite la integración directa sin necesidad de expandir el vocabulario. Se construye un conjunto de datos para *fine-tuning* supervisado que habilita la generación de mallas a partir de indicaciones textuales, la producción de salidas intercaladas (texto y mallas) y la comprensión de las mallas. Con este enfoque, LLaMA-Mesh alcanza una calidad comparable a la de modelos entrenados desde cero sin afectar el rendimiento en la generación textual.

* **MinerU: An Open-Source Solution for Precise Document Content Extraction** (sep 2024 – Shanghai Artificial Intelligence Laboratory)  
  [arXiv](https://arxiv.org/abs/2409.18839)  
  **Keywords**: extracción de contenido, documentos, código abierto, visión por computador  
  **Descripción**: Este artículo presenta MinerU, una solución de código abierto para la extracción precisa de contenido en documentos. Los autores proponen un método innovador que integra técnicas de procesamiento de imagen y algoritmos de reconocimiento para identificar y extraer información relevante, validándolo mediante experimentos comparativos.

* **Image-to-LaTeX Converter for Mathematical Formulas and Text** (7 ago 2024 – Saarland University)  
  [arXiv](https://arxiv.org/abs/2408.04015) | [GitHub](https://github.com/d-gurgurov/im2latex?tab=readme-ov-file)
  **Keywords**: Multimodalidad, Imagen, Texto, OCR, *transformers*, LoRA
  **Descripción**: En este proyecto se entrena un modelo encoder-decoder de visión para generar código LaTeX a partir de imágenes que contienen fórmulas matemáticas y texto. Se desarrollan dos versiones: una base, que utiliza un encoder basado en Swin Transformer y un decodificador basado en GPT-2 entrenado con imágenes generadas automáticamente, y otra afinada mediante Low-Rank Adaptation (LoRA) entrenada con fórmulas manuscritas. Se evalúa la calidad de la conversión mediante la métrica BLEU y se comparan los resultados con modelos similares, como Pix2Text, TexTeller y Sumen. El proyecto aporta modelos de código abierto y código desde cero para la construcción de estos sistemas con entrenamiento distribuido y optimización en GPU.

## Recursos

### Repositorios de artículos

* 🔥***LLM Reasoning Papers*** (15 ene 2025 – philschmid)
  Repositorio de artículos
  [Hugging Face](https://huggingface.co/collections/philschmid/llm-reasoning-papers-66e6abbdf5579b829f214de8)
  **Descripción**: Colección curada que reúne artículos para mejorar las capacidades de razonamiento de los modelos de lenguaje grandes.


### Frameworks

* 🔥🔥🔥 ***AnyModel*** (2025) 
  [git](https://github.com/ritabratamaiti/AnyModal), [HF](https://huggingface.co/AnyModal/LaTeX-OCR-Llama-3.2-1B),  [dataset 1](https://huggingface.co/datasets/unsloth/LaTeX_OCR), [dataset 2](https://huggingface.co/datasets/linxy/LaTeX_OCR)  
  **Descripción**: Encoder with Llama 3.2-1B. 🔥🔥🔥 AnyModal es un framework modular y extensible para integrar diversas modalidades de entrada.

### OCR/PDF
* ***Vision Parser:*** (enero 2025 – GitHub) .  
  [git](https://github.com/iamarunbrahma/vision-parse)
  **Descripción**: 🔥🔥🔥 Acepta múltiples modelos. Basado en Ollama

* ***MinerU*** (2025) 
  [git](https://github.com/opendatalab/MinerU), [doc](https://mineru.readthedocs.io/en/latest/index.html), [api](https://mineru.readthedocs.io/en/latest/user_guide/usage/api.html)  
  AGPL
  **Descripción**: Converts PDFs into machine-readable formats

* **im2latex** (7 ago 2024 – GitHub)
  [GitHub](https://github.com/d-gurgurov/im2latex?tab=readme-ov-file)
  **Descripción**: Repositorio que contiene código y documentación para un convertidor de imágenes a LaTeX, facilitando la transformación de fórmulas matemáticas y texto a código LaTeX mediante técnicas de visión por ordenador.

* **TexTeller** (6 jun 2024 – GitHub)
  [GitHub](https://github.com/OleehyO/TexTeller)
  **Descripción**: Repositorio que ofrece un sistema de reconocimiento de fórmulas en imágenes, permitiendo convertir imágenes a código LaTeX con alta precisión y robustez, basado en modelos end-to-end y técnicas avanzadas de OCR.

* ⚠️**Pix2Text** (15 jul 2024 – GitHub) ⭐⭐⭐
  [GitHub](https://github.com/breezedeus/Pix2Text)
  **Descripción**: Repositorio que proporciona un modelo para convertir imágenes en texto. Basado en técnicas de OCR y aprendizaje profundo, destaca por su capacidad de generalización y precisión en la extracción de contenido visual.