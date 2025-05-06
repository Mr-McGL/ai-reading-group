# Generación Aumentada por Recuperación (Retrieval Augmented Generation - RAG)

## Índice

- [Generación Aumentada por Recuperación (Retrieval Augmented Generation - RAG)](#generación-aumentada-por-recuperación-retrieval-augmented-generation---rag)
  - [Papers](#papers)
  - [Otros recursos](#otros-recursos)
    - [Webs](#codigo)

## Papers

* **PathRAG: Pruning Graph-based Retrieval Augmented Generation with Relational Paths** (18 feb 2025 – Beijing, Hong Kong)  
  [arXiv](https://arxiv.org/abs/2502.14902) | [GitHub](https://github.com/BUPT-GAMMA/PathRAG)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), generación aumentada por recuperación (*Retrieval-Augmented Generation* - RAG), grafos de conocimiento, eficiencia  
  **Descripción**: Este trabajo presenta **PathRAG**, una metodología que mejora la generación aumentada por recuperación basada en grafos al centrarse en rutas relacionales clave dentro del grafo de indexación. A diferencia de enfoques anteriores que pueden introducir redundancia al considerar información amplia de comunidades o vecinos inmediatos, **PathRAG** utiliza una poda basada en flujo para identificar y recuperar rutas esenciales entre nodos relacionados con la consulta. 

* **Retrieval-Augmented Systems Can Be Dangerous Medical Communicators** (18 feb 2025 – MIT, Standford, Duke)  
  [arXiv](https://arxiv.org/abs/2502.14898v1)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), generación aumentada por recuperación (*Retrieval-Augmented Generation* - RAG), comunicación médica, seguridad  
  **Descripción**: Este estudio analiza cómo los sistemas de generación aumentada por recuperación (RAG) pueden producir respuestas médicas que, aunque literalmente precisas y basadas en fuentes confiables, resultan pragmáticamente engañosas para los pacientes. 


* **A Survey of Graph Retrieval-Augmented Generation for Customized Large Language Models** (21 ene 2025 – Hong Kong Polytechnic)  
  [arXiv](https://arxiv.org/abs/2501.13958) | [GitHub](https://github.com/DEEP-PolyU/Awesome-GraphRAG)  
  **Keywords**: RAG, grafos  
  **Descripción**: Este artículo realiza un repaso sistemático de GraphRAG, una metodología que integra conocimientos estructurados en grafos para personalizar los LLMs (*Large Language Models* - Modelos de Lenguaje de Gran Tamaño), facilitando la recuperación y generación de información en dominios especializados.

* **Fact, Fetch, and Reason: A Unified Evaluation of Retrieval-Augmented Generation** (24 ene 2025 – Harvard University, Google DeepMind, Meta)  
  [arXiv](https://arxiv.org/abs/2409.12941) | [Hugging Face](https://huggingface.co/datasets/google/frames-benchmark)  
  **Keywords**: RAG, evaluación, razonamiento, recuperación de información  
  **Descripción**: Este artículo introduce FRAMES, un conjunto de evaluación diseñado para medir la precisión factual, la recuperación de información y la capacidad de razonamiento de los sistemas RAG (*Retrieval-Augmented Generation*). A diferencia de benchmarks previos que evalúan estos aspectos por separado, FRAMES proporciona un marco unificado que analiza el rendimiento de modelos de lenguaje en escenarios complejos de recuperación y generación de conocimiento. Los experimentos revelan que los modelos actuales tienen dificultades con tareas de razonamiento de múltiples pasos, destacando la importancia de mejorar la planificación de recuperación y la integración de información en sistemas RAG.

* **Agentic Retrieval-Augmented Generation: A Survey on Agentic RAG** (15 ene 2025 – Cleveland State University, The Davey Tree Expert Company, The MathWorks Inc, Northeastern University)  
  [arXiv](https://arxiv.org/abs/2501.09136) | [GitHub](https://github.com/asinghcsu/AgenticRAG-Survey)  
  **Keywords**: Agentic RAG, LLMs, Multi-Agent Collaboration  
  **Descripción**: Este artículo revisa Agentic RAG, un enfoque que introduce agentes autónomos en los sistemas RAG, mejorando la recuperación, el razonamiento multiagente y la adaptabilidad dinámica.


* **Don't Do RAG: When Cache-Augmented Generation is All You Need for Knowledge Tasks** (20 dic 2024 – Taiwan)  
  [arXiv](https://arxiv.org/abs/2412.15605)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), generación aumentada por recuperación (*Retrieval-Augmented Generation* - RAG), generación aumentada por caché (*Cache-Augmented Generation* - CAG), eficiencia  
  **Descripción**: Este trabajo propone la **generación aumentada por caché** (*Cache-Augmented Generation* - CAG) como una alternativa a la generación aumentada por recuperación (*Retrieval-Augmented Generation* - RAG) en modelos de lenguaje grandes. CAG implica precargar todos los recursos relevantes en el contexto extendido del modelo antes de la inferencia, eliminando la necesidad de recuperación en tiempo real. 

* **LightRAG: Simple and Fast Retrieval-Augmented Generation** (8 oct 2024 – Beijing, Hong Kong)  nted Generation** (8 oct 2024 – Beijing, Hong Kong)  
  [arXiv](https://arxiv.org/abs/2410.05779v1) | [GitHub](https://github.com/HKUDS/LightRAG)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), generación aumentada por recuperación (*Retrieval-Augmented Generation* - RAG), estructuras de grafos, eficiencia  
  **Descripción**: Este trabajo presenta **LightRAG**, un marco que incorpora estructuras de grafos en los procesos de indexación y recuperación de texto para mejorar los sistemas de generación aumentada por recuperación. El sistema emplea un mecanismo de recuperación de dos niveles que mejora la obtención de información tanto a nivel bajo como alto. 

* **From Local to Global: A Graph RAG Approach to Query-Focused Summarization** (24 abr 2024 – Microsoft)  
  [arXiv](https://arxiv.org/abs/2404.16130v1)    
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), generación aumentada por recuperación (*Retrieval-Augmented Generation* - RAG), resumen orientado a consultas (*Query-Focused Summarization* - QFS), grafos de conocimiento (*Knowledge Graphs*)    
  **Descripción**: Este trabajo introduce **Graph RAG**, una metodología que combina la generación aumentada por recuperación con grafos de conocimiento para abordar tareas de resumen orientado a consultas en grandes colecciones de texto.  


## Otros recursos

### Blog

### Código

* ⚠️**Awesome-GraphRAG** (21 ene 2025 – Hong Kong Polytechnic)  ⭐⭐⭐
  [GitHub](https://github.com/DEEP-PolyU/Awesome-GraphRAG)  
  **Descripción**: Repositorio que recopila recursos y referencias sobre *GraphRAG*.

* **LightRAG: Simple and Fast Retrieval-Augmented Generation** (8 oct 2024 – Beijing, Hong Kong)  
  [GitHub](https://github.com/HKUDS/LightRAG)  
  **Descripción**: Repositorio de **LightRAG**.

* **PathRAG: Pruning Graph-based Retrieval Augmented Generation with Relational Paths** (18 feb 2025 – Beijing, Hong Kong)  
[GitHub](https://github.com/BUPT-GAMMA/PathRAG)  
**Descripción**: Repositorio de **PathRAG**.
