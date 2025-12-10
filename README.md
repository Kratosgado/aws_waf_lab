<!--toc:start-->

- [📄 AWS Well-Architected and CAF Assessment Report](#📄-aws-well-architected-and-caf-assessment-report)
  - [1. Approach and Methodology](#1-approach-and-methodology)
    - [Phase 1: Architecture Review and Risk Identification (Task 1)](#phase-1-architecture-review-and-risk-identification-task-1)
    - [Phase 2: Framework Evaluation (Tasks 2 & 3)](#phase-2-framework-evaluation-tasks-2-3)
    - [Phase 3: Improved Architecture Design (Task 4)](#phase-3-improved-architecture-design-task-4)
  - [2. Repository Contents and Deliverables](#2-repository-contents-and-deliverables)
  - [3. Evaluation Criteria Focus](#3-evaluation-criteria-focus)
  <!--toc:end-->

## 📄 AWS Well-Architected and CAF Assessment Report

This repository contains the deliverables for the lab exercise: **Design and Evaluate an AWS Solution Using the Well-Architected and Cloud Adoption Frameworks**. The objective was to evaluate the migration of a two-tier web application to AWS against industry best practices and propose an optimized, well-architected design.

---

### 1. Approach and Methodology

The project followed a three-phase methodology to ensure the proposed design was robust, secure, and aligned with organizational readiness:

#### Phase 1: Architecture Review and Risk Identification (Task 1)

The initial phase involved analyzing the stated existing two-tier architecture (frontend + backend database). The focus was on identifying inherent risks, such as single points of failure, lack of scalability, and potential security gaps (e.g., open security groups).

#### Phase 2: Framework Evaluation (Tasks 2 & 3)

- **AWS Well-Architected Framework (WAF):** The five pillars (Operational Excellence, Security, Reliability, Performance Efficiency, and Cost Optimization) were applied to structure the technical assessment. This resulted in specific, actionable recommendations and the identification of supporting AWS services.
- **AWS Cloud Adoption Framework (CAF):** The six perspectives (Business, People, Governance, Platform, Security, Operations) were used to evaluate the organization's readiness for the transformation. This informed necessary non-technical enablers, particularly in training and governance.

#### Phase 3: Improved Architecture Design (Task 4)

Based on the comprehensive findings from the WAF and CAF evaluations, a revised, multi-AZ, managed-service-oriented AWS architecture was designed. This design explicitly addresses all identified weaknesses and incorporates key services to meet the criteria for reliability, security, and cost-efficiency.

---

### 2. Repository Contents and Deliverables

The repository contains the following files, which collectively fulfill the submission criteria:

| File Name                   | Description                                                                                                                  | Related Task(s) |
| :-------------------------- | :--------------------------------------------------------------------------------------------------------------------------- | :-------------- |
| `README.md`                 | Explains the project approach and repository structure.                                                                      | N/A             |
| `aws_waf_caf_assessment.md` | The main report containing the completed WAF assessment table (Task 2) and the detailed CAF readiness summary (Task 3).      | Tasks 2 & 3     |
| `diagram.png`               | A visual representation of the improved, Well-Architected, and multi-AZ AWS design (e.g., using ALB, ASG, and RDS Multi-AZ). | Task 4          |

### 3. Evaluation Criteria Focus

The design prioritizes the following criteria, as outlined in the evaluation rubric:

- **Technical Understanding (30%):** Accurate application of WAF pillars (e.g., using RDS Multi-AZ for Reliability) and CAF perspectives (e.g., addressing the People perspective through training).
- **Architecture Design Quality (25%):** The proposed design utilizes managed services and multi-AZ deployments to ensure scalability, security, and high availability.
