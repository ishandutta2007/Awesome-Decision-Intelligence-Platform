# Awesome-Decision-Intelligence-Platform

# Top Decision Intelligence Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Automated Insight Discovery, Decision Automation & Contextual Analytics*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Decision Intelligence**. These tools help organizations move beyond static dashboards to automatically discover why metrics change, generate actionable recommendations, and automate decision workflows.

**Examples** include Tellius, Pyramid Analytics, DataRobot AI Cloud, C3 AI, Peak AI, Quantexa, Sisu Data, BeyondCore, Aible, and Sapiens Decision (the category leaders).

**Open-source emphasis**: Decision Intelligence is a **deeply commercialized category**—Tellius, Pyramid, and DataRobot lead the market. The open-source ecosystem is **nascent and primarily focused on the decision execution layer** rather than automated insight discovery. **Kev** (Apache-2.0) provides an open-source decision engine for typed choice/score/noul primitives with self-hosting support . **OpenSmartRoute** delivers intelligent routing and decision orchestration with multi-armed bandit strategies and MCP integration . This section documents these emerging solutions honestly.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Tellius](https://www.tellius.com/)**
  **Decision intelligence platform with conversational AI (Kaiya) and automated insight discovery.** **Tellius 5.4** introduces **dynamic parameters** for calculated columns in live Business Views, enabling on-the-fly scenario analysis (e.g., adjusting tax rate to see real-time revenue impact) . **Kaiya** now supports **multi-model LLM backends** (Gemini alongside OpenAI) with secure, role-based administration . **Smart deduplication** for insights automatically detects and manages data duplication from complex joins, ensuring accurate metrics (e.g., focusing TRx analysis on relevant dimensions like Payment Type, Brand, Channel) . **Embeddable Kaiya** allows conversational analytics to be integrated directly into customer applications . Insight results now distinguish **direct contributors (What)** from **influencing factors (Why)**, with sorting by absolute or percentage change and direct Vizpad integration for deeper analysis .

- **[Pyramid Analytics](https://www.pyramidanalytics.com/)**
  **All-in-one decision intelligence platform unifying data prep, business analytics, and data science.** Includes **hundreds of built-in data connectors** and a **super-fast direct query engine (PYRANA)** ensuring flexibility without data extraction . **Virtual semantic models** hide database complexity while enabling sophisticated business logic and dynamic calculations . **Governance features** include granular role-based access, centralized business logic library (Tabulate, Master Flow), version control, and standardized metrics with built-in auditing . **Recognized as a Visionary in 2026 Gartner Magic Quadrant for ABI** and **Ranked #1 in Gartner Critical Capabilities 2026** .

- **[DataRobot AI Cloud](https://www.datarobot.com/)**
  **Unified AI platform for decision intelligence and automated machine learning.** Provides **end-to-end automation** from data to value, with continuous automation maintaining model accuracy as conditions change . **Decision Intelligence Flows** enable automation and scaling of decisions beyond predictions . **Deployment flexibility** across public cloud, data center, and edge environments . **Trusted AI capabilities** include transparency, explainability, and guardrails to prevent bias . **MLOps** provides centralized deployment, monitoring, and governance of all production models . **Application Builder** enables no-code creation and sharing of AI applications for field decision-makers .

- **[C3 AI](https://c3.ai/)**
  **Enterprise AI platform with decision intelligence applications.** **C3 Code** uses **application packages** encoding real enterprise operations (assets, processes, events, metrics) so AI starts from operational context rather than blank schema . **US Marine Corps case study**: Manpower optimization that previously took **a month** of piecemeal processing (Databricks → Excel → Jupyter → Qlik) now completes in **a few hours** using C3 AI's integrated workflow . **Modular architecture** integrates with existing technology stacks (Delta Lake, Databricks) without data replication . **Industry-specific ontologies** for process optimization, financial services (AML, smart lending), defense/intelligence (readiness optimization), and more .

- **[Peak AI](https://peak.ai/)**
  **Decision intelligence platform focused on commercial operations (retail, CPG, manufacturing).** **Joined UiPath in 2025**, combining Peak's Agentic Intelligence with UiPath's automation platform to create agentic solutions that predict, decide, and act autonomously . **Agentic solutions** include **Agentic Commercial Pricing**, **Agentic Inventory Management**, and **Agentic Merchandising**—going beyond insights to execute decisions automatically . **Predict, Decide, Act framework** adapts to real-time conditions across pricing, supply chain, and merchandising .

- **[Quantexa](https://www.quantexa.com/)**
  **Decision Intelligence Platform purpose-built for complex, high-stakes environments where trust, transparency, and explainability are non-negotiable.** **Context is foundational**: unifies data from anywhere, then uses **market-leading entity resolution** and **graph analytics** to reveal relationships, behaviors, networks, and risks . **Quantexa Knowledge Graph (QKG)** was officially patented . **Quantexa AI** includes **Agent Gateway** for secure multi-agent orchestration with governance, lineage, and compliance, supporting open standards (MCP, A2A) . **Q Assist Workspace** enables contextual understanding across data, applications, and industry use cases with grounded, explainable outputs . **Quantexa Cloud AML** is the first SaaS offering for US mid-size banks .

- **[Sisu Data](https://sisu.ai/)**
  **Decision intelligence engine for automated diagnostic analytics.** **Created from Stanford University research**, Sisu automatically explores every possible combination of dimensions to find what's driving changes in key metrics . **Retail use case**: Diagnoses Average Order Value (AOV) and Units Per Transaction (UPT) fluctuations across product, price, discounting, day part, and customer segment . **Scale**: **5M facts found for customers in the past year**, **4M+ rows analyzed per second**, **47B factor combinations tested** . Customers include Microsoft, Samsung, and Upwork .

- **[BeyondCore](https://www.beyondcore.com/)**
  **Smart Data Discovery platform for zero-click business insights.** **Automatically analyzes millions of data combinations in minutes** to deliver unbiased answers, explanations, and recommendations . **Zero-click analytics**: Truly dynamic dashboards present the most important graphs in order of impact, distinguishing trends from blips without manual effort . **BeyondCore Story** provides narrative explanations behind analysis . **Outputs to PowerPoint and Word** for easy consumption . Backed by **20+ patents** and 10 years of R&D . Selected as a **Visionary in Gartner Magic Quadrant for BI and Analytics Platforms (2016)** .

- **[Aible](https://www.aible.com/)**
  **ROI-optimized AutoML platform delivering real business impact through seamless collaboration.** **Aible Business** empowers business people and managers to create AI that delivers sustained business impact by capturing enterprise cost-benefit tradeoffs and operational constraints . **Aible Advanced** enables data scientists to create **Blueprints** encoding best practices while retaining complete visibility . **Aible for One** builds predictive models within Salesforce or Tableau in minutes . **Monitors and quantifies AI value**, alerting CDOs when outcomes don't match predictions and recommending specific remediations .

- **[Sapiens Decision](https://www.sapiens.com/)**
  **Decision intelligence platform turning business logic into a true enterprise asset.** Gartner Peer Insights rating: **4.4 stars with 30 reviews** . Users praise its **ability to handle both simple and complex business rules** and the ease of making decision changes, providing a structured way to manage logic and ensure consistent application of business rules .

## Open-Source GitHub Projects

### Decision Engines & Routing

- **[Kev](https://github.com/arjun988/Kev)**
  **Open-source decision engine for typed choice/score/noul primitives with calibrated probabilities.** **Apache-2.0 licensed**, self-hostable with Ollama or any OpenAI-compatible model . **Core innovation**: "Kev is the open control plane. The intelligence is whatever model you point it at." **BYO model support**: Ollama, vLLM, OpenAI, Gemini-compat . **Wire format**: Same shape as System One (`choice` / `score` / `noul`) . **Offline mode**: Mock backend for CI and demos . **Developer experience**: Playground, SDK, CLI, MCP, LangChain/LlamaIndex integrations . **Benchmarks** (qwen3.5:9b via Ollama, 100% GPU): **Banking77 83%** (choice, n=600), **CLINC OOS 86%** (choice, n=600), **AG News 86.5%** (choice, n=600), **SST-5 89.5%** within-1 (score, n=600), **Civil Comments 81%** (noul, n=600) . **Ops metrics**: p50/p95 504/803ms (2 questions), **0% parse-fail**, **0% rerun agreement flip** .

- **[OpenSmartRoute](https://pypi.org/project/opensmartroute/)**
  **Open-source intelligent routing and decision orchestration framework.** **Core capability**: Routes decisions across LLM targets, tools, and agents with **sub-millisecond signal processing** (task type, domains, complexity, reasoning need, PII, language, modality, history) . **Decision strategies**: Rules, capability fit, example similarity, task table, Thompson and LinUCB bandits, IRT, Bradley-Terry, Markov lookahead, multi-turn history embeddings, learning-to-defer, edge/cloud tiers, token budgets, auctions, user adaptation, and LLM judge (consulted only below confidence threshold) . **Production features**: Circuit breakers, learner state persistence (Redis/SQL), audit logging, tenant middleware, guard middleware for PII redaction . **Hosted platform** available for enterprise deployment .

### Additional Strong Open-Source Options

- **Decision Engines**: **Kev** (Apache-2.0, typed primitives, self-hostable) .
- **Decision Routing**: **OpenSmartRoute** (multi-armed bandit strategies, MCP integration) .
- **Contextual Analytics**: The open-source ecosystem for automated insight discovery (Tellius, Sisu, BeyondCore equivalents) is **essentially non-existent**—this remains a commercial-only capability.

**Frameworks for building custom systems**: Combine **Kev** for typed decision execution with calibrated probabilities, **OpenSmartRoute** for intelligent routing and decision orchestration across models and tools, and **Apache KIE/Drools** (see Decision Automation ecosystem) for rule-based decision logic. Add **PostgreSQL** for persistence and **Docker** for deployment. **Note**: Automated insight discovery and contextual analytics—the core value of Tellius, Sisu, and Quantexa—have **no open-source equivalents** and require commercial platforms.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Decision Intelligence platforms handle sensitive business logic and decision data; ensure proper access controls and compliance with governance policies.
- **Open-source reality**: Decision Intelligence is **one of the least developed open-source categories** in the data and analytics stack. The open-source ecosystem is limited to **decision execution engines** (**Kev**) and **routing frameworks** (**OpenSmartRoute**) . The core capabilities of commercial platforms—**automated insight discovery** (Tellius, Sisu, BeyondCore), **contextual entity resolution and graph analytics** (Quantexa), **ROI-optimized AutoML** (Aible, DataRobot), and **agentic decision automation** (Peak, C3 AI)—have **no production-ready open-source equivalents**. Organizations seeking these capabilities must adopt commercial platforms or invest in significant custom development.

---

**Made for data leaders, analytics engineers, decision architects, and AI/ML practitioners.**
Let's make decision intelligence more open, transparent, and actionable.
