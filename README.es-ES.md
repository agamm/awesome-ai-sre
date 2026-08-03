

# Awesome AI SRE [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Aplicando inteligencia artificial a la ingeniería de fiabilidad de sitios (SRE): respuesta autónoma a incidentes, observabilidad inteligente e infraestructura con autoreparación.

> Abierto a conversaciones sobre adquisiciones o alianzas estratégicas que preserven el valor del proyecto para los usuarios existentes. Consultas serias a través de LinkedIn.


## Contenidos

- [Agentes AI para SRE](#ai-sre-agents)
- [Depuración en Producción con IA](#ai-production-debugging)
- [Gestión de Incidentes](#incident-management)
- [Plataformas de Observabilidad](#observability-platforms)
- [Plataformas AIOps](#aiops-platforms)
- [Análisis de Registros y Detección de Anomalías](#log-analysis-and-anomaly-detection)
- [Ingeniería de Caos](#chaos-engineering)
- [Automatización de Runbooks](#runbook-automation)
- [Optimización de Costos en la Nube](#cloud-cost-optimization)
- [Herramientas de DevOps con LLM](#llm-powered-devops-tools)
- [Benchmarks para Agentes](#agent-benchmarks)
- [Artículos de Investigación](#research-papers)
- [Blogs y Boletines](#blogs-and-newsletters)
- [Listas de la Comunidad](#community-lists)

## Agentes AI para SRE

*Agentes de IA autónomos diseñados específicamente para flujos de trabajo de SRE: investigan alertas, realizan análisis de causa raíz y resuelven incidentes con mínima intervención humana.*

- [Resolve AI](https://resolve.ai) - Plataforma autónoma de SRE creada por los co-creadores de OpenTelemetry que busca una tasa de resolución autónoma del 80 % mediante investigación paralela de hipótesis.
- [Middleware OpsAI](https://middleware.io/product/ops-ai/) - Agente AI para SRE que detecta problemas en APM, RUM, registros y Kubernetes, rastrea errores hasta la línea exacta de código mediante GitHub MCP y abre un PR con una corrección o la aplica automáticamente en Kubernetes sin despertar a su ingeniero en guardia.
- [Cleric](https://cleric.ai) - Compañero autónomo de IA para SRE que investiga alertas 24/7 y entrega análisis de causa raíz en Slack.
- [NeuBird](https://neubird.ai) - Copiloto de IA SRE con capacidades de agente para TI empresarial, con análisis de telemetría potenciado por LLM y más de 230 000 alertas resueltas.
- [Phoebe AI](https://phoebe.ai) - Predice incidentes a partir de indicadores tempranos y genera correcciones preventivas utilizando enjambres de IA multiagente.
- [Ciroos AI](https://ciroos.ai) - Compañero de IA SRE multiagente construido sobre arquitecturas MCP y A2A para orquestación extensible entre herramientas.
- [Dash0](https://dash0.com) - Observabilidad nativa de IA con agentes especializados para triaje en guardia, consultas PromQL y automatización de paneles.
- [Datadog Bits AI](https://www.datadoghq.com/product/ai/bits-ai-sre/) - Agente autónomo de guardia incorporado en Datadog que analiza runbooks y telemetría antes de que los respondedores inicien sesión.
- [Harness AI SRE](https://www.harness.io/products/ai-sre) - Agente de cambios consciente de los humanos con AI Scribe que captura señales de Slack, Teams y Zoom y las correlaciona con cambios en el sistema.
- [Azure SRE Agent](https://azure.microsoft.com/en-us/products/sre-agent) - Agente de IA para monitoreo, diagnóstico y resolución de problemas en aplicaciones alojadas en Azure, con un constructor de subagentes sin código.
- [Causely](https://www.causely.ai) - Motor de IA causal que determina la única causa raíz de tormentas de alertas utilizando razonamiento causal en lugar de correlación.
- [DrDroid](https://drdroid.io) - Agente AI para SRE con gráfico de conocimiento para recomendaciones de investigación, automatización de PlayBooks y bot de AlertOps en Slack.
- [TierZero AI](https://tierzero.ai) - Gestión autónoma de problemas de infraestructura que investiga, triaja y resuelve automáticamente problemas de infraestructura.
- [Kubiya](https://www.kubiya.ai) - Plataforma de ingeniería de agentes con comandos de lenguaje natural para Slack y Teams, automatización de Terraform y CI/CD, y control de acceso basado en roles.
- [SRE.ai](https://www.sre.ai) - Agentes de IA de lenguaje natural para flujos de trabajo complejos de DevOps empresarial, incluyendo CI/CD y pruebas.
- [Sherlocks.ai](https://www.sherlocks.ai) - Asistente SRE nativo de IA que automatiza la respuesta a incidentes, el análisis de causa raíz y la prevención de apagones con memoria institucional.
- [Parity](https://www.tryparity.com) - Agente de IA para fiabilidad de infraestructura en la nube y operaciones de Kubernetes.
- [Beeps](https://beeps.dev) - Plataforma de guardia que ayuda a desarrolladores y agentes a resolver tiempos de inactividad más rápido.
- [Kura](https://www.usekura.com) - Copiloto de DevOps con IA para gestión de infraestructura en la nube de AWS y respuesta a incidentes.
- [Wild Moose](https://www.wildmoose.ai) - Primer respondedor de IA para incidentes de producción que investiga y revela la causa raíz en menos de un minuto.
- [NudgeBee](https://github.com/nudgebee/nudgebee) - Plataforma de SRE con agentes autohospedada que investiga incidentes hasta una causa raíz citada en AWS, Azure, GCP y Kubernetes, revela gastos y desperdicios de redimensionamiento, y ejecuta runbooks de remediación con control de aprobación, con soporte para bring-your-own-model en nueve proveedores de LLM.
- [Agent SRE](https://agentsre.ai) - Agente de IA para ingeniería de fiabilidad de sitios autónoma.
- [Anyshift](https://anyshift.io) - Agente AI para SRE que investiga incidentes de producción rastreando cambios a través de un gráfico de infraestructura versionado para identificar causas raíz.
- [Aurora](https://github.com/Arvo-AI/aurora) - Agente AI para SRE de código abierto (Apache 2.0) que investiga incidentes de forma autónoma y entrega análisis de causa raíz en AWS, Azure, GCP y Kubernetes, con soporte para bring-your-own-LLM que incluye modelos locales mediante Ollama.
- [Guardian by Metoro](https://metoro.io/ai-sre-agent) - Agente AI para SRE en Kubernetes que detecta problemas, encuentra la causa raíz y abre PRs de corrección automáticamente.
- [Hyground](https://hyground.ai) - Un agente AI para SRE soberano diseñado para operar software complejo en toda su pila, encontrar causas raíz automáticamente y reducir el trabajo manual de DevOps.

## Depuración en Producción con IA

*Herramientas potenciadas por IA para la depuración de aplicaciones en producción en tiempo real: añadiendo observabilidad sin nuevas implementaciones y remediando problemas de código de forma autónoma.*

- [Lightrun](https://lightrun.com) - Plataforma AI para SRE para remediación autónoma de código que permite añadir registros, instantáneas y métricas a producción sin reinicios.
- [Sentry Seer](https://sentry.io/product/seer/) - Agente de depuración AI construido sobre telemetría de producción que identifica problemas accionables, realiza análisis de causa raíz y genera correcciones de código.

## Gestión de Incidentes

*Plataformas mejoradas con IA para gestionar el ciclo de vida completo de incidentes: detección, triaje, respuesta, comunicación y postmortems.*

- [PagerDuty AIOps](https://www.pagerduty.com/platform/aiops/) - Gestión de incidentes empresarial con reducción de ruido basada en ML, AI Agent Suite con SRE Agent y Copilot, e integración con servidor MCP.
- [incident.io](https://incident.io) - Gestión de incidentes nativa de Slack con AI para SRE, triaje de alertas AI, postmortems AI, transcripción de llamadas Scribe e integración con Claude y Cursor.
- [Rootly](https://rootly.com) - Gestión de incidentes nativa de IA con investigación potenciada por LLM en toda la pila de observabilidad.
- [FireHydrant](https://firehydrant.com) - Resúmenes de incidentes potenciados por IA, enriquecimiento de contexto consciente de Zoom y retrospectivas redactadas por IA. En proceso de adquisición por Freshworks.
- [Hyperping](https://hyperping.com) - Monitoreo de disponibilidad, API y servidores con programación de guardia y páginas de estado, expuesto a agentes de IA a través de un servidor MCP remoto que cubre monitores, apagones, informes MTTR/MTTA y programación de guardia.
- [Squadcast](https://squadcast.com) - Gestión de incidentes con clustering de alertas impulsado por IA y agrupación automática de incidentes relacionados. Adquirido por SolarWinds.
- [Zenduty](https://zenduty.com) - Gestión de guardia e incidentes con AI Summarizer, AI Postmortem y AI Scheduling. Adquirido por Xurrent, rebranding a Xurrent IMR.
- [BetterStack](https://betterstack.com) - Monitoreo de disponibilidad y gestión de incidentes amigable para desarrolladores con observabilidad integrada.

## Plataformas de Observabilidad

*Observabilidad de pila completa con capacidades de IA: detección de anomalías, consultas de lenguaje natural y alertas inteligentes a través de métricas, registros y trazas.*

- [Datadog](https://www.datadoghq.com) - Observabilidad SaaS unificada con detección automática Watchdog AI, monitoreo predictivo de métricas y observabilidad de LLM en más de 600 integraciones.
- [Dynatrace](https://www.dynatrace.com) - Observabilidad de pila completa con motor Davis AI para análisis continuo de dependencias, detección de anomalías y Davis CoPilot para remediación en lenguaje natural.
- [New Relic](https://newrelic.com) - Observabilidad de pila completa con asistente NRAI para consultas en lenguaje natural y detección de anomalías potenciada por IA.
- [Grafana](https://grafana.com) - Observabilidad de código abierto con Grafana Assistant para consultas en lenguaje natural, investigación autónoma de incidentes y detección de anomalías basada en ML.
- [Splunk](https://www.splunk.com) - Observabilidad empresarial con detección de anomalías impulsada por IA a escala y ITSI con análisis predictivo basado en ML. Parte de Cisco.
- [Elastic AI Assistant](https://www.elastic.co/elasticsearch/ai-assistant) - Asistente de IA en Kibana para consultas en lenguaje natural de registros, métricas y trazas con triaje de alertas contextual y base de conocimiento potenciada por RAG.
- [Honeycomb](https://www.honeycomb.io) - Observabilidad para servicios distribuidos con Query Assistant, Honeycomb Intelligence, espacio de trabajo Canvas guiado por IA y servidor MCP alojado.
- [Coroot](https://coroot.com) - Observabilidad de código abierto con análisis de causa raíz potenciado por IA e instrumentación automática basada en eBPF.
- [Last9](https://last9.io) - Observabilidad unificada con SDK Agentic SRE, integración de copiloto AI con Claude, Cursor y Slack, y TSDB gestionado.
- [SigNoz](https://signoz.io) - Plataforma de observabilidad nativa de OpenTelemetry de código abierto para registros, métricas y trazas con análisis de correlación unificado.
- [Middleware](https://middleware.io) - Plataforma de observabilidad de pila completa que detecta problemas en APM, RUM, registros e infraestructura, y los resuelve usando OpsAI, un agente AI para SRE que identifica la causa raíz y corrige problemas automáticamente con una tasa de resolución automatizada del 70 %.
- [Metoro](https://metoro.io/) - Plataforma de observabilidad nativa de Kubernetes con telemetría eBPF integrada, investigación con IA, verificación de implementación y análisis de causa raíz.
- [Radar](https://github.com/skyhook-io/radar) - Observabilidad de Kubernetes de código abierto con topología, tráfico de servicios y línea de tiempo de eventos, más un servidor MCP integrado y una auditoría de 31 mejores prácticas para asistentes de IA.

## Plataformas AIOps

*Plataformas que aplican ML e IA a las operaciones de TI: correlacionando eventos, reduciendo el ruido de alertas y automatizando flujos de trabajo operativos a escala.*

- [BigPanda](https://www.bigpanda.io) - AIOps para entornos de alto volumen de alertas con correlación de eventos que reduce el volumen de alertas en un 95 %+ y AI Incident Assistant.
- [Moogsoft](https://www.moogsoft.com) - AIOps con deduplicación de eventos, enriquecimiento contextual, correlación inteligente y análisis automatizado de causa raíz. Parte de Dell Technologies.
- [LogicMonitor](https://www.logicmonitor.com) - Monitoreo de infraestructura en la nube con agente Edwin AI para resúmenes en lenguaje claro, análisis predictivo y pronóstico de capacidad.
- [Selector AI](https://www.selector.ai) - Observabilidad de red potenciada por IA con Network Large Language Model, reducción del 90 % del ruido de alertas y modelado de gemelo digital.
- [Keep](https://www.keephq.dev) - AIOps y gestión de alertas de código abierto con correlación entre herramientas de monitoreo y más de 50 integraciones.

## Análisis de Registros y Detección de Anomalías

*Herramientas especializadas para análisis de registros impulsado por IA, reconocimiento de patrones y detección automática de anomalías.*

- [Sumo Logic](https://www.sumologic.com) - Análisis de registros nativo de la nube con detección de anomalías en tiempo real potenciada por IA y reconocimiento de patrones basado en ML.
- [Graylog](https://graylog.org) - Gestión de registros de código abierto para recopilación, indexación y análisis centralizados con alertas de anomalías.
- [Logz.io](https://logz.io) - Observabilidad en la nube construida sobre ELK y OpenSearch con análisis de registros potenciado por IA, detección de anomalías basada en ML y servidor MCP.
- [OpenObserve](https://openobserve.ai) - Plataforma de alto rendimiento de código abierto para registros, métricas y trazas con análisis en tiempo real.
- [LogAI](https://github.com/salesforce/logai) - Biblioteca de código abierto de Salesforce para agrupación de registros, detección de anomalías y resumen con pipelines de ML modulares.

## Ingeniería de Caos

*Herramientas para probar proactivamente la resiliencia del sistema: ahora mejoradas con IA para diseño inteligente de experimentos, control del alcance del impacto y análisis automatizado.*

- [ChaosEater](https://github.com/ntt-dkiku/chaos-eater) - Herramienta de investigación que utiliza LLM para automatizar completamente el ciclo de ingeniería de caos, desde la identificación de requisitos hasta el diseño, ejecución y análisis del experimento.
- [Harness Chaos Engineering](https://www.harness.io/products/chaos-engineering) - Ingeniería de caos empresarial con recomendaciones de pruebas derivadas de LLM, reducción inteligente del alcance del impacto e integración con herramientas MCP.
- [Gremlin](https://www.gremlin.com) - Herramienta comercial pionera de ingeniería de caos con plantillas de ataque, monitoreo de métricas de infraestructura y soporte multi-nube.
- [Steadybit](https://steadybit.com) - Ingeniería de caos con marco de extensión de código abierto, políticas de resiliencia y automatización de experimentos.
- [LitmusChaos](https://litmuschaos.io) - Ingeniería de caos de código abierto de CNCF para Kubernetes con ChaosHub para experimentos compartidos.
- [Chaos Mesh](https://chaos-mesh.org) - Ingeniería de caos nativa de Kubernetes de código abierto de CNCF con inyección de fallos completa para pods, red, E/S, tiempo y kernel.
- [AWS Fault Injection Service](https://aws.amazon.com/fis/) - Ingeniería de caos nativa de AWS con plantillas de experimentos integradas y controles de seguridad.

## Automatización de Runbooks

*Herramientas potenciadas por IA para automatizar runbooks operativos: convirtiendo procedimientos manuales en flujos de trabajo autoejecutables con toma de decisiones inteligente.*

- [Rundeck](https://www.rundeck.com) - Automatización de runbooks de código abierto y comercial con GUI de autoservicio, programación de trabajos, RBAC y más de 1000 plugins de integración. Parte de PagerDuty.
- [StackStorm](https://stackstorm.com) - Automatización impulsada por eventos de código abierto con motor de reglas, más de 6000 acciones y ChatOps. Utilizado por Netflix para infraestructura con autoreparación.
- [Ansible Lightspeed](https://www.redhat.com/en/technologies/management/ansible/ansible-lightspeed) - Generación de playbook de Ansible potenciada por IA mediante IBM watsonx con conversión de lenguaje natural a código de Ansible y soporte para MCP.
- [RunWhen](https://www.runwhen.com) - Plataforma para orquestación de agentes SRE y flujos de trabajo de solución de problemas automatizados.

## Optimización de Costos en la Nube

*Plataformas impulsadas por IA para optimizar el gasto en la nube: redimensionamiento autónomo, gestión de compromisos y asignación de costos consciente de las cargas de trabajo.*

- [CAST AI](https://cast.ai) - Optimización de costos de Kubernetes con redimensionamiento en tiempo real de pods, optimización de autoscaling, pronóstico predictivo de capacidad y bin-packing avanzado.
- [Sedai](https://sedai.io) - Optimización autónoma de la nube usando aprendizaje por refuerzo patentado para redimensionamiento, escalado de capacidad consciente de la carga de trabajo y ahorros de costos del 30-50 %.
- [ProsperOps](https://www.prosperops.com) - Optimización autónoma de compromisos que gestiona más de $6 mil millones en uso anual de la nube. Adquirido por Flexera.
- [Kubecost](https://kubecost.com) - Monitoreo de costos de Kubernetes de código abierto con asignación de costos en tiempo real y recomendaciones automatizadas de redimensionamiento.
- [Vantage](https://www.vantage.sh) - Gestión de costos multi-nube con FinOps Agent para identificación de ahorros impulsada por IA y servidor MCP de código abierto.
- [nOps](https://www.nops.io) - FinOps centrado en AWS con agente AI entrenado con datos del cliente para optimización automatizada de compromisos.
- [Finout](https://www.finout.io) - FinOps empresarial con MegaBill para consolidación de costos multi-proveedor y atribución de costos potenciada por IA.
- [Spot.io](https://spot.io) - Automatización de infraestructura en la nube con optimización de instancias spot y gestión de compromisos. Parte de NetApp.
- [CloudPilot AI](https://cloudpilot.ai) - Gestión de capacidad nativa de Kubernetes con escalado predictivo que anticipa proactivamente los picos de uso.

## Herramientas de DevOps con LLM

*Herramientas que aprovechan modelos de lenguaje grandes para interacción de lenguaje natural con infraestructura, generación de código para operaciones y flujos de trabajo de DevOps asistidos por IA.*

- [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) - Proyecto CNCF para diagnósticos de Kubernetes potenciados por IA con experiencia de SRE codificada en analizadores y múltiples backends de LLM.
- [HolmesGPT](https://github.com/HolmesGPT/holmesgpt) - Proyecto CNCF Sandbox que proporciona un agente de guardia AI 24/7 con ciclo de agente que consulta datos de observabilidad en vivo desde Prometheus, Grafana, Datadog y Kubernetes.
- [Kube-Copilot](https://github.com/feiskyer/kube-copilot) - Operaciones de Kubernetes de lenguaje natural a código abierto con generación de manifiestos y escaneo de seguridad.
- [Lens Prism](https://lenshq.io) - Copiloto AI en Lens Desktop para interacción de lenguaje natural consciente del contexto con clusters de Kubernetes en vivo.
- [GitHub Copilot Agent Mode](https://github.com/features/copilot) - Asistente de codificación AI con capacidades de agente de DevOps para validación de infraestructura, respuesta a incidentes y automatización de pipelines.
- [GitLab Duo](https://about.gitlab.com/gitlab-duo/) - IA en todo el ciclo de vida DevSecOps con análisis de trazas de trabajos fallidos, identificación de causa raíz y Security Analyst Agent.
- [Grafana Assistant](https://grafana.com/docs/grafana/latest/dashboards/manage-dashboards/#ai-generated-dashboard) - Asistente AI para creación de paneles en lenguaje natural, investigación autónoma de incidentes y generación de consultas.

## Benchmarks para Agentes

*Marcos y benchmarks para evaluar el rendimiento de los agentes AI para SRE.*

- [SRE Bench](https://sreben.ch/) - Benchmark para evaluar agentes AI para SRE en tareas operativas realistas.

## Artículos de Investigación

*Investigación académica e industrial clave sobre la aplicación de IA y ML a la ingeniería de fiabilidad de sitios y operaciones de TI.*

<!--lint disable awesome-list-item-->

- [STRATUS: Un sistema multiagente para la ingeniería de fiabilidad autónoma de nubes modernas](https://arxiv.org/abs/2502.00055) — NeurIPS 2025.
- [ChaosEater: Automatización completa de la ingeniería de caos con modelos de lenguaje grandes](https://arxiv.org/abs/2501.02531) — ASE 2025.
- [Soluciones AIOps para la gestión de incidentes](https://arxiv.org/abs/2404.01363) — Revisión exhaustiva de la literatura, 2024.
- [Una revisión de AIOps en la era de los modelos de lenguaje grandes](https://arxiv.org/abs/2404.09837) — ACM Computing Surveys 2025.
- [Análisis automático de causa raíz mediante modelos de lenguaje grandes para incidentes en la nube](https://arxiv.org/abs/2305.15778) — EuroSys 2024.
- [FaultProfIT: Perfilado jerárquico de fallos de tickets de incidentes en sistemas de nube a gran escala](https://arxiv.org/abs/2402.02952) — ICSE-SEIP 2024.

<!--lint enable awesome-list-item-->

## Blogs y Boletines

- [SRE Weekly](https://sreweekly.com) - Boletín curado sobre escalabilidad, disponibilidad, respuesta a incidentes y automatización.
- [Last Week in AWS](https://www.lastweekinaws.com) - Noticias y comentarios semanales sobre AWS por Corey Quinn.
- [Google Cloud DevOps and SRE Blog](https://cloud.google.com/blog/products/devops-sre) - Prácticas y herramientas para DevOps y SRE a escala.
- [The New Stack](https://thenewstack.io) - Cobertura de tecnología nativa de la nube con extenso contenido sobre IA y SRE.
- [incident.io Blog](https://incident.io/blog) - Contenido práctico sobre herramientas SRE y IA.
- [Doctor Droid Notes](https://notes.drdroid.io) - Blog de ingeniería SRE centrado en IA.
- [NeuBird Blog](https://neubird.ai/blog) - Predicciones de GenAI para SRE y análisis de la industria.
- [Metoro Blog](https://metoro.io/blog) - Contenido sobre observabilidad, IA para SRE y Kubernetes.
- [Hyground Blog](https://hyground.ai/blog) - Contenido sobre IA para SRE, observabilidad, GenAI / seguridad.

## Listas de la Comunidad

*Otras colecciones curadas en el espacio de IA y operaciones.*

- [awesome-AIOps](https://github.com/OpsPAI/awesome-AIOps) - Investigación académica y materiales industriales sobre AIOps.
- [awesome-LLM-AIOps](https://github.com/Jun-jie-Huang/awesome-LLM-AIOps) - Investigación y artículos de AIOps específicos para LLM.
- [awesome-chaos-engineering](https://github.com/dastergon/awesome-chaos-engineering) - Recursos integrales de ingeniería de caos.

## Contribuciones

¡Las contribuciones son bienvenidas! Lea las [directrices de contribución](contributing.md) primero.
