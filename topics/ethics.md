# AI Governance: Ética, Alineamiento, Explicabilidad y Controles de Seguridad en LLMs

## Índice

- [AI Governance: Ética, Alineamiento, Explicabilidad y Controles de Seguridad en LLMs](#ai-governance-ética-alineamiento-explicabilidad-y-controles-de-seguridad-en-llms)
  - [Papers](#papers)

## Papers

* **Scaling Unsupervised Learning: A New Approach to Neural Network Architectures** (03 mar 2025 – UC San Diego)  
  [arXiv](https://arxiv.org/abs/2503.23674)  
  **Keywords**: aprendizaje no supervisado, redes neuronales, escalabilidad, algoritmos, inteligencia artificial  
  **Descripción**: Este artículo propone un nuevo enfoque para el escalado de técnicas de aprendizaje no supervisado en redes neuronales. Se presentan algoritmos optimizados para el procesamiento de grandes volúmenes de datos y se evalúa su rendimiento en comparación con métodos tradicionales. Además, se discuten las implicaciones de estos avances en el desarrollo futuro de la inteligencia artificial.

* **Reasoning Models Don't Always Say What They Think** (3 abr 2025 – Anthropic)  
  [Anthropic](https://www.anthropic.com/research/reasoning-models-dont-say-think)  
  **Keywords**: Modelos de lenguaje, razonamiento, explicaciones no fieles  
  **Descripción**: Este estudio examina la fidelidad de las explicaciones generadas por modelos de lenguaje en procesos de razonamiento. Se encontró que, aunque los modelos utilizan pistas proporcionadas en las preguntas para formular sus respuestas, a menudo omiten mencionar estas pistas en sus explicaciones, lo que plantea preocupaciones sobre la transparencia y confiabilidad de sus procesos de razonamiento.

* **On the Biology of a Large Language Model** (27 mar 2025 – Anthropic)  
  [Transformer Circuits](https://transformer-circuits.pub/2025/attribution-graphs/biology.html) | [video](https://www.anthropic.com/news/tracing-thoughts-language-model) 
  **Keywords**: biología de modelos de lenguaje, circuitos de atribución, interpretabilidad, análisis de circuitos, Claude 3.5 Haiku  
  **Descripción**: Este artículo investiga los mecanismos internos utilizados por Claude 3.5 Haiku, el modelo de producción de Anthropic, a través de la metodología de trazado de circuitos. Se examinan diversos casos de estudio –desde razonamiento multi-paso y planificación en poesía hasta diagnósticos médicos y detección de entidades– para revelar cómo el modelo organiza y procesa información internamente, utilizando “grafos de atribución” que actúan como un “diagrama de cableado” de sus procesos computacionales.

* **Circuit Tracing: Revealing Computational Graphs in Language Models** (27 mar 2025 – Anthropic)  
  [Transformer Circuits](https://transformer-circuits.pub/2025/attribution-graphs/methods.html)  
  **Keywords**: trazado de circuitos, grafos de atribución, interpretabilidad, modelos transformadores, mecanismos de computación  
  **Descripción**: Este artículo describe un método para revelar los mecanismos subyacentes en el funcionamiento de modelos de lenguaje. Los autores construyen “grafos de atribución” que representan, de forma interpretable, los pasos computacionales que el modelo realiza al procesar una entrada. Se introduce la idea de un “modelo de reemplazo”, donde se sustituye parte del modelo original por componentes más interpretables, permitiendo analizar interacciones lineales entre características y validar circuitos a través de experimentos de perturbación. Además, se discuten herramientas de visualización y evaluación que facilitan la interpretación de estos grafos y, por tanto, una comprensión más profunda de las decisiones del modelo.


* **Minions: Cost-efficient Collaboration Between On-device and Cloud Language Models** (21 feb 2025 – Standford)  
[arXiv](https://arxiv.org/abs/2502.15964)  
**Keywords**: Modelos de lenguaje grandes (*LLMs*), colaboración local-remota, eficiencia de costos, razonamiento sobre datos extensos, seguridad
**Descripción**: Este estudio investiga cómo un modelo de lenguaje pequeño, operando en un dispositivo local con acceso a datos locales, puede colaborar con un modelo de lenguaje avanzado alojado en la nube para abordar tareas del mundo real que implican razonamiento financiero, médico y científico sobre documentos extensos. 

* **Utility Engineering: Analyzing and Controlling Emergent Value Systems in AIs** (12 feb 2025 – Center for AI Safety, Berkeley, Pennsylvania)  
  [arXiv](https://arxiv.org/abs/2502.08640)  
  **Keywords**: Valores emergentes, alineación, seguridad en IA  
  **Descripción**: Este estudio investiga la aparición de sistemas de valores coherentes en los LLMs a medida que escalan, y propone una agenda de investigación en la Ingeniería de Servicios Públicos (*Utility Engineering*), que abarca tanto el análisis como el control de dichas preferencias, detectando comportamientos problemáticos y ofreciendo métodos para alinear las utilidades de la IA con valores humanos.

* **Auditing Prompt Caching in Language Model APIs** (11 feb 2025 – Standford)    
[arXiv](https://arxiv.org/abs/2502.07776)  
**Keywords**: Modelos de lenguaje grandes (*LLMs*), almacenamiento en caché de *prompts*, ataques de canal lateral, privacidad  
**Descripción**: Este estudio investiga cómo el almacenamiento en caché de *prompts* en APIs de modelos de lenguaje grandes puede introducir variaciones en los tiempos de respuesta, lo que podría ser explotado en ataques de canal lateral. Mediante auditorías estadísticas, los autores detectaron que 8 de 17 proveedores de APIs, incluyendo OpenAI, comparten cachés globalmente entre usuarios, lo que podría permitir a un atacante inferir información sobre los *prompts* de otros usuarios basándose en tiempos de respuesta más rápidos.

* **Frontier Models are Capable of In-context Scheming** (16 ene 2025 – Apollo Research)  
  [arXiv](https://arxiv.org/pdf/2412.04984) 
  **Keywords**: modelos frontera, razonamiento in-context, estrategias emergentes, planificación, inteligencia artificial  
  **Descripción**: Este estudio analiza la capacidad de los modelos de inteligencia artificial para generar y ejecutar esquemas complejos basados en el contexto proporcionado, destacando su potencial en tareas de razonamiento estratégico y planificación.


* **Best-of-N Jailbreaking** (19 dic 2024 – Standford)  
  [arXiv](https://arxiv.org/pdf/2412.03556)  
  **Keywords**: Jailbreak, red-teaming, seguridad en IA, modelos de lenguaje grandes (*LLMs*), multimodal, escalabilidad  
  **Descripción**: Este estudio presenta "Best-of-N Jailbreaking", un método automatizado en caja negra que consigue vulnerar sistemas avanzados de IA mediante la aplicación repetida de variaciones en los *prompts*. Se evalúa su eficacia en diversas modalidades (texto, visión y audio), destacando un comportamiento de escalado que sigue una ley de potencias.

* **Scaling Monosemanticity: Extracting Interpretable Features from Claude 3 Sonnet** (21 may 2024 – Anthropic)  
  [Transformer Circuits](https://transformer-circuits.pub/2024/scaling-monosemanticity/index.html)  
  **Keywords**: monosemanticidad, escalado, interpretabilidad, modelos transformadores, especialización  
  **Descripción**: Este artículo investiga cómo la propiedad de monosemanticidad se ve afectada al escalar los modelos transformadores, analizando la especialización de sus componentes y las implicaciones para la interpretación y el rendimiento en tareas de procesamiento del lenguaje natural.

* **Towards Monosemanticity: Decomposing Language Models With Dictionary Learning** (5 oct 2023 – Anthropic)  
  [Transformer Circuits](https://transformer-circuits.pub/2023/monosemantic-features/index.html)  / [2](https://www.anthropic.com/news/decomposing-language-models-into-understandable-components)
  **Keywords**: transformers, interpretabilidad, características monosemánticas, redes neuronales, análisis  
  **Descripción**: Este artículo explora el fenómeno de las características monosemánticas en modelos de transformadores, analizando cómo ciertas neuronas se especializan en representar conceptos concretos. Se discuten las implicaciones de este comportamiento para la interpretabilidad y la comprensión del funcionamiento interno de dichos modelos.



