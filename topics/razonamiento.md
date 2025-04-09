# Razonamiento

## Índice

- [Razonamiento](#razonamiento)
  - [Estrategias](#estrategias)
  - [Papers](#papers)
    - [Otros](#otros)
    - [Modelos](#modelos)
  - [Otros recursos](#otros-recursos)
    - [Repositorio de artículos](#repositorio-de-artículos)
    - [Blogs](#blogs)
    - [Código](#código)
    - [Vídeos](#vídeos)

## Estrategias

- ***Chain-of-Thoughts*** (Cadena de pensamiento): Estrategia de *prompting* en la que se pide al modelo que genere razonamientos intermedios.
- ***Chain-of-Draft/Short Chain-of-Thoughts*** (Cadenas de borradores/Cadenas cortas): Estrategia de *prompting* en la que se pide al modelo que genere razonamientos intermedios concisos y eficientes, capturando solo la información esencial.
- ***In-Context Learning*** (Aprendizaje en contexto): Estrategia de *prompting* en la que se proporcionan ejemplos en el prompt.
- **Modelos inductivos y búsqueda simbólica**: Se entrena al modelo para que, en lugar de dar la respuesta, devuelva una función o una cadena lógica formal que resuelva el problema.
- ***Output Review Models (ORM)***: Verificadores de la salida final.
- ***Process Review Models (PRM)***: Verificadores del proceso paso a paso, lo que permite un control directo de los recursos.
- **Modelos correctores**: Se pide al modelo que revise y corrija pasos de su cadena de pensamiento.
- ***Reinforcement Learning with Verifiable Rewards (RLVR)*** (Aprendizaje por refuerzo con recompensas verificables): Entrenamiento por refuerzo en problemas donde se conoce la salida.
- ***Test-Time Training*** (Entrenamiento en tiempo de prueba): Ajuste de pesos en tiempo de inferencia.
- ***Latent Space Implicit Reasoning*** (Razonamiento implícito en el espacio latente): En lugar de verbalizar la cadena de pensamiento, se utilizan redes recurrentes capaces de razonar en el espacio latente.
- Carga dinámica de pesos ajustados para distintos problemas.

## Papers

### Otros

* **Reasoning Models Don't Always Say What They Think** (3 abr 2025 – Anthropic)  
  [Anthropic](https://www.anthropic.com/research/reasoning-models-dont-say-think)  
  **Keywords**: Modelos de lenguaje, razonamiento, explicaciones no fieles  
  **Descripción**: Este estudio examina la fidelidad de las explicaciones generadas por modelos de lenguaje en procesos de razonamiento. Se encontró que, aunque los modelos utilizan pistas proporcionadas en las preguntas para formular sus respuestas, a menudo omiten mencionar estas pistas en sus explicaciones, lo que plantea preocupaciones sobre la transparencia y confiabilidad de sus procesos de razonamiento.

### Modelos

* **Intelligence at the Edge of Chaos** (1 mar 2025 - Yale University, Columbia University, Northwestern University, Idaho State University)  
  [arXiv](https://arxiv.org/pdf/2410.02536)  
  **Keywords**: Inteligencia emergente, autómatas celulares elementales, complejidad, edge of chaos, LLMs, representaciones, razonamiento, predicción de jugadas de ajedrez  
  **Descripción**: Este estudio explora la relación entre la complejidad de sistemas basados en autómatas celulares elementales (ECA) y la emergencia de inteligencia en modelos de lenguaje grandes (*LLMs*). Se entrena una variante modificada del GPT-2 sobre datos generados por diversas reglas de ECA y se evalúa su desempeño en tareas de razonamiento y predicción de jugadas de ajedrez. Los resultados indican que la eficiencia de los modelos mejora al preentrenarse con datos de complejidad intermedia, sugiriendo un “punto óptimo” o "edge of chaos" para el aprendizaje efectivo.

* **Order Doesn't Matter, But Reasoning Does: Training LLMs with Order-Centric Augmentation** (27 feb 2025 – Shanghai)  
  [arXiv](https://arxiv.org/abs/2502.19907)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), razonamiento lógico, aumento de datos centrado en el orden  
  **Descripción**: Este estudio aborda la sensibilidad de los modelos de lenguaje grandes al orden de las premisas y los pasos de razonamiento. 

* **Chain of Draft: Thinking Faster by Writing Less** (25 feb 2025 – Zoom Communications)  
  [arXiv](https://arxiv.org/abs/2502.18600)  
  **Keywords**: Razonamiento, *Chain of Thought* (cadena de pensamiento), eficiencia  
  **Descripción**: Este trabajo propone "Chain of Draft" (CoD), una estrategia de *prompting* , donde los modelos de lenguaje generan razonamientos intermedios mínimos pero informativos al resolver tareas. Al reducir la verbosidad y centrarse en ideas clave, CoD iguala "Chain of Thought" (CoT) utilizando solo el 7,6% de los tokens, lo que reduce significativamente el coste y la latencia en diversas tareas de razonamiento. 

* **DeepSeek-R1** (19 feb 2025 – DeepSeek)  
  [DeepSeek_R1.pdf](https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf)  
  **Keywords**: Razonamiento, *reinforcement learning* (aprendizaje por refuerzo), *reinforcement fine-tuning* (ajuste fino mediante refuerzo)  
  **Descripción**: Modelo *open source* de razonamiento.

* **Can 1B LLM Surpass 405B LLM? Rethinking Compute-Optimal Test-Time Scaling** (10 feb 2025 – Shanghai AI Laboratory, BUPT …)  
  [arXiv](https://arxiv.org/abs/2502.06703) | [Página web](https://ryanliu112.github.io/compute-optimal-tts/)  
  **Keywords**: Razonamiento, PRM, eficiencia  
  **Descripción**: Investiga la asignación óptima de cómputo durante la inferencia, demostrando que modelos pequeños pueden superar a modelos mucho más grandes mediante estrategias de escalado en tiempo de prueba.

* **Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach** (7 feb 2025 – Max Planck Institute, Universidad de Maryland y Lawrence Livermore National Laboratory)  
  [arXiv](https://arxiv.org/abs/2502.05171)  
  **Keywords**: Razonamiento, *latent space* (espacio latente)  
  **Descripción**: Modelo *open source* de razonamiento. Arquitectura que escala el cómputo en tiempo de prueba mediante razonamiento implícito en el espacio latente.

* **Competitive Programming with Large Reasoning Models** (3 feb 2025 – OpenAI)  
  [arXiv](https://arxiv.org/abs/2502.06807)  
  **Keywords**: Razonamiento, *reinforcement learning*, *reinforcement fine-tuning*  
  **Descripción**: Este estudio demuestra que el uso de aprendizaje por refuerzo en modelos de lenguaje de gran tamaño mejora significativamente el rendimiento en tareas complejas de programación y razonamiento.

* **Kimi k1.5: Scaling Reinforcement Learning with LLMs** (22 ene 2025 – Kimi Team)  
  [arXiv](https://arxiv.org/abs/2501.12599) | [GitHub](https://github.com/MoonshotAI/Kimi-k1.5)  
  **Keywords**: Razonamiento, modelos de lenguaje grandes (*LLMs*), aprendizaje por refuerzo (*Reinforcement Learning*), multimodalidad  
  **Descripción**: Este trabajo presenta **Kimi k1.5**, un modelo multimodal de lenguaje de gran tamaño entrenado mediante aprendizaje por refuerzo. El modelo destaca por su capacidad para procesar contextos largos de hasta 128k tokens y por su rendimiento superior en tareas de razonamiento, alcanzando puntuaciones de 77.5 en AIME y 96.2 en MATH 500. Además, introduce técnicas para mejorar modelos de razonamiento de cadena corta (*short-CoT*), superando significativamente a modelos existentes como GPT-4o y Claude Sonnet 3.5. El repositorio de GitHub proporciona el informe completo y recursos adicionales.

* **Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters** (22 ene 2025 – Google y UC Berkeley)  
  [OpenReview](https://openreview.net/forum?id=4FWAwZtd2n)  
  **Keywords**: Razonamiento, *Test Time Compute* (cómputo en tiempo de prueba), *Test Time Scaling* (escalado en tiempo de prueba)  
  **Descripción**: Este estudio analiza cómo la asignación óptima de recursos computacionales durante la inferencia puede superar a modelos mucho más grandes en evaluaciones equivalentes en FLOPs. Se investigan dos mecanismos principales para escalar el cómputo en tiempo de prueba: PRMs y actualización adaptativa de la distribución de respuestas del modelo.

* **Inference-Time Scaling for Diffusion Models beyond Scaling Denoising Steps** (16 ene 2025 – DeepMind)  
  [arXiv](https://arxiv.org/abs/2501.09732)  
  **Keywords**: Razonamiento, modelos de difusión (*Diffusion Models*), *Test Time Scaling* / *Inference Time Scaling*  
  **Descripción**: Investiga cómo el rendimiento de los modelos de difusión puede mejorar con un aumento en el cómputo durante la inferencia, más allá de simplemente incrementar los pasos de *denoising* (eliminación de ruido).

* **The Lessons of Developing Process Reward Models in Mathematical Reasoning** (13 ene 2025 – QWEN)  
  [arXiv](https://arxiv.org/abs/2501.07301)  
  **Keywords**: Razonamiento, *Process Reward Models* (PRM)  
  **Descripción**: El equipo de QWEN presenta prácticas y lecciones en la construcción de modelos de recompensa de procesos para el razonamiento matemático, destacando desafíos en la anotación de datos y metodologías de evaluación.

* **Transformer²: Self-Adaptive LLMs** (9 ene 2025 – Sakana AI)  
  [arXiv](https://arxiv.org/abs/2501.06252) 
  [Sakana AI](https://sakana.ai/transformer-squared/)  
  **Keywords**: Razonamiento, Singular Value Fine-Tuning (SVF), Adaptación dinámica  
  **Descripción**: Sistema de aprendizaje automático que ajusta dinámicamente sus pesos para adaptarse a diversas tareas en tiempo real. Utiliza **descomposición en valores singulares y aprendizaje por refuerzo** para permitir que los modelos de lenguaje se adapten a nuevas tareas sin necesidad de reentrenamiento extenso, mejorando la eficiencia y el rendimiento.

* **Scaling of Search and Learning: A Roadmap to Reproduce o1 from Reinforcement Learning Perspective** (18 dic 2024 – Shanghai AI Laboratory)  
  [arXiv](https://arxiv.org/abs/2412.14135)  
  **Keywords**: Razonamiento, o1  
  **Descripción**: Presenta la supuesta arquitectura de o1.

* **The Surprising Effectiveness of Test-Time Training for Abstract Reasoning** (11 nov 2024 – MIT)  
  [arXiv PDF](https://arxiv.org/pdf/2411.07279)  
  **Keywords**: Razonamiento, Test-Time Training (TTS), ARC (*Abstraction and Reasoning Corpus*), *in-context learning* (aprendizaje en contexto)  
  **Descripción**: Estudia la eficacia del entrenamiento en tiempo de prueba (TTT) para mejorar las capacidades de razonamiento de los modelos de lenguaje, utilizando el ARC como referencia.

* **Combining Induction and Transduction for Abstract Reasoning** (4 nov 2024 – Cornell, Autodesk)  
  [arXiv](https://arxiv.org/abs/2411.02272)  
  **Keywords**: Razonamiento, Modelos Inductivos vs Modelos Transductivos, ARC  
  **Descripción**: Investiga si, al aprender una correspondencia entrada-salida a partir de muy pocos ejemplos, es preferible inferir primero una función latente que explique los ejemplos o predecir directamente nuevas salidas de prueba. Además, entrena en variaciones sintéticas de programas en Python que resuelven tareas de ARC, y encuentra que los modelos inductivos y transductivos resuelven diferentes tipos de problemas, de modo que combinarlos se aproxima al rendimiento humano en ARC.

* **Addressing the Abstraction and Reasoning Corpus via Procedural Example Generation** (10 abr 2024 – ETH Zurich)  
  [arXiv](https://arxiv.org/abs/2404.07353)  
  **Descripción**: Presenta un código para generar procedimentalmente ejemplos para las tareas de entrenamiento de ARC. Para cada una de las 400 tareas se creó un generador que sigue la lógica de transformación de los ejemplos originales, permitiendo realizar experimentos que pueden suponer avances importantes en el benchmark.

* **Algorithm Design for Learned Algorithms** (25 mar 2024 – Max Planck Institute, University of Maryland…)  
  [OpenReview](https://openreview.net/forum?id=N2M8zxPcKp)  
  **Keywords**: *algorithmic reasoning* (razonamiento algorítmico)  
  **Descripción**: Analiza cómo el ajuste de parámetros en redes neuronales permite aprender algoritmos, explorando el equilibrio entre eficiencia, exactitud y generalidad en diversas tareas.

* **Math-Shepherd: Verify and Reinforce LLMs Step-by-step without Human Annotations** (19 feb 2024 – DeepSeek-AI, Ohio State University, Peking University)  
  [arXiv](https://arxiv.org/abs/2312.08935)  
  **Keywords**: Razonamiento, *process supervision* (supervisión de procesos), *reinforcement learning*, *LLMs*  
  **Descripción**: Presenta un modelo de recompensa por procesos matemáticos que refuerza el rendimiento de los LLMs en tareas de razonamiento, eliminando la necesidad de anotaciones manuales.

* **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models** (5 feb 2024 – DeepSeek)  
  [arXiv](https://arxiv.org/abs/2402.03300)  
  **Keywords**: Razonamiento  
  **Descripción**: Presenta DeepSeekMath 7B, un modelo que amplía las capacidades de DeepSeek-Coder-Base-v1.5 7B mediante un preentrenamiento adicional con 120.000 millones de tokens relacionados con matemáticas. El modelo alcanza una puntuación del 51,7% en el benchmark MATH sin depender de herramientas externas ni técnicas de votación, acercándose al rendimiento de modelos como Gemini-Ultra y GPT-4. Además, se desarrolla el modelo de aprendizaje por refuerzo (RL) utilizado en R1.

* **Let's Verify Step by Step** (31 may 2023 – OpenAI)  
  [arXiv](https://arxiv.org/abs/2305.20050)  
  **Keywords**: Razonamiento, PRM, *active learning* (aprendizaje activo)  
  **Descripción**: Estudio que mejora el razonamiento en múltiples pasos mediante la supervisión detallada del proceso y el uso de *active learning*.

* **STaR: Bootstrapping Reasoning With Reasoning** (20 may 2022 – Google Research, Stanford)  
  [arXiv](https://arxiv.org/abs/2203.14465)  
  **Keywords**: Razonamiento, cadena de pensamiento (*chain-of-thought*), ajuste fino (*fine-tuning*)  
  **Descripción**: Primeros intentos de razonamiento. Mejora la capacidad de los modelos de lenguaje para generar razonamientos paso a paso, conocidos como "chain-of-thought", en tareas complejas como matemáticas o preguntas de sentido común. La contribución principal del artículo es el método utilizado para generar el conjunto de datos con el que se realiza el fine-tuning del modelo.

 
* **Chain-of-Thought Prompting Elicits Reasoning in Large Language Models** (28 ene 2022 – Google)  
  [arXiv](https://arxiv.org/abs/2201.11903)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), razonamiento, *Chain-of-Thought Prompting*  
  **Descripción**: Este trabajo explora cómo la generación de una cadena de pensamiento—una serie de pasos de razonamiento intermedios—mejora significativamente la capacidad de los modelos de lenguaje grandes para realizar razonamientos complejos. 

## Otros recursos

### Repositorio de artículos

  * 🔥***LLM Reasoning Papers*** (15 ene 2025 – philschmid)  
    Repositorio de artículos  
    [Hugging Face](https://huggingface.co/collections/philschmid/llm-reasoning-papers-66e6abbdf5579b829f214de8)  
    **Descripción**: Colección curada que reúne artículos para mejorar las capacidades de razonamiento de los modelos de lenguaje grandes.  


### Blogs

* ***How Scaling Laws Drive Smarter, More Powerful AI*** (12 feb 2025 – NVIDIA)  
  Blog  
  [Blog de NVIDIA](https://blogs.nvidia.com/blog/ai-scaling-laws/#:~:text=Scaling%20laws%20describe%20how%20the,parameters%20or%20computational%20resources%20increases.)  
  **Descripción**: Entrada del blog que detalla cómo las leyes de escalabilidad en IA establecen la relación entre la cantidad de datos, parámetros y recursos computacionales con la mejora en el rendimiento de los modelos. Explica conceptos de preentrenamiento, postentrenamiento y escalado en tiempo de inferencia, poniendo especial énfasis en la importancia de aplicar computación acelerada para soportar modelos de razonamiento complejo.


* ***Automating GPU Kernel Generation with DeepSeek R1 and Inference Time Scaling*** (fecha – NVIDIA Developer)  
  Blog  
  [Developer Blog de NVIDIA](https://developer.nvidia.com/blog/automating-gpu-kernel-generation-with-deepseek-r1-and-inference-time-scaling/)  
  **Descripción**: Entrada del blog que explica cómo DeepSeek R1 automatiza la generación de kernels para GPU, permitiendo optimizar el rendimiento en tiempo de inferencia. El artículo aborda técnicas avanzadas de deep learning para la generación eficiente de código en GPU y describe cómo el escalado en tiempo de inferencia puede mejorar la eficiencia y capacidad de respuesta de los modelos de inteligencia artificial en producción.


* 🔥🔥🔥***Data-optimal scaling laws*** (2025 – Life Architect)  
  Blog  
  [Blog](https://lifearchitect.ai/chinchilla/)  
  **Descripción**: Resumen del escaladado de datos (ratio datos/parametros para maximizar un coste computacional dado)

### Código

* **DeepScaleR-1.5B-Preview** (febrero 2025 – Agentica)  
  [Hugging Face](https://huggingface.co/agentica-org/DeepScaleR-1.5B-Preview)  
  **Descripción**: Modelo de lenguaje ajustado a partir de DeepSeek-R1-Distilled-Qwen-1.5B utilizando aprendizaje por refuerzo distribuido.

* **Kimi k1.5** (22 ene 2025 – Kimi Team)  
  [GitHub](https://github.com/MoonshotAI/Kimi-k1.5)  
  **Descripción**: Repositorio del proyecto Kimi k1.5.

* **TinyZero: Reproducción de DeepSeek R1-Zero** (febrero 2025 – Berkeley)  
  [GitHub](https://github.com/Jiayi-Pan/TinyZero)  
  **Descripción**: Implementación accesible y minimalista de DeepSeek R1-Zero, enfocada en tareas de cuenta regresiva y multiplicación.

* **R1-V: Reforzando la Capacidad de Generalización en Modelos Visión-Lenguaje con Menos de $3** (febrero 2025 – Deep-Agent)  
  [GitHub](https://github.com/Deep-Agent/R1-V)  
  **Descripción**: Demuestra que el aprendizaje por refuerzo con recompensas verificables supera al ajuste supervisado tradicional en modelos de visión-lenguaje.

* **Compute Optimal TTS** (10 feb 2025 – Shanghai AI Laboratory, Tsinghua University, Harbin Institute of Technology, BUPT)  
  [Página web](https://ryanliu112.github.io/compute-optimal-tts/)  
  **Descripción**: Explica cómo calcular parámetros óptimos para el escalado en tiempo de prueba (Test Time Scaling).

### Vídeos

* **Test Time Scaling/Test Time Compute: Análisis de la literatura reciente** (febrero 2025 – Discover IA - YouTube)  
  [YouTube](https://www.youtube.com/watch?v=uqCoR_1jZPI&ab_channel=DiscoverAI)  
  **Descripción**: Video que analiza distintos papers en el campo, desde modelos basados en PRM (*Process Review Models*) hasta los últimos modelos recurrentes que razonan en el espacio latente.

* **Reinforcement Fine-Tuning—12 Days of OpenAI: Day 2** (diciembre 2024 – OpenAI)  
  [YouTube](https://www.youtube.com/watch?v=yCIYS9fx56U) | [OpenAI](https://openai.com/form/rft-research-program/)  
  **Descripción**: Miembros del equipo de OpenAI presentan el programa de investigación sobre ajuste fino mediante refuerzo, destacando su importancia en el desarrollo de modelos de lenguaje más precisos y eficientes.

* **The AI Reasoning Lie** (febrero 2025 – Discover IA - YouTube)  
    [YouTube](https://www.youtube.com/watch?v=oE98PJefK4w&ab_channel=DiscoverAI)  
    **Descripción**:Limitaciones de los modelos de razonamiento.

