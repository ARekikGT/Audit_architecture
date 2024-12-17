# Audit Report Project - Firma'IQ System

## Project Overview
This repository contains files related to a comprehensive **security and performance audit** of a **microservices-based architecture**. The audit focuses on enhancing the resilience, automation, and scalability of the Firma'IQ system.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Documents](#documents)
- [Project Goals](#project-goals)
- [Tools and Methodologies](#tools-and-methodologies)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Contributors](#contributors)

---

## Documents
The repository includes the following key files:

1. **Audit Report** (`Audit_report.pdf`):  
   A detailed technical audit addressing system infrastructure, CI/CD pipelines, microservices, and security vulnerabilities.

2. **Progress Meetings (PVs)** (`PVs.pdf`):  
   Summaries of progress meetings detailing tasks, findings, and responsibilities.

3. **Audit Presentation Speech** (`speech audit.pdf`):  
   Script used for presenting audit findings, risk assessments, and recommendations.

---

## Project Goals
The primary goals of the audit are:
1. **Identify and mitigate risks** in infrastructure, microservices, and CI/CD pipelines.
2. **Enhance system resilience** against failures and cyber threats.
3. **Improve scalability and automation** using industry-standard tools and frameworks.
4. Ensure compliance with **ISO 27001** and **GDPR** regulations.

---

## Tools and Methodologies
The following tools and frameworks were used during the audit:

- **Security and Vulnerability Assessment**:
  - Lynis (System hardening)
  - Trivy (Docker vulnerability scanning)
  - SonarQube (Code quality analysis)
  - HashiCorp Vault (Secrets management)

- **Monitoring and Observability**:
  - Prometheus and Grafana (Metrics and visualization)
  - Jaeger (Distributed tracing)

- **Risk Assessment Framework**:
  - MEHARI for risk prioritization.

---

## Key Findings
1. **Unsecured Secrets**: Sensitive credentials stored in plain text.
2. **API Security Issues**: Lack of proper authentication and rate-limiting mechanisms.
3. **Overly Permissive RBAC Policies**: Increased risk of unauthorized access.
4. **Outdated Docker Images**: Containing unpatched vulnerabilities.
5. **Network Vulnerabilities**: Unencrypted inter-service communication.

---

## Recommendations
The audit recommends the following key actions:

1. **Secure Secrets**: Implement **HashiCorp Vault** for credentials management.
2. **API Hardening**: Use **OAuth 2.0** and rate-limiting for APIs.
3. **Kubernetes Security**: Refine **RBAC policies** and deploy **Istio** for mTLS.
4. **CI/CD Enhancements**: Integrate vulnerability scanning tools into pipelines.
5. **Monitoring and Observability**: Deploy **Prometheus** and **Grafana** with real-time alerts.

A phased action plan is suggested for immediate, short-term, and long-term improvements.

---

## Contributors
- **Ahmed Rekik**
- **Achraf Ben Abdallah**
- **Hani Yousfi**
- **Mayssa Larguech**

---

## Usage
To access the reports and supporting documents:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo-name/audit-report.git
