# Lab 2 Submission

## Task 1 - Git Object Model Exploration

### Commands Used:
- `git cat-file -p <blob_hash>` (4db373667a50f14a411bb5c7e879690fd08aacc1) - Shows file content
- `git cat-file -p <tree_hash>` (a10335e640753b2ad0258ad6a113e695ec4cf95e) - Shows directory structure
- `git cat-file -p <commit_hash>` (9815971) - Shows commit metadata

### Outputs:
1) # 🚀 DevOps Introduction Course: Principles, Practices & Tooling

[![Labs](https://img.shields.io/badge/Labs-80%25-blue)](#-lab-based-learning-experience)
[![Exam](https://img.shields.io/badge/Exam-20%25-orange)](#-evaluation-framework)
[![Hands-On](https://img.shields.io/badge/Focus-Hands--On%20Labs-success)](#-lab-based-learning-experience)
[![Level](https://img.shields.io/badge/Level-Bachelor-lightgrey)](#-course-roadmap)

Welcome to the **DevOps Introduction Course**, where you will gain a **solid foundation in DevOps principles and practical skills**.  
This course is designed to provide a comprehensive understanding of DevOps and its key components.  

Through **hands-on labs and lectures**, you’ll explore version control, software distribution, CI/CD, containerization, cloud computing, and beyond — the same workflows used by modern engineering teams.

---

## 📚 Course Roadmap

Practical modules designed for incremental skill development:

| #  | Module                              | Key Topics & Technologies                                                                                                 |
|----|-------------------------------------|--------------------------------------------------------------------------------------------------------------------------|
| 1  | **Introduction to DevOps**          | Core principles, essential tools, DevOps concepts                                                                        |
| 2  | **Version Control**                 | Collaborative development workflows, Git tooling                                                                         |
| 3  | **CI/CD**                           | Continuous integration/deployment practices                                                                              |
| 4  | **Networking & OS for DevOps**      | IP/DNS, firewalls, Linux fundamentals (shell/systemd/logs), permissions, troubleshooting, DevOps-friendly distros        |
| 5  | **Virtualization**                  | Virtualization concepts, benefits in modern IT infrastructures                                                           |
| 6  | **Containers**                      | Docker containerization, Kubernetes orchestration                                                                        |
| 7  | **GitOps & Progressive Delivery**   | Git as source of truth, Argo CD, canary/blue-green deployments, feature flags, rollbacks                                |
| 8  | **SRE & Resilience**                | SLOs/SLAs/SLIs, error budgets, incident management, chaos engineering, postmortems                                       |
| 9  | **Security in DevOps (DevSecOps)**  | Shift-left security, SAST/DAST, SBOM, container/image scanning (Trivy/Snyk), secret management                           |
| 10 | **Cloud Fundamentals**              | AWS/Azure/GCP basics, IaaS/PaaS/SaaS, regions/zones, pricing, core services (EC2/S3/IAM/VPC), cloud-native patterns      |
| 11 | **Bonus**                           | Web3 Infrastructure, decentralized storage, IPFS, Fleek                                                                 |

---

## 🖼 Module Flow Diagram

```mermaid
flowchart TD
    A[Intro to DevOps] --> B[Version Control]
    B --> C[CI/CD]
    C --> D[Networking & OS]
    D --> E[Virtualization]
    E --> F[Containers]
    F --> G[GitOps & Progressive Delivery]
    G --> H[SRE & Resilience]
    H --> I[Security in DevOps]
    I --> J[Cloud Fundamentals]
    J --> K[Bonus: Web3 Infrastructure]
````

---

## 🛠 Lab-Based Learning Experience

**80% of your grade comes from hands-on labs** — each designed to build real-world skills:

1. **Lab Structure**

   * Task-oriented challenges with clear objectives
   * Safe environments using containers or local VMs

2. **Submission Workflow**

   * Fork course repository → Create lab branch → Complete tasks
   * Push to fork → Open Pull Request → Receive feedback & evaluation

3. **Grading Advantage**

   * **Perfect Lab Submissions (10/10)**: Exam exemption + bonus points
   * **On-Time Submissions (≥6/10)**: Guaranteed pass (C or higher)
   * **Late Submissions**: Maximum 6/10

---

## 📊 Evaluation Framework

*Transparent assessment for skill validation*

### Grade Composition

* Labs (10 × 8 points each): **80%**
* Final Exam (comprehensive): **20%**

### Performance Tiers

* **A (90-100)**: Mastery of core concepts, innovative solutions
* **B (75-89)**: Consistent completion, minor improvements needed
* **C (60-74)**: Basic competency, needs reinforcement
* **D (0-59)**: Fundamental gaps, re-attempt required

---

## ✅ Success Path

> *"Complete all labs with ≥6/10 to pass. Perfect lab submissions grant exam exemption and bonus points toward an A."*

---
2) 100644 blob b1f8af089a94f160ce00ed7710f07a7e9ba6c584    lab1.md
100644 blob 1468ba02d6bcacd3fee5fd378cc02717a8cb2fbc    lab2.md
100644 blob 411667d52f3cf22d20c521bf8703398134ce3d73    object-test.txt
3) tree 9058b84d819ee9fa97a5261d0560c31098861cbf
parent 9d0dbf71bf8942b39f857cb5c1714658d4ec2fa0
author Ivan Ilyichev <i.ilyichev@innopolis.university> 1757758944 +0300
committer Ivan Ilyichev <i.ilyichev@innopolis.university> 1757758944 +0300
gpgsig -----BEGIN SSH SIGNATURE-----
 U1NIU0lHAAAAAQAAADMAAAALc3NoLWVkMjU1MTkAAAAgxG9OJKNqhDWFRHA0IEFb07k4Zj
 8nyjRk1OaI1ul2yZ0AAAADZ2l0AAAAAAAAAAZzaGE1MTIAAABTAAAAC3NzaC1lZDI1NTE5
 AAAAQFOAjuqDyg7bE1hGc7xBlans35k3OhJmgj5bpbPD2pt30Xc6hTYI1FdKzrqr+J2e5j
 XbtVOHlqtLtyW47Yk6Pgs=
 -----END SSH SIGNATURE-----

feat: add second line to obejct test


### Explanation:
- **Blob**: Stores the actual file content as a binary object
- **Tree**: Represents a directory structure, listing files and subdirectories with their permissions and object hashes
- **Commit**: Contains metadata about the commit including author, date, message, and references to tree and parent commits