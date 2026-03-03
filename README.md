# Awesome AI SRE [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Applying artificial intelligence to site reliability engineering — autonomous incident response, intelligent observability, and self-healing infrastructure.

## Contents

- [AI SRE Agents](#ai-sre-agents)
- [AI Production Debugging](#ai-production-debugging)
- [Incident Management](#incident-management)
- [Observability Platforms](#observability-platforms)
- [AIOps Platforms](#aiops-platforms)
- [Log Analysis and Anomaly Detection](#log-analysis-and-anomaly-detection)
- [Chaos Engineering](#chaos-engineering)
- [Runbook Automation](#runbook-automation)
- [Cloud Cost Optimization](#cloud-cost-optimization)
- [LLM-Powered DevOps Tools](#llm-powered-devops-tools)
- [Agent Benchmarks](#agent-benchmarks)
- [Research Papers](#research-papers)
- [Blogs and Newsletters](#blogs-and-newsletters)
- [Community Lists](#community-lists)

## AI SRE Agents

*Autonomous AI agents purpose-built for SRE workflows — investigating alerts, performing root cause analysis, and resolving incidents with minimal human intervention.*

- [Resolve AI](https://resolve.ai) - Autonomous SRE platform by OpenTelemetry co-creators that targets 80% autonomous resolution rate with parallel hypothesis investigation.
- [Cleric](https://cleric.ai) - Autonomous AI SRE teammate that investigates alerts 24/7 and delivers root cause analysis in Slack.
- [NeuBird](https://neubird.ai) - Agentic AI SRE co-pilot for enterprise IT with LLM-powered telemetry analysis and 230K+ alerts resolved.
- [Phoebe AI](https://phoebe.ai) - Predicts incidents from leading indicators and generates pre-emptive fixes using multi-agent AI swarms.
- [Ciroos AI](https://ciroos.ai) - Multi-agentic AI SRE teammate built on MCP and A2A architectures for extensible cross-tool orchestration.
- [Dash0](https://dash0.com) - AI-native observability with specialized agents for on-call triage, PromQL queries, and dashboard automation.
- [Datadog Bits AI](https://www.datadoghq.com/product/ai/bits-ai-sre/) - Autonomous AI on-call agent embedded in Datadog that analyzes runbooks and telemetry before responders log in.
- [Harness AI SRE](https://www.harness.io/products/ai-sre) - Human-aware change agent with AI Scribe that captures Slack, Teams, and Zoom signals and correlates them with system changes.
- [Azure SRE Agent](https://azure.microsoft.com/en-us/products/sre-agent) - AI agent for monitoring, diagnosing, and resolving issues in Azure-hosted applications with no-code sub-agent builder.
- [Causely](https://www.causely.ai) - Causal AI engine that determines the single root cause from alert storms using causal reasoning rather than correlation.
- [DrDroid](https://drdroid.io) - AI SRE agent with knowledge graph for investigation recommendations, PlayBooks automation, and AlertOps Slack bot.
- [TierZero AI](https://tierzero.ai) - Autonomous infrastructure issue management that auto-investigates, triages, and resolves infrastructure issues.
- [Kubiya](https://www.kubiya.ai) - Agentic engineering platform with natural language Slack and Teams commands, Terraform and CI/CD automation, and role-based access control.
- [SRE.ai](https://www.sre.ai) - Natural language AI agents for complex enterprise DevOps workflows including CI/CD and testing.
- [Sherlocks.ai](https://www.sherlocks.ai) - AI-native SRE assistant that automates incident response, root cause analysis, and outage prevention with institutional memory.
- [Parity](https://www.tryparity.com) - AI agent for cloud infrastructure reliability and Kubernetes operations.
- [Beeps](https://beeps.dev) - On-call platform that helps developers and agents resolve downtime faster.
- [Kura](https://www.usekura.com) - AI DevOps copilot for AWS cloud infrastructure management and incident response.
- [Wild Moose](https://www.wildmoose.ai) - AI first responder for production incidents that investigates and surfaces root cause in under one minute.
- [Nudge Bee](https://nudgebee.com) - Enterprise AI-agentic workflow platform for SRE and CloudOps with pre-built AI assistants and customizable workflows.
- [Agent SRE](https://agentsre.ai) - AI agent for autonomous site reliability engineering.

## AI Production Debugging

*AI-powered tools for debugging production applications in real-time — adding observability without redeployments and autonomously remediating code issues.*

- [Lightrun](https://lightrun.com) - AI SRE platform for autonomous code remediation that lets you add logs, snapshots, and metrics to production without restarts.
- [Sentry Seer](https://sentry.io/product/seer/) - AI debugging agent built on production telemetry that identifies actionable issues, performs root cause analysis, and generates code fixes.

## Incident Management

*AI-enhanced platforms for managing the full incident lifecycle — detection, triage, response, communication, and post-mortems.*

- [PagerDuty AIOps](https://www.pagerduty.com/platform/aiops/) - Enterprise incident management with ML-based noise reduction, AI Agent Suite with SRE Agent and Copilot, and MCP server integration.
- [incident.io](https://incident.io) - Slack-native incident management with AI SRE, AI alert triage, AI postmortems, Scribe call transcription, and Claude and Cursor integration.
- [Rootly](https://rootly.com) - AI-native incident management with LLM-powered investigation across the observability stack.
- [FireHydrant](https://firehydrant.com) - AI-powered incident summaries, Zoom-aware context enrichment, and AI-drafted retrospectives. Being acquired by Freshworks.
- [Squadcast](https://squadcast.com) - Incident management with AI-driven alert clustering and automatic grouping of related incidents. Acquired by SolarWinds.
- [Zenduty](https://zenduty.com) - On-call and incident management with AI Summarizer, AI Postmortem, and AI Scheduling. Acquired by Xurrent, rebranding to Xurrent IMR.
- [BetterStack](https://betterstack.com) - Developer-friendly uptime monitoring and incident management with integrated observability.

## Observability Platforms

*Full-stack observability with AI capabilities — anomaly detection, natural language querying, and intelligent alerting across metrics, logs, and traces.*

- [Datadog](https://www.datadoghq.com) - Unified SaaS observability with Watchdog AI auto-detection, predictive metrics monitoring, and LLM observability across 600+ integrations.
- [Dynatrace](https://www.dynatrace.com) - Full-stack observability with Davis AI engine for continuous dependency analysis, anomaly detection, and Davis CoPilot for natural language remediation.
- [New Relic](https://newrelic.com) - Full-stack observability with NRAI assistant for natural language queries and AI-powered anomaly detection.
- [Grafana](https://grafana.com) - Open source observability with Grafana Assistant for natural language queries, autonomous incident investigation, and ML-based anomaly detection.
- [Splunk](https://www.splunk.com) - Enterprise observability with AI-driven anomaly detection at scale and ITSI with ML-based predictive analytics. Part of Cisco.
- [Elastic AI Assistant](https://www.elastic.co/elasticsearch/ai-assistant) - AI assistant in Kibana for natural language log, metrics, and trace querying with contextual alert triage and RAG-powered knowledge base.
- [Honeycomb](https://www.honeycomb.io) - Observability for distributed services with Query Assistant, Honeycomb Intelligence, AI-guided Canvas workspace, and hosted MCP server.
- [Coroot](https://coroot.com) - Open source observability with AI-powered root cause analysis and eBPF-based auto-instrumentation.
- [Last9](https://last9.io) - Unified observability with Agentic SRE SDK, AI copilot integration with Claude, Cursor, and Slack, and managed TSDB.
- [SigNoz](https://signoz.io) - Open source OpenTelemetry-native observability platform for logs, metrics, and traces with unified correlation analysis.

## AIOps Platforms

*Platforms that apply ML and AI to IT operations — correlating events, reducing alert noise, and automating operational workflows at scale.*

- [BigPanda](https://www.bigpanda.io) - AIOps for high-alert-volume environments with event correlation reducing alert volume by 95%+ and AI Incident Assistant.
- [Moogsoft](https://www.moogsoft.com) - AIOps with event deduplication, contextual enrichment, intelligent correlation, and automated root cause analysis. Part of Dell Technologies.
- [LogicMonitor](https://www.logicmonitor.com) - Cloud-based infrastructure monitoring with Edwin AI agent for plain-language summaries, predictive analytics, and capacity forecasting.
- [Selector AI](https://www.selector.ai) - AI-powered network observability with Network Large Language Model, 90% alert noise reduction, and digital twin modeling.
- [Keep](https://www.keephq.dev) - Open source AIOps and alert management with correlation across monitoring tools and 50+ integrations.

## Log Analysis and Anomaly Detection

*Specialized tools for AI-driven log analytics, pattern recognition, and automated anomaly detection.*

- [Sumo Logic](https://www.sumologic.com) - Cloud-native log analytics with real-time AI-powered anomaly detection and ML-based pattern recognition.
- [Graylog](https://graylog.org) - Open source log management for centralized collection, indexing, and analysis with anomaly alerting.
- [Logz.io](https://logz.io) - Cloud observability built on ELK and OpenSearch with AI-powered log analysis, ML-based anomaly detection, and MCP server.
- [OpenObserve](https://openobserve.ai) - Open source high-performance log, metrics, and trace platform with real-time analytics.
- [LogAI](https://github.com/salesforce/logai) - Open source library by Salesforce for log clustering, anomaly detection, and summarization with modular ML pipelines.

## Chaos Engineering

*Tools for proactively testing system resilience — now enhanced with AI for intelligent experiment design, blast radius control, and automated analysis.*

- [ChaosEater](https://github.com/ntt-dkiku/chaos-eater) - Research tool using LLMs to fully automate the chaos engineering cycle from requirement identification through experiment design, execution, and analysis.
- [Harness Chaos Engineering](https://www.harness.io/products/chaos-engineering) - Enterprise chaos engineering with LLM-derived test recommendations, intelligent blast radius downscaling, and MCP tool integration.
- [Gremlin](https://www.gremlin.com) - Pioneer commercial chaos engineering tool with attack templates, infrastructure metrics monitoring, and multi-cloud support.
- [Steadybit](https://steadybit.com) - Chaos engineering with open source extension framework, resilience policies, and experiment automation.
- [LitmusChaos](https://litmuschaos.io) - CNCF open source chaos engineering for Kubernetes with ChaosHub for shared experiments.
- [Chaos Mesh](https://chaos-mesh.org) - CNCF open source Kubernetes-native chaos engineering with comprehensive fault injection for pods, network, IO, time, and kernel.
- [AWS Fault Injection Service](https://aws.amazon.com/fis/) - AWS-native chaos engineering with integrated experiment templates and safety controls.

## Runbook Automation

*AI-powered tools for automating operational runbooks — converting manual procedures into self-executing workflows with intelligent decision-making.*

- [Rundeck](https://www.rundeck.com) - Open source and commercial runbook automation with self-service GUI, job scheduling, RBAC, and 1000+ integration plugins. Part of PagerDuty.
- [StackStorm](https://stackstorm.com) - Open source event-driven automation with rules engine, 6000+ actions, and ChatOps. Used by Netflix for self-healing infrastructure.
- [Ansible Lightspeed](https://www.redhat.com/en/technologies/management/ansible/ansible-lightspeed) - AI-powered Ansible playbook generation via IBM watsonx with natural language to Ansible code and MCP support.
- [RunWhen](https://www.runwhen.com) - Platform for SRE agent orchestration and automated troubleshooting workflows.

## Cloud Cost Optimization

*AI-driven platforms for optimizing cloud spend — autonomous rightsizing, commitment management, and workload-aware cost allocation.*

- [CAST AI](https://cast.ai) - Kubernetes cost optimization with real-time pod rightsizing, autoscaling optimization, predictive capacity forecasting, and advanced bin-packing.
- [Sedai](https://sedai.io) - Autonomous cloud optimization using patented reinforcement learning for rightsizing, workload-aware capacity scaling, and 30-50% cost savings.
- [ProsperOps](https://www.prosperops.com) - Autonomous commitment optimization managing $6B+ annual cloud usage. Acquired by Flexera.
- [Kubecost](https://kubecost.com) - Open source Kubernetes cost monitoring with real-time cost allocation and automated rightsizing recommendations.
- [Vantage](https://www.vantage.sh) - Multi-cloud cost management with FinOps Agent for AI-driven savings identification and open source MCP server.
- [nOps](https://www.nops.io) - AWS-focused FinOps with AI agent trained on customer data for automated commitment optimization.
- [Finout](https://www.finout.io) - Enterprise FinOps with MegaBill for multi-provider cost consolidation and AI-powered cost attribution.
- [Spot.io](https://spot.io) - Cloud infrastructure automation with spot instance optimization and commitment management. Part of NetApp.
- [CloudPilot AI](https://cloudpilot.ai) - Kubernetes-native capacity management with predictive scaling that anticipates usage spikes proactively.

## LLM-Powered DevOps Tools

*Tools leveraging large language models for natural language interaction with infrastructure, code generation for operations, and AI-assisted DevOps workflows.*

- [K8sGPT](https://github.com/k8sgpt-ai/k8sgpt) - CNCF project for AI-powered Kubernetes diagnostics with SRE experience codified into analyzers and multiple LLM backends.
- [HolmesGPT](https://github.com/HolmesGPT/holmesgpt) - CNCF Sandbox project providing a 24/7 on-call AI agent with agentic loop querying live observability data from Prometheus, Grafana, Datadog, and Kubernetes.
- [Kube-Copilot](https://github.com/feiskyer/kube-copilot) - Open source natural language to Kubernetes operations with manifest generation and security scanning.
- [Lens Prism](https://lenshq.io) - AI copilot in Lens Desktop for context-aware natural language interaction with live Kubernetes clusters.
- [GitHub Copilot Agent Mode](https://github.com/features/copilot) - AI coding assistant with DevOps agent capabilities for infrastructure validation, incident response, and pipeline automation.
- [GitLab Duo](https://about.gitlab.com/gitlab-duo/) - AI throughout the DevSecOps lifecycle with failed job trace analysis, root cause identification, and Security Analyst Agent.
- [Grafana Assistant](https://grafana.com/docs/grafana/latest/dashboards/manage-dashboards/#ai-generated-dashboard) - AI assistant for natural language dashboard creation, autonomous incident investigation, and query generation.

## Agent Benchmarks

*Frameworks and benchmarks for evaluating AI SRE agent performance.*

- [SRE Bench](https://sreben.ch/) - Benchmark for evaluating AI SRE agents on realistic operational tasks.

## Research Papers

*Key academic and industry research on applying AI and ML to site reliability engineering and IT operations.*

<!--lint disable awesome-list-item-->

- [STRATUS: A Multi-agent System for Autonomous Reliability Engineering of Modern Clouds](https://arxiv.org/abs/2502.00055) — NeurIPS 2025.
- [ChaosEater: Fully Automating Chaos Engineering with Large Language Models](https://arxiv.org/abs/2501.02531) — ASE 2025.
- [AIOps Solutions for Incident Management](https://arxiv.org/abs/2404.01363) — Comprehensive literature review, 2024.
- [A Survey of AIOps in the Era of Large Language Models](https://arxiv.org/abs/2404.09837) — ACM Computing Surveys 2025.
- [Automatic Root Cause Analysis via Large Language Models for Cloud Incidents](https://arxiv.org/abs/2305.15778) — EuroSys 2024.
- [FaultProfIT: Hierarchical Fault Profiling of Incident Tickets in Large-scale Cloud Systems](https://arxiv.org/abs/2402.02952) — ICSE-SEIP 2024.

<!--lint enable awesome-list-item-->

## Blogs and Newsletters

- [SRE Weekly](https://sreweekly.com) - Curated newsletter on scalability, availability, incident response, and automation.
- [Last Week in AWS](https://www.lastweekinaws.com) - Weekly AWS news and commentary by Corey Quinn.
- [Google Cloud DevOps and SRE Blog](https://cloud.google.com/blog/products/devops-sre) - Practices and tools for DevOps and SRE at scale.
- [The New Stack](https://thenewstack.io) - Cloud-native technology coverage with extensive AI and SRE content.
- [incident.io Blog](https://incident.io/blog) - Practical SRE and AI tools content.
- [Doctor Droid Notes](https://notes.drdroid.io) - AI-focused SRE engineering blog.
- [NeuBird Blog](https://neubird.ai/blog) - GenAI SRE predictions and industry analysis.

## Community Lists

*Other curated collections in the AI and operations space.*

- [awesome-AIOps](https://github.com/OpsPAI/awesome-AIOps) - Academic research and industrial materials on AIOps.
- [awesome-LLM-AIOps](https://github.com/Jun-jie-Huang/awesome-LLM-AIOps) - LLM-specific AIOps research and papers.
- [awesome-chaos-engineering](https://github.com/dastergon/awesome-chaos-engineering) - Comprehensive chaos engineering resources.

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
