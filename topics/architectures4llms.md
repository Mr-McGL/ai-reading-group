# Arquitecturas y Limitaciones de los Grandes Modelos de Lenguaje

## Índice

- [Arquitecturas y Limitaciones de los Grandes Modelos de Lenguaje](#arquitecturas-y-limitaciones-de-los-grandes-modelos-de-lenguaje)
  - [Papers](#papers)
    - [Uso de herramientas](#uso-de-herramientas)
    - [Ventana de Contexto](#ventana-de-contexto)
  - [Otros Recursos](#otros-recursos)
    - [Vídeos](#vídeos)

## Papers

### Arquitecturas

* **Large Language Diffusion Models** (18 feb 2025 – Renmin University of China, Ant Group)  
  [arXiv](https://arxiv.org/pdf/2502.09992)  
  **Keywords**: Modelos de lenguaje grandes, difusión, generative modeling, in-context learning, razonamiento inverso, escalabilidad  
  **Descripción**: Este estudio introduce LLaDA, un modelo de difusión para grandes modelos de lenguaje entrenado desde cero bajo un paradigma de preentrenamiento y fine-tuning supervisado. A diferencia de los modelos autorregresivos tradicionales, LLaDA define la distribución del modelo mediante un proceso de enmascaramiento aleatorio y un predictor de máscaras basado en Transformers, lo que permite capturar dependencias bidireccionales y superar limitaciones inherentes a la generación token a token. Los resultados demuestran que LLaDA es competitivo en escalabilidad y rendimiento en tareas de comprensión, matemáticas, generación de código y diálogo, estableciendo a los modelos de difusión como una alternativa prometedora a los enfoques autorregresivos.


### Uso de herramientas

* **Toolformer: Language Models Can Teach Themselves to Use Tools** (9 feb 2023 – META/Pompeu Fabra)  
  [arXiv](https://arxiv.org/abs/2302.04761) | [GitHub](https://github.com/conceptofmind/toolformer)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), herramientas externas, aprendizaje auto-supervisado  
  **Descripción**: Este trabajo introduce **Toolformer**, un modelo que se entrena para decidir qué APIs llamar, cuándo llamarlas, qué argumentos pasar y cómo incorporar mejor los resultados en la predicción de tokens futuros. 

### Ventana de Contexto

* **Titans: Learning to Memorize at Test Time** (31 dic 2024 – Google Research)  
  [arXiv](https://arxiv.org/abs/2501.00663)  
  **Keywords**: Ventana de contexto, **Long Term Memory** (memoria a largo plazo)  
  **Descripción**: Este estudio introduce un nuevo módulo de memoria neural a largo plazo que aprende a memorizar el contexto histórico y asiste al mecanismo de atención para enfocarse en el contexto actual, utilizando información del pasado distante y escalando eficientemente a ventanas de contexto superiores a 2 millones de tokens.

* **LongRoPE: Extending LLM Context Window Beyond 2 Million Tokens** (21 feb 2024 – Microsoft Research)  
  [arXiv](https://arxiv.org/abs/2402.13753)  
  **Keywords**: Ventana de contexto, *rotary position embedding*  
  **Descripción**: Se presenta una innovadora técnica que extiende la ventana de contexto de los LLMs (Large Language Models - Modelos de Lenguaje de Gran Tamaño) hasta más de 2 millones de tokens mediante estrategias de interpolación y extensión progresiva, manteniendo el rendimiento en tareas con contextos breves.

* **RoFormer: Enhanced Transformer with Rotary Position Embedding** (20 abr 2021 – Zhuiyi Technology Co., Ltd. Shenzhen)  
  [arXiv](https://arxiv.org/abs/2104.09864)  
  **Keywords**: Ventana de contexto, *rotary position embedding*  
  **Descripción**: Propone una mejora en la arquitectura Transformer mediante la incorporación de Rotary Position Embedding, lo que permite un modelado más flexible y eficaz de las relaciones posicionales en secuencias, optimizando el desempeño en tareas de procesamiento de lenguaje.


### Eficiencia/Caches

* **Auditing Prompt Caching in Language Model APIs** (11 feb 2025 – Standford)  
  [arXiv](https://arxiv.org/abs/2502.07776)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), almacenamiento en caché de *prompts*, ataques de canal lateral, privacidad  
  **Descripción**: Este estudio investiga cómo el almacenamiento en caché de *prompts* en APIs de modelos de lenguaje grandes puede introducir variaciones en los tiempos de respuesta, lo que podría ser explotado en ataques de canal lateral. Mediante auditorías estadísticas, los autores detectaron que 8 de 17 proveedores de APIs, incluyendo OpenAI, comparten cachés globalmente entre usuarios, lo que podría permitir a un atacante inferir información sobre los *prompts* de otros usuarios basándose en tiempos de respuesta más rápidos. 

* **Don't Do RAG: When Cache-Augmented Generation is All You Need for Knowledge Tasks** (20 dic 2024 – Taiwan)  
  [arXiv](https://arxiv.org/abs/2412.15605)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), generación aumentada por recuperación (*Retrieval-Augmented Generation* - RAG), generación aumentada por caché (*Cache-Augmented Generation* - CAG), eficiencia  
  **Descripción**: Este trabajo propone la **generación aumentada por caché** (*Cache-Augmented Generation* - CAG) como una alternativa a la generación aumentada por recuperación (*Retrieval-Augmented Generation* - RAG) en modelos de lenguaje grandes. CAG implica precargar todos los recursos relevantes en el contexto extendido del modelo antes de la inferencia, eliminando la necesidad de recuperación en tiempo real. 


* **Prompt Cache: Modular Attention Reuse for Low-Latency Inference** (7 nov 2023 – Google, Yale)  
  [arXiv](https://arxiv.org/abs/2311.04934)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), reutilización de estados de atención, inferencia de baja latencia  
  **Descripción**: Este trabajo presenta **Prompt Cache**, una técnica para acelerar la inferencia en modelos de lenguaje grandes mediante la reutilización de estados de atención en diferentes *prompts*. 




## Otros Recursos

### Vídeos

* **RoPE Rotary Position Embedding to 100K Context Length** (23 may 2024 – DiscoverAI)  
  [YouTube](https://www.youtube.com/watch?v=DvP8f7eWS7U)  
  **Descripción**: Análisis de RoPE aplicado a la extensión de la ventana de contexto.

* **LongRoPE & Theta Scaling to 1 Mio Token** (25 may 2024 – DiscoverAI)  
  [YouTube](https://www.youtube.com/watch?v=RCSvpYb90qE)  
  **Descripción**: Análisis de LongRoPE en la ampliación de la ventana de contexto.




