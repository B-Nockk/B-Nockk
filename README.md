# Benson OgheneOchuko
> DevOps Engineer | Infrastructure Automation & Reliability | Lagos, Nigeria

I build cloud infrastructure that stays up on its own and doesn't need babysitting. My focus is on zero-touch provisioning, GitOps-driven deployments, and engineering resilient systems that handle scale without inflating cloud costs. I treat infrastructure as code to eliminate configuration drift, safeguard against human error, and ensure developers can ship code seamlessly.

---

### :: Core Focus
+ **Infrastructure as Code & GitOps:** Automating environments end-to-end to maintain exact parity across stages and prevent unauthorized drift.
+ **CI/CD & Code Delivery:** Designing safety-gated pipelines that ship code reliably with zero downtime, including mandatory confirmation gates for destructive actions.
+ **Container Orchestration:** Deploying, securing, and managing highly available microservices on Kubernetes.
+ **Observability & Security:** Implementing default-deny network policies and host-level telemetry to catch anomalies before they impact production.

### :: Technical Stack
| Category | Technologies |
| :--- | :--- |
| **Cloud & Orchestration** | AWS (EC2, S3, Route 53), Kubernetes (K3s), Docker |
| **IaC & CI/CD** | Terraform (HCL), Ansible, GitHub Actions, ArgoCD |
| **Networking & Security** | TLS (Let's Encrypt), UFW, seccomp, default-deny NetworkPolicies |
| **Observability** | Prometheus, Grafana, Node Exporter, JSON Logging |
| **Languages & DB** | Go, Python, Bash, PostgreSQL |

---

### :: Featured Projects

**[1] Phoenix TaskApp: GitOps-Driven Kubernetes Cluster**
A complete CI/CD and infrastructure pipeline for a containerized microservice application.
* Provisioned a 3-node high-availability Kubernetes (K3s) cluster on AWS using Terraform and Ansible.
* Built a GitHub Actions pipeline triggering ArgoCD for zero-touch deployments, enabling zero-downtime rolling updates.
* Optimized instance sizing to sustain ~375 req/sec (51,614 requests at 100% success) on a minimal t3.small server.

**[2] Bare-Metal Observability & Resource Tuning**
A lightweight, high-fidelity monitoring setup designed for resource-constrained servers.
* Cut idle server memory consumption by over 60% by stripping non-essential background daemons.
* Deployed Prometheus and Grafana directly to the host OS to avoid container runtime overhead.
* Engineered a custom Go service to expose kernel-level `auditd` logs as Prometheus metrics without heavy log-aggregation agents.

**[3] Linux System Hardening & Auditing Toolkit**
A Linux-native hardening toolkit built in Bash that validates and enforces OS security policies from a central JSON configuration file. 
* Validates `sshd_config`, executes atomic rule replacements, and strictly enforces state compliance.
* Manages user lifecycles and requires group-based authorization for any system-modifying operations.
* Generates dual audit trails: an operational log for routine monitoring and a timestamped forensic log co-located with config backups.

---
> Contact: ob.ogheneochuko@gmail.com | LinkedIn: [Benson OgheneOchuko](https://linkedin.com/in/B-Nockk) | GitHub: [@B-Nockk](https://github.com/B-Nockk)
