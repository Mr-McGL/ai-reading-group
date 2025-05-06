# Agentización

## Índice

- [Agentización](#agentización)
  - [Papers](#papers)
  - [Otros recursos](#otros-recursos)
    - [Cursos](#cursos)
    - [Código](#código)

## Papers

* >>>> **Advances and Challenges in Foundation Agents: From Brain-Inspired Intelligence to Evolutionary, Collaborative, and Safe Systems** (31 mar 2025 – Google, Meta ...)  
  [arXiv](https://www.arxiv.org/abs/2504.01990) | [github_papers](https://github.com/FoundationAgents/awesome-foundation-agents?tab=readme-ov-file)
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), agentes inteligentes, auto-mejora, evolución colaborativa, seguridad  
  **Descripción**: Este artículo ofrece una revisión exhaustiva sobre los fundamentos y desafíos en el desarrollo de agentes inteligentes basados en modelos de lenguaje grandes. Se explora una arquitectura modular inspirada en el cerebro humano que integra componentes para la percepción, memoria, modelado del mundo, procesamiento de recompensas y sistemas análogos a las emociones. Además, se analizan mecanismos de auto-mejora y evolución adaptativa, así como la colaboración en sistemas multiagente, subrayando la necesidad de construir sistemas seguros, éticos y robustos para su implementación en entornos reales.

* **PaperBench: Evaluating AI’s Abilities to Replicate AI Research** (2025 – OpenAI)  
  [OpenAI](https://cdn.openai.com/papers/22265bac-3191-44e5-b057-7aaacd8e90cd/paperbench.pdf)  
  **Keywords**: replicación, benchmark, inteligencia artificial, evaluación, rúbricas  
  **Descripción**: Este artículo presenta PaperBench, un benchmark diseñado para evaluar la capacidad de agentes de IA para replicar investigaciones en el ámbito de la inteligencia artificial. Los agentes deben replicar por completo los experimentos descritos en 20 artículos presentados en ICML 2024, partiendo de cero y sin utilizar el código original. La evaluación se fundamenta en rúbricas detalladas, co-diseñadas con los autores de los trabajos, que desglosan cada proceso de replicación en múltiples sub-tareas (desde la implementación del código hasta la ejecución y verificación de resultados). Además, se introduce un evaluador automático basado en LLM para calificar escalablemente cada intento de replicación.  
  **Replica de google**: 
  [AI co-scientist](https://research.google/blog/accelerating-scientific-breakthroughs-with-an-ai-co-scientist/)  
  [Resultados](https://www.forbes.com/sites/lesliekatz/2025/02/19/google-unveils-ai-co-scientist-to-supercharge-research-breakthroughs/)  
  **Sarkana**:  
  [The AI Scientist Generates its First Peer-Reviewed Scientific Publication](https://sakana.ai/ai-scientist-first-publication/)

* **Agentic Reasoning: Reasoning LLMs with Tools for Deep Research** (7 feb 2025 – Oxford)  
  [arXiv](https://arxiv.org/abs/2502.04644) | [GitHub](https://github.com/theworldofagents/Agentic-Reasoning)  
  **Keywords**: *LLMs* (modelos de lenguaje grandes), razonamiento, agentes, herramientas externas, investigación profunda (*deep research*), *knowledge graph* (grafo de conocimiento), RAG
  **Descripción**: Este trabajo introduce **Agentic Reasoning**, un marco que mejora el razonamiento de los *LLMs* integrando *agents* que utilizan herramientas externas.  


* **Agentless: Demystifying LLM-based Software Engineering Agents** (1 jul 2024 – University of Illinois)  
  [arXiv](https://arxiv.org/abs/2407.01489) | [GitHub](https://github.com/OpenAutoCoder/Agentless)  
  **Keywords**: Agentización, modelos de lenguaje grandes (*LLMs*), automatización  
  **Descripción**: Este trabajo presenta un enfoque simplificado para resolver problemas de desarrollo de software sin recurrir a agentes autónomos complejos. A diferencia de métodos anteriores que utilizan agentes capaces de ejecutar comandos y planificar acciones, **Agentless** emplea un proceso de tres fases: localización del problema, reparación y validación del parche. El estudio destaca el potencial de técnicas más simples y rentables en el desarrollo autónomo de software.


* **Judging LLM-as-a-Judge with MT-Bench and Chatbot Arena** (28 dec 2023 – UC Berkeley)  
  [OpenReview](https://openreview.net/forum?id=uccHPGDlao) | [GitHub](https://github.com/lm-sys/FastChat/tree/main/fastchat/llm_judge)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), preferencia humana, pruebas de evaluación, evaluación  
  **Descripción**: La evaluación de asistentes conversacionales basados en modelos de lenguaje grandes (LLMs) es desafiante debido a la falta de *benchmarks* adecuados para medir preferencias humanas. Se propone el enfoque *LLM-as-a-judge*, donde LLMs avanzados actúan como jueces en evaluaciones abiertas, analizando sesgos y limitaciones. La validación con **MT-bench** y **Chatbot Arena** muestra que modelos como GPT-4 alcanzan más del 80% de concordancia con evaluadores humanos, demostrando que *LLM-as-a-judge* es un método escalable y explicable que complementa los *benchmarks* tradicionales.

## Otros recursos

### Cursos

* ***NVIDIA: Cursos RAG + Agentes*** (NVIDIA)  
  Curso  
  [Buscar Cursos](https://www.nvidia.com/en-us/training/find-training/) | [RAG 1](https://learn.nvidia.com/courses/course-detail?course_id=course-v1:DLI+S-FX-15+V1) | [RAG 2](https://learn.nvidia.com/courses/course-detail?course_id=course-v1:DLI+S-FX-16+V1)  
  **Descripción**: Agentes + RAG + Cursos varios

### Código


* **Agentic Reasoning: Reasoning LLMs with Tools for Deep Research** (7 feb 2025 – Oxford)  
  [GitHub](https://github.com/theworldofagents/Agentic-Reasoning)  
  **Descripción**: Repositorio de **Agentic Reasoning**.


* **Agentless**  (1 jul 2024 – University of Illinois)  
  [GitHub](https://github.com/OpenAutoCoder/Agentless)  
  **Descripción**: Repositorio del proyecto **Agentless**.