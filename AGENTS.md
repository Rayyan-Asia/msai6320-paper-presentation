# AGENTS.md: Paper Presentation

Point of reference for continuing sessions. Read this first, then continue from any unchecked item below. Tick items off and add notes as work is done.

## Context

- Course: MSAI6320 (NLP), Dr. Ahmed Shawahna. Team of two students. Weight: 5% of the grade.
- Task: present a recent NLP-related paper (published 2025 or 2026) using a self-contained Jupyter Notebook that serves as the slides. About 20 minutes, live in class.
- Paper: *The Illusion of Thinking: Understanding the Strengths and Limitations of Reasoning Models via the Lens of Problem Complexity* (Shojaee, Mirzadeh, et al., Apple). arXiv 2506.06941 (v3, Nov 2025). Local copy: `Paper Presentation.pdf` (39 pages).
- The paper needs instructor approval, and each team must pick a unique paper (first come, first served).

## Paper summary (for reference)

- Evaluates large reasoning models (LRMs) vs standard LLMs on four controllable puzzles: Tower of Hanoi, Checker Jumping, River Crossing, Blocks World. Complexity is a single dial (e.g. number of disks).
- Claims: accuracy collapses beyond a complexity threshold; reasoning effort (tokens) rises then falls despite remaining budget; three regimes (standard models win at low complexity, LRMs win at medium, both collapse at high).
- Frontier models in the paper: Claude 3.7 Sonnet (thinking/non-thinking), DeepSeek-R1/V3, o3-mini.

## Required notebook sections (from the professor)

1. Introduction: problem, significance, background.
2. Methodology: detailed approach, key components, relevant math.
3. Figures and visualizations: original or reproduced, with attribution.
4. Implementation/demonstration: re-implementation or demo of key components, or a detailed code walkthrough.
5. Critical analysis: strengths, limitations, relation to other work, research directions.

## Deliverables

- Completed notebook (`.ipynb`), also used live.
- All supporting code, data, documents needed to run or understand it.
- Submit through ITC no later than the scheduled presentation date.

## Pending items

- [ ] Get instructor approval for this paper and confirm it is registered on the course sheet (registration deadline was Nov 8, 2026; check status).
- [ ] Find out the scheduled presentation date.
- [ ] Check whether the authors released code or puzzle simulators (none found in the PDF text; check the arXiv page). If none, write our own simulators.
- [ ] Create the notebook skeleton with the five required sections.
- [ ] Write the introduction and background.
- [ ] Write the methodology (puzzle definitions, complexity measures, how answers and reasoning traces are verified).
- [ ] Reproduce or redraw key figures with attribution.
- [ ] Implement the demo: puzzle simulators (start with Tower of Hanoi), a move validator, and a small accuracy-vs-complexity experiment with a small open model if feasible on a laptop or Colab.
- [ ] Write the critical analysis (strengths, limitations such as output-length limits and puzzle representativeness, related work, future directions).
- [ ] Time a full run-through (target 20 minutes).
- [ ] Add a `requirements.txt` and confirm the notebook runs end to end from a clean environment.
- [ ] Submit the notebook and supporting files through ITC.

## Working notes

- Keep compute light: the notebook should run on a laptop or Google Colab.
- Do not copy paper text or figures without attribution.
