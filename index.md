# Proplens – AI Operating System for Property Development

Proplens is an AI-driven operating system designed for real estate developers and construction companies. In property development, projects span years, data is scattered across many systems, and execution relies on coordination between internal teams and 50–100 external consultants and suppliers per project. Proplens centralizes these workflows by deploying a team of specialized AI agents that automate high-effort, repetitive tasks and orchestrate project-level decisions.

Our goal is to become the central operating system that understands project context end-to-end, connects siloed systems of record, and continuously optimizes outcomes across the development lifecycle.

---

## 1. Problem We Address

Property development projects are complex and coordination-heavy:

- Data is fragmented across CRM, spreadsheets, BOQs, contract folders, bid documents, site reports, and regulatory submissions.
- Internal teams (sales, finance, procurement, project management, design) all use different tools with little “binding glue” between them.
- Every project involves dozens of external parties: brokers, consultants, contractors, suppliers, authorities, and service providers.
- Many workflows are repetitive and manual: responding to buyer enquiries, chasing documents, validating BOQs, comparing bids, checking compliance rules, and reconciling costs vs. site progress.

This creates long cycle times, information gaps, and avoidable delays.

---

## 2. Our Solution: AI Agents for the Development Lifecycle

Proplens provides an AI operating system composed of specialized agents that understand real estate and construction workflows. These agents automate both **function-specific** tasks and **cross-departmental** workflows that require triaging data across multiple files and teams.

### Core Capabilities

- Orchestrate multi-step workflows end-to-end (not just single prompts).
- Read and understand project files: BOQs, RFPs, contracts, invoices, regulatory guidelines, drawings, and site reports.
- Connect internal systems of record with external consultants and suppliers.
- Keep project-level objectives in view while optimizing local tasks.

---

## 3. Key Agents & Use Cases

### 🏡 Ria – Smart Sales & Leasing Concierge  
- Handles top-of-funnel buyer and tenant enquiries.  
- Qualifies leads, answers project questions, proposes viewing slots.  
- Remembers preferences and personalizes follow-up.  
- Shortens the journey from enquiry to property tour and increases sales productivity.

### 📊 Alex – Sales Intelligence Assistant  
- Bridges internal CRM data with external market intel.  
- Surfaces comparable projects, pricing ranges, and availability.  
- Prepares concise talking points so sales teams never need to say “I’ll get back to you” for basic questions.

### 🤝 Elizabeth – Customer Service Agent  
- Automates 60–80% of customer and tenant interactions.  
- Resolves questions on billing, payment milestones, documentation, and handover status.  
- Builds a longitudinal view of customer/tenant behavior and can help generate referral sales with personalized content.

### 🧱 Anna – Procurement Agent  
- Researches and profiles suppliers for specific materials across markets.  
- Reads and compares RFP responses, levels bids, and ranks suppliers based on custom parameters.  
- Compares current offers with historical PO rates, helping reduce procurement delays and leakages.

### 💰 Patrick – Costing & Budgeting Agent  
- Generates and validates BOQ line items using past project data.  
- Compares BOQ pricing with live market information on the web.  
- Tracks budgeted vs. actual costs by trade and WBS item, and raises alerts for variances.  
- Reconciles billing against verified site progress.

### 📜 Luke – Regulatory Compliance Agent  
- Helps teams query city-specific regulations using natural language.  
- Analyzes historical comments from municipal authorities to predict likely objections.  
- Surfaces potential non-compliant design elements early, reducing submission iterations.  
- Roadmap: real-time compliance checks as designs are updated inside BIM tools.

---

## 4. How Proplens Uses Google Cloud

Proplens is built natively on Google Cloud to achieve scalability, security, and reliability:

- **Vertex AI** – hosts and orchestrates the large language models behind each agent, manages prompt workflows, and enables fine-tuning on project-specific data.
- **Cloud Run** – runs stateless agent services and orchestration APIs, scaling automatically based on usage from web apps, CRMs, and external integrations.
- **BigQuery** – serves as the unified analytics layer for project records, interactions, costs, and performance metrics across projects.
- **Document AI** – interprets complex documents: BOQs, supplier bids, contracts, regulatory guidelines, site reports, and other semi-structured PDFs.
- **Cloud Storage** – stores documents, design files, logs, and other artifacts that agents consume and produce.

This architecture allows us to plug AI agents into existing developer tools without forcing customers to replace their entire stack.

---

## 5. Example End-to-End Workflow

**Lead to Deal (Sales & Leasing)**  
1. Buyer enquiry arrives via web form, chat, or portal.  
2. Ria (Sales Concierge) qualifies the lead, asks clarifying questions, and proposes viewing times.  
3. Alex (Sales Intelligence) enriches the lead with internal CRM history and market data.  
4. The system passes a clean, structured lead record to the sales CRM.  
5. Sales receives a prioritized queue with recommended next actions.

Outcome: reduced response times, more qualified leads, shorter sales cycles, and higher team productivity.

---

## 6. Roadmap

Our roadmap expands from customer-facing workflows towards deeper project operations:

- Procurement automation across more trades and markets.  
- Advanced site documentation analytics and risk signals.  
- Real-time project planning support, combining schedules, costs, and constraints.  
- Tighter BIM integration for compliance and design-intent checks.

By focusing on these higher-value workflows, Proplens aims to become the central OS that manages project-level goals across the entire development lifecycle.

---

## 7. About Proplens

Proplens is focused exclusively on the built environment: real estate developers, construction companies, and their extended networks of consultants and suppliers. We work with customers who want to reduce manual coordination, unlock data trapped in documents, and make faster, more confident project decisions with AI.

- 🌐 Website: https://proplens.info  
- 📧 Contact: joao.paulo@proplens.info
