# Awesome-Dynamic-Agreement-Assembly-Execution

## Top Dynamic Agreement Assembly & Execution Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Template-Driven Document Generation, Dynamic Clause Assembly & E-Signature Execution*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Dynamic Agreement Assembly & Execution**. These tools help organizations generate contracts and documents from templates populated with live data—covering everything from Salesforce-native document generation and CPQ-driven proposal assembly to open-source template engines and e-signature platforms that complete the execution loop.

**Examples** include Conga Composer, Nintex Drawloop, S-Docs, Formstack Documents, HotDocs, Windward Studios, Docma, Carbone, and LibreSign (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted document generation, open-source template engines, and community-driven e-signature—ideal for organizations seeking data sovereignty and avoiding per-document or per-user SaaS fees. The open-source landscape spans **template engines** (Carbone, docxtpl-ng, Docma) for generating documents from data, and **e-signature platforms** (LibreSign, @hasna/signatures) for completing execution. Note that **Salesforce-native generation** (Conga, Drawloop, S-Docs) has no open-source equivalent—those require the commercial ecosystem.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Conga Composer](https://www.conga.com/)** | Salesforce-native document generation with templates, data merging, and multi-format output. **30-day free trial with 10 user licenses** available. Discounts of up to 25% based on user volume, contract length, and commitment . | Quote-only (discounts up to 25% for volume/commitment); free trial with 10 users | **30-day free trial** (10 user licenses)  |
| **[Nintex Drawloop DocGen](https://www.nintex.com/)** | Salesforce document generation with workflow automation. NSW Government contract listed at **$42,110.41** (estimated, inc GST) for a subscription including support and maintenance . | Quote-only (enterprise contract; government example ~$42K) | No free tier listed; demo via sales |
| **[S-Docs](https://www.sdocs.com/)** | Salesforce-native document generation with **unlimited e-signature envelopes** on signature packages—no per-envelope fees. Free plan available (self-service, no guaranteed response times); paid plans add support and SLAs . | Quote-only (free plan available; paid plans for support/SLA) | **Free plan** available (self-service, no guaranteed support response)  |
| **[Formstack Documents](https://www.formstack.com/)** | Document generation platform with templates and data merging. **Starting price: $99/month** (Software Advice). Suite pricing (Forms + Documents + Sign): **$250–$299/month** with 5,000 submissions per form and 10 GB storage . | **$99/month** (starting); Suite: $250–$299/month  | No free tier listed; trial available |
| **[HotDocs](https://www.hotdocs.com/)** | Document automation and assembly platform. Software Advice lists a starting price (likely per-user; specific tier not detailed in search results). | Quote-only (per-user or enterprise) | Trial available via sales |
| **[Windward Studios](https://www.windwardstudios.com/)** | Document generation and reporting platform with data-driven templates. Positioned for visually rich documents with charts and tables . | Quote-only | Trial available |
| **[Adobe Acrobat Sign](https://www.adobe.com/sign.html)** | E-signature execution layer that integrates with document generation workflows. **Per-license billing** with seat subscriptions. | Acrobat Standard for teams: **$16.99/user/month** (annual) | Free Developer Edition + sandbox for API testing |
| **[DocuSign Gen](https://www.docusign.com/)** | Salesforce-native document generation and e-signature. Integrated into DocuSign CLM and Salesforce workflows. | Quote-only (enterprise contract) | No free tier; demo via sales |
| **[PandaDoc](https://www.pandadoc.com/)** | Document workflow platform with template-based generation and e-signature. Free eSign plan: 5 documents/month. | Starter: **$19/seat/month** (annual); Business: $49/seat/month | **Free**: 5 documents/month; **14-day trial**  |
| **[Icertis Dynamic Agreement Engine](https://www.icertis.com/)** | Enterprise CLM with dynamic agreement assembly using clause libraries, rules-based fallback language, and AI-assisted drafting. | Quote-only (enterprise contract) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Carbone](https://github.com/carboneio/carbone)** | [![Stars](https://img.shields.io/github/stars/carboneio/carbone?style=social&color=white)](https://github.com/carboneio/carbone/stargazers) | **The most mature open-source document generation engine.** Node.js, MIT licensed. Templates are **LibreOffice/Microsoft Office documents** (DOCX, ODT, XLSX, PPTX, HTML) with `{d.variable}` JSON markers. Renders to DOCX/XLSX/PPTX/ODT/ODS/ODP/HTML, and to **PDF via LibreOffice** (with worker management and retry logic). Multilingual templates, built-in date/number formatters, and custom JavaScript formatters . **Best for teams wanting self-hosted document generation from Office templates with JSON data.** |
| **[Docma](https://github.com/OriginEnergy/docma)** | [![Stars](https://img.shields.io/github/stars/OriginEnergy/docma?style=social&color=white)](https://github.com/OriginEnergy/docma/stargazers) | **Document composition and assembly engine from Origin Energy.** Python, Apache 2.0 (check repo). Assembles PDF and HTML documents from templates with **dynamic data-driven content**—conditionals, loops, and transformations. Composes multiple source documents into a single output. Supports **watermarking/stamping**, Vega-lite charts with live database connections, and deep schema validation of parameters . **Best for complex multi-document assembly with conditional inclusion and charting.** |
| **[docxtpl-ng](https://github.com/python-docx-ng/docxtpl-ng)** | [![Stars](https://img.shields.io/github/stars/python-docx-ng/docxtpl-ng?style=social&color=white)](https://github.com/python-docx-ng/docxtpl-ng/stargazers) | **Jinja2 templating for Word documents—the modern MIT-licensed implementation.** Use a `.docx` file as a template: design in Word, insert `{{ customer.name }}`, render from Python. Supports Jinja2 control tags (`{%tr %}`, `{%p %}`, `{%tc %}`) for table/paragraph/cell repetition. **Independent implementation** of the original `docxtpl` (not a fork), MIT licensed instead of LGPL . **Note: v0.1.1 Alpha**—feature-complete but not battle-tested on large corpora. Best for Python teams needing Word-native template rendering. |
| **[Caxton](https://github.com/insightindustry/caxton)** | [![Stars](https://img.shields.io/github/stars/insightindustry/caxton?style=social&color=white)](https://github.com/insightindustry/caxton/stargazers) | **Declarative Python library for generating documents from application data.** Define document structure and semantics; renderers handle output formats (XLSX, etc.). Stable v1.0.0 pending DSL finalization. MIT licensed . **Best for Python teams wanting a declarative, format-agnostic document generation DSL.** |
| **[LibreSign](https://github.com/LibreSign/libresign)** | [![Stars](https://img.shields.io/github/stars/LibreSign/libresign?style=social&color=white)](https://github.com/LibreSign/libresign/stargazers) | **Open-source e-signature platform for the execution step of agreement workflows.** AGPL-3.0, Nextcloud-integrated. Secure, legally compliant document signing with full data control. Recognized as a Digital Public Good by the Digital Public Goods Alliance. Used by Brazilian government entities including the Navy and NIC.br . **Best for organizations already on Nextcloud needing native e-signature.** |
| **[@hasna/signatures](https://github.com/hasna/signatures)** | [![Stars](https://img.shields.io/github/stars/hasna/signatures?style=social&color=white)](https://github.com/hasna/signatures/stargazers) | **Developer-first open-source e-signature platform with MCP, CLI, and REST API.** SQLite database, zero external dependencies. Sign PDFs with **text signatures (Google Fonts), image signatures, or AI-generated drawings**. Detects existing signature fields in PDF forms. Full-text search, project/collection management, and connector integration for external tools. Three interfaces: `open-signatures` CLI, `signatures-mcp` (MCP server), `signatures-serve` (REST API) . **Best for developers wanting lightweight, scriptable PDF signing with AI-agent integration.** |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[pdf-lib](https://github.com/Hopding/pdf-lib)** | — | JavaScript library for PDF creation and form filling. **12x faster than Puppeteer for form filling** (5s vs 60s for 1000 PDFs) with 200MB vs 4GB RAM. Can create **real signature fields** detectable by DocuSign/Adobe Sign, flatten forms after filling, and merge multi-document packets . **Best for JS/TS teams embedding PDF assembly and form filling into their applications.** |

**Frameworks for building custom systems**: Choose **Carbone** for Office-template-based generation with JSON data and PDF conversion , **Docma** for complex multi-document assembly with conditional inclusion and charts , **docxtpl-ng** for Word-native Jinja2 templating in Python , and **LibreSign** or **@hasna/signatures** for the execution step —creating a fully open-source agreement assembly and signing pipeline without per-document or per-user fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Agreement assembly and execution platforms handle legally binding documents and personal data; ensure compliance with ESIGN, UETA, eIDAS, and applicable data protection regulations. **Audit trails and document integrity are legally critical**—validate that generated PDFs and signature evidence meet your jurisdiction's requirements.
- **Salesforce-native generation has no open-source equivalent.** Conga, Drawloop, and S-Docs are deeply embedded in the Salesforce data model—open-source template engines (Carbone, docxtpl-ng) can generate documents but require custom integration with Salesforce APIs . **S-Docs offers a genuine free plan** (self-service, no guaranteed support) and **unlimited e-signature envelopes** on signature packages —a notable exception to envelope-based pricing . **Open-source e-signature licensing matters**: LibreSign is **AGPL-3.0** (network-use obligations) , while @hasna/signatures is more permissive (check package license). **Docxtpl-ng is Alpha (v0.1.1)**—validate against your template corpus before production use . Always test document output fidelity and signature legality before relying on any tool for binding agreements.

---

**Made for legal ops teams, sales engineers, and developers building document automation infrastructure.**  
Let's make dynamic agreement assembly and execution more open, accurate, and verifiable.
