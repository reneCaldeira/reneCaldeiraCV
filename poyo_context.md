# PoYo Model Context: reneCaldeiraCV (Enterprise Architect Portfolio)

## 1. Candidate Profile & Core Identity
- **Name**: Renê Caldeira
- **Target Title**: Enterprise IT Architect (EITA) | Lead Cloud Architect | Product Line Architect
- **Experience**: 22+ years in IT across enterprise architecture, cloud-native systems, software engineering leadership, digital transformation, and AI integration.
- **Contact Info**:
  - Email: `renedeoliveiracaldeira@gmail.com`
  - Phone: `+55 11-98778-9168`
  - Location: Indaiatuba/SP - Brazil
  - Website: `https://renecaldeira.com.br`
  - LinkedIn: `https://www.linkedin.com/in/renecaldeira/`
- **Languages**: Portuguese (Fluent), English (Fluent), Spanish (Intermediate)
- **Profile Summary**:
  "With over 22 years of experience in IT, I have a strong background in architecture, management, and development across web, mobile, desktop, IVR, and cloud projects. I hold a bachelor's degree in telecommunications engineering, a postgraduate degree in mobile application development, and two MBAs in IT project management and solution architecture. Additionally, I have earned multiple certifications and completed various industry-relevant courses, equipping me with expertise in the latest technologies on the market. Currently leading efforts to integrate AI into enterprise-level platforms."

## 2. Core Architectural Competencies & Main Skills
- Enterprise IT Architecture (EITA) & TOGAF / Architecture Governance
- Cloud-Native Architecture & Microservices (Microsoft Azure, AWS, GCP, IBM Cloud)
- Generative AI & Enterprise LLM Integration (OpenAI, ChatGPT, Copilot, AI Governance)
- Cross-functional Technical Leadership & Engineering Management
- Product Line Architecture & System Integrations (SAP S/4HANA, Salesforce, Adobe AEM)
- Modern Practices: SRE, DevSecOps, DORA Metrics, FinOps, Lean Six Sigma, SAFe, PDCA
- Tech Stack & Engineering: Java, .NET Core, Node.js, Python, Apache Kafka, IBM Event Streams, REST/SOAP APIs, Micro-frontends, Hexagonal Architecture.

## 3. Career Experience History
### 1. Corteva Agriscience (May 2023 - Present)
- **Role**: Enterprise Solutions Architect - LATAM
- **Enterprise Architecture**:
  - Maintain consistency of enterprise architectural principles across commercial product lines.
  - Setting standards and guardrails for cloud software development (tools, frameworks, languages).
  - Design reference architectures and blueprints for enterprise software development.
  - Advancing enterprise-wide AI capabilities and applications (Copilot, ChatGPT).
  - IT process management over cyberSecurity, privacy, solution architecture and software development teams.
- **Leadership**:
  - Interviewing, hiring, and onboarding architecture and engineering teams.
  - Driving PDCA/Continuous Improvement, test pyramids, quality metrics, observability, DevSecOps.
  - Technical leadership in digital ag products for buying, selling, and farming across LATAM.
- **Product Line Architecture**:
  - Cloud architectural lead for complex integrations with SAP S/4HANA, Salesforce, Adobe Experience Manager (AEM).
  - "Make or Buy" analysis for large-scale enterprise platforms.
  - On-premises dehydration of monoliths into microservices groups inside Azure.
  - IT governance, situational walls, architectural MVPs, responsibility matrices, and architectural roadmaps.

### 2. CI&T (Mar 2020 - Apr 2023)
- **Role**: Lead Solutions Architect
- Digital Transformation for tier-1 financial institutions, implementing DevSecOps and Lean practices.
- AI project development and governance using CI&T Flow AI platform.
- Cloud migrations to Azure & IBM ICP; dehydration of banking monoliths into microservices.
- Event-driven architecture (Kafka, IBM Event Streams), hexagonal architecture, micro-frontends.
- Technical leadership, hiring, coaching on SAFe/Lean Digital, DORA metrics, SRE.

### 3. Veloe (Jan 2019 - Feb 2020)
- **Role**: Cloud Solutions Architect
- Alignment of IT strategy with corporate growth objectives.
- Design & deployment of microservices and serverless architectures in AWS.
- Supported architecture for WebApp, Mobile App, Marketing & Growth-Hacking.
- Architectural cost optimization (FinOps), process time reduction, high availability, and DevSecOps.

### 4. Mutant (Jun 2017 - Dec 2018)
- **Role**: SR Software Architect / Tech Lead
- Clients: Global Telecom (Vivo), Insurance (Mapfre, Bradesco Seguros), Banking (Riachuelo Credit, Bradesco).
- Tech leadership for IVR development teams; systems in Avaya and Genesys (Java, JS).
- Full solution design, REST/SOAP APIs, integrations between modern frontends and legacy backends.

## 4. Education
- **FIAP** (2020 - 2021): MBA in Solution Architecture
- **Laureate Education** (2018 - 2019): MBA in IT Project Management
- **FMU** (2014 - 2016): Engineer's degree in Mobile Applications & Video Game Development
- **PUC - Campinas** (2001 - 2007): Bachelor's Degree in Electrical, Electronics and Communications Engineering

## 5. Website Architecture & Current Style
- **Aesthetic Direction**: Swiss Architectural Dossier (`#0b0e14` background, `#121722` surfaces, `#00e5a3` signal green accent, monospace data ledgers, serif/display headings).
- **Zero Frameworks**: Single static `index.html` + `avatar.jpg` + `resume.pdf`.

## 6. Current Task: Mobile Responsiveness Refinement
- **Issue**: Desktop rail (`aside.dossier-rail`) stacks vertically as an 800px tall block on mobile viewports (<860px), pushing the primary hero below the fold.
- **Issues to Resolve**:
  1. Top classification bar wraps and collides on 360-390px screens.
  2. Sidebar rail should become a compact mobile header on screens <860px (avatar + name/title + horizontal scrollable nav chip bar).
  3. Action buttons (`INITIATE CONTACT` and `DOWNLOAD RESUME (PDF) ↓`) should stack vertically (full width) on <640px to prevent truncation.
  4. Role pills in hero (`.role-pill`) should wrap properly and adjust padding/font-size.
  5. Data matrix / tables (`.data-matrix`, `.contact-table`) should format cleanly without horizontal squishing or overflow of long email/text.
