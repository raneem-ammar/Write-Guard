# WriteGuard: A Process-Based Academic Integrity Assistant for Online Document Collaboration

[GitHub Repository](https://github.com/raneem-ammar/Write-Guard.git)

---

## Supervisor
**Professor Ashraf Hafez Badawi**  
Zewail City of Science and Technology and Innovation  
Computational Science and Artificial Intelligence  
Email: abadawi@zewailcity.edu.eg

**Programs:**  
- Information Technology (Networks, Security, and Governance)  
- Data Science and Artificial Intelligence  

**Semester / Year:** Fall 2025  
**Date of Submission:** 25 / 10 / 2025  

---

## Team Members
-------------------------------------------------------------------------------
|         Name       |     ID    |              Email                 | Program |
|--------------------|-----------|------------------------------------|
| Raneem Tamer Ammar | 202200956 |  s-raneem.ammar@zewailcity.edu.eg  |  ITNS   |
| Mariam Mohamed Goda| 202201223 |  s-mariam.goda@zewailcity.edu.eg   |  DSAI   |
| Nosyba Mohamed     | 202201717 |  s-nosyba.mohamed@zewailcity.edu.eg|  DSAI   |
| Tasneim Amged      | 202201968 |  s-tasneim.el-din@zewailcity.edu.eg|  DSAI   |
--------------------------------------------


## Abstract
The rapid integration of AI tools like ChatGPT, Claude, and Gemini has created significant challenges for academic institutions in maintaining integrity within student writing. Traditional plagiarism detection systems only evaluate final text submissions and fail to capture AI-assisted writing processes.  

**WriteGuard** addresses this issue by introducing a real-time, browser-based academic integrity monitoring system that integrates with online collaborative editors such as Google Docs, Microsoft Office 365, and Zoho Writer. It captures the writing process itself—including keystroke patterns, copy-paste activity, typing velocity, and AI-generated content indicators.  

The backend system processes this data securely and provides educators with visual reports highlighting suspicious behaviors while ensuring student privacy. The outcome is a transparent, privacy-conscious tool that enhances trust, promotes fair evaluation, and redefines academic integrity monitoring in the digital era.

---

## Problem Statement & Motivation
The widespread availability of AI text generation tools has made it increasingly difficult for educators to verify the authenticity of student work. Traditional plagiarism detection tools focus on static, final outputs, making them ineffective against AI-assisted writing. Students can easily paste machine-generated text into documents, bypassing detection and undermining learning objectives.  

This problem affects universities, instructors, and accreditation bodies concerned with the credibility of academic submissions. The lack of process-based integrity mechanisms threatens fair evaluation and institutional reputation.  

**Need:** A transparent, process-aware integrity system capable of monitoring how content is produced rather than only what is submitted.

---

## Proposed Solution
**WriteGuard** is a real-time academic integrity monitoring tool integrated with browser-based document editors.  

**Core Functionalities:**  
- **Keystroke Dynamics Monitoring:** Capture typing speed, rhythm, and pauses.  
- **Copy-Paste Detection:** Identify large or repetitive paste actions from external sources.  
- **AI Text Detection:** Use linguistic and behavioral analysis to flag potential AI-generated content.  
- **Behavioral Analysis:** Compare typing consistency with individual baselines.  
- **Reporting Dashboard:** Provide educators with visual analytics and process summaries.  

**Innovation:** Unlike traditional output-based systems, WriteGuard focuses on **process-based verification**, analyzing how the text was created. This allows educators to detect irregularities that suggest AI assistance or non-original work while respecting student privacy.

---

## Project Scope

### In Scope
- Browser extension for Google Docs, Office 365, and Zoho Writer  
- Real-time keystroke and clipboard activity tracking  
- AI-based linguistic and behavioral analysis engine  
- Secure backend server for data aggregation and reporting  
- Educator dashboard with visual analytics  
- Security and compliance framework (encryption, integrity monitoring, anti-tampering)

### Out of Scope
- Offline editors (e.g., Microsoft Word desktop)  
- LMS platform integration (e.g., Moodle, Blackboard)  
- Webcam or biometric proctoring features  

### Assumptions & Limitations
- Requires internet connectivity for backend synchronization  
- Limited editor API access may restrict feature completeness  
- Keystroke collection anonymized to ensure GDPR and FERPA compliance  

---

## High-Level Timeline

| Phase | Description | Duration (weeks) | Deliverables |
|-------|-------------|-----------------|-------------|
| Research & Requirement Analysis | Literature review, use case identification, ethical & legal compliance | 4 | Requirements document, design brief |
| Design & Planning | System architecture, UI mockups, database & ML model design | 3 | System design document, architecture diagrams |
| Implementation Part 1 | Develop browser extension, backend API, and database | 5 | Functional prototype (v1), basic monitoring |
| Testing & Evaluation | Penetration testing, usability tests, model tuning | 4 | Test report, final GitHub repository, demo presentation |

---

## Technology Stack

**Frontend:** JavaScript/TypeScript, React, Plasmo Framework  
**Backend:** Node.js (Express), Python (FastAPI)  
**Database:** PostgreSQL, MongoDB  
**Machine Learning:** scikit-learn, PyTorch, Hugging Face Transformers  
**Security:** HashiCorp Vault, TLS 1.3, AES-256 encryption  
**Deployment:** Docker, Nginx  

**Justification:** Open-source, industry-grade technologies ensure scalability, high security, and cross-browser compatibility. Modular design allows parallel development between IT and DSAI students.

**Program Focus:**  
- **IT (Raneem):** System security, integration, encryption, penetration testing  
- **DSAI (Mariam, Nosyba, Tasneim):** Machine learning model design, text analysis, data visualization

---

## Success Metrics & Evaluation Plan
------------------------------------------------------------------------------------------------------------------------------
|    Metric    |                             Description                                | Evaluation Method                  |
|--------------|------------------------------------------------------------------------|------------------------------------|
| Accuracy     | Correctly identify AI-generated vs human-written text                  | Performance testing, ML evaluation |
| Performance  | Maintain low latency (<1s overhead)                                    | System profiling, load testing     |
| Security     | Detect tampering or data leaks                                         | Penetration testing, code audits   |
| Usability    | Educator satisfaction and clarity                                      | Feedback surveys, pilot deployment |
| Reliability  | 99% uptime with no data loss                                           | Continuous monitoring and logging  |
------------------------------------------------------------------------------------------------------------------------------
---

## Team Roles & Responsibilities



---

## Communication Plan
- **Meetings:** Weekly progress meetings (Microsoft Teams)  
- **Tools:** GitHub (version control), Trello (task management), Google Docs (documentation)  
- **Documentation:** Centralized technical wiki and system design documentation  

---

## References
- OpenAI. GPT-2 Output Detector. MIT License  
- TensorFlow.js Documentation. Client-Side ML Framework  
- OWASP. Web Application Security Testing Guide  
- HashiCorp Vault. Secrets Management Framework  
- Hugging Face Transformers. Pretrained NLP Models  
- Plasmo Framework. Browser Extension Development Toolkit  


