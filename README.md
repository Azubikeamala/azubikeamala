# Hi, I'm Amalachukwu Azubike 👋🏾

### Application Security & AI Security Engineer  
**AI / LLM Security · Secure SDLC · AI Governance & Responsible AI · Software Engineering**

I build, break, secure, and help govern modern applications and AI-enabled systems.

My background sits at the intersection of **software engineering and cybersecurity**. I started in IT and systems support, moved into application development, and then into application security, penetration testing, cybersecurity research, and AI/LLM security.

Today, my work focuses on identifying where risk enters applications and AI systems, understanding how those systems fail under attack, and designing practical controls that engineering and security teams can implement.

🌐 **Portfolio:** [www.amalachukwu.com](https://www.amalachukwu.com)

---

## 🔐 What I Work On

### Application Security
- Secure Software Development Lifecycle (SSDLC)
- SAST / DAST
- Web application security
- API security
- Authentication & authorization
- Threat modeling
- Vulnerability assessment
- Secure coding & remediation
- OWASP Top 10
- CI/CD security
- Security headers, CSP & input validation

### 🤖 AI / LLM Security
- Prompt injection
- Indirect prompt injection
- Jailbreak testing
- Sensitive-data leakage
- LLM red teaming
- AI threat modeling
- Risk scoring
- Model routing
- Output validation
- Defense-in-depth for LLM applications
- Adaptive security controls

Tools and technologies I have worked with include:

`Promptfoo` · `Garak` · `PyRIT` · `Hugging Face` · `Burp Suite` · `OWASP ZAP` · `SonarQube` · `Snyk` · `Nessus` · `OpenVAS` · `Wireshark` · `Nmap`

### ⚖️ AI Governance, Risk & Responsible AI
I am also building depth at the intersection of **AI security, privacy, risk and governance**, including:

- AI system risk assessment
- Responsible AI
- AI lifecycle governance
- Privacy and AI
- Human oversight
- Transparency & accountability
- AI controls and evidence
- AI monitoring
- Vendor / third-party AI risk
- NIST AI RMF
- ISO/IEC 42001 concepts
- EU AI Act awareness
- Governance of generative AI systems

My interest here is practical:

> How do organizations adopt AI without treating security, privacy, accountability and human impact as afterthoughts?

---

# 🧪 Selected Security & AI Work

## Adaptive Moving Target Defense for LLM Security

My MSc research explores whether LLM systems can respond more effectively to **prompt injection, jailbreak and data-leakage attacks** by adapting their defensive strategy according to detected risk instead of relying on one static defense.

The work includes:

- Risk-based request classification
- Adaptive defensive prompting
- Model-routing strategies
- Local + API model experimentation
- Prompt-injection and jailbreak testing
- Canary-based data-leakage detection
- Promptfoo attack integration
- Garak and PyRIT red-team testing
- Static vs adaptive defense comparison
- Attack-success-rate evaluation
- Benign utility measurement
- Latency and cost analysis
- Repeated-seed and ablation experiments

**Research area:** AI Security · LLM Security · Adaptive Defense · GenAI Red Teaming

---

## Three-Layer Defense Framework for Secure LLM Applications

Designed and evaluated a defense-in-depth architecture for protecting LLM-enabled applications.

### Layer 1 — Context Isolation
Restrict what information the model is authorized to access.

### Layer 2 — Prompt Sanitization
Detect and filter malicious or manipulative input.

### Layer 3 — Response Redaction
Inspect generated output and prevent sensitive-data exposure.

The project reinforced a principle that shapes much of my AI-security work:

> LLMs process language, not trust. Security boundaries must exist around the model.

🔗 [View related LLM security work](https://github.com/Azubikeamala/Data-Leakage-Attacks-LLM-)

---

## LLM Data Leakage Attack & Defense Lab

Built an intentionally vulnerable LLM-enabled application to demonstrate how poor context separation can cause **cross-user sensitive-data leakage**.

Architecture:

`Frontend → Flask API → LLM Layer → Response`

The project explores moving from:

**Vulnerable implementation → Attack → Detection → Layered defense**

using controls such as:

- Context isolation
- Prompt sanitization
- Output filtering
- Access boundaries
- Defense-in-depth

🔗 [View project](https://github.com/Azubikeamala/Data-Leakage-Attacks-LLM-)

---

## Penetration Testing & Application Security Labs

Hands-on security work has included:

- Reconnaissance and enumeration
- Vulnerability assessment
- SQL injection
- XSS
- CSRF
- IDOR-style access-control testing
- Authentication attacks
- Buffer-overflow fundamentals
- Exploitation and post-exploitation
- Privilege escalation
- Password and hash attacks
- Network attack simulation
- Secure remediation analysis

Tools have included:

`Kali Linux` · `Burp Suite` · `OWASP ZAP` · `Metasploit` · `Nmap` · `Wireshark` · `Nessus` · `OpenVAS` · `Hashcat` · `John the Ripper`

---

## 🧬 Machine Learning-Based Malware Classification & APT Attribution

Built a cybersecurity threat-intelligence workflow for classifying malware samples against known APT groups using opcode-based features.

The project included:

- Malware opcode extraction
- Dataset construction
- Unigram / bigram feature engineering
- SVM
- KNN
- Decision Tree
- Accuracy / precision / recall / F1 evaluation
- Confusion-matrix analysis
- Threat-intelligence interpretation

🔗 [View Cyber Threat Intelligence work](https://github.com/Azubikeamala/CIS-6530)

---

## 🔎 AI-Generated Voice / Deepfake Fraud Evidence Triage

Built a digital-forensics application exploring how investigators could systematically triage suspected AI-generated audio and video evidence.

The application incorporates:

- SHA-256 evidence hashing
- Metadata extraction
- Evidence-integrity checks
- Rule-based triage
- Structured forensic findings
- Synthetic/deepfake evidence considerations

This project sits at the intersection of:

`Digital Forensics + AI Misuse + Fraud + Evidence Integrity`

---

# 🛠️ I Also Build Software

Security is stronger when you understand what engineering teams are actually building.

My software-development background includes:

`Python` · `JavaScript` · `React` · `Node.js` · `Express` · `Flask` · `Django` · `SQL` · `PostgreSQL` · `MongoDB` · `Firebase` · `REST APIs` · `Authentication` · `OAuth` · `Git` · `Vercel`

I have built full-stack applications involving:

- Authentication and authorization
- APIs
- Databases
- Real-time data
- AI integrations
- Responsive interfaces
- Backend services
- Cloud deployment
- Testing
- Security controls

---

# 🚀 Commercial SaaS Builder

Alongside my cybersecurity work, I build commercial SaaS products aimed at solving practical business problems.

This keeps my security work grounded in real engineering decisions involving:

- Product architecture
- Authentication
- APIs
- Multi-tenant applications
- AI integrations
- Third-party services
- Billing
- Deployment
- Privacy
- Security
- Governance
- Cost and usability trade-offs

### Selected Products

#### QuickHalo
Customer-retention and business automation SaaS for service businesses, with capabilities around automated follow-up, recurring-customer engagement, booking and customer communication.

#### AI Governance & Audit Platform — In Development
A SaaS platform designed to help organizations manage AI inventories, risk assessments, policies, controls, evidence, remediation and ongoing AI governance.

The goal is to make responsible AI governance operational rather than simply producing policy documents.

More products are currently in development.

---

# 🎓 Education

### Master of Cybersecurity & Threat Intelligence
**University of Guelph**

Focus areas include:

- Application Security
- Penetration Testing
- Cyber Threat Intelligence
- Digital Forensics
- Cryptography
- Privacy & Governance
- AI / LLM Security Research

### Postgraduate Diploma — Computer Application Development
**Conestoga College**

Software architecture, application development, databases, web technologies and deployment.

---

# 🏅 Certifications & Specialized Training

- **CompTIA Security+**
- **ISC2 Certified in Cybersecurity (CC)**
- **Data Privacy, Security and Governance — University of Guelph**
- Agentic AI training and continuing AI-security education

---

# 🔭 Current Focus

- 🔐 Application Security & Product Security
- 🤖 AI / LLM Security
- 🧪 GenAI Red Teaming
- 🧠 Adaptive defenses for LLM systems
- ⚖️ AI Governance & Responsible AI
- 🛡️ Secure AI application architecture
- 🚀 Building secure commercial SaaS products

---

# 🤝 Let's Connect

I'm particularly interested in opportunities and conversations involving:

**Application Security · Product Security · AI Security · GenAI Security · LLM Security · AI Governance · Responsible AI · Security Engineering**

🌐 Portfolio: [www.amalachukwu.com](https://www.amalachukwu.com)  
💼 LinkedIn: [Amalachukwu Azubike](https://www.linkedin.com/in/amalachukwu-azubike/)  
💻 GitHub: [@Azubikeamala](https://github.com/Azubikeamala)

---

## 📊 GitHub Activity

[![](https://raw.githubusercontent.com/Azubikeamala/azubikeamala/master/profile-summary-card-output/darcula/0-profile-details.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)

[![](https://raw.githubusercontent.com/Azubikeamala/azubikeamala/master/profile-summary-card-output/darcula/1-repos-per-language.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)
[![](https://raw.githubusercontent.com/Azubikeamala/azubikeamala/master/profile-summary-card-output/darcula/2-most-commit-language.svg)](https://github.com/vn7n24fzkq/github-profile-summary-cards)
