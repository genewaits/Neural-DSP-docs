# Information Architecture: Redesigning Neural DSP Documentation

This document explains the rationale behind the structural overhaul of the official Archetype: Gojira X user manual. The goal was to transform a monolithic PDF document into a modern, modular, and task-oriented documentation site.

---

## 1. The Core Problem with the Original PDF Structure
The original user guide combines several documentation types into a single, chronological flow. This forces the user to sift through technical specifications, iLok license licensing theories, and UI knobs explanations just to complete a basic task (like fixing an audio routing issue).

Key flaws identified:
* **High Cognitive Load:** Theoretical topics (e.g., "What is latency?") are mixed directly into quick-start configuration steps.
* **Low Findability:** Urgent troubleshooting scenarios (e.g., Mac audio silence) are not indexed or separated from general settings.
* **Lack of Hierarchy:** The manual lacks a clear separation between onboarding (Getting Started), daily tasks, and deep-dive references.

---

## 2. The New Structural Framework 
To improve usability, the documentation was restructured into distinct modules following the **Diátaxis framework** (Tutorials, How-To Guides, Reference, and Explanation).
Here is how the repository content is mapped out:

```text
Neural-DSP-docs/ (Root)
├── README.md                      # Project overview and Case Study introduction
├── audit.md                       # Critical analysis of the original manual
├── information-architecture.md    # This file (structural roadmap and rationale)
├── getting-started.md             # Task-oriented onboarding (Installation & First Launch)
└── troubleshooting.md              # Symptom-cause-solution guide for common errors
```




