# Benson OgheneOchuko
> Systems Administrator | Backend Engineering Background | Lagos, Nigeria

I manage server infrastructure, enforce security policies, and maintain system reliability across Linux and Windows environments. My work focuses on standardizing server configurations to minimize downtime, ensure strict security compliance, and provide clear audit logs for IT operations.

> Contact: Ob.ogheneOchuko@gmail.com | LinkedIn: [Ochuko](https://www.linkedin.com/in/ogheneochukobenson/)
---

### :: Core Focus
+ **System Standardization:** Enforcing consistent OS configurations and IaC across environments to eliminate configuration drift and prevent production incidents.
+ **Security & Compliance:** Translating security policies into applied system rules and generating tamper-evident audit trails for incident investigation.
+ **Observability:** Implementing structured logging and metrics collection to detect and resolve system anomalies before they impact operations.
+ **Disaster Recovery:** (Currently building a project focused on data redundancy, routine backups, and fast-restore protocols).

### :: Technical Stack
| Category | Technologies |
| :--- | :--- |
| **OS & Admin** | Linux, Windows Server, systemd, SSH, bash/PowerShell |
| **Infrastructure Management** | Terraform, Ansible, Make |
| **Networking & Routing** | Caddy, Nginx, DNS routing, TCP/IP |
| **Cloud Platforms** | GCP, AWS |
| **Observability** | Prometheus, Grafana, Structured JSON Logging |
| **Languages** | Go, Python, Bash, PowerShell |

---

### :: Featured Projects

**[1] Cross-Platform System Hardening Toolkit**
A policy-driven rule engine written in Bash and PowerShell that enforces system security against a central JSON configuration file. 
* Validates `sshd_config`, executes atomic rule replacements, and strictly enforces state compliance.
* Manages user lifecycles and requires group-based authorization for any system-modifying operations.
* Generates dual audit trails: an operational log for routine monitoring and a timestamped forensic log co-located with config backups.

**[2] Infrastructure-as-Code Standardization**
A standardized provisioning system designed to maintain exact parity between staging and production environments.
* Built modular Terraform configurations for GCP/AWS compute, PostgreSQL, and S3 object storage.
* Applied fail-fast input validation at the infrastructure layer to reject malformed configurations prior to resource creation.

**[3] Server Provisioning Pipeline**
A provisioning orchestrator built in Go that generates Terraform state from configuration payloads.
* Configured asynchronous Slack webhook alerts for immediate deployment tracking and incident response.
* Utilizes Ansible for consistent post-provisioning package installation and user creation.

---
> Contact: Ob.ogheneOchuko@gmail.com | LinkedIn: [Ochuko](https://www.linkedin.com/in/ogheneochukobenson/)
