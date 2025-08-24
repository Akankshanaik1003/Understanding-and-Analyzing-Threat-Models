
# Threat Modeling Report – OWASP Juice Shop

## 📌 Internship Task – Understanding and Analyzing Threat Models

This repository contains my internship task submission for **Threat Modeling**, where I analyzed the **OWASP Juice Shop** application using the **STRIDE framework**.

OWASP Juice Shop is known as one of the most insecure web applications intentionally created for learning purposes. It contains vulnerabilities such as SQL Injection, Cross-Site Scripting (XSS), Insecure Direct Object References, and Broken Authentication, making it a suitable target for this exercise.

---

## 📖 Report Overview

The report includes:

* **Introduction** – Purpose of the exercise and why Juice Shop was chosen.
* **Threat Modeling Approach** – STRIDE framework (Spoofing, Tampering, Repudiation, Information Disclosure, DoS, Elevation of Privilege).
* **System Overview** – Architecture of Juice Shop (frontend, backend, database, authentication, admin panel).
* **Detailed STRIDE Threat Analysis** – Examples of threats in Juice Shop with mitigation strategies.
* **Security Controls Summary** – Mapping STRIDE categories to potential threats and security measures.
* **Conclusion** – Key learnings as a student performing threat modeling.

---

## 🔐 STRIDE Threat Categories & Examples

| STRIDE Category            | Potential Threat in Juice Shop                     | Mitigation                           |
| -------------------------- | -------------------------------------------------- | ------------------------------------ |
| **Spoofing**               | SQL Injection login bypass                         | Parameterized queries, MFA           |
| **Tampering**              | Modifying product prices in requests               | Server-side validation, sanitization |
| **Repudiation**            | Denying unauthorized actions                       | Logging, audit trails                |
| **Information Disclosure** | Error messages revealing SQL queries, exposed APIs | Generic errors, encryption           |
| **DoS**                    | Overloading server with fake requests              | Rate limiting, WAF                   |
| **Elevation of Privilege** | Unauthorized admin panel access                    | RBAC, authorization checks           |

---

## 📂 Files in this Repository

* `Threat_Modeling_Report.docx` – Full detailed report (5–6 pages).
* `README.md` – This file, summary of the task.

---

## 🏁 Conclusion

Performing this threat modeling task using **STRIDE** gave me hands-on understanding of how to:

* Identify vulnerabilities systematically.
* Think like both an attacker and defender.
* Propose mitigation strategies for common web application threats.


Do you want me to also make the **README shorter and very professional** (like most GitHub repos) or keep it **student-style explanatory** like above?
