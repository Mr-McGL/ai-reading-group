# Neurociencia y Medicina

## Índice

- [Índice](#índice)
- [Papers](#papers)
  - [Relación entre IA y neurociencia](#relación-entre-ia-y-neurociencia)
  - [LLMs y salud mental](#llms-y-salud-mental)
- [Medicina](#medicina)
- [Recursos](#recursos)

## Papers

### Relación entre IA y neurociencia

* **Emergence of Language in the Developing Brain** (2025 – Meta FAIR Science)
  [Artículo](https://go.fb.me/hfh9i5), [Anuncio de Meta](https://ai.meta.com/blog/meta-fair-science-new-open-source-releases/)
  **Descripción**: Estudio conjunto con el Rothschild Foundation Hospital que mapea cómo surgen las representaciones del lenguaje en cerebros en desarrollo (2 – 5 años) mediante la grabación de actividad de más de 7 400 electrodos intracraneales. Revela paralelismos sorprendentes con representaciones de LLMs como wav2vec 2.0 y Llama 4, avanzando en la intersección de IA y neurociencia del lenguaje.

* **A unified acoustic-to-speech-to-language embedding space captures the neural basis of natural language processing in everyday conversations** (31 mar 2025 – Google, Princeton)  
  [Nature Human Behaviour](https://www.nature.com/articles/s41562-025-02105-9)  
  **Keywords**: procesamiento del lenguaje natural, embeddings acústico-habla-lingüística, electrocorticografía (ECoG), modelo multimodal, conversaciones reales  
  **Descripción**: Este estudio introduce un marco computacional unificado que integra representaciones acústicas, de habla y lingüísticas extraídas de un modelo multimodal (*Whisper*) para predecir la actividad neural durante conversaciones cotidianas. Mediante el uso de electrocorticografía en pacientes durante interacciones naturales, se mapea la alineación entre las distintas capas del modelo y las áreas cerebrales implicadas en la percepción y producción del lenguaje, demostrando una correlación robusta en la actividad neuronal.

* **Advances and Challenges in Foundation Agents: From Brain-Inspired Intelligence to Evolutionary, Collaborative, and Safe Systems** (31 mar 2025 – Google, Meta ...)  <<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<<  
[arXiv](https://www.arxiv.org/abs/2504.01990) | [github_papers](https://github.com/FoundationAgents/awesome-foundation-agents?tab=readme-ov-file)  
  **Keywords**: Modelos de lenguaje grandes (*LLMs*), agentes inteligentes, auto-mejora, evolución colaborativa, seguridad    
  **Descripción**: Este artículo ofrece una revisión exhaustiva sobre los fundamentos y desafíos en el desarrollo de agentes inteligentes basados en modelos de lenguaje grandes. Se explora una arquitectura modular inspirada en el cerebro humano que integra componentes para la percepción, memoria, modelado del mundo, procesamiento de recompensas y sistemas análogos a las emociones. Además, se analizan mecanismos de auto-mejora y evolución adaptativa, así como la colaboración en sistemas multiagente, subrayando la necesidad de construir sistemas seguros, éticos y robustos para su implementación en entornos reales.*


* **Leveraging a Large Language Model to Assess Quality-of-Care: Monitoring ADHD Medication Side Effects** (24 abr 2024 – Standford) 
  [medRxiv](https://www.medrxiv.org/content/10.1101/2024.04.23.24306225v1)    
  **Keywords**: ADHD; large language model; LLaMA; quality‑of‑care measurement; electronic health records; side effects monitoring; pediatrics; natural language processing   
  **Descripción**: Este estudio de cohorte retrospectivo incluyó 1.247 niños de 6–11 años con diagnóstico de TDAH y al menos dos encuentros de medicación entre 2015 y 2022 en una red de atención primaria comunitaria. Se entrenó, evaluó y desplegó el modelo LLaMA de código abierto en 15.593 notas clínicas de encuentros presenciales, telemáticos y telefónicos relacionados con TDAH, comparando su detección de la indagación de efectos secundarios con la revisión manual de historias clínicas.

* **Neuroscience-Inspired Artificial Intelligence** (19 jul 2017 – Neuron)
  [Neuron](https://doi.org/10.1016/j.neuron.2017.06.011)  
  **Keywords**: Inteligencia artificial, neurociencia, modelos inspirados en el cerebro  
  **Descripción**: Este artículo argumenta que una mejor comprensión de los cerebros biológicos puede desempeñar un papel vital en la construcción de máquinas inteligentes. Se examinan las interacciones históricas entre los campos de la inteligencia artificial y la neurociencia, destacando avances actuales en IA inspirados en el estudio de la computación neuronal en humanos y otros animales. Se concluye resaltando temas compartidos que pueden ser clave para avanzar en futuras investigaciones en ambos campos.


### LLMs y salud mental

* **Integrating Artificial Intelligence into Clinical Practice** (15 abr 2025 – Dartmouth, Hanover)  
  [New England Journal of Medicine - AI](https://ai.nejm.org/doi/full/10.1056/AIoa2400802)    
  **Keywords**: inteligencia artificial, medicina de precisión, diagnóstico asistido, ética médica, aprendizaje automático  
  **Descripción**: En este artículo se exploran los avances y desafíos asociados a la incorporación de la inteligencia artificial en el ámbito clínico. Se examinan estudios y casos prácticos que evidencian cómo la IA puede optimizar la toma de decisiones médicas, mejorar la precisión en el diagnóstico y personalizar tratamientos, a la vez que se analizan los dilemas éticos que plantea su implementación.

* **Large language models deconstruct the clinical intuition behind diagnosing autism** (26 mar 2025 – Universidades e instituciones de Montreal)  
[Cell](https://www.cell.com/cell/fulltext/S0092-8674%2825%2900213-2),
[git](https://github.com/dblabs-mcgill-mila/NLP-ASD)  
**Keywords**: autismo; diagnóstico clínico; intuición clínica; modelos de lenguaje a gran escala; LLM; explicabilidad; DSM-5; comportamientos repetitivos estereotipados; intereses especiales; conductas basadas en percepción.  
**Descripción**: Este estudio emplea grandes modelos de lenguaje para descomponer y examinar la lógica de la intuición clínica de expertos a partir de informes médicos, con el fin de entender mejor el diagnóstico del trastorno del espectro autista. Tras un preentrenamiento en cientos de millones de oraciones generales y un ajuste fino con más de 4.000 registros de salud libres, el modelo distingue entre casos confirmados y sospechosos de autismo. Mediante una estrategia de explicabilidad, el sistema identifica las frases más determinantes para la decisión diagnóstica, resaltando criterios clave del DSM-5 como los comportamientos repetitivos estereotipados, intereses especiales y conductas basadas en la percepción. Los hallazgos ofrecen una visión profunda del proceso de diagnóstico y abren camino a herramientas clínicas asistidas por IA.

* **Identifying Psychiatric Manifestations in Outpatients with Depression and Anxiety: A Large Language Model-Based Approach** (3 ene 2025 – Multiples Universidades Chinas)  
[medRxiv](https://www.medrxiv.org/content/10.1101/2025.01.03.24318117v1)
**Keywords**: depresión; ansiedad; manifestaciones psiquiátricas; modelos de lenguaje a gran escala; entrevistas psiquiátricas; registros médicos electrónicos; aprendizaje automático; explicabilidad; clasificación.  
**Descripción**: Este estudio explora la capacidad de los modelos de lenguaje a gran escala para automatizar la identificación de categorías diagnósticas y síntomas a partir de diálogos psiquiatra-paciente en 1 160 pacientes ambulatorios con trastornos de depresión y ansiedad. Se elaboró un corpus de entidades clínicas a partir de anotaciones en registros médicos electrónicos y escalas de evaluación, y se emplearon LLM para identificar síntomas y evaluar escalas de valoración. Mediante un pipeline de aprendizaje en ensamblaje con validación cruzada de 10 pliegues, el sistema alcanzó una precisión del 86,9 % en la detección de anotaciones clínicas, 74,7 % (ansiedad) y 77,2 % (depresión) en identificación de síntomas, y 75,5 % al diferenciar pacientes con depresión y ansiedad según códigos ICD-10. El análisis de características generadas por el modelo destacó marcadores como anhedonia y disminución de la volición en depresión, y tensión e incapacidad para relajarse en ansiedad, demostrando el potencial de los LLM para mejorar el diagnóstico psiquiátrico y ofrecer insights interpretables.

* **Transparent but Powerful: Explainability, Accuracy, and Generalizability in ADHD Detection from Social Media Data** (University of Amsterdam, University of Florida, 23 nov 2024)  
[arXiv](https://arxiv.org/abs/2411.15586)  
**Keywords**: TDAH; detección; explicabilidad; precisión; generalizabilidad; redes sociales; procesamiento de lenguaje natural; aprendizaje automático; BiLSTM; transformer; cribado digital.  
**Descripción**: Este estudio explora métodos para detectar el trastorno por déficit de atención e hiperactividad (TDAH) a partir de datos de redes sociales, comparando modelos de aprendizaje automático y profundo basados en BiLSTM y arquitecturas transformer. Se analizan las compensaciones entre interpretabilidad y rendimiento, y se evalúa la capacidad de generalización mediante datos de Reddit y Twitter. Los resultados identifican patrones lingüísticos clave asociados al TDAH y proporcionan bases para el desarrollo de herramientas de cribado digital no invasivas y escalables.


* **A New Perspective on ADHD Research: Knowledge Graph Construction with LLMs and Network Based Insights** (19 sep 2024 – University at Albany)
[arXiv](https://arxiv.org/abs/2409.12853)  
  **Keywords**: ADHD; knowledge graph; large language models; LLM; network analysis; k-core; Graph-RAG; natural language processing; social and information networks  
  **Descripción**: Este estudio presenta la construcción de un grafo de conocimiento integral sobre el trastorno por déficit de atención e hiperactividad, integrando literatura científica y datos clínicos mediante modelos de lenguaje a gran escala. Mediante un análisis de red —incluyendo técnicas de k-core— se identificaron los nodos y relaciones más críticos para comprender la patología. A partir de estos hallazgos, se diseñó Graph-RAG, un chatbot context-aware que utiliza el grafo para ofrecer interacciones precisas e informadas. Este enfoque no solo profundiza el entendimiento del TDAH, sino que también proporciona una herramienta valiosa para investigación y aplicaciones clínicas.

## Medicina

* **MINIMAR (MINimum Information for Medical AI Reporting)** (2020 – Standford)
  [Artículo](https://academic.oup.com/jamia/article/27/12/2011/5864179?login=false)
  **Descripción**: Propuesta de un conjunto de estándares mínimos para la elaboración de informes sobre modelos de inteligencia artificial en el ámbito sanitario. Define cuatro componentes esenciales —población y entorno del estudio, características demográficas de los datos de entrenamiento, arquitectura del modelo y procesos de evaluación y validación— con el fin de garantizar transparencia, reproducibilidad y control de sesgos en las aplicaciones clínicas.


## Recursos


* **HealthBench** (2025 – OpenAI)
  [Dataset](https://openai.com/index/healthbench/)
  **Descripción**: Benchmark diseñado para evaluar la capacidad de los sistemas de IA en escenarios de salud realistas. HealthBench incluye 5 000 conversaciones multi-turno entre usuarios (pacientes o profesionales) y modelos de IA, cada una valorada mediante una rúbrica elaborada por 262 médicos con práctica en 60 países. Las conversaciones, generadas de forma sintética y mediante pruebas adversariales humanas, cubren múltiples idiomas, especialidades y niveles de complejidad, y se han definido 48 562 criterios de evaluación que abarcan precisión, calidad de comunicación, profundidad de respuesta y adecuación al contexto clínico. Este dataset permite medir la utilidad, fiabilidad y margen de mejora de los modelos de IA en tareas sanitarias, estableciendo así una línea base para futuros avances.


