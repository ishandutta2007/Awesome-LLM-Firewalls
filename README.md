# Awesome-LLM-Firewalls
## Top LLM Firewalls & Guardrails Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on LLM Security, Prompt Protection & Output Guardrails*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** building **LLM Firewalls & Guardrails**. These tools protect large language models from prompt injection, jailbreaking, toxic output, data leakage, hallucinations, and other security risks while ensuring safe, compliant, and reliable AI interactions.

**Examples** include Akamai Firewall for AI, CalypsoAI Moderator, Lakera Guard, Lasso Security, WhyLabs LLM Security, LLM Guard, and NVIDIA NeMo Guardrails (the category leaders). Tools listed here emphasize **real-time protection**, content moderation, policy enforcement, and observability for production LLM applications.

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, local deployment, full customization, and complete control — ideal for developers and organizations building secure, sovereign LLM systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS Products](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS Products

### Core Platforms (LLM Firewalls & Guardrails)

- **[Akamai Firewall for AI](https://www.akamai.com/)**  
  Enterprise-grade security layer that protects AI applications from prompt injection, data exfiltration, and malicious usage.

- **[CalypsoAI Moderator](https://calypsoai.com/)**  
  Advanced AI safety platform for moderating inputs and outputs with customizable policies and real-time protection.

- **[Lakera Guard](https://lakera.ai/)**  
  Leading LLM security solution focused on prompt injection defense and secure AI deployment.

- **[Lasso Security](https://lasso.security/)**  
  AI security platform providing comprehensive guardrails and threat detection for LLM applications.

- **[WhyLabs LLM Security](https://whylabs.ai/)**  
  Observability and security platform with specialized LLM monitoring and protection features.

- **[NVIDIA NeMo Guardrails](https://www.nvidia.com/)**  
  Comprehensive guardrails toolkit for controlling LLM behavior, safety, and alignment.

### Advanced & Specialized Platforms

**Other notable mentions**: Protect AI, HiddenLayer, and various enterprise LLM security suites.

## Open-Source GitHub Projects

### Dedicated LLM Firewall & Guardrails Projects

- **[LLM Guard](https://github.com/protectai/llm-guard)**  
  Comprehensive open-source toolkit for detecting and preventing prompt injections, toxicity, PII leakage, and other LLM risks. Highly extensible and production-ready.

- **[NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)**  
  Open-source toolkit for adding programmable guardrails to LLM applications, including topical rails, safety rails, and custom behaviors.

- **[Outlines](https://github.com/outlines-dev/outlines)**  
  Open-source library for guiding LLM outputs with regex, JSON schemas, and grammars — essential for safe and structured generation.

- **[Rebuff](https://github.com/protectai/rebuff)**  
  Open-source prompt injection detection and defense framework that learns from attacks over time.

- **[LangChain Guardrails](https://github.com/langchain-ai/langchain)**  
  Built-in guardrails and output parsers within the popular LangChain ecosystem for secure agent and chain execution.

- **[Llama Guard](https://github.com/facebookresearch/llama-recipes)** (and official Meta releases)  
  Open-source safety classifier models and tools from Meta for content moderation and risk detection.

- **[Presidio](https://github.com/microsoft/presidio)**  
  Microsoft’s open-source PII detection and anonymization toolkit, widely used to protect sensitive data in LLM pipelines.

- **[NeMo Guardrails Examples](https://github.com/NVIDIA/NeMo-Guardrails)**  
  Rich collection of production guardrail examples and templates.

- **[Guardrails AI](https://github.com/guardrails-ai/guardrails)**  
  Open-source framework for adding structural and semantic guardrails to LLM outputs with validation and correction.

- **[Prompt Security / Injection Detection Tools](https://github.com/search?q=prompt+injection+detection)**  
  Multiple community projects focused on detecting and mitigating prompt injection attacks.

### Additional Strong Open-Source Options

- **[TextAttack](https://github.com/QData/TextAttack)** — Adversarial robustness testing and attack generation for LLMs.
- **[AICL Guard](https://github.com/search?q=ai+content+moderation)** — Various content safety classifiers.
- **[LangSmith / LangChain tracing** with custom guardrails.
- **[Ollama + Guardrails** community integrations for local safe LLM deployment.
- Many **RAG-specific guardrail** repositories for retrieval safety and output validation.

**Frameworks for building custom firewalls**: Combine **LLM Guard**, **NeMo Guardrails**, **Outlines**, and **Guardrails AI** with **LangGraph** for comprehensive, production-grade LLM security layers.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- LLM security is an evolving field. No single tool provides 100% protection — use defense-in-depth strategies.
- Self-hosted open-source solutions require careful configuration and ongoing monitoring.

---

**Made for AI engineers, security teams, and responsible AI practitioners.**  
Let's make LLM deployments more secure, controllable, and trustworthy.