# 🤖 BUS5001 Assignment 3 – Evaluating NotebookLM as an Educational Assistant

This repository documents the evaluation of **NotebookLM**, an AI-powered note-taking assistant by Google, for academic use in university settings. The analysis was conducted through a simulated student scenario in the context of the subject BUS5001 – Artificial Intelligence in Business.

---

## 🎯 Objectives

- Assess NotebookLM’s capabilities aligned with core academic workflows
- Simulate real-world student interaction with lecture content
- Reflect critically on accuracy, usefulness, and limitations
- Provide evidence-based insights and practical recommendations

---

## 🧪 Academic Scenario

**Use case:** A student preparing for BUS5001 Assignment 3 on Dialogflow CX uploads the workshop handout into NotebookLM.  
They explore all 5 key features of the assistant to revise, extract key insights, and structure their understanding before submitting the assignment.

---

## 🧩 Feature-Based Evaluation

Each feature was tested and analysed using the uploaded workshop PDF. Details and reflections for each capability are documented below:

| Feature             | Summary |
|---------------------|---------|
| 📄 [Briefing Doc](docs/briefing.md)        | Auto-generates a structured summary of core content |
| 🧠 [Study Guide](docs/study_guide.md)      | Produces question-style prompts to aid revision |
| 🗺️ [Mind Map](docs/mindmap.md)            | Visualises concepts and hierarchies from source material |
| ❓ [FAQ](docs/faq.md)                      | Extracts short clarifications and explanations |
| 💬 [Chat Interface](docs/chat.md)         | Enables contextual Q&A and deeper understanding |

---

## 📸 Screenshots

All screenshots and supporting files are available in the [`/screenshots`](https://github.com/Diinmel/BUS5001_21964848_A3/tree/main/screenshots) folder.

---

## 🧠 Key Insights

- NotebookLM supports **scaffolded learning**, where students can engage with content through summarisation, exploration, and question-based review.
- The **chat-based interface** allows for fast retrieval and deeper engagement with course material — especially valuable in technical subjects.
- While hallucination risks are low with well-structured PDFs, ambiguous prompts may still lead to unsupported outputs.
- Its strength lies in **augmenting academic workflows**, not replacing human instruction or verification.

---

## ⚠️ Concerns & Recommendations

| Area               | Concern / Limitation | Recommendation |
|--------------------|----------------------|----------------|
| Hallucinations     | Occasionally fabricates detail if prompt is vague | Include citations for all outputs; verify facts |
| Input format       | Only supports PDFs and text | Expand to slides, spreadsheets, and LMS exports |
| Depth of reasoning | Some outputs overly generic | Combine with domain-specific prompts or use alongside LLM chat tools |

---

## 🔗 Repository Structure

```bash
📁 docs/                  # Feature-based evaluation notes
    ├─ briefing.md
    ├─ study_guide.md
    ├─ mindmap.md
    ├─ faq.md
    └─ chat.md
📁 screenshots/           # Experiment images
📄 README.md              # Overview & reflection
