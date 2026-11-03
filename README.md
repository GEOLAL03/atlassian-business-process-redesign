# Business Process Redesign and Optimization Using Collaborative Tools: An Atlassian Case Study

![Academic Project](https://img.shields.io/badge/Type-Academic%20Project-1f6feb?style=flat-square) ![BPM](https://img.shields.io/badge/Research-BPM-00875a?style=flat-square) ![Digital Transformation](https://img.shields.io/badge/Focus-Digital%20Transformation-6554c0?style=flat-square)

**University of Patras | Computer Engineering and Informatics (CEID)**<br>
Introduction to Information Systems | Spring Semester 2026 | Academic Year 2025-2026

[Full Academic Report](docs/Report.pdf) · [Project Presentation](docs/Presentation.pdf)

## Project Overview

This academic project investigates how collaborative platforms and the Atlassian ecosystem can support **Business Process Management (BPM)**, business process redesign, operational efficiency, and digital transformation. It connects strategic information-systems concepts with the coordination of people, workflows, and organizational knowledge.

The study combines a literature review, an analysis of collaborative tools, a hypothetical software-development scenario, and a published industrial case study. Porter's Five Forces, Value Chain analysis, and the BPM lifecycle provide the framework for examining how integrated workflows could address fragmented communication, missing requirements, duplicated work, and limited process visibility.

> **Research scope:** This repository contains academic research and case-study analysis. The technologies described were examined in the coursework; their inclusion does not imply that the project authors deployed them. Hypothetical estimates and findings attributed to the published industrial case are identified separately below.

## Table of Contents

- [Project Overview](#project-overview)
- [Research Objectives](#research-objectives)
- [Technologies and Platforms Examined](#technologies-and-platforms-examined)
- [Research Methodology](#research-methodology)
- [Hypothetical Case Study](#hypothetical-case-study)
- [Real-World Case Study](#real-world-case-study)
- [Future Directions](#future-directions)
- [Academic Deliverables](#academic-deliverables)
- [Authors](#authors)
- [Academic Context](#academic-context)
- [Disclaimer](#disclaimer)

## Research Objectives

- Analyze BPM principles and the relationship between process improvement and digital transformation.
- Apply **Porter's Five Forces** and **Value Chain** models to competitive pressures and activities where information systems can add value.
- Evaluate the Atlassian collaborative ecosystem, including its integration opportunities, organizational benefits, and adoption challenges.
- Examine business process redesign through **As-Is** and **To-Be** models.
- Analyze a hypothetical software-development organization alongside the published **ISC Applied Systems** case study.
- Explore AI-driven automation and emerging BPM technologies as directions for further research.

## Technologies and Platforms Examined

The following table summarizes each technology's role **as discussed in the report**. It describes the study's analytical scope, rather than a software stack implemented in this repository.

| Technology or platform | Role examined in the research |
| --- | --- |
| **Jira** | Issue tracking, requirements management, Scrum and Kanban workflows, process visibility, and KPI dashboards. |
| **Confluence** | Knowledge management system (KMS), collaborative wiki, specifications, and documentation linked to Jira issues. |
| **Bitbucket** | Source control, pull requests, code review, and continuous integration and delivery (CI/CD) in the proposed development workflow. |
| **Atlassian Cloud** | SaaS delivery, shared access to collaborative tools, and the organizational implications of cloud adoption. |
| **Jira Automation** | Proposed rules for assignments, notifications, escalations, and workflow transitions. |
| **Jira Service Management** | Service workflows, customer interaction, and support processes. |
| **Zoom / Microsoft Teams** | Communication and meeting integrations considered alongside Jira and Confluence. |
| **Google Meet / Loom** | Additional meeting and asynchronous video tools discussed in the collaboration analysis. |
| **eazyBI** | Requirements-coverage analysis, traceability metrics, and reporting in the ISC Applied Systems case. |
| **Atlassian Intelligence** | AI-assisted knowledge work and automation discussed in the report's future directions. |

The evaluation also considers administration complexity, licensing costs, learning requirements, and vendor dependence. Tool adoption is assessed together with training, clear responsibilities, and organizational change.

*Source: [Report, Sections 3-6](docs/Report.pdf#page=16).*

## Research Methodology

The methodology is theoretical and analytical, combining the following elements:

1. **Literature review:** Examine academic work on information systems, BPM, Agile practices, performance indicators, and digital transformation, together with product documentation cited in the report.
2. **BPM lifecycle:** Organize the analysis around process identification, As-Is analysis, To-Be design, implementation planning, and ongoing monitoring. The implementation stages belong to the scenarios analyzed in the report.
3. **Porter's Five Forces:** Relate competitive rivalry, new entrants, substitutes, customer power, and supplier power to the strategic role of collaborative platforms.
4. **Value Chain analysis:** Identify inefficiencies in primary and support activities, then consider the broader Value Web connecting an organization with its customers, suppliers, and partners.
5. **As-Is and To-Be process modeling:** Compare fragmented workflows with a proposed integrated approach to requirements, documentation, development, testing, and delivery.
6. **Key Performance Indicators (KPIs):** Use the report's estimated before-and-after values to illustrate assessment of the hypothetical redesign, while keeping externally reported industrial findings separate.
7. **Case study analysis:** Connect the hypothetical scenario and the published ISC Applied Systems case to the theoretical framework.

The contribution is a structured synthesis and application of these frameworks. The repository contains no experimental dataset or deployed application. The report identifies a focus on technology/software organizations and proposes broader comparisons and empirical research as future work.

*Sources: [Report, Section 1.3](docs/Report.pdf#page=8), [Chapters 4-5](docs/Report.pdf#page=29), and [Section 7.2](docs/Report.pdf#page=53).*

## Hypothetical Case Study

### Organization and proposed redesign

The scenario concerns a **hypothetical software-development organization with 100-500 employees**. Its initial processes rely on email, Word and Excel documents, in-person meetings, and manual testing. The analysis identifies missing requirements, duplicated effort, delivery delays, fragmented knowledge, and limited visibility into work in progress.

The proposed To-Be process connects Jira issues, Confluence specification pages, refinement meetings, sprint planning, Bitbucket pull requests, automated testing, and completion documentation.

| Process activity | As-Is workflow | Proposed To-Be workflow |
| --- | --- | --- |
| Requirements intake | Requests dispersed across email threads | Jira issues with ownership, status visibility, and notifications |
| Specification and knowledge sharing | Separate Word/Excel documents | Confluence specification pages linked to Jira |
| Coordination and planning | In-person discussions and fragmented follow-up | Integrated refinement meetings and Jira sprint planning |
| Development and testing | Disconnected code review and manual tests | Bitbucket pull requests and CI/CD linked to Jira issues |
| Delivery and organizational learning | Separate delivery and documentation activities | Jira completion status with shared Confluence documentation |

### Estimated KPI outcomes

> **Hypothetical estimates, not experimental results.** Every value below comes from the report's hypothetical case study. These are estimated outcomes used to illustrate the proposed redesign; they are not independently measured results from an implementation by the project authors.

| KPI | As-Is baseline | Estimated To-Be outcome | Estimated improvement reported |
| --- | --- | --- | --- |
| Pre-release defects | 100% of baseline | 45-65% of baseline | 35-55% reduction |
| Early-testing defects | 100% of baseline | 55-60% of baseline | 40-45% reduction |
| Software quality | Reference baseline | Improvement of 50-70% | 50-70% increase |
| Sprint delivery time | 100% of baseline | Approximately 72% of baseline | 28% reduction |
| Rework | 100% of baseline | Approximately 60% of baseline | 40% reduction |
| Meeting time per week | 8.5 hours | 4.2 hours | Approximately 51% reduction |
| Onboarding time | 3 days | Less than 1 day | Approximately 67% reduction, as reported |

**Interpretation:** Percentage baselines are normalized reference values, not defect probabilities or observed sample counts. The software-quality row retains the report's broad metric without assigning it an invented measurement scale. The meeting and onboarding percentages reproduce the report's rounded values; the stated onboarding times imply a reduction greater than two-thirds.

*Sources: [Report, Sections 4.1-4.3](docs/Report.pdf#page=29); KPI table in [Section 4.4, PDF page 37 / printed page 36](docs/Report.pdf#page=37); estimated-value caption on [PDF page 39 / printed page 38](docs/Report.pdf#page=39). [Presentation, slide 22](docs/Presentation.pdf#page=22) summarizes the first three KPI ranges.*

## Real-World Case Study

### ISC Applied Systems

The report analyzes **ISC Applied Systems**, a provider of communication and safety systems for urban transit, working with **Nuum Solutions**. The case concerns requirements management and traceability across customer, system, hardware, software, and test requirements, with a CMMI Level 2 requirements-management objective.

The solution described in the academic report centers on:

- **Jira:** Custom issue types, fields, and links such as `implements` / `implemented by` to connect requirements, changes, tasks, defects, and tests.
- **Confluence:** Internal requirements documentation and Jira-linked information.
- **eazyBI:** Coverage reports identifying linked, unlinked, tested, resolved, and justified requirements.
- **JIRA Misc Custom Fields and Impact for JIRA:** Calculated requirement-status fields, hierarchy analysis, and traceability reporting.

Together, these components support investigation of missing links, visibility into verification status, and more systematic requirements management.

### Findings attributed to the published case

| Finding reproduced in the academic report | Reported outcome |
| --- | --- |
| Requirements-management time | 20% reduction, associated with easier access to requirements information |
| After-the-fact errors | 5-10% reduction, associated with more frequent validation |
| Unlinked hardware requirements | 18% were identified as having no subsystem association and reported as corrected |
| Traceability and process improvement | Coverage reporting and achievement of the CMMI Level 2 requirements-management objective, as described in the report |

**Attribution:** These findings are reproduced from the academic report's account of **Filion et al. (2017)**, its reference [5]. They were not measured or independently reproduced by this student project. In particular, **18% is the share of hardware requirements identified as unlinked**, not a percentage improvement in performance.

Underlying publication cited in the report: Filion, L., Daviot, N., Le Bel, J.-P., & Gagnon, M. (2017). *Using Atlassian Tools for Efficient Requirements Management: An Industrial Case Study*. 2017 Annual IEEE International Systems Conference (SysCon), pp. 1-6. [DOI: 10.1109/SYSCON.2017.7934769](https://doi.org/10.1109/SYSCON.2017.7934769).

*Sources: [Report, Chapter 5](docs/Report.pdf#page=41), including [traceability findings on PDF page 45](docs/Report.pdf#page=45) and [outcomes on PDF page 46](docs/Report.pdf#page=46); [Presentation, slides 24-27](docs/Presentation.pdf#page=24).*

## Future Directions

The report discusses the following possibilities for extending BPM and collaborative work:

| Direction | Potential application examined |
| --- | --- |
| **Artificial Intelligence** | Summarization, knowledge retrieval, documentation assistance, and service support. |
| **Predictive Analytics** | Investigating potential delays, workload patterns, and requirements-coverage gaps. |
| **Process Mining** | Discovering workflows from event logs, checking conformance, and identifying opportunities for improvement. |
| **Intelligent Automation** | Combining workflow rules and AI assistance to reduce repetitive coordination tasks. |
| **Digital Twins of Organizations** | Modeling organizational processes, data, technology, and people to explore proposed changes through simulation. |
| **Low-Code / No-Code BPM** | Enabling users to configure process automation with less custom programming. |

These are research directions and proposed extensions, not completed implementations or a guarantee of current product capabilities. The report also proposes comparative platform evaluation, empirical research in Greek enterprises, and assessment of adoption return on investment.

*Sources: [Report, Chapter 6](docs/Report.pdf#page=49) and [Section 7.2](docs/Report.pdf#page=53).*

## Academic Deliverables

| Document | Contents | Format and language |
| --- | --- | --- |
| [**Full Academic Report**](docs/Report.pdf) | Theoretical framework, platform analysis, both case studies, future directions, and bibliography | PDF, 57 pages, Greek |
| [**Project Presentation**](docs/Presentation.pdf) | Slide-based overview of the research and its case studies | PDF, 38 slides, Greek |

The PDFs preserve the original supplied files byte for byte; only their repository filenames have changed. This README provides an English overview of the Greek-language deliverables.

```text
atlassian-business-process-redesign/
├── README.md
├── .gitignore
└── docs/
    ├── Report.pdf
    └── Presentation.pdf
```

## Authors

- **Georgios Lalas**
- **Leonidas Gkourvelos**
- **Alexandros-Marios Afratis**

## Academic Context

| Field | Details |
| --- | --- |
| University | University of Patras |
| Department | Department of Computer Engineering and Informatics (CEID) |
| Course | Introduction to Information Systems |
| Academic year | 2025-2026 |
| Semester | Spring 2026 |
| Project type | Academic research and case study analysis |

The project was developed as coursework for **Introduction to Information Systems** at the University of Patras. Its focus is the analysis and redesign of business processes through collaborative information systems.

## Disclaimer

This repository documents academic research and analysis. It is **not an official Atlassian project** and is **not affiliated with or endorsed by Atlassian**. Product and organization names belong to their respective owners. Quantitative values should be read within the hypothetical or externally reported case-study context stated above.
