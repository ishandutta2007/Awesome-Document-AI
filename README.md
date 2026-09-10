<p align="center">
  <img src="assets/banner.svg" alt="Awesome Document AI Banner" width="100%" />
</p>

# 📄 Awesome Document AI & Intelligent Document Processing (IDP) ⚡🤖

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Document-AI/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Document-AI?style=flat-square&logo=github&color=gold" alt="Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Document-AI/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Document-AI?style=flat-square&logo=github&color=blue" alt="Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Document-AI/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Document-AI/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

> 🌟 **A comprehensive, SEO-optimized curated catalog of Intelligent Document Processing (IDP), Document AI, OCR engines, Vision-Language Models (VLMs), Layout Analysis, and Table Extraction frameworks.** Build high-performance pipelines for PDFs, scanned records, financial reports, forms, and enterprise RAG applications.

---

## 🔍 Overview & Document AI Pipeline Architecture

Modern **Document AI** and **Intelligent Document Processing (IDP)** unify **OCR, document layout analysis, table extraction, reading-order detection, form key-value extraction, handwriting recognition, vision-language models, and structured output (JSON / Markdown)** for LLMs and Retrieval-Augmented Generation (RAG).

```text
┌──────────────────────┐
                    │      Applications    │
                    │                      │
                    │ RAG │ ERP │ Search   │
                    │ CRM │ Agents │ ETL  │
                    └──────────┬───────────┘
                                │
                    ┌──────────▼───────────┐
                    │ Structured Output    │
                    │                      │
                    │ JSON │ Markdown │ XML│
                    └──────────┬───────────┘
                                │
                    ┌──────────▼───────────┐
                    │ Document Understanding│
                    │                      │
                    │ Tables │ Forms       │
                    │ Entities │ Layout    │
                    └──────────┬───────────┘
                                │
                    ┌──────────▼───────────┐
                    │ OCR / Document VLM   │
                    │                      │
                    │ PaddleOCR │ Surya    │
                    │ Document VLMs        │
                    └──────────┬───────────┘
                                │
                    ┌──────────▼───────────┐
                    │ Document Processing  │
                    │                      │
                    │ Docling │ MinerU     │
                    │ Unstructured │ Marker│
                    └──────────┬───────────┘
                                │
                    ┌──────────▼───────────┐
                    │ Documents            │
                    │                      │
                    │ PDF │ DOCX │ XLSX    │
                    │ PPTX │ Images        │
                    └──────────────────────┘
```

---

## 📑 Table of Contents

- [☁️ SaaS & Hosted Document AI Platforms](#️-saas--hosted-document-ai-platforms)
  - [📊 Market Size & Sector Dynamics](#-market-size--sector-dynamics)
  - [🏢 Commercial IDP Comparison Matrix](#-commercial-idp-comparison-matrix)
- [⭐ Open-Source Document AI Ecosystem](#-open-source-document-ai-ecosystem)
- [📈 Star History](#-star-history)
- [🤝 Contributing](#-contributing)
- [📄 License](#-license)

---

## ☁️ SaaS & Hosted Document AI Platforms

### 📊 Market Size & Sector Dynamics

> 💡 **Estimated Market Size & Industry Concentration:** The global **Intelligent Document Processing (IDP) and Document AI market** is estimated at **$2.5B – $3.8B in 2024–2025** and is projected to expand to **$12B – $15B by 2030–2032** (CAGR ~28–33%). The sector is **moderately fragmented** rather than winner-take-all: cloud hyperscalers (*Microsoft Azure, Google Cloud, AWS*) dominate high-throughput utility OCR and foundational model APIs, while a resilient mid-market of specialized vertical IDP platforms (*ABBYY, Hyperscience, Rossum, Tungsten Automation*) and modern GenAI-native parsing engines (*LlamaIndex, Unstructured*) command high-value workflow automation, finance/insurance compliance pipelines, and multimodal RAG ingestion.

### 🏢 Commercial IDP Comparison Matrix

*The table below is sorted by **Company Size (Valuation / Market Cap / Revenue) descending**, providing starting tier pricing and specific free tier / trial terms for each service:*

| Platform | Company | Company Size (Valuation / Market Cap / Revenue) | Primary Focus & Key Capabilities | Pricing | Free Tier Limits |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Azure AI Document Intelligence](https://azure.microsoft.com/products/ai-services/ai-document-intelligence)** | Microsoft | ~$3.1T Market Cap / $245B+ Rev | Enterprise document layout analysis, OCR, prebuilt models (invoices, receipts, tax forms, IDs), and custom extraction. | Starts at $1.50 per 1,000 pages ($0.0015/page) for Read OCR; $10.00 per 1,000 pages ($0.01/page) for Layout & Prebuilt models; $50.00 per 1,000 pages for Custom extraction | Free forever: 500 pages/month (F0 tier, first 2 pages per document, max 4 MB, 20 calls/min); Free trial: 30 days with $200 Azure credits |
| **[Google Document AI](https://cloud.google.com/document-ai)** | Google Cloud | ~$2.1T Market Cap / $350B+ Rev | Document parsing, Enterprise Document OCR, Form Parser, pre-trained processor suites (lending, procurement, contracts), and custom extractors. | Starts at $1.50 per 1,000 pages ($0.0015/page) for Enterprise Document OCR; $10.00 per 1,000 pages for Document Layout; $30.00 per 1,000 pages for Form Parser; $0.10/page for specialized invoice/receipt processors | Free forever: 1,000 pages/month (Enterprise Document OCR processor); Free trial: 90 days with $300 cloud credits across Google Cloud |
| **[Amazon Textract](https://aws.amazon.com/textract/)** | AWS | ~$2.0T Market Cap / $600B+ Rev | Managed OCR, automated table extraction, form key-value pair extraction, signatures, query-based data extraction, and expense processing. | Starts at $1.50 per 1,000 pages ($0.0015/page) for Detect Document Text; $15.00 per 1,000 pages for Tables; $50.00 per 1,000 pages for Forms; $10.00 per 1,000 pages for Analyze Expense | Free trial: 3 months (90 days) free tier with 1,000 pages/month for Detect Document Text, and 100 pages/month for Analyze Document (Tables/Forms/Queries) or Analyze Expense |
| **[Instabase](https://instabase.com/)** | Instabase | ~$2.0B Valuation ($177M raised) | AI Hub platform for complex document understanding, conversational reasoning, unstructured data extraction, and automated business workflows. | Commercial plan starts at $200/month (includes base credit allowance; consumption-based top-ups); Enterprise annual contracts start at ~$30,000/year | Free forever: Community tier with 100 free credits/month (~100 document pages); Free trial: 14 days with full access to Commercial tier features |
| **[Tungsten Automation (Kofax)](https://www.tungstenautomation.com/)** | Tungsten Automation | ~$2.0B+ Valuation / ~$600M+ Rev | Enterprise TotalAgility IDP platform, high-speed document capture, cognitive data classification, handwriting extraction, and process orchestration. | Desktop Power PDF starts at $129 one-time license; TotalAgility cloud/enterprise subscriptions start at ~$25,000/year (~$0.15–$0.40/page) | Free trial: 15-day free trial for desktop Power PDF; 30-day enterprise evaluation / test drive on request for TotalAgility cloud platform |
| **[Hyperscience](https://www.hyperscience.com/)** | Hyperscience | ~$1.6B Valuation ($288M raised) | Hyperautomation and IDP platform specializing in high-accuracy cursive handwriting recognition, mixed forms processing, and human-in-the-loop workflows. | AWS Marketplace Private Cloud Professional starts at $50,000/year (12-month contract; starting at ~$0.10–$0.30 per page depending on volume commitments) | Free trial: 30-day enterprise Proof-of-Concept (POC) evaluation with custom document sets upon sales qualification |
| **[ABBYY Vantage](https://www.abbyy.com/vantage/)** | ABBYY | ~$1.5B Valuation / ~$300M+ Rev | Cloud-native IDP architecture featuring pre-trained cognitive "Document Skills" for invoices, bills of lading, purchase orders, and custom skill training. | Entry enterprise packages start at ~$40,000/year (or starting from ~$0.10–$0.20 per page for mid-volume tiers); FineReader PDF desktop starts at $99/year | Free trial: 60 days including up to 2,000 pages for core document skills and 1,000 pages for trained skills; FineReader PDF has a 7-day free trial |
| **[Unstructured](https://unstructured.io/)** | Unstructured | ~$400M Valuation ($65M raised) | Document ETL, semantic partitioning, chunking, OCR, table extraction, and multi-format conversion (PDF, DOCX, PPTX) for LLMs and RAG pipelines. | Pay-as-you-go starts at $0.03 per page ($30 per 1,000 pages) on hosted Serverless API; Enterprise platform starts at $1,000/month | Free forever: 15,000 free pages on Serverless API (no expiration / no time limit, up to 100 pages per file) |
| **[Rossum](https://rossum.ai/)** | Rossum | ~$300M+ Valuation ($105M raised) | Cloud AP workflow and transactional document understanding platform with automated vendor communication and cognitive data capture. | Starter plan starts at $18,000/year (~$1,500/month) for up to 24,000 documents/year (overage ~$0.50–$0.80/document) | Free trial: 14 days with up to 300 documents processed and full platform access (no credit card required) |
| **[Nanonets](https://nanonets.com/)** | Nanonets | ~$200M Valuation ($42M raised) | AI-driven workflow automation, pre-trained OCR for invoices, receipts, and bills of lading, plus continuous self-learning custom model retraining. | Pay-per-run starts at $0.02/run for basic OCR, $0.10/run for classification/validation, and $0.30/run for complex data extraction; Starter subscription starts at $499/month (includes 5,000 pages) | Free forever: $50 in free starting credits (up to ~500 pages processed, no expiration, no credit card required) |
| **[Indico Data](https://indicodata.ai/)** | Indico Data | ~$180M Valuation ($66M raised) | Intake and underwriting automation, claims processing, and unstructured document understanding for financial services, banking, and insurance. | Enterprise platform subscriptions start at ~$50,000/year (AWS Marketplace private offers / annual contract) | Free trial: 30-day guided Proof-of-Concept (POC) pilot on enterprise document sets upon sales qualification |
| **[LlamaParse](https://www.llamaindex.ai/llamaparse)** | LlamaIndex | ~$120M Valuation ($10.5M raised) | GenAI-native document parsing for RAG pipelines, table extraction, multimodal layout recognition, and structured JSON/Markdown output. | Starter plan starts at $50/month (includes 40,000 credits; overage at $1.25 per 1,000 credits; 1 credit/page for Fast mode, 3 credits/page for Cost-effective mode) | Free forever: 10,000 credits/month (~1,000 to 10,000 pages depending on mode, 20 requests/minute, 10 GB storage, no credit card required) |
| **[Veryfi](https://www.veryfi.com/)** | Veryfi | ~$120M Valuation ($15M+ raised) | Real-time financial document OCR, receipt and invoice line-item extraction, bank statement parsing, mobile camera SDK, and fraud detection. | OCR API Starter starts at $500/month minimum commitment (covers up to 6,250 receipts at $0.08/doc or 3,125 invoices at $0.16/doc); SaaS Expense starts at $19.99/user/month | Free forever: 100 documents/month on API Free tier; Free trial: 14 days with full platform access (no credit card required) |
| **[Base64.ai](https://base64.ai/)** | Base64.ai | ~$100M Valuation / Seed-funded | Universal document AI for worldwide ID documents, driver licenses, passports, invoices, forms, and checks with facial recognition matching. | Pay-as-you-go starts at $0.05 per page ($50 per 1,000 pages for general OCR; $0.15/page for IDs and forms); monthly volume plans start at $199/month | Free forever: 100 free pages/credits upon registration (no credit card required, 10 req/sec limit); Mock API for unlimited testing |
| **[Docugami](https://www.docugami.com/)** | Docugami | ~$90M Valuation ($15M raised) | Business document engineering, Semantic XML extraction, agreement and contract understanding, and hierarchical document chunking for RAG. | Starter tier starts at $600/month (includes 4 user seats and up to 1,000 page uploads/month with rollover; overage at $0.60/page) | Free trial: 14 days with up to 1,000 pages included (no credit card required) |
| **[Docsumo](https://www.docsumo.com/)** | Docsumo | ~$70M Valuation ($4M+ raised) | Automated data capture for financial services, bank statements, tax returns, pay stubs, invoices, and automated verification rules. | Starter plan starts at $299/month on annual billing (or $500/month monthly billing for up to 1,000 pages/month; overage $0.20/page) | Free trial: 14 days with 100 to 1,000 document pages included (no credit card required) |
| **[Mindee](https://www.mindee.com/)** | Mindee | ~$60M Valuation ($16M raised) | Developer-friendly document parsing API, prebuilt APIs for financial/identity documents, and custom docTR-based document model builder. | Starter plan starts at €44/month (~$48/month, billed annually) or €49/month billed monthly (includes 6,000 credits; overage from €0.044/credit) | Free trial: 14 days with 200 pages / credits included (no credit card required); Community plan with 250 pages/month for open-source builders |
| **[Klippa](https://www.klippa.com/)** | Klippa | ~$60M Valuation (~$8M ARR) | DocHorizon IDP platform, receipt and invoice scanning, ID verification, automated KYC, and mobile OCR scanning SDK. | SpendControl starts at €95/month (~$103/month for up to 50 documents); DocHorizon API plans start at €250/month (or pay-per-document from €0.10/doc) | Free trial: 14 days / guided POC with €25 in free API credits upon registration (no credit card required) |
| **[Hypatos](https://hypatos.ai/)** | Hypatos | ~$50M Valuation ($15M raised) | Deep learning document automation, accounts payable, order confirmations, remittance advices, and ERP integrations. | Starts at €0.20 per transaction for order confirmations/delivery notes and €0.25 per transaction for invoices (typical entry package from ~€1,000/month) | Free trial: 30-day Proof-of-Concept (POC) pilot evaluation with client sample documents upon request |
| **[Affinda](https://www.affinda.com/)** | Affinda | ~$40M Valuation (~$5M ARR) | Resume and CV parsing, recruitment intelligence, invoice extraction, purchase order processing, and searchable document archive. | Pay-as-you-go starts at $0.20 per page (scales down to $0.05/page for high volumes); Resume Parser starts at $0.10 per document (minimum $10 top-up) | Free trial: 14 days with 200 platform credits / pages (no credit card required) |
| **[Ephesoft (Transact)](https://www.ephesoft.com/)** | Ephesoft (Tungsten) | Acquired (~$40M valuation) | Enterprise document classification, OCR extraction, cloud content services, and automated export to ERP/ECM systems. | Cloud IDP packages start at ~$5,000/month (~$60,000/year) for standard enterprise processing volume | Free trial: 30-day guided evaluation / test environment upon request |
| **[Parseur](https://parseur.com/)** | Parseur | ~$15M Valuation (Bootstrapped) | AI-assisted parser for PDFs, emails, invoices, spreadsheets, order confirmations, and no-code automated export to Google Sheets/Zapier. | Starts at $39/month (includes 100 credits/pages; $0.39/credit; $79/month for 300 credits) | Free forever: 20 pages/month (includes AI parsing engine, unlimited mailboxes, 90-day retention, no credit card required) |

---

## ⭐ Open-Source Document AI Ecosystem

*Leading open-source document parsing, layout analysis, OCR engines, and document VLMs, sorted by GitHub stars (descending):*

| Project | License | Primary Focus | Description |
| :--- | :--- | :--- | :--- |
| **[MarkItDown](https://github.com/microsoft/markitdown)** [![Stars](https://img.shields.io/github/stars/microsoft/markitdown?style=social&color=white)](https://github.com/microsoft/markitdown/stargazers) | MIT | Multi-Format Document to Markdown | Python tool converting files (PDF, DOCX, PPTX, XLSX, images, audio) into Markdown for LLM analysis and indexing workflows. |
| **[Stirling-PDF](https://github.com/Stirling-Tools/Stirling-PDF)** [![Stars](https://img.shields.io/github/stars/Stirling-Tools/Stirling-PDF?style=social&color=white)](https://github.com/Stirling-Tools/Stirling-PDF/stargazers) | GPL-3.0 | Local PDF Manipulation & OCR | Robust, locally hosted one-stop PDF manipulation, OCR conversion, splitting, merging, and redaction suite. |
| **[RAGFlow (DeepDoc)](https://github.com/infiniflow/ragflow)** [![Stars](https://img.shields.io/github/stars/infiniflow/ragflow?style=social&color=white)](https://github.com/infiniflow/ragflow/stargazers) | Apache-2.0 | Deep Document Understanding & RAG | Open-source RAG engine based on deep document understanding (DeepDoc), parsing complex layouts, tables, and charts. |
| **[PaddleOCR](https://github.com/PaddlePaddle/PaddleOCR)** [![Stars](https://img.shields.io/github/stars/PaddlePaddle/PaddleOCR?style=social&color=white)](https://github.com/PaddlePaddle/PaddleOCR/stargazers) | Apache-2.0 | Multilingual OCR & Layout Analysis | Practical ultra-lightweight OCR system supporting 100+ languages, PP-Structure document analysis, table recognition, and key information extraction. |
| **[MinerU](https://github.com/opendatalab/MinerU)** [![Stars](https://img.shields.io/github/stars/opendatalab/MinerU?style=social&color=white)](https://github.com/opendatalab/MinerU/stargazers) | Custom Apache-2.0 | High-Precision PDF Extraction | Transforms complex documents (scientific papers, books, financial reports) into clean, LLM-ready Markdown and structured JSON. |
| **[Tesseract OCR](https://github.com/tesseract-ocr/tesseract)** [![Stars](https://img.shields.io/github/stars/tesseract-ocr/tesseract?style=social&color=white)](https://github.com/tesseract-ocr/tesseract/stargazers) | Apache-2.0 | Foundational OCR Engine | The world's most widely adopted open-source optical character recognition engine, supporting Unicode and over 100 languages. |
| **[Docling](https://github.com/docling-project/docling)** [![Stars](https://img.shields.io/github/stars/docling-project/docling?style=social&color=white)](https://github.com/docling-project/docling/stargazers) | MIT | Enterprise Document Parsing & Conversion | Advanced document conversion tool by IBM Research parsing PDF, DOCX, PPTX, and XLSX into structured Markdown/JSON with native table and layout models. |
| **[Umi-OCR](https://github.com/hiroi-sora/Umi-OCR)** [![Stars](https://img.shields.io/github/stars/hiroi-sora/Umi-OCR?style=social&color=white)](https://github.com/hiroi-sora/Umi-OCR/stargazers) | AGPL-3.0 | Offline OCR Application | Fast, free offline desktop OCR software supporting batch image/PDF recognition, watermark filtering, and multi-language extraction. |
| **[Paperless-ngx](https://github.com/paperless-ngx/paperless-ngx)** [![Stars](https://img.shields.io/github/stars/paperless-ngx/paperless-ngx?style=social&color=white)](https://github.com/paperless-ngx/paperless-ngx/stargazers) | GPL-3.0 | Document Management System | Community-supported document archiving system with automated OCR, machine learning tagging, full-text search, and multi-user indexing. |
| **[Marker](https://github.com/datalab-to/marker)** [![Stars](https://img.shields.io/github/stars/datalab-to/marker?style=social&color=white)](https://github.com/datalab-to/marker/stargazers) | Custom / GPL code | High-Accuracy PDF to Markdown | Deep learning pipeline converting PDFs to Markdown and JSON with high speed and high accuracy for complex tables, LaTeX equations, and multi-column layouts. |
| **[OCRmyPDF](https://github.com/ocrmypdf/OCRmyPDF)** [![Stars](https://img.shields.io/github/stars/ocrmypdf/OCRmyPDF?style=social&color=white)](https://github.com/ocrmypdf/OCRmyPDF/stargazers) | MPL-2.0 | Searchable PDF Generation | Adds high-fidelity searchable OCR text layers into scanned PDF files while preserving the original visual fidelity. |
| **[EasyOCR](https://github.com/JaidedAI/EasyOCR)** [![Stars](https://img.shields.io/github/stars/JaidedAI/EasyOCR?style=social&color=white)](https://github.com/JaidedAI/EasyOCR/stargazers) | Apache-2.0 | Deep Learning OCR | Ready-to-use OCR library supporting 80+ languages and popular writing scripts including Latin, Chinese, Arabic, Devanagari, and Cyrillic. |
| **[Surya](https://github.com/datalab-to/surya)** [![Stars](https://img.shields.io/github/stars/datalab-to/surya?style=social&color=white)](https://github.com/datalab-to/surya/stargazers) | Custom / GPL code | Multilingual OCR & Layout Analysis | Multilingual OCR, document layout analysis, reading order detection, and table recognition toolkit supporting 90+ languages. |
| **[olmOCR](https://github.com/allenai/olmocr)** [![Stars](https://img.shields.io/github/stars/allenai/olmocr?style=social&color=white)](https://github.com/allenai/olmocr/stargazers) | Apache-2.0 | Vision-Language Document Parsing | Allen Institute for AI's toolkit for converting PDFs to clean Markdown using fine-tuned vision-language models for layout, math, and tables. |
| **[Unstructured](https://github.com/Unstructured-IO/unstructured)** [![Stars](https://img.shields.io/github/stars/Unstructured-IO/unstructured?style=social&color=white)](https://github.com/Unstructured-IO/unstructured/stargazers) | Apache-2.0 | Document Preprocessing & ETL | Open-source library for ingesting, partitioning, cleaning, and transforming unstructured documents for LLM pipelines and RAG applications. |
| **[pdfplumber](https://github.com/jsvine/pdfplumber)** [![Stars](https://img.shields.io/github/stars/jsvine/pdfplumber?style=social&color=white)](https://github.com/jsvine/pdfplumber/stargazers) | MIT | Plumb PDF Details & Tables | Precise Python tool to extract detailed character, line, rectangle, layout, and tabular data from digital PDFs. |
| **[PyMuPDF](https://github.com/pymupdf/PyMuPDF)** [![Stars](https://img.shields.io/github/stars/pymupdf/PyMuPDF?style=social&color=white)](https://github.com/pymupdf/PyMuPDF/stargazers) | AGPL-3.0 | High-Performance PDF Engine | Extremely fast Python bindings for MuPDF for text extraction, rasterization, document manipulation, and layout analysis. |
| **[Nougat](https://github.com/facebookresearch/nougat)** [![Stars](https://img.shields.io/github/stars/facebookresearch/nougat?style=social&color=white)](https://github.com/facebookresearch/nougat/stargazers) | MIT | Neural Optical Understanding | Meta AI's visual transformer model for parsing academic documents, scientific papers, mathematical formulas, and tables into LaTeX/Markdown. |
| **[GOT-OCR2.0](https://github.com/Ucas-HaoranWei/GOT-OCR2.0)** [![Stars](https://img.shields.io/github/stars/Ucas-HaoranWei/GOT-OCR2.0?style=social&color=white)](https://github.com/Ucas-HaoranWei/GOT-OCR2.0/stargazers) | Apache-2.0 | Unified End-to-End OCR Model | General OCR Theory model unifying plain text OCR, formatted text OCR, sheet music, charts, and molecular formulas in a 580M VLM. |
| **[docTR](https://github.com/mindee/doctr)** [![Stars](https://img.shields.io/github/stars/mindee/doctr?style=social&color=white)](https://github.com/mindee/doctr/stargazers) | Apache-2.0 | Deep Learning Text Recognition | Seamless PyTorch/TensorFlow library for end-to-end document text detection, recognition, and OCR-related tasks. |
| **[LayoutParser](https://github.com/Layout-Parser/layout-parser)** [![Stars](https://img.shields.io/github/stars/Layout-Parser/layout-parser?style=social&color=white)](https://github.com/Layout-Parser/layout-parser/stargazers) | Apache-2.0 | Deep Learning Layout Analysis | Unified Python toolkit with pretrained models for document layout detection, OCR integration, and table boundary identification. |
| **[Camelot](https://github.com/camelot-dev/camelot)** [![Stars](https://img.shields.io/github/stars/camelot-dev/camelot?style=social&color=white)](https://github.com/camelot-dev/camelot/stargazers) | MIT | Tabular Data Extraction from PDFs | Python library that extracts tabular data from PDFs into pandas DataFrames using lattice and stream parsing algorithms. |
| **[Tabula](https://github.com/tabulapdf/tabula-java)** [![Stars](https://img.shields.io/github/stars/tabulapdf/tabula-java?style=social&color=white)](https://github.com/tabulapdf/tabula-java/stargazers) | MIT | PDF Table Extraction Engine | Java library for extracting tables from PDF files, serving as the core engine behind the popular tabula-py wrapper. |

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Document-AI&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Document-AI&type=date&legend=top-left)

---

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:
1. Ensure the SaaS product or open-source tool is actively maintained.
2. For SaaS additions, provide exact starting tier pricing and specific free tier / free trial limits in the tabular format.
3. For open-source additions, include the official GitHub repository link with the star count badge.
4. Submit a pull request with clear documentation and links.

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
