# Hi, I'm DeJurnett 👋

### IAM Engineer in the making. I build identity labs end to end, break them, and write down how I fixed them.

Over 12 weeks I built a hands on IAM portfolio across Okta, SailPoint IdentityIQ, Microsoft Entra ID, and CyberArk. Every project has a working build, real screenshots from start to finish, and a Snags section where I explain what went wrong, which layer it lived in, and how I proved the fix.

The part I care about most is the troubleshooting. Anyone can follow an install guide. The useful skill is finding out why something that looks healthy is not actually working.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-DeJurnett_Norrington-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dejurnett-norrington/)

---

## Projects

The full identity lifecycle, in the order I built it: log in, join, move, leave, lock down, automate, measure, govern, and protect the master keys.

| Project | What it proves | Stack |
|---|---|---|
| [**Okta SSO and Lifecycle Management**](https://github.com/GokuCooper/okta_sso_lifecycle_management) | Three apps on one login over SAML, OIDC, and SCIM, with group membership driven by department | Okta |
| [**SailPoint HR Source and Aggregation**](https://github.com/GokuCooper/sailpoint_iiq_hr_source_aggregation) | An HR file as the source of truth, with correlation and manager relationships | SailPoint IdentityIQ 8.3 |
| [**SailPoint Joiner and Leaver Automation**](https://github.com/GokuCooper/sailpoint_iiq_jml_workflows) | Hire to live account in 4 min 25 sec and termination to disabled in 3 min 22 sec, zero manual steps | SailPoint IdentityIQ, MySQL, BeanShell |
| [**Entra ID Conditional Access and Zero Trust**](https://github.com/GokuCooper/entra_conditional_access_zero_trust) | Four Conditional Access policies, a break glass account, and just in time admin with PIM | Microsoft Entra ID P2 |
| [**PowerShell for IAM Automation**](https://github.com/GokuCooper/powershell_iam_automation) | Bulk joiners, stale account reports, group access audits, and a break glass sign in alarm | PowerShell, Microsoft Graph |
| [**Microsoft Graph Inactive Account Report**](https://github.com/GokuCooper/msgraph_inactive_user_report) | An app registration with read only access that finds inactive accounts and routes them to managers | Python, Microsoft Graph |
| [**IAM Metrics Dashboard**](https://github.com/GokuCooper/iam_metrics_dashboard) | Six identity health KPIs across two platforms, with a before and after remediation run | Python, Entra ID, Okta API |
| [**SailPoint Access Governance**](https://github.com/GokuCooper/sailpoint_iiq_access_governance) | A 10 role RBAC model, SoD rules, and a manager certification that took violations from 3 to 0 | SailPoint IdentityIQ 8.3 |
| [**CyberArk PAM for a Tier 0 Domain Admin**](https://github.com/GokuCooper/cyberark_pam_tier0_privileged_access) | A Domain Admin password nobody knows, used only through a recorded session, reviewed by a separate auditor | CyberArk PAM 12.6, Active Directory |

---

## How I work

- **Verify, don't trust the screen.** I confirm changes with PowerShell, logs, or a second system before calling something done.
- **Name the layer first.** Network, DNS, OS, policy, application, or licensing. Fixing the wrong layer wastes the most time.
- **Make the smallest change that solves the problem.** One platform exception instead of a company wide setting. One scoped override instead of turning a safety off.
- **Leave evidence.** Numbered screenshots and exported reports, so anyone can check my work.

## Tools

**Identity platforms:** Okta, SailPoint IdentityIQ, Microsoft Entra ID, CyberArk PAM, Active Directory
**Protocols and concepts:** SAML, OIDC, OAuth 2.0, SCIM, MFA, Conditional Access, PIM, RBAC, SoD, access certification, JML
**Automation:** PowerShell, Python, Microsoft Graph, Okta API, REST
**Infrastructure:** Windows Server, VMware Workstation, MySQL, Apache Tomcat, IIS
**Security tooling:** gitleaks

---

Every project in this portfolio was scanned for secrets with gitleaks before I published this page. All names and accounts in my labs are test data.
