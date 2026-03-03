# Awesome AI SRE [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of AI-powered tools, platforms, and resources for Site Reliability Engineering.

AI is transforming how teams operate production systems — from autonomous incident response and intelligent alert correlation to LLM-powered diagnostics and self-healing infrastructure. This list tracks the tools, research, and communities at the intersection of AI and SRE.

## Contents

- [AI SRE Agents](#ai-sre-agents)
- [Incident Management](#incident-management)
- [Observability Platforms](#observability-platforms)
- [AIOps Platforms](#aiops-platforms)
- [Log Analysis & Anomaly Detection](#log-analysis--anomaly-detection)
- [Chaos Engineering](#chaos-engineering)
- [Runbook Automation](#runbook-automation)
- [Cloud Cost Optimization](#cloud-cost-optimization)
- [Capacity Planning](#capacity-planning)
- [LLM-Powered DevOps Tools](#llm-powered-devops-tools)
- [Agent Benchmarks](#agent-benchmarks)
- [Open Source](#open-source)
- [Research Papers](#research-papers)
- [Blogs & Newsletters](#blogs--newsletters)
- [Community Lists](#community-lists)

---

## AI SRE Agents

*Autonomous AI agents purpose-built for SRE workflows — investigating alerts, performing root cause analysis, and resolving incidents with minimal human intervention.*

| Tool | Description |
|------|-------------|
| [Cleric](https://cleric.ai) | Autonomous AI SRE teammate that investigates alerts 24/7 and delivers root cause analysis in Slack. Gartner Cool Vendor 2025. |
| [Resolve AI](https://resolve.ai) | AI SRE built by OpenTelemetry co-creators. Autonomous alert handling and root cause analysis, saving up to 20 hrs/week per on-call engineer. |
| [NeuBird](https://neubird.ai) | Agentic AI SRE co-pilot for enterprise IT. LLM-powered telemetry analysis with 230K+ alerts resolved autonomously. |
| [Causely](https://www.causely.ai) | Causal AI engine that determines the single root cause from alert storms using causal reasoning, not just correlation. Best Use of AI, O11ys 2024. |
| [DrDroid](https://drdroid.io) | AI SRE agent with knowledge graph for investigation recommendations, PlayBooks automation, and AlertOps Slack bot. Free tier available. |
| [TierZero AI](https://tierzero.ai) | Autonomous infrastructure issue management — auto-investigates, triages, and resolves infrastructure issues. |
| [Kubiya](https://www.kubiya.ai) | Agentic engineering platform with natural language Slack/Teams commands, Terraform/CI-CD automation, and role-based access control. |
| [SRE.ai](https://www.sre.ai) | AI-powered platform for automating SRE practices across the software lifecycle. |
| [Parity](https://www.tryparity.com) | AI agent for cloud infrastructure reliability. |
| [Beeps](https://www.beeps.co) | AI-powered incident response agent. |
| [Kura](https://www.usekura.com) | AI SRE agent focused on incident investigation and resolution. |
| [Wild Moose](https://www.wildmoose.ai) | AI-powered incident response automation. |
| [Sherlocks.ai](https://www.sherlocks.ai) | AI detective for production incidents and root cause analysis. |
| [Nudge Bee](https://nudgebee.com) | AI SRE agent for proactive reliability management. |
| [Agent SRE](https://agentsre.ai) | AI agent for autonomous site reliability engineering. |

## Incident Management

*AI-enhanced platforms for managing the full incident lifecycle — detection, triage, response, communication, and post-mortems.*

| Tool | Description |
|------|-------------|
| [PagerDuty AIOps](https://www.pagerduty.com/platform/aiops/) | Enterprise incident management with ML-based noise reduction (up to 87% alert reduction), intelligent event correlation, and AI Agent Suite. |
| [incident.io](https://incident.io) | Slack-native incident management with AI SRE capabilities, automated workflows, and on-call scheduling. |
| [Rootly](https://rootly.com) | Slack-native incident management with AI-powered alert grouping, automated root cause analysis, and codifiable automation. |
| [FireHydrant](https://firehydrant.com) | Incident management with pattern recognition, automated notifications, and corrective action automation. |
| [Squadcast](https://squadcast.com) | Incident management with AI-driven alert clustering and automatic grouping of related incidents. |
| [Zenduty](https://zenduty.com) | On-call and incident management with ML-based priority auto-assignment from historical incident data. |
| [BetterStack](https://betterstack.com) | Developer-friendly uptime monitoring and incident management with integrated observability. |

## Observability Platforms

*Full-stack observability with AI capabilities — anomaly detection, natural language querying, and intelligent alerting across metrics, logs, and traces.*

| Tool | Description |
|------|-------------|
| [Datadog](https://www.datadoghq.com) | Unified SaaS observability with Watchdog AI auto-detection, predictive metrics monitoring, and LLM observability. 600+ integrations. |
| [Dynatrace (Davis AI)](https://www.dynatrace.com) | Full-stack observability with Davis AI engine for continuous dependency analysis, anomaly detection, and Davis CoPilot for natural language remediation. |
| [New Relic](https://newrelic.com) | Full-stack observability with NRAI assistant for natural language queries and AI-powered anomaly detection. |
| [Grafana](https://grafana.com) | Open source observability with Grafana Assistant for natural language queries, autonomous incident investigation, and ML-based anomaly detection. |
| [Splunk](https://www.splunk.com) | Enterprise observability with AI-driven anomaly detection at scale and ITSI with ML-based predictive analytics. |
| [Elastic AI Assistant](https://www.elastic.co/elasticsearch/ai-assistant) | AI assistant in Kibana for natural language log/metrics/trace querying, contextual alert triage, and RAG-powered knowledge base. |
| [Honeycomb](https://www.honeycomb.io) | Observability for distributed services with Query Assistant, Honeycomb Intelligence, AI-guided Canvas workspace, and hosted MCP server. |
| [Coroot](https://coroot.com) | Open source observability with AI-powered root cause analysis and eBPF-based auto-instrumentation. Zero config covers 80%+ of common issues. |
| [Last9](https://last9.io) | Unified observability with Agentic SRE SDK, AI copilot integration (Claude, Cursor, Slack), and managed TSDB. Gartner Cool Vendor 2025. |
| [SigNoz](https://signoz.io) | Open source, OpenTelemetry-native observability platform for logs, metrics, and traces with unified correlation analysis. |

## AIOps Platforms

*Platforms that apply ML and AI to IT operations — correlating events, reducing alert noise, and automating operational workflows at scale.*

| Tool | Description |
|------|-------------|
| [BigPanda](https://www.bigpanda.io) | AIOps for high-alert-volume environments with event correlation reducing alert volume by 95%+ and agentic AI for incident routing. |
| [Moogsoft](https://www.moogsoft.com) | AIOps with event deduplication, contextual enrichment, intelligent correlation, and automated root cause analysis. |
| [LogicMonitor](https://www.logicmonitor.com) | Cloud-based infrastructure monitoring with Edwin AI agent for plain-language summaries, predictive analytics, and capacity forecasting. |
| [Selector AI](https://www.selector.ai) | AI-powered network observability with Network Large Language Model (NLM), 90% alert noise reduction, and digital twin modeling. |
| [Keep](https://www.keephq.dev) | Open source AIOps and alert management with correlation across monitoring tools and 50+ integrations. |

## Log Analysis & Anomaly Detection

*Specialized tools for AI-driven log analytics, pattern recognition, and automated anomaly detection.*

| Tool | Description |
|------|-------------|
| [LogAI](https://github.com/salesforce/logai) | Open source library by Salesforce for log clustering, anomaly detection, and summarization with modular ML pipelines. OpenTelemetry-compatible. |
| [Graylog](https://graylog.org) | Open source log management for centralized collection, indexing, and analysis with anomaly alerting. |
| [Sumo Logic](https://www.sumologic.com) | Cloud-native log analytics with real-time AI-powered anomaly detection and ML-based pattern recognition. |
| [Logz.io](https://logz.io) | Cloud observability built on ELK/OpenSearch with AI-powered log analysis and ML-based anomaly detection. |
| [OpenObserve](https://openobserve.ai) | Open source, high-performance log/metrics/trace platform with real-time analytics and reduced storage costs. |

## Chaos Engineering

*Tools for proactively testing system resilience — now enhanced with AI for intelligent experiment design, blast radius control, and automated analysis.*

| Tool | Description |
|------|-------------|
| [ChaosEater](https://github.com/ntt-dkiku/chaos-eater) | Research tool using LLMs to fully automate the chaos engineering cycle: requirement identification, experiment design, execution, and analysis. |
| [Harness Chaos Engineering](https://www.harness.io/products/chaos-engineering) | Enterprise chaos engineering with LLM-derived test recommendations, intelligent blast radius downscaling, and MCP tool integration. |
| [Gremlin](https://www.gremlin.com) | Pioneer commercial chaos engineering tool with attack templates, infrastructure metrics monitoring, and multi-cloud support. |
| [Steadybit](https://steadybit.com) | Chaos engineering with open source extension framework, resilience policies, and experiment automation. |
| [LitmusChaos](https://litmuschaos.io) | CNCF open source chaos engineering for Kubernetes with ChaosHub for shared experiments. |
| [Chaos Mesh](https://chaos-mesh.org) | CNCF open source Kubernetes-native chaos engineering with comprehensive fault injection. |
| [AWS Fault Injection Service](https://aws.amazon.com/fis/) | AWS-native chaos engineering with integrated experiment templates and safety controls. |

## Runbook Automation

*AI-powered tools for automating operational runbooks — converting manual procedures into self-executing workflows with intelligent decision-making.*

| Tool | Description |
|------|-------------|
| [Rundeck](https://www.rundeck.com) | Open source + commercial runbook automation with self-service GUI, job scheduling, RBAC, and 1000+ integration plugins. Part of PagerDuty. |
| [StackStorm](https://stackstorm.com) | Open source event-driven automation ("IFTTT for Ops") with rules engine, 6000+ actions, and ChatOps. Used by Netflix for self-healing infrastructure. |
| [Shoreline.io](https://www.shoreline.io) | Real-time fleet-wide incident automation with Op DSL, auto-remediation linked to alerts, and blast radius controls. Acquired by NVIDIA. |
| [Ansible Lightspeed](https://www.redhat.com/en/technologies/management/ansible/ansible-lightspeed) | AI-powered Ansible playbook generation via IBM watsonx with natural language to Ansible code and MCP support. |
| [Transposit](https://www.transposit.com) | API-first runbook automation connecting people, tools, and communication for incident response. |
| [RunWhen](https://www.runwhen.com) | Platform for SRE agent orchestration and automated troubleshooting workflows. |

## Cloud Cost Optimization

*AI-driven platforms for optimizing cloud spend — autonomous rightsizing, commitment management, and workload-aware cost allocation.*

| Tool | Description |
|------|-------------|
| [CAST AI](https://cast.ai) | Kubernetes cost optimization with real-time pod rightsizing, autoscaling optimization, and advanced bin-packing. |
| [Sedai](https://sedai.io) | Autonomous cloud optimization using patented reinforcement learning for rightsizing. 30-50% cost savings. |
| [ProsperOps](https://www.prosperops.com) | Autonomous commitment optimization managing $6B+ annual cloud usage. Acquired by Flexera. |
| [Kubecost](https://kubecost.com) | Open source Kubernetes cost monitoring with real-time cost allocation and automated rightsizing recommendations. |
| [Vantage](https://www.vantage.sh) | Multi-cloud cost management with FinOps Agent for AI-driven savings identification and open source MCP server. |
| [nOps](https://www.nops.io) | AWS-focused FinOps with AI agent trained on customer data for automated commitment optimization. |
| [Finout](https://www.finout.io) | Enterprise FinOps with MegaBill for multi-provider cost consolidation and AI-powered cost attribution. |
| [Spot.io](https://spot.io) | Cloud infrastructure automation with spot instance optimization and commitment management. Part of NetApp. |

## Capacity Planning

*AI tools for forecasting resource needs and scaling infrastructure proactively — predicting demand before it becomes an incident.*

| Tool | Description |
|------|-------------|
| [CloudPilot AI](https://cloudpilot.ai) | Kubernetes-native capacity management with predictive scaling that anticipates usage spikes proactively. |
| [CAST AI](https://cast.ai) | Predictive autoscaling and capacity forecasting with intelligent instance selection. |
| [Sedai](https://sedai.io) | RL-based capacity optimization with workload-aware scaling and autonomous resource adjustment. |
| [LogicMonitor](https://www.logicmonitor.com) | Capacity trending algorithms for forecasting future resource behavior. |
| [Hyperview](https://hyperviewhq.com) | DCIM platform with real-time data center capacity insights and resource allocation optimization. |

## LLM-Powered DevOps Tools

*Tools leveraging large language models for natural language interaction with infrastructure, code generation for operations, and AI-assisted DevOps workflows.*

| Tool | Description |
|------|-------------|
| [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) | CNCF project for AI-powered Kubernetes diagnostics. SRE experience codified into analyzers, supports multiple LLM backends. |
| [HolmesGPT](https://github.com/HolmesGPT/holmesgpt) | CNCF Sandbox project. 24/7 on-call AI agent with agentic loop querying live observability data from Prometheus, Grafana, Datadog, and K8s. |
| [Kube-Copilot](https://github.com/feiskyer/kube-copilot) | Open source natural language to Kubernetes operations with manifest generation and security scanning. |
| [Lens Prism](https://lenshq.io) | AI copilot in Lens Desktop for context-aware natural language interaction with live Kubernetes clusters. |
| [GitHub Copilot Agent Mode](https://github.com/features/copilot) | AI coding assistant with DevOps agent capabilities for infrastructure validation, incident response, and pipeline automation. |
| [GitLab Duo](https://about.gitlab.com/gitlab-duo/) | AI throughout the DevSecOps lifecycle with failed job trace analysis, root cause identification, and Security Analyst Agent. |
| [Grafana Assistant](https://grafana.com) | AI assistant for natural language dashboard creation, autonomous incident investigation, and query generation. |
| [Dynatrace Davis CoPilot](https://www.dynatrace.com) | Generative AI layer on Davis AI for natural language summaries of causal analysis and remediation step generation. |

## Agent Benchmarks

*Frameworks and benchmarks for evaluating AI SRE agent performance.*

| Resource | Description |
|----------|-------------|
| [SRE Bench](https://sreben.ch/) | Benchmark for evaluating AI SRE agents on realistic operational tasks. |

## Open Source

*Notable open source projects at the intersection of AI and SRE.*

| Project | Description |
|---------|-------------|
| [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) | CNCF — AI-powered Kubernetes diagnostics with multi-LLM support and extensible analyzers. |
| [HolmesGPT](https://github.com/HolmesGPT/holmesgpt) | CNCF Sandbox — Agentic incident investigation across Prometheus, Grafana, Datadog, and Kubernetes. |
| [Coroot](https://github.com/coroot/coroot) | AI-powered observability with eBPF auto-instrumentation and automated root cause analysis. |
| [Keep](https://github.com/keephq/keep) | AIOps and alert management with 50+ tool integrations and alert correlation. |
| [StackStorm](https://github.com/StackStorm/st2) | Linux Foundation — Event-driven automation with 6000+ actions and ChatOps. |
| [LitmusChaos](https://github.com/litmuschaos/litmus) | CNCF — Kubernetes-native chaos engineering with ChaosHub. |
| [Chaos Mesh](https://github.com/chaos-mesh/chaos-mesh) | CNCF — Comprehensive Kubernetes fault injection. |
| [LogAI](https://github.com/salesforce/logai) | Salesforce — Modular log analytics with clustering, anomaly detection, and summarization. |
| [Kube-Copilot](https://github.com/feiskyer/kube-copilot) | Natural language Kubernetes management with multi-LLM support. |
| [SRE Agent](https://github.com/fuzzylabs/sre-agent) | AI agent for monitoring and diagnosing Kubernetes issues. |
| [ChaosEater](https://github.com/ntt-dkiku/chaos-eater) | LLM-based fully automated chaos engineering cycle. |
| [Kubecost](https://github.com/kubecost/cost-analyzer-helm-chart) | Kubernetes cost monitoring and rightsizing recommendations. |
| [SigNoz](https://github.com/SigNoz/signoz) | OpenTelemetry-native observability for logs, metrics, and traces. |
| [OpenObserve](https://github.com/openobserve/openobserve) | High-performance log/metrics/trace platform. |
| [Steadybit](https://github.com/steadybit) | Chaos engineering with open source extension framework. |
| [Obot](https://github.com/obot-platform/obot) | Open source agent orchestration platform. |
| [ControlFlow](https://github.com/PrefectHQ/ControlFlow) | Prefect's framework for building AI agent workflows. |

## Research Papers

*Key academic and industry research on applying AI/ML to site reliability engineering and IT operations.*

- [STRATUS: A Multi-agent System for Autonomous Reliability Engineering of Modern Clouds](https://arxiv.org/abs/2502.00055) — NeurIPS 2025. LLM-based multi-agent SRE system with specialized agents for detection, diagnosis, and mitigation.
- [ChaosEater: Fully Automating Chaos Engineering with Large Language Models](https://github.com/ntt-dkiku/chaos-eater) — ASE 2025. First LLM-based system for fully automated chaos engineering, introduces Validation as Code.
- [AIOps Solutions for Incident Management: Technical Guidelines and a Comprehensive Literature Review](https://arxiv.org/abs/2404.01363) — 2024. Comprehensive survey covering detection, prediction, root cause analysis, and automated healing.
- [A Survey of AIOps in the Era of Large Language Models](https://dl.acm.org/) — ACM Computing Surveys 2025. Analysis of 183 research articles (2020-2024) on LLMs applied to AIOps.
- [Automatic Root Cause Analysis via Large Language Models for Cloud Incidents](https://dl.acm.org/) — EuroSys 2024. LLM-powered root cause analysis for production cloud incidents.
- [FaultProfIT: Hierarchical Fault Profiling of Incident Tickets in Large-scale Cloud Systems](https://dl.acm.org/) — ICSE-SEIP 2024. Hierarchical ML approach to fault profiling from incident tickets.
- [When AIOps Become "AI Oops": Subverting LLM-driven IT Operations via Telemetry Manipulation](https://www.rsaconference.com/) — RSA Conference 2025. Security research on adversarial attacks against AIOps systems.

## Blogs & Newsletters

### Newsletters

| Newsletter | Description |
|------------|-------------|
| [SRE Weekly](https://sreweekly.com) | Curated newsletter on scalability, availability, incident response, and automation. |
| [Last Week in AWS](https://www.lastweekinaws.com) | Weekly AWS news and commentary by Corey Quinn. |

### Blogs

| Blog | Description |
|------|-------------|
| [Google Cloud DevOps & SRE](https://cloud.google.com/blog/products/devops-sre) | Google's practices and tools for DevOps/SRE at scale. |
| [The New Stack](https://thenewstack.io) | Cloud-native technology coverage with extensive AI-SRE content. |
| [incident.io Blog](https://incident.io/blog) | Practical SRE and AI tools content. |
| [Notes by Doctor Droid](https://notes.drdroid.io) | AI-focused SRE engineering blog. |
| [NeuBird Blog](https://neubird.ai/blog) | GenAI SRE predictions and industry analysis. |

## Community Lists

*Other curated collections in the AI + operations space.*

| List | Description |
|------|-------------|
| [awesome-AIOps](https://github.com/OpsPAI/awesome-AIOps) | Academic research and industrial materials on AIOps. |
| [awesome-LLM-AIOps](https://github.com/Jun-jie-Huang/awesome-LLM-AIOps) | LLM-specific AIOps research and papers. |
| [awesome-chaos-engineering](https://github.com/dastergon/awesome-chaos-engineering) | Comprehensive chaos engineering resources. |
| [awesome-runbook](https://github.com/runbear-io/awesome-runbook) | Runbook documents, software, and resources. |

---

## Contributing

Contributions welcome! Read the [contribution guidelines](CONTRIBUTING.md) first.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
