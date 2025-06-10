# 🎓 Role-Based Reflections – Evaluating NotebookLM in Academic Contexts

NotebookLM was tested across 5 key features using BUS5001 materials. This section examines how well it supports three distinct academic roles: **students**, **lecturers**, and **researchers**.

---

## 👩‍🎓 Student Perspective

### 🧠 Learning Needs
- Understand key concepts efficiently  
- Prepare for assignments or exams  
- Connect fragmented notes into a coherent whole  

### ✅ Strengths
- **Briefing Doc**: Helps reduce overwhelm by summarising technical documents like Dialogflow CX workshop notes  
- **Study Guide**: Supports surface-level recall, useful for short quizzes or peer flashcards  
- **Chat Interface**: Enables spontaneous clarification (“What’s the difference between a Page and a Flow?”)

### ⚠️ Limitations and Improvements
- **Limitation**: Doesn’t adapt to user knowledge level  
  **💡 Suggestion**: Add *student profiles* (e.g., beginner/intermediate) to control explanation complexity  
- **Limitation**: Lacks conceptual scaffolding or guided pathways  
  **💡 Suggestion**: Support structured prompts like “suggest 3 starter questions about entity types”  
- **Limitation**: Study Guide only scratches Bloom’s “Remember” layer  
  **💡 Suggestion**: Let students select cognitive level (“Apply”, “Evaluate”, “Create”) – as supported in Claude or ChatGPT

### 🎯 Application to Assignment Scenario

In the context of BUS5001 Assignment 3, the student used NotebookLM to prepare for the design and analysis of a chatbot using Dialogflow CX. Each feature of the tool aligned with a specific academic task:
**Briefing Doc** was used to quickly extract a structured summary of the workshop material, helping the student understand agent components without re-reading the full tutorial.
**Study Guide** served as a first-round revision tool, especially when revisiting concepts like "fulfillment" and "intents" during assignment documentation.
**Mind Map** provided an early-stage overview to visually separate confusing terms (e.g., Pages vs. Forms), which helped in sketching the chatbot flow before working in Dialogflow CX.
**Chat Interface** was leveraged to clarify dependencies (e.g., How do forms relate to parameters and state transitions?) and explore platform logic in preparation for the demo.
**FAQ** was referenced while writing technical definitions in the report and video narration script.
Despite these strengths, some limitations required the cross-checking or cross-referencing the workshop PDF for more precise details.
This confirms that NotebookLM can serve as a preparation and support tool for practical deliverables, but still relies on the student’s initiative to structure prompts and verify critical concepts.

---

## 👨‍🏫 Lecturer Perspective

### 📋 Needs
- Validate if content communicates the intended hierarchy  
- Build questions or identify what might confuse students  
- Spot pedagogical gaps in handouts

### ✅ Strengths
- **Mind Map**: Visualises missing links (e.g., Handler logic vs. Fulfillment path)  
- **FAQ**: Reveals unclear points by surfacing student-style questions  
- **Briefing Doc**: Acts as a check for whether learning outcomes are preserved in tone and focus

### ⚠️ Limitations and Improvements
- **Limitation**: Flattened emphasis — treats all concepts equally  
  **💡 Suggestion**: Allow tagging for *core*, *supporting*, or *examples* (like LMS outcome tagging)  
- **Limitation**: No awareness of what is *instructional priority*  
  **💡 Suggestion**: Let lecturers weight certain terms or outcomes  
- **Limitation**: Mind Map doesn’t group terms by pedagogy or topic clusters  
  **💡 Suggestion**: Support concept bundling (e.g., “Fulfillment + Webhook + Response flow”)

---

## 🧑‍🔬 Researcher Perspective

### 🔍 Use Cases
- Explore terminology across dense literature  
- Pose iterative queries to refine understanding  
- Segment and extract parts of academic papers

### ✅ Strengths
- **FAQ**: Surfaces dense definitions quickly  
- **Chat**: Allows hypothesis-driven interrogation of documents

### ⚠️ Limitations and Improvements
- **Limitation**: Cannot handle multiple files or cross-compare ideas  
  **💡 Suggestion**: Enable multi-PDF uploads and queries like “How is 'intent' defined across all?”  
- **Limitation**: No metadata awareness (e.g., can’t distinguish between Methods vs. Appendix)  
  **💡 Suggestion**: Support document segmentation (e.g., “Summarise only Section 3.2”)

---

## 🔧 Cross-Role Recommendations (Actionable + Trend-Informed)

| Challenge                           | Solution                                                    | Tools that already do this           |
|-------------------------------------|--------------------------------------------------------------|--------------------------------------|
| Flat output tone                    | Role selector (Student/Lecturer/Researcher)                  | ChatGPT Custom GPTs, Gemini API      |
| Low question depth                  | Bloom-level toggles (Apply/Evaluate)                         | Claude, Perplexity reasoning toggles |
| Lack of inquiry scaffolding         | Clarification styles (diagram, analogy, example)             | Claude analogy engine, ChatGPT roleplay |
| Poor concept priority weighting     | Core/supporting/exam flagging via tags                       | LMS tools (e.g., Moodle)             |
| One-file limitation                 | Multi-document memory and linked reasoning                   | ChatGPT-4 w/ Files, Perplexity Pro   |

---

## 🧠 Strategic Takeaway

NotebookLM is **not yet a full educational assistant**, but it works well as:
- A **modular companion** for fact-checking, light review, and clarification  
- A **starting point** for note-based automation and revision design  
- A **complement** to larger LLMs when paired with more dynamic reasoning tools

To truly empower learning and research in higher ed, it must shift from **summarising** to **scaffolding** — making role-aware, structured, and multi-source insights possible.
