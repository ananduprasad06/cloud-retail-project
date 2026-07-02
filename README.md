# Implementation of Cloud Computing in Business Operation

**MCA Project · Cloud Computing Specialization**

A research and systems-analysis study on cloud computing adoption in retail business operations — examining benefits, challenges, security considerations, and best practices, with a conceptual system design and an illustrative demo of the project's own algorithmic logic.

**🔗 Live site:** `https://<your-username>.github.io/<repo-name>/`

---

## About this project

This is a **research and systems-analysis project**, not a deployed software product. It combines:

- A structured literature review of cloud computing models and retail adoption trends
- Primary research: structured interviews with practicing IT professionals
- Case study analysis of retail organizations' cloud migration initiatives
- Conceptual system design: DFDs, UML diagrams (Use Case, Class, Sequence, Activity), an ER diagram, and a database schema
- A practical adoption framework and best-practice recommendations

Full details are in the [project report](downloads/Project_Report.pdf).

## What's on this site

| Section | Description |
|---|---|
| **Objectives** | The four research objectives from the project brief |
| **Architecture** | The conceptual hybrid cloud architecture (Figure 3.1 from the report) |
| **Live Demo** | An interactive, browser-side demo of the two conceptual algorithms described in Section 5.5 (stock availability check, cloud auto-scaling trigger) |
| **Findings** | Summary of interview insights and the on-premises vs. cloud comparison |
| **Downloads** | The full report (PDF/DOCX) and final presentation (PPTX) |

## A note on the "live demo"

The interactive demo runs the project's **own pseudocode** from Section 5.5 of the report, client-side, in the browser. It is included to make the conceptual logic tangible and testable — it is **not** a claim of a deployed retail system, and the site says so explicitly. No backend, database, or production system exists for this project; see Chapter 1.3 and Chapter 5.1 of the report for the project's stated scope.

## Repository structure

```
.
├── index.html              # Single-page site (no build step required)
├── assets/                  # Diagrams and screenshots used on the site
│   ├── architecture.png
│   ├── er.png
│   └── qollabb.png
└── downloads/                # Submission deliverables
    ├── Project_Report.pdf
    ├── Project_Report.docx
    └── Final_Presentation.pptx
```

## Running locally

No build tools required — it's a static page.

```bash
python3 -m http.server 8000
# then open http://localhost:8000
```

## Author

**Anandumon Prasad Thuruthel**
Enrollment No: O24MCA110149
Mentor: Ms. Vasanthi Chandran — Qollabb / Plag Pro, Noida
