<!-- Header -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0070F3,100:38BDF8&height=190&section=header&text=Ahmed%20Khater&fontSize=52&fontColor=ffffff&fontAlignY=36&desc=Cloud%20%26%20DevOps%20Engineer%20%C2%B7%20AWS%20Certified%20Solutions%20Architect&descSize=16&descAlignY=58&animation=fadeIn" alt="Ahmed Khater · Cloud & DevOps Engineer" width="100%" />
</p>

<p align="center">
  <a href="https://ahmeddhussain.github.io">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=3291FF&center=true&vCenter=true&width=620&lines=I+build+platforms+that+deploy+themselves.;GitOps+on+EKS+with+ArgoCD+%2B+Argo+Rollouts;Terraform+%C2%B7+Ansible+%C2%B7+Kubernetes+%C2%B7+AWS;Hardening+RHEL+to+CIS+Level+1;Breaking+clusters+on+purpose+to+measure+RTO" alt="Typing intro" />
  </a>
</p>

<p align="center">
  <a href="https://ahmeddhussain.github.io"><img src="https://img.shields.io/badge/🌐_Portfolio-ahmeddhussain.github.io-0070F3?style=for-the-badge&labelColor=0a0a0a" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/ahmed-khater2611"><img src="https://img.shields.io/badge/LinkedIn-ahmed--khater2611-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0a0a0a" alt="LinkedIn" /></a>
  <a href="mailto:ahmedkhater2611@gmail.com"><img src="https://img.shields.io/badge/Email-Get_in_touch-38BDF8?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0a0a0a" alt="Email" /></a>
  <a href="https://instagram.com/ahmeddhussain"><img src="https://img.shields.io/badge/Instagram-ahmeddhussain-E4405F?style=for-the-badge&logo=instagram&logoColor=white&labelColor=0a0a0a" alt="Instagram" /></a>
  <img src="https://img.shields.io/badge/Status-Open_to_work-3291FF?style=for-the-badge&labelColor=0a0a0a" alt="Open to work" />
</p>

---

### 👋 About me

I'm a **Cloud & DevOps Engineer** in Cairo. I write infrastructure as code, deliver it through GitOps, lock it down by default, and **break it on purpose to prove it recovers**.

```yaml
ahmed:
  role:        Cloud & DevOps Engineer
  location:    Cairo, Egypt 🇪🇬
  certified:   [AWS Solutions Architect, AWS Cloud Practitioner]
  trained_at:  NTI Cloud DevOps Accelerator (Hire Ready Initiative)
  interned_at: iVolve Technologies
  education:   B.Sc. Electronics & Communications, Suez Canal University (GPA 3.4)
  building:    [Nexora, Enterprise Linux Lab]
  motto:       "If it isn't in Git, it doesn't exist. If it's never been tested, it doesn't work."
```

---

### 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

#### 🏦 [Nexora: GitOps core-banking platform](https://github.com/Nexora-Banking-App/Nexora-Banking-App)
6 microservices (FastAPI + NGINX) for transfers, accounts, auth and fraud scoring on **EKS** with RDS MySQL and Kafka (Strimzi). The work is split across 6 repos so each CI/CD job only gets the permissions it needs.

- 🔐 GitHub Actions authenticates to AWS through **OIDC** · **Trivy** scanning · **Cosign** image signing
- 🐤 **Argo Rollouts** canary (10 → 50 → 100%) gated on Prometheus metrics
- 🛡️ Istio mTLS · IRSA + External Secrets · default-deny NetworkPolicies
- 📈 Prometheus · Grafana · Loki · Tempo · 12 alerts, each with a runbook
- ⏱️ DR drill: deleted the EKS cluster and rebuilt it in **23m 50s**

`EKS` `Terraform` `ArgoCD` `Istio` `Kafka` `GitHub Actions`

</td>
<td width="50%" valign="top">

#### 🐧 [Enterprise Linux Lab: a company's IT on AWS](https://github.com/ahmeddhussain/Linux-System-Administration)
A complete **RHEL 10** environment for a fictional company. Terraform provisions it, Ansible configures it, and it's destroyed after each session and rebuilt from Git.

- 👤 **FreeIPA** identity: HBAC and sudo rules, SSH keys · WireGuard VPN
- 🌐 Workstations have no direct internet; a **Squid** proxy allows HTTPS only
- 📁 NFSv4 homes and team shares through automount, with quotas and ACLs
- ✅ **OpenSCAP CIS Level 1** on every host · auditd · AIDE · TLS log shipping
- 🧪 **158 automated checks** · patching in rings · restore and incident drills

`RHEL` `FreeIPA` `Ansible` `Terraform` `OpenSCAP` `Squid`

</td>
</tr>
</table>

#### More projects

| Project | What it is | Stack |
|---|---|---|
| 🔁 [**GitOps Pipeline on EKS**](https://github.com/ahmeddhussain/ivolve-GitOps) | A CI/CD platform with no stored credentials for a 3-service app; ArgoCD syncs the cluster on every merge | Actions · ArgoCD · Terraform · ESO |
| 🔧 [**Jenkins CI/CD with security gates**](https://github.com/ahmeddhussain/ivolve-CloudDevOpsProject) | Multi-branch pipelines with SonarQube and Trivy gates, built with Terraform and Ansible, observed with Prometheus, Grafana and Loki | Jenkins · Helm · Ansible · EKS |
| 🛡️ [**Kubernetes Phishing-Sim Lab**](https://github.com/ahmeddhussain/phishing-app-k8s) | Hardened Kubernetes: RBAC, Cilium FQDN egress rules, default-deny policies, HPA | Kubernetes · Cilium |
| 🏗️ [**3-Tier Web App on AWS**](https://github.com/ahmeddhussain/terraform-aws-project) | A three-tier web application provisioned with modular Terraform | Terraform · AWS |
| 🎓 [**NTI Final Project**](https://github.com/ahmeddhussain/nti-final-project) | Capstone of the NTI Cloud DevOps Accelerator: an end-to-end pipeline on AWS | AWS · CI/CD · K8s |
| 📚 [**Jenkins Shared Library**](https://github.com/ahmeddhussain/jenkins-shared-lib) | Reusable Groovy pipeline steps for Jenkins | Jenkins · Groovy |

---

### 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,terraform,ansible,kubernetes,docker,jenkins,githubactions,prometheus,grafana&theme=dark" alt="Cloud and DevOps tools" /><br/>
  <img src="https://skillicons.dev/icons?i=linux,redhat,bash,python,git,nginx,kafka,mysql,fastapi&theme=dark" alt="Systems and code" />
</p>

| Area | Tools |
|---|---|
| ☁️ **Cloud** | AWS: EKS, EC2, VPC, RDS, ECR, ALB, IAM / OIDC / IRSA, Secrets Manager, SSM, S3, CloudWatch |
| 🧱 **IaC & config** | Terraform · CloudFormation · Ansible · Ansible Vault |
| ☸️ **Containers** | Kubernetes · OpenShift · Docker · Podman · Helm · Kustomize |
| 🔁 **Delivery** | GitHub Actions · Jenkins (shared libraries) · ArgoCD · Argo Rollouts |
| 🛡️ **Security** | Trivy · Cosign · SonarQube · Istio mTLS · Cilium · OpenSCAP · FreeIPA |
| 📈 **Observability** | Prometheus · Grafana · Loki · Tempo · OpenTelemetry · CloudWatch |
| 🐧 **Systems** | RHEL / Linux administration · Networking (CCNA) · WireGuard · Squid · NFS · Bash · Python |

---

### 🎓 Certifications & training

<p>
  <img src="https://img.shields.io/badge/AWS_Certified-Solutions_Architect-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white&labelColor=232F3E" alt="AWS Solutions Architect" />
  <img src="https://img.shields.io/badge/AWS_Certified-Cloud_Practitioner-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white&labelColor=232F3E" alt="AWS Cloud Practitioner" />
  <img src="https://img.shields.io/badge/AWS_Academy-Cloud_Foundations-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white&labelColor=232F3E" alt="AWS Academy Cloud Foundations" />
  <img src="https://img.shields.io/badge/AWS_Academy-Cloud_Security_Foundations-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white&labelColor=232F3E" alt="AWS Academy Cloud Security Foundations" />
</p>

- 🚀 **NTI Cloud DevOps Accelerator**, Hire Ready Initiative (2026)
- 💼 **DevOps Intern, iVolve Technologies** (2026)
- 🎓 **B.Sc. Electronics & Communications Engineering**, Suez Canal University (2020 – 2025)
- 📘 Courses: CCNA · MCSA · Virtualization

---

### 📊 GitHub stats

<p align="center">
  <img height="165" src="https://github-readme-stats.shion.dev/api?username=ahmeddhussain&show_icons=true&hide_border=true&bg_color=0a0a0a&title_color=3291ff&icon_color=38bdf8&text_color=ededed&ring_color=0070f3" alt="GitHub stats" />
  <img height="165" src="https://github-readme-stats.shion.dev/api/top-langs/?username=ahmeddhussain&layout=compact&hide_border=true&bg_color=0a0a0a&title_color=3291ff&text_color=ededed" alt="Top languages" />
</p>
<p align="center">
  <img src="https://streak-stats.demolab.com/?user=ahmeddhussain&hide_border=true&background=0a0a0a&ring=0070F3&fire=38BDF8&currStreakNum=EDEDED&sideNums=EDEDED&currStreakLabel=3291FF&sideLabels=A1A1A1&dates=6F6F6F&stroke=262626" alt="GitHub streak" />
</p>

---

<p align="center">
  <b>💬 Ask me about</b> AWS · Terraform · GitOps · Kubernetes · Jenkins · Linux hardening<br/>
  <sub>Looking for a Cloud / DevOps / Platform Engineer? → <a href="https://ahmeddhussain.github.io"><b>ahmeddhussain.github.io</b></a></sub>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:38BDF8,100:0070F3&height=110&section=footer" alt="" width="100%" />
</p>
