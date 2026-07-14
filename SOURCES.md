# Resume Source of Truth — Tan Wei Jie

> This file is the SINGLE GROUND TRUTH for the resume website. Every claim on the
> public site must be traceable to a fact in this file. Do NOT invent facts,
> metrics, dates, or links that are not here.

---

## PUBLIC-SAFE vs INTERNAL-ONLY

**INTERNAL-ONLY — MUST NOT appear on the public site:**
- Internal Jira ticket IDs (SRE-xxxx), jira.geotab.com / atlassian.net links
- Internal Google Docs / Chat / Superset / Grafana URLs
- Performance ratings (P3), manager names, employee IDs (WTANX01)
- Any confidential Geotab infrastructure detail (server names like myapp292, customer names like Brinks/JB Hunt)

Translate internal achievements into outcome-focused, public-safe bullets.

---

## IDENTITY

- Display name on site heading: **Tan Wei Jie** (nickname "WJ")
- Title: **Senior Site Reliability Engineer**
- Location: Singapore
- Experience: 12+ years in IT (SRE / DevOps focus)

### Contact
- Email: tanweijie89@gmail.com
- LinkedIn: https://www.linkedin.com/in/tan-wei-jie-26a02167/
- GitHub: https://github.com/zshrine

---

## SUMMARY (from pre-Geotab resume, still accurate framing)

Seasoned Site Reliability / DevOps Engineer with 12+ years in IT. Witnessed the
evolution from monolithic on-prem deployments to stateless microservices in the
cloud, and the shift from licensed software to SaaS. Focus on reliability,
availability, and scalability of complex systems. Strong in research/POCs to
improve performance and stability, building robust CI/CD pipelines, and
optimizing operational processes. Fast learner in dynamic environments.

---

## EXPERIENCE (verified across all sources)

### Geotab — Senior Site Reliability Engineer (Dec 2025 – Present)
Source: 2025 Dayforce workbook, job assignment "Senior Site Reliability Engineering",
manager review closed 17/12/2025. Team: SRE Data Delivery Services (DDS), Singapore.
Promoted from SRE to Senior SRE in Dec 2025.

### Geotab — Site Reliability Engineer (2024 – Dec 2025)
Source: 2024 Dayforce workbook, job assignment "Site Reliability Engineering",
period 01/01/2024 – 31/12/2024, described as "first year". DDS SRE team, Singapore.
Actual start date: Nov 2023 (confirmed by candidate).

**Geotab achievements (both years combined, public-safe framing):**

- **Global SME for the Prometheus monitoring stack** (Prometheus, Alertmanager,
  Grafana) — recognized as the key subject-matter expert on the global SRE team.
- **Secondary SME for Registry & Reverse Proxy** — expert-level knowledge, guiding
  teammates; drove post-incident monitoring improvements, a deployment review
  process, and new registry/login-page alarms.
- **Migrated the alerting platform from a legacy stack (SMA/BigQuery) to Prometheus**;
  authored the migration guide and the alarm-creation documentation used by the team.
- **Resolved high-impact alerting defects:** eliminated duplicate GetVersion alerts;
  fixed a bug where new-server alerts fired ~4 hours late; built provisioning-aware
  GetVersion alerts that correctly handle newly provisioned machines (received team kudos).
- **CUJ/SLO program (MyGeotab):** helped define Critical User Journeys, SLIs and SLOs;
  co-built the main CUJ dashboard; delivered quarterly SLO reviews.
- **Problem management: improved process adherence to 100% in Q3, up from 65%** the
  prior quarter.
- **Pioneered AI tooling for the SRE team** — built a NotebookLM-based troubleshooting
  knowledge base and a Gemini-based assistant for weekly handover reports; trained
  the team and promoted AI adoption beyond SRE.
- Built an **SLA uptime dashboard** (Grafana + Superset + BigQuery), custom alert
  routes to notify the CS team for VIP databases, a maintenance-window view that
  reconciles against Alertmanager silences, and data-cleanup automation for
  maintenance records.
- **On-call incident lead:** drove cross-team recovery, coordinated L3 teams (dev,
  DBA, CAE), and championed customer-impact-first incident response.
- Reduced alert noise / false positives by rewriting alarm rules and standardizing
  exclusion logic; cut the number of silences required.

**Geotab role-based competencies (from promotion justification):**
MyGeotab architecture (monolith, HAM, HAM v2, split-app), GitOps + rollbacks,
Unleash feature flags, GCP, Prometheus stack (SME), automation/toil reduction,
incident management, troubleshooting/RCA (assisting L3), SLO/SLI/SLA & CUJ design,
capacity planning / cost management, Terraform (working knowledge), documentation.

---

### Merquri Pte Ltd — Site Reliability / DevOps Engineer (Sept 2021 – 2023)
Source: pre-Geotab resume.
- Part of DevOps team; primary role SRE — set up monitoring and alarms for apps/middleware.
- Worked mainly on Prometheus, Grafana, CloudWatch; troubleshot via dashboards/metrics.
- Log centralisation with Fluent Bit + AWS Elasticsearch (OpenSearch); wrote filters
  and ISM (index state management) policies.
- Troubleshot pod/node failures and application performance irregularities.
- Wrote a Lambda for cross-account logging.
- Set up APM using Apache SkyWalking.
- Also (work milestones): designed workflow for centralised Alertmanager; set up
  observability tooling across environments (kube-prometheus-stack, Fluent Bit);
  built a new production AWS account — VPC/CIDR/route tables/VPC peering, EC2 launch
  templates, EKS, MSK, Redis; installed cluster tooling via Helm (kube-prometheus-stack,
  cert-manager, etc).

### Toppan Ecquaria Pte Ltd — Senior Product / DevOps Engineer (Feb 2018 – Sept 2021)
Source: pre-Geotab resume.
- Enhanced the core Ecquaria product; supported multiple client projects.
- Researched and adopted new tools/tech into the product framework.
- Set up Docker Swarm and deployed microservices frameworks for multiple projects.
- Built CI/CD pipelines (Jenkins, SonarQube, Nexus Repository) tailored per project.
- Developed/executed automated tests on Katalon; set up centralised Dependency-Track.
- Deployed Tyk API gateway (HA clustering) for various projects.
- Led an overseas training programme in Brunei to train clients on company products;
  internal product-training speaker.
- Docker CIS-benchmark hardening; pen-testing with OWASP ZAP DAST and IBM AppScan.
- Built and maintained custom Docker images (ELK, Glowroot, etc).
- Load testing with JMeter; ELK implementations per project.
- Built SSO using SAML/OIDC with ADFS / Azure AD as IdP.
- Upgraded integrated OSS/commercial tools: Elastic Stack, Glowroot, Nexus Repository,
  Dependency-Check/Track. Set up Selenium Grid.

### NCS Pte Ltd — Senior Consultant (2015 – Feb 2018)
Source: pre-Geotab resume.
- Team lead for the ICA technical-refresh programme (web + batch apps).
- Upgrades: WebLogic 8→10, JDK 1.4→1.6, RSA server; migrated CVS from Borland
  StarTeam to GitLab.
- Lead developer for the SG50 birth registration & birth-certificate implementation.
- Led a team of 3–4 developers; managed project scope, effort/budget quotation,
  and delivery timelines; supported users during major incidents.

### NCS Pte Ltd — Consultant (2013 – 2015)
- Gathered requirements, translated tech specs into business solutions.
- Lead developer for major enhancements; guided new team members.

### NCS Pte Ltd — Associate Consultant (2011 – 2013)
- System enhancements and bug fixes; daily batch-job monitoring and recovery;
  data patching and user support.

---

## SKILLS (merged pre-Geotab + Geotab, deduped)

### Observability & Monitoring
Prometheus (SME/expert), Alertmanager, Grafana, Blackbox exporter, PromQL,
Elastic Stack / Elastic APM, Apache SkyWalking, Glowroot, cAdvisor, node_exporter,
Fluent Bit, AWS CloudWatch, Superset, BigQuery (analytics/alerting).

### Cloud & Infrastructure
GCP (Geotab), AWS (EKS, OpenSearch, ElastiCache, CloudWatch, Lambda, MSK, VPC/networking),
Kubernetes, Helm, Docker (build, Swarm, CIS hardening), Terraform, Pulumi.

### SRE / Reliability practice
Incident management & on-call leadership, problem management, SLO/SLI/SLA & CUJ design,
capacity planning & cost management, GitOps + rollbacks, Unleash feature flags,
toil reduction / automation, root-cause analysis.

### CI/CD & Quality
Jenkins, GitLab CI, SonarQube, Nexus Repository, OWASP Dependency-Check/Track,
CoreOS Clair, OWASP ZAP, IBM AppScan, Selenium Grid, Katalon, JMeter.

### Programming & Data
Java / J2EE, JavaScript, Groovy, Bash shell scripting, Python (working),
Oracle PL/SQL, MySQL, MongoDB, Redis, Kafka.

### Security / Identity
SSO with SAML & OIDC, ADFS, Azure AD, HashiCorp Vault (novice), CyberArk Conjur (novice).

### AI / Tooling (Geotab)
NotebookLM, Gemini, prompt engineering — applied to SRE troubleshooting & handover automation.

---

## EDUCATION
- Murdoch University — Degree in IT Management (2012 – 2013)
- Singapore Polytechnic — Diploma in Information Technology (2006 – 2009)
- Deyi Secondary School — GCE O Level (2002 – 2005)

## INTERESTS
Rock climbing, diving.

---

## CAREER DIRECTION (from workbooks, for optional "About/Goals" framing)
Progression: SRE → Senior SRE (achieved Dec 2025) → aiming toward Tech Lead / leading
large-scale technical solutions. Focus areas: expanding SME breadth, automation/toil
reduction, and Kubernetes-native monitoring as fleet moves to HAM v2.
