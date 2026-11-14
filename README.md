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
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global market for contract lifecycle management (CLM), document automation, and e-signatures represents an estimated **$15B–$22B+** ecosystem, expanding at ~13–25% CAGR as enterprise agreements shift from static templates to intelligent, dynamic workflows. The sector is **moderately fragmented yet top-heavy**: mega-cap digital document and signature infrastructure providers (e.g., Adobe, DocuSign) dominate core e-signature execution and broad horizontal workflows, while an active, fragmented ecosystem of enterprise CLM leaders and vertical document generation vendors captures specialized CPQ, CRM-native, and complex multi-clause assembly needs.

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Revenue) | Pricing (Starting) | Free Tier / Trial Limits | Description |
|---------|------------------------------------|-------------------|--------------------------|-------------|
| **[Adobe Acrobat Sign](https://www.adobe.com/sign.html)** | **~$26.0B** TTM Revenue / ~$200B+ Market Cap | **$16.99/user/month** (annual, Acrobat Standard for teams) | **30-day free trial** (up to 200 transaction units; 7-day trial on standard Pro bundles; permanent free Developer Sandbox) | E-signature execution layer that integrates with document generation workflows. Per-license billing with seat subscriptions. |
| **[DocuSign Gen](https://www.docusign.com/)** | **~$3.36B** TTM Revenue / ~$10B–$12B Market Cap | **$20/user/month** (annual add-on for Salesforce; base eSign starts at $10/mo) | **30-day free trial** (Business Pro evaluation; permanent free account allows signing & up to 3–5 total sent envelopes) | Salesforce-native document generation and e-signature. Integrated into DocuSign CLM and Salesforce workflows. |
| **[Icertis Dynamic Agreement Engine](https://www.icertis.com/)** | **$5.0B** Valuation / ~$300M–$350M ARR | **~$150–$350/user/month** (enterprise contracts; median ACV starting ~$100,000/yr) | **No free self-serve trial** (guided enterprise demo & custom sandbox POC only) | Enterprise CLM with dynamic agreement assembly using clause libraries, rules-based fallback language, and AI-assisted drafting. |
| **[Nintex Drawloop DocGen](https://www.nintex.com/)** | **~$2.0B** Valuation / ~$250M ARR | **$5,000/company/year** (or ~$12–$20/user/month equivalent) | **30-day free trial** (includes 5 full user licenses via Salesforce AppExchange + sandbox testing) | Salesforce document generation with workflow automation. NSW Government contract listed at $42,110.41 (estimated, inc GST) for enterprise deployment. |
| **[HotDocs](https://www.hotdocs.com/)** | **~$1.6B** Parent Valuation (Mitratech) / ~$150M–$220M Revenue | **$25/user/month** (or ~$125/month for small team base package) | **30-day evaluation trial** (requires sales-assisted license token; or guided live demo) | Document automation and assembly platform with enterprise rules engines for legal and commercial document suites. |
| **[PandaDoc](https://www.pandadoc.com/)** | **$1.0B** Valuation / ~$100M ARR | **$19/user/month** (billed annually; $35/mo month-to-month) | **14-day free trial** (full access) + **Free forever eSign plan** (up to 5 document uploads & signatures/month) | Document workflow platform with template-based generation and e-signature. |
| **[Conga Composer](https://www.conga.com/)** | **~$715M+** Acquisition Basis / ~$200M–$388M ARR | **$35/user/month** (annual baseline contract; discounts up to 25% for high-volume commitments) | **30-day free trial** (includes 10 user licenses with AppExchange install) | Salesforce-native document generation with templates, data merging, and multi-format output. |
| **[Formstack Documents](https://www.formstack.com/)** | **$425M** Valuation / ~$35M–$55M ARR | **$99/month** (Starter tier; Suite starts at $250–$299/month) | **14-day free trial** (full feature access without credit card) | Document generation platform with templates and data merging. |
| **[S-Docs](https://www.sdocs.com/)** | Bootstrapped / **~$6.6M** ARR | **$25/user/month** (billed annually; minimum contract requirement of $3,000/year) | **Free forever plan** (unlimited users & templates; capped at 150 document generations & 50 e-signatures total) | Salesforce-native document generation with unlimited e-signature envelopes on signature packages—no per-envelope fees. |
| **[Windward Studios](https://www.windwardstudios.com/)** | Acquired (Apryse) / **~$4.6M** Pre-Acquisition Revenue | **$209/month** (Flex model starting tier; Pro pay-per-server at $496/month) | **14-to-30-day free trial** (evaluation watermark and output cap; no credit card required) | Document generation and reporting platform with data-driven templates. Positioned for visually rich documents with charts and tables. |

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
