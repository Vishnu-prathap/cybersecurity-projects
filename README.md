# Cybersecurity Projects

> A growing portfolio of self-directed cybersecurity projects spanning Governance, Risk & Compliance (GRC), Security Operations (SOC), and IT Auditing.

[![NIST CSF](https://img.shields.io/badge/Framework-NIST%20CSF%20v1.1-1F4E79)](https://www.nist.gov/cyberframework)
[![Status](https://img.shields.io/badge/Status-Active-success)]()
[![Last Updated](https://img.shields.io/badge/Last%20Updated-May%202026-blue)]()

---

## About This Repository

I'm a cybersecurity student building a public record of my learning through realistic, scenario-based projects. Each project in this repository is designed to mirror the kind of work performed by entry-level GRC analysts, SOC analysts, and IT auditors. Where a project uses a fictional company, that is stated clearly — the goal is to demonstrate **methodology and deliverable quality**, not to claim real-world engagements.

Everything here is **my own work**, written from scratch, and aligned to recognized industry frameworks (NIST CSF, NIST 800-53, CIS Controls, ISO 27001) so that the artifacts resemble those produced in actual professional practice.

---

## About Me

I'm a first-year cybersecurity student focused on building practical, document-driven skills in risk assessment, security policy, and compliance. My interests sit at the intersection of **technical security** and **governance** — understanding not just how attacks work, but how organizations measure, prioritize, and respond to risk.

**Areas I'm actively developing:**
- Risk assessment methodologies (qualitative and quantitative)
- Control framework mapping (NIST CSF, ISO 27001, CIS Controls)
- Security policy and procedure writing
- SOC analyst workflows (detection engineering, incident triage)
- IT general controls (ITGC) auditing

**Currently learning:** Splunk fundamentals, Sigma rule writing, and the FTC Safeguards Rule.

---

## Projects

### 1. Cybersecurity Risk Assessment — Harbor & Finch CPAs

A full risk assessment for a fictional 28-person public accounting firm handling sensitive client financial data. Demonstrates an end-to-end GRC analyst workflow from scoping through treatment recommendations.

**What's in it:**
- Executive summary written for non-technical leadership
- Documented scoping decisions and 5×5 likelihood-impact methodology
- Ten identified risks scored, ranked, and plotted on a heatmap
- Each risk mapped to specific NIST CSF subcategories (e.g., PR.AC-1, DE.CM-7)
- Recommended controls with effort estimates and a 30 / 90 / 180-day treatment roadmap
- Regulatory analysis covering IRS Publication 4557, FTC Safeguards Rule (GLBA), and SOX exposure

**Framework:** NIST Cybersecurity Framework v1.1
**Deliverables:** Word document (`.docx`), LaTeX source (`.tex`), compiled PDF
**Skills demonstrated:** Risk identification, qualitative risk analysis, control mapping, regulatory awareness, executive-ready report writing

📂 [`/01-risk-assessment-harbor-finch/`](./01-risk-assessment-harbor-finch/)

---

### 2. *[Coming soon]* SOC Detection Rule & Incident Response Runbook

A Sigma detection rule for a specific attack technique paired with a one-page analyst runbook covering triage, investigation, and escalation steps.

**Planned framework:** MITRE ATT&CK
**Planned deliverables:** Sigma rule (`.yml`), Markdown runbook

---

### 3. *[Coming soon]* CIS Controls Mini Audit

A self-audit of a personal Windows or Linux endpoint against 10–15 CIS Controls v8 safeguards, documenting findings (pass/fail/partial) with evidence and recommendations.

**Planned framework:** CIS Controls v8 (Implementation Group 1)
**Planned deliverables:** Audit workpaper, findings report

---

## Repository Structure

```
cybersecurity-projects/
├── README.md                              ← you are here
├── 01-risk-assessment-harbor-finch/
│   ├── README.md                          ← project-specific notes
│   ├── Harbor_Finch_CPAs_Risk_Assessment.docx
│   ├── risk_assessment.tex
│   └── risk_assessment.pdf
├── 02-soc-detection-runbook/              ← coming soon
└── 03-cis-controls-audit/                 ← coming soon
```

---

## How I Approach These Projects

Every project follows the same discipline:

1. **Scope it like a real engagement.** Define what's in and out of scope before any analysis.
2. **Pick a real framework.** Map findings, controls, or detections to a recognized standard so the work is portable.
3. **Produce a real deliverable.** Each project ends in a document, rule, or report that a hiring manager could open and evaluate in under five minutes.
4. **Document my reasoning.** Methodology sections explain *why* I scored or chose something, not just *what* I concluded.
5. **Be honest about scope.** Fictional scenarios are labeled as such. The skill being demonstrated is the methodology, not a fabricated engagement.

---

## Frameworks & Standards Referenced

- **NIST Cybersecurity Framework v1.1** — risk management and control mapping
- **NIST SP 800-61** — incident response planning
- **CIS Controls v8** — endpoint and operational security
- **ISO/IEC 27001** — information security management systems
- **FTC Safeguards Rule (GLBA)** — financial-services data protection
- **IRS Publication 4557** — taxpayer data safeguards
- **MITRE ATT&CK** — adversary tactics and techniques

---

## Contact

If you're a recruiter, hiring manager, or fellow student and want to discuss any of these projects, feel free to reach out:

- **GitHub:** [Vishnu-prathap](https://github.com/Vishnu-prathap)
- **LinkedIn:** [linkedin.com/in/vishnu-prathap]((https://www.linkedin.com/in/vishnu-prathap-jrvp-43a775383/))
- **Email:** vishnu.prathapjrvp@gmail.com

---

## License

The documentation and reports in this repository are released under the [MIT License](LICENSE) for educational and portfolio purposes. Fictional company names, scenarios, and data are entirely my own invention; any resemblance to real organizations is coincidental.

---

*Last updated: May 2026*
