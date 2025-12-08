#  CSAI 498 / CSAI 499 – Graduation Project Proposal

##  Project Title
**WriteGuard: A Process-Based Academic Integrity Assistant for Online Document Collaboration**

**GitHub Repository:** [https://github.com/raneem-ammar/Write-Guard.git](https://github.com/raneem-ammar/Write-Guard.git)

---

##  Supervisor
**Professor. Ashraf Hafez Badawi**  
Zewail City of Science and Technology and Innovation  
Computational Science and Artificial Intelligence  
**Email:** abadawi@zewailcity.edu.eg

### Programs
- Information Technology (Networks, Security, and Governance)
- Data Science and Artificial Intelligence  

**Semester / Year:** Fall 2025  
**Date of Submission:** 25 / 10 / 2025  

---

##  Team Members

| Name | ID | Email | Program |
|------|----|--------|----------|
| **Raneem Tamer Ammar** | 202200956 | s-raneem.ammar@zewailcity.edu.eg | ITNS |
| **Mariam Mohamed Goda** | 202201223 | s-mariam.goda@zewailcity.edu.eg | DSAI |
| **Nosyba Mohamed** | 202201717 | s-nosyba.mohamed@zewailcity.edu.eg | DSAI |
| **Tasneim Amged** | 202201968 | s-tasneim.el-din@zewailcity.edu.eg | DSAI |

---

##  Abstract
The rapid integration of **Artificial Intelligence (AI)** tools such as ChatGPT, Claude, and Gemini has introduced significant challenges for academic institutions striving to uphold academic integrity in student writing. Traditional plagiarism detection systems are limited to analyzing the final submitted text, overlooking the writing process entirely.

**WriteGuard** addresses this gap by providing a **real-time, process-based academic integrity monitoring system** integrated with online editors like **Google Docs**, **Microsoft Office 365**, and **Zoho Writer**. It captures **keystroke dynamics, typing velocity, copy-paste behavior, and AI-generated indicators** while preserving privacy via encryption and ethical data practices.

The backend engine analyzes this data to generate **visual integrity reports** that help educators detect suspicious writing behavior. By focusing on *how* text is written rather than *what* is written, WriteGuard establishes a **new paradigm in academic integrity** — privacy-conscious, scalable, and AI-aware.

---

##  Problem Statement & Motivation
The rise of **AI text generation tools** (e.g., ChatGPT, Claude, Gemini) has blurred the lines between genuine student effort and machine-generated work. Current plagiarism detectors only evaluate the *final text*, missing crucial insights from the writing process.

This limitation poses a serious threat to **fair assessment** and **institutional credibility**, as undetected AI-generated content undermines trust in academic outcomes. The absence of **process-based verification** systems leaves universities vulnerable to integrity breaches.

Thus, there is a pressing need for a **transparent, process-aware, and privacy-respecting system** capable of identifying AI-assisted writing behaviors — ensuring that academic authenticity remains measurable in the digital era.

---

##  Proposed Solution
**WriteGuard** is a browser-integrated academic integrity assistant designed for platforms like **Google Docs**, **Microsoft Office 365**, and **Zoho Writer**.

Unlike traditional tools, it **records and analyzes the writing process** — including **keystroke dynamics, typing velocity, copy-paste activity**, and **AI-text signatures**. The system securely processes the data through an **AI-powered backend**, generating **interactive educator dashboards** with anomaly alerts.

###  Core Functionalities
- **Keystroke Dynamics Monitoring:** Capture and analyze typing speed, rhythm, and pauses.  
- **Copy-Paste Detection:** Identify abnormal paste activity.  
- **AI Text Detection:** Flag potential AI-generated segments.  
- **Behavioral Analysis:** Compare writing patterns against user baselines.  
- **Reporting Dashboard:** Visual analytics and alerts for educators.

###  Innovation
WriteGuard introduces **process-based verification**, transitioning from product-based plagiarism detection to **behavioral transparency** — ensuring evidence-backed authenticity and ethical AI detection.

---

##  Project Scope

### In Scope
- Browser Extension (Google Docs, Office 365, Zoho Writer)  
- Real-Time Keystroke & Clipboard Monitoring  
- AI-Powered Behavioral and Linguistic Analysis  
- Secure Backend (Encryption, Integrity Checks)  
- Educator Dashboard with Analytics & Alerts  
- GDPR and FERPA-Compliant Data Handling  

### Out of Scope
- Offline Editors (e.g., Microsoft Word)  
- LMS Integration (Moodle, Blackboard)  
- Webcam or Biometric Proctoring  

### Assumptions & Limitations
- Requires Internet Connectivity  
- Browser API Limitations Apply  
- Privacy-Compliant Data Storage (Encrypted & Anonymized)

---

##  High-Level Timeline

| Phase | Description | Duration (Weeks) | Deliverables |
|-------|--------------|------------------|---------------|
| **Research & Requirement Analysis** | Literature review, use case identification, GDPR/FERPA compliance mapping | 4 | Requirements Document, Ethical Compliance Report |
| **Design & Planning** | System architecture, UI/UX mockups, database schemas, ML pipeline design | 3 | Design Documents, Architecture Diagrams |
| **Implementation – Part 1** | Browser extension, backend APIs, real-time monitoring integration | 5 | Prototype v1, API Modules, Dashboard |
| **Testing & Evaluation** | Security and usability testing, ML performance validation | 4 | Test Report, Final GitHub Repo, Evaluation Metrics |

---

## Technology Stack & Theoretical Basis

| Layer               | Technology                       | Language      | Program Focus        | Purpose                                                                 |
|---------------------|-----------------------------------|---------------|-----------------------|-------------------------------------------------------------------------|
| **Browser Extension** | React + Plasmo (MV3)              | TypeScript    | SWD, DSAI             | Secure typed implementation with Manifest V3 support for modular UI     |
| **Frontend Dashboard** | React                              | TypeScript    | SWD, DSAI             | Build responsive dashboards for monitoring and analytics                |
| **Backend API**       | NestJS                             | TypeScript    | ITNS, SWD             | Enterprise-grade APIs with strong security and clean architecture       |
| **AI/ML Engine**      | FastAPI, PyTorch, scikit-learn, HuggingFace | Python | DSAI | NLP model hosting, AI inference, text detection, explainable AI         |
| **Database**          | PostgreSQL                          | SQL           | ITNS, SWD             | ACID-compliant storage for structured/unstructured behavioral data      |
| **Queue**             | Redis Streams                       | Redis script  | ITNS                  | Real-time event ingestion and message streaming                         |
| **Security**          | HashiCorp Vault, TLS 1.3, AES-256   | N/A           | ITNS                  | Secrets management, authentication, encryption, and data integrity      |
| **Reverse Proxy**     | Nginx                               | N/A           | ITNS                  | SSL termination, rate limiting, routing                                 |
| **Deployment**        | Docker, Kubernetes                  | N/A           | ITNS, SWD             | Containerized deployment, scaling, and CI/CD integration                |
| **Visualization**     | Plotly Dash, Tableau                | Python / N/A  | DSAI                  | Explainable AI dashboards and analytical reporting                      |


## Technology Justification

- **React + Plasmo (MV3)**  
  Enables secure, modular, and maintainable browser extensions with full Manifest V3 compliance and TypeScript type-safety.

- **React Dashboard**  
  Provides a mature UI ecosystem for building highly responsive, component-driven monitoring and analytics dashboards.

- **NestJS (Backend API)**  
  Offers enterprise-grade architecture, built-in security patterns, and scalable TypeScript-based backend services.

- **FastAPI (AI/ML Engine)**  
  Extremely fast Python framework ideal for hosting NLP pipelines, AI inference services, and academic-grade ML APIs.

- **PostgreSQL (Primary Database)**  
  ACID-compliant relational database ensuring data integrity, strong consistency, and structured storage for behavioral events.

- **Redis Streams (Real-Time Queue)**  
  Supports high-throughput event ingestion, streaming analytics, and decoupled backend processing.

- **PyTorch + Transformers (AI Models)**  
  Provide state-of-the-art deep learning capabilities, enabling robust text analysis, feature extraction, and explainable AI.

- **Nginx (Reverse Proxy)**  
  Handles SSL/TLS termination, rate limiting, request routing, and improves system security and performance.

- **Docker + Kubernetes**  
  Guarantee reproducible environments, scalable deployment, fault tolerance, and microservice orchestration.

- **HashiCorp Vault + TLS 1.3 + AES-256**  
  Enforce strict secrets management, secure communication, encryption standards, and Zero-Trust aligned security.

- **OWASP Best Practices**  
  Ensure code quality, vulnerability mitigation, and compliance with modern security requirements.


###  Program Focus
- **ITNS (Raneem):** Security, integration, encryption, deployment pipelines.  
- **DSAI (Mariam, Nosyba, Tasneim):** AI model design, training, and visualization.  
- **SWD (All):** Software architecture, modular development, clean design.

---

##  Success Metrics & Evaluation Plan

| Metric | Description | Evaluation Method |
|---------|--------------|-------------------|
| **AI Detection Accuracy** | Distinguish AI vs human writing | ≥90% F1-score on labeled data |
| **Performance & Latency** | Monitor delay under real-time use | <1s keystroke logging, <2s update delay |
| **Security & Integrity** | Data confidentiality, tamper-proofing | Penetration testing, checksum validation |
| **Usability & UX** | Educator and student satisfaction | ≥85% positive rating |
| **Reliability** | Uptime and fault tolerance | ≥99% uptime |
| **Data Quality** | Robust ML datasets | Continuous validation and retraining |

---

##  Team Roles & Responsibilities

| Member | Program | Role | Contribution |
|---------|----------|------|---------------|
| **Raneem Tamer Ammar** | ITNS | Security Infrastructure Engineer | TLS/AES encryption, Docker/Nginx setup, compliance testing. **Deliverables:** SOC Dashboard, Anti-Tampering System. |
| **Tasneim Amged** | DSAI | Deep Learning & Data Engineer | Preprocessing, feature extraction, dataset versioning. **Deliverables:** Cleaned Dataset, Feature Framework. |
| **Nosyba Mohamed** | DSAI | ML Research Engineer | **Train and validate hybrid ML models (Random Forest, SVM), fuse temporal data, optimize Feature Importance Analysis, and deploy RESTful inference services using FastAPI or Flask.** **Deliverables:** Trained Models, Benchmark Report, REST API. |
| **Mariam Mohamed Goda** | DSAI | Explainable NLP & Dashboard Developer | Transformer-based NLP, LIME/SHAP integration, educator dashboard. **Deliverables:** NLP/XAI Modules, Visualization Dashboards. |

###  Shared Responsibilities
- Frontend UI & Dashboard Development  
- RESTful API Integration  
- GitHub Documentation & CI/CD  
- Ethical and Legal Compliance  

---

##  Communication Plan
- **Meetings:** Weekly syncs with supervisor  
- **Tools:** Trello (tasks), GitHub (version control), Teams (communication)  
- **Documentation:** GitHub Wiki + Biweekly Reports  

---

##  References

**[1]** T. Issa, R. Issa, and M. Isaias, “A teamwork framework for preventing breaches of academic integrity,” *Procedia – Social and Behavioral Sciences*, vol. XX, 2024. [Online]. Available: [https://www.sciencedirect.com/science/article/pii/S2405844024147901](https://www.sciencedirect.com/science/article/pii/S2405844024147901)

**[2]** A. Nguyen, “Human-AI collaboration patterns in AI-assisted academic writing,” *Higher Education Research & Development*, 2024. [Online]. Available: [https://www.tandfonline.com/doi/full/10.1080/03075079.2024.2323593](https://www.tandfonline.com/doi/full/10.1080/03075079.2024.2323593)

**[3]** W. Sutherland-Smith, “‘Crossing the line’: Collusion or collaboration in university group work?,” *Australian Universities’ Review*, vol. 55, no. 1, pp. 51–59, 2013. [Online]. Available: [https://files.eric.ed.gov/fulltext/EJ1004398.pdf](https://files.eric.ed.gov/fulltext/EJ1004398.pdf)

**[4]** Y. Liu et al., “**RoBERTa: A robustly optimized BERT pretraining approach**,” *arXiv preprint arXiv:1907.11692*, 2019. [Online]. Available: [https://arxiv.org/abs/1907.11692](https://arxiv.org/abs/1907.11692)

**[5]** M. Gao et al., “**DetectGPT: Zero-shot machine-generated text detection using probability curvature**,” *arXiv preprint arXiv:2301.11305*, 2023. [Online]. Available: [https://arxiv.org/abs/2301.11305](https://arxiv.org/abs/2301.11305)

**[6]** S. Foltýnek, M. Bjelobaba, and T. Glendinning, “**Artificial intelligence and academic integrity**,” *International Journal for Educational Integrity*, vol. 19, no. 1, 2023. [Online]. Available: [https://edintegrity.biomedcentral.com/articles/10.1007/s40979-023-00146-z](https://edintegrity.biomedcentral.com/articles/10.1007/s40979-023-00146-z)

**[7]** T. Wolf et al., “**Transformers: State-of-the-art natural language processing**,” *arXiv preprint arXiv:1908.10084*, 2019. [Online]. Available: [https://arxiv.org/abs/1908.10084](https://arxiv.org/abs/1908.10084)

**[8]** J. Perez et al., “**On detecting machine-generated text using large language models**,” *NeurIPS 2023 Conference Proceedings*, 2023. [Online]. Available: [https://neurips.cc/virtual/2023/poster/71713](https://neurips.cc/virtual/2023/poster/71713)

**[9]** Carnegie Mellon University, “**Keystroke Dynamics Benchmark Dataset and Research**,” *School of Computer Science – CMU*, 2024. [Online]. Available: [https://www.cs.cmu.edu/~keystroke/#sec2](https://www.cs.cmu.edu/~keystroke/#sec2)

**[10]** Google, **Chrome Extension Developer Guide (Manifest V3)**, 2024. [Online]. Available: [https://developer.chrome.com/docs/extensions/mv3/](https://developer.chrome.com/docs/extensions/mv3/)

**[11]** Google, **Google Docs API Documentation**, 2024. [Online]. Available: [https://developers.google.com/docs/api](https://developers.google.com/docs/api)

**[12]** TensorFlow, **TensorFlow.js Tutorials and Developer Documentation**, 2024. [Online]. Available: [https://www.tensorflow.org/js/tutorials](https://www.tensorflow.org/js/tutorials)

**[13]** OWASP Foundation, **OWASP Top Ten Security Guidelines**, 2024. [Online]. Available: [https://owasp.org/](https://owasp.org/)

**[14]** Mozilla Developer Network (MDN), **Web Crypto API Reference**, 2024. [Online]. Available: [https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Crypto_API)

**[15]** GPTZero, **AI-Generated Text and Keystroke Monitoring Tool**, 2024. [Online]. Available: [https://gptzero.me/](https://gptzero.me/)

**[16]** Turnitin, **Plagiarism Detection and Academic Integrity Platform**, 2024. [Online]. Available: [https://www.turnitin.com/](https://www.turnitin.com/)

**[17]** Draftback, **Google Docs Revision Playback Extension**, 2024. [Online]. Available: [https://draftback.com/](https://draftback.com/)

**[18]** Originality.AI, **AI Content Detection and Plagiarism Analysis**, 2024. [Online]. Available: [https://originality.ai/](https://originality.ai/)

**[19]** Hello-SimpleAI, **HC3: Human-ChatGPT Comparison Corpus Dataset**, 2023. [Online]. Available: [https://huggingface.co/datasets/Hello-SimpleAI/HC3](https://huggingface.co/datasets/Hello-SimpleAI/HC3)

**[20]** Webis Group, **PAN Author Profiling and Plagiarism Detection Datasets**, 2024. [Online]. Available: [https://pan.webis.de/data.html](https://pan.webis.de/data.html)

**[21]** Zenodo Repository, **Academic Integrity and AI Text Generation Datasets**, 2024. [Online]. Available: [https://zenodo.org/records/4906326](https://zenodo.org/records/4906326)

**[22]** U.S. Department of Education, **Family Educational Rights and Privacy Act (FERPA)**, 2024. [Online]. Available: [https://studentprivacy.ed.gov/ferpa](https://studentprivacy.ed.gov/ferpa)

**[23]** European Union, **General Data Protection Regulation (GDPR)**, 2018. [Online]. Available: [https://gdpr-info.eu/](https://gdpr-info.eu/)

**[24]** Association for Computing Machinery (ACM), **ACM Code of Ethics and Professional Conduct**, 2024. [Online]. Available: [https://www.acm.org/code-of-ethics](https://www.acm.org/code-of-ethics)

**[25]** IEEE, “**Ethically aligned design: A vision for prioritizing human well-being with autonomous and intelligent systems**,” *IEEE Standards Association*, 2020. [Online]. Available: [https://ethicsinaction.ieee.org](https://ethicsinaction.ieee.org)

**[26]** L. Nguyen et al., “**Improving AI-Generated Text Detection Using Multi-Stage Fine-Tuning**,” *arXiv preprint arXiv:2405.16422*, 2024. [Online]. Available: [https://arxiv.org/abs/2405.16422](https://arxiv.org/abs/2405.16422)

**[27]** A. N. A. Halim et al., “**Machine Learning Approaches in Academic Integrity Analysis**,” *Procedia Computer Science*, vol. 215, pp. 1123–1132, 2022. [Online]. Available: [https://www.sciencedirect.com/science/article/pii/S1877050922010134](https://www.sciencedirect.com/science/article/pii/S1877050922010134)

**[28]** A. K. Jha et al., “**Explainable AI for Educational Integrity Systems**,” *Technologies*, vol. 10, no. 3, 2022. [Online]. Available: [https://www.mdpi.com/2227-7080/10/3/57](https://www.mdpi.com/2227-7080/10/3/57)

**[29]** ACL Anthology, “**Detection of AI-Generated Texts in Academic Contexts**,” *ACL 2021 Proceedings*, 2021. [Online]. Available: [https://aclanthology.org/2021.acl-long.552.pdf](https://aclanthology.org/2021.acl-long.552.pdf)

**[30]** Secure Controls Framework (SCF), **Cybersecurity and Privacy Control Framework**, 2024. [Online]. Available: [https://securecontrolsframework.com/](https://securecontrolsframework.com/)



