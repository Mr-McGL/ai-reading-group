# Razonamiento

## Papers

* **The Surprising Effectiveness of Test-Time Training for Abstract Reasoning** (11 nov 2024 - MIT)  
  https://arxiv.org/pdf/2411.07279 
  **Keywords**: Razonamiento, Test-Time Training (TTS), ARC *Abstraction and Reasoning Corpus*, *in-context learning*  
  **Descripcion**: Este estudio investiga la eficacia del entrenamiento en tiempo de prueba (TTT) para mejorar las capacidades de razonamiento de los modelos de lenguaje, utilizando el *Abstraction and Reasoning Corpus* (ARC) como referencia.

* **Combining Induction and Transduction for Abstract Reasoning** (4 nov 2024 - Cornell, Autodesk)  
  https://arxiv.org/abs/2411.02272  
  **Keywords**: Razonamiento, Modelos Inductivos vs Modelos Tranductivos, ARC  
  **Descripcion**: Este estudio investiga si, al aprender una correspondencia entrada-salida a partir de muy pocos ejemplos, es mejor inferir primero una función latente que explique los ejemplos o predecir directamente nuevas salidas de prueba.e entrena en variaciones sintéticas de programas en Python que resuelven tareas de ARC.e encuentra que los modelos inductivos y transductivos resuelven diferentes tipos de problemas de prueba, y que combinarlos se aproxima al rendimiento humano en ARC.

* **Addressing the Abstraction and Reasoning Corpus via Procedural Example Generation** (10 abr 2024 - ETH Zurich)  
  https://arxiv.org/abs/2404.07353  
  **Keywords**: Razonamiento, ARC  
  *Descripcion*: ste trabajo presenta un código para generar procedimentalmente ejemplos para las tareas de entrenamiento de ARC.ara cada una de las 400 tareas, se creó un generador de ejemplos que sigue la lógica de transformación de los ejemplos originales.sto permite realizar una amplia gama de experimentos que pueden ser pasos importantes hacia avances en el benchmark.

* **STaR: Bootstrapping Reasoning With Reasoning** (20 may 2022 - Google Research)  
  https://arxiv.org/abs/2203.14465  
  *Notas*: Primeros intentos de razonamiento.  
* **Scaling of Search and Learning: A Roadmap to Reproduce o1 from Reinforcement Learning Perspective** (18 dic 2024 - Shanghai AI Laboratory)  
  https://arxiv.org/abs/2412.14135  
  *Notas*: Supuesta arquitectura de o1.  
* **DeepSeek-R1** (19 feb 2025 - DeepSeek)  
  https://github.com/deepseek-ai/DeepSeek-R1/blob/main/DeepSeek_R1.pdf  
  *Notas*: Modelo *open source*.  
* **DeepSeekMath: Pushing the Limits of Mathematical Reasoning in Open Language Models** (5 feb 2024 - DeepSeek)  
  https://arxiv.org/abs/2402.03300  
  *Notas*: ste trabajo presenta DeepSeekMath 7B, un modelo que amplía las capacidades de DeepSeek-Coder-Base-v1.5 7B mediante un preentrenamiento adicional con 120.000 millones de tokens relacionados con matemáticas.l modelo logra una puntuación del 51,7% en el benchmark MATH sin depender de herramientas externas ni técnicas de votación, acercándose al rendimiento de modelos como Gemini-Ultra y GPT-4.demás, _***se desarrolla el modelo de aprendizaje por refuerzo (RL) utilizado en R1***_
* **Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters** (22 ene 2025 - Google y UC Berkeley)  
  https://openreview.net/forum?id=4FWAwZtd2n  
  *Notas*: Este estudio de Google y UC Berkeley analiza cómo la asignación óptima de recursos computacionales durante la inferencia puede superar a modelos mucho más grandes en evaluaciones equivalentes en FLOPs. 
* **Inference-Time Scaling for Diffusion Models beyond Scaling Denoising Steps** (enero 2025 - DeepMind)  
  https://arxiv.org/abs/2501.09732  
  *Notas*: Este trabajo investiga cómo el rendimiento de los modelos de difusión puede mejorar con un aumento en el cómputo durante la inferencia, más allá de simplemente incrementar los pasos de denoising. 
* **The Lessons of Developing Process Reward Models in Mathematical Reasoning** (enero 2025 - QWEN)  
  https://arxiv.org/abs/2501.07301  
  *Notas*: El equipo QWEN presenta prácticas y lecciones en la construcción de modelos de recompensa de procesos para el razonamiento matemático, destacando desafíos en la anotación de datos y metodologías de evaluación. 
