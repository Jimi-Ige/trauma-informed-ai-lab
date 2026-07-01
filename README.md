# Trauma Informed AI Lab

Open-source research infrastructure for trauma-informed AI in health and social services.

TIAIL is the research program of [Nest and Rise, Inc.](https://tiail.org), a 501(c)(3) nonprofit based in Baltimore, MD. This repository holds the lab's public artifacts as they are released: governance frameworks, evaluation rubrics, model benchmarks, and reference implementations for use by nonprofits, public agencies, and researchers.

The work is public by design.

## What lives here today

- [Ethical AI principles](EthicalAIPrinciples.md). The foundational commitments guiding TIAIL's research and engineering decisions.
- [Contributing guide](CONTRIBUTING.md). How to participate as a developer, ethicist, clinician, privacy practitioner, or contributor with lived experience of the systems we study.

## What we are working toward

- Institutional review protocols and deployment criteria for AI in regulated care settings.
- Evaluation rubrics calibrated to clinical and human services settings, including a retraumatization risk scoring protocol.
- Model benchmarks for trauma-informed performance on intake, triage, and case management tasks.
- Open-source toolkits and documentation frameworks for Medicaid, HUD, and grant compliance.

## Governance and Standards

Trauma Informed AI Lab (TIAL) develops governance frameworks and evaluation tools grounded in established
standards and adapted for the specific risks of AI systems serving vulnerable
populations in healthcare and social services. The work is governance research
first: the social mission is delivered through controls, evidence, and
auditable design, not sentiment.

### Framework Alignment

**NIST AI RMF**
The Govern, Map, Measure, and Manage functions applied to AI systems serving
vulnerable populations. Govern establishes accountability for systems affecting
people with limited recourse; Map identifies context-specific harms before
deployment; Measure defines fairness and safety metrics for the population
served; Manage operationalizes monitoring and intervention thresholds.

**ISO 42001 (in progress)**
AI Management System design adapted for healthcare and social services contexts,
where the operating environment includes protected health information, eligibility
determinations, and populations who cannot easily contest an automated decision.

**Trauma-Informed Design Principles**
Safety, trustworthiness, peer support, collaboration, empowerment, and cultural
sensitivity embedded as governance requirements rather than afterthoughts. Each
principle maps to a concrete control: trustworthiness to explainability,
empowerment to human-in-the-loop and contestability, safety to harm monitoring
and intervention thresholds.

### Risk Focus Areas

- **Bias and fairness in eligibility decisions** — AI systems that influence
  access to housing, healthcare, and social services can produce disparate impact
  on the populations least able to challenge it. We define fairness metrics and
  disparate-impact monitoring before deployment, not after harm.
- **Data privacy and consent for populations with limited agency** — consent
  frameworks designed for users who may face cognitive, legal, language, or
  power-asymmetry barriers to meaningful consent.
- **Human-in-the-loop controls for high-stakes decisions** — required human
  review at every decision point where the consequence of an error is material
  to a person's safety, benefits, or care.
- **Auditability and explainability for publicly funded AI** — systems funded by
  public dollars must be reconstructable and explainable to a non-technical
  oversight body, not only to engineers.

### Standards and Regulatory Context

- **HIPAA** — Privacy and Security Rule requirements for AI systems that process,
  store, or route protected health information, including minimum-necessary access
  and audit controls for agentic components.
- **Federal procurement AI governance** — transparency, oversight, and documentation
  requirements for AI used in publicly funded programs.
- **State-level AI regulation** — emerging frameworks governing automated decision
  systems in benefits, healthcare, and consumer contexts.

---

Feedback and collaboration welcome.
[jimiige.com](https://jimiige.com) | [LinkedIn](https://linkedin.com/in/jimi-ige)

## Get involved

- Site: https://tiail.org
- Volunteer: https://forms.cloud.microsoft/r/xCedQ68MdC
- Discord: https://discord.com/invite/9vfjCa8Usj
- Newsletter: https://substack.com/@nestandrise
- Donate: https://givebutter.com/InnovationFund

## License

MIT. See [LICENSE](LICENSE).
