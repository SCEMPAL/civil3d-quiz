# Civil 3D Assessment & Quiz Engine

A lightweight, standalone web application designed for assessing and practicing Autodesk Civil 3D skills across various domains (Surfaces, Alignments, Pipe Networks, Toolspace, Points) and experience levels.

The assessment runs locally in any modern web browser while dynamically pulling from an expandable, cloud-hosted question database.

---

## Features

- **Zero Setup Required:** Pure HTML, CSS, and Vanilla JavaScript—no local server setup, Node.js, or complex dependencies required.
- **Dynamic Question Loading:** Seamlessly fetches questions from an external JSON bank with automatic fallback to built-in local questions if offline.
- **Adaptive Weighting:** Tracks domain-specific misses to prioritize weaker areas in future test sets.
- **Multiple Assessment Modes:**
  - **Exam Mode:** Standard timed assessment with final scoring.
  - **Study Mode:** Immediate feedback and detailed explanations per question.
- **Privacy First:** User progress and data remain on the client machine.

---

## File Structure

```text
├── Civil3D_Quiz_v6.html   # The main standalone application file
├── questions.json         # Hosted question bank database
└── README.md              # Project documentation
