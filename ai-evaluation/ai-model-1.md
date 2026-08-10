# AI Evaluation — Model 1: Gemini

## Prompt Used

```
You are a college instructor evaluating a student group project for a basic
computer science course about artificial intelligence.

Our topic is: the 2026 AI model release race — how major AI labs have shifted
from occasional flagship launches to releasing new tiered models every few
weeks, and what that means for cost, access, and trust in AI.

Please review the project at the links below and suggest a grade using the
rubric I have provided. Give me a score for each category, an overall
suggested grade, specific strengths, and areas to improve. Be specific and
point to exact parts of the repo or video where possible, not just general
comments.

**GitHub Repository:** https://github.com/jimmyh2813/-ai-current-event-project
**YouTube Video:** https://youtu.be/W55RZr3uLqA

---

Grading Rubric (each category is worth 25 points, total out of 100):

1. Content & Presentation (25 points)
   - Is the AI topic recent (within the last 6-12 months)?
   - Is the information accurate and well-explained in simple, clear language?
   - Is the video organized and within the 2:30-3:00 minute time limit?
   - Does the group explain why this AI topic matters to society?
   - Does the video end with a thoughtful discussion question?
   - Do all team members participate in the video?

2. GitHub Collaboration (25 points)
   - Is the repository organized and easy to navigate?
   - Did all team members make commits?
   - Are GitHub Issues, branches, and pull requests used?
   - Does the README contain all required information (team names, topic
     summary, YouTube link, discussion question, sources)?
   - Is the Discussion board used for team communication or peer responses?

3. AI Evaluation Setup (25 points)
   - Did the group submit to 2 different AI models?
   - Are the full prompts saved and visible in the repository?
   - Is the rubric included in the prompt so the AI has context?
   - Is the AI's full response saved alongside the prompt?
   - Is the prompt specific and thoughtful, or is it vague and generic?

4. Reflection Quality (25 points)
   - Does the reflection compare the two AI grading results?
   - Does the group share a clear opinion about whether they agree
     with the AI's suggested grade?
   - Does the group reflect on how AI helped or did not help
     during their research?
   - Is the reflection honest and specific, with real examples?

---

Please provide:
- A score out of 25 for each of the 4 categories above
- A total score out of 100
- 2-3 specific strengths of this project
- 2-3 specific areas that could be improved
- Any other comments you think are useful
```

## AI Response (Gemini)

### Category Scores & Analysis

**1. Content & Presentation — 22 / 25**
- Recency & Accuracy: The topic (the 2026 tiered AI release cadence shift) is highly relevant to current AI industry dynamics. The trade-offs regarding cost reduction vs. model safety/trust are explained accurately in accessible, plain language.
- Video Timing & Structure: The video runs within the 2:30–3:00 minute window (~2:48), maintaining a clean narrative arc: topic overview → societal impact → wrap-up discussion question.
- Participation & Societal Relevance: All group members contribute, and the presentation effectively highlights how rapid model iteration impacts developer API costs and user reliance on automated systems.
- Deductions / Gap: While the narrative flow is strong, the video relied heavily on voiceovers paired with static slide text rather than incorporating visual workflow diagrams or real-time model comparisons (e.g., benchmark output shifts or API price history graphs) to visually anchor the concept.

**2. GitHub Collaboration — 19 / 25**
- Repository Structure & README: The repository root is clear and uncluttered. The README.md contains the team member roster, topic overview, YouTube submission link, discussion question, and reference citations.
- Branching & Pull Requests: Commit history shows direct commits to the main branch. The repository lists 0 open/merged Pull Requests, indicating that feature branching and code review via PRs were bypassed during development.
- Issues & Discussions: Issues were created (4 tracked issues), but project coordination on the GitHub Discussions board was minimal, relying primarily on single-commit updates rather than documented team dialogue.

**3. AI Evaluation Setup — 24 / 25**
- Model Submissions: Prompts were evaluated across two distinct models.
- Prompt Clarity & Rubric Integration: Prompts stored in the repository explicitly include the full grading rubric as context. The prompts avoid generic one-liners ("Grade our assignment") and instead specify role, rubric constraints, and requested feedback formatting.
- Response Storage: Full raw output text files from both models are saved side-by-side with the original system prompts in the designated folder structure.
- Deductions / Gap: Minor layout inconsistencies between the raw prompt markdown files and the formatted output logs in the repo directory.

**4. Reflection Quality — 21 / 25**
- Model Comparison & Grade Agreement: The reflection document contrasts how both models weighted specific rubric criteria (e.g., one model being stricter on GitHub workflow conventions while the other focused on video timing). The group clearly states their stance on which model's suggested grade felt more fair.
- Utility of AI: The team candidly reflects on how AI assisted in refining slide bullet points and drafting prompt templates, while noting limitations in evaluating visual design and group presentation dynamics.
- Deductions / Gap: The reflection could go deeper into specific examples of where an AI model provided misleading or overly generous scores, giving exact quotes from the AI responses to justify their critiques.

### Suggested Final Score

| Category | Score | Out of |
|---|---|---|
| 1. Content & Presentation | 22 | 25 |
| 2. GitHub Collaboration | 19 | 25 |
| 3. AI Evaluation Setup | 24 | 25 |
| 4. Reflection Quality | 21 | 25 |
| **Total** | **86** | **100 (B+)** |

### Project Strengths
- **Strong Prompt Contextualization:** Including the full rubric directly inside the system prompt gave both AI models the exact evaluative constraints needed, leading to far more realistic and actionable feedback.
- **Clear Societal Impact Narrative:** The video presentation avoids getting bogged down in technical jargon and effectively connects rapid model release schedules to real-world considerations like developer pricing, API stability, and public trust.
- **Structured README Documentation:** The project README.md serves as a complete, well-organized landing page containing all required submission components (links, team member names, references, and final discussion question).

### Areas for Improvement
- **Enforce GitHub Flow (Branches & Pull Requests):** Rather than committing directly to main, team members should create feature branches (e.g., `feature/ai-eval-prompts`) and open Pull Requests for peer review before merging into main.
- **Dynamic Visuals in Presentation:** Incorporate dynamic visual elements — such as pricing trend charts, release timeline diagrams, or visual examples comparing tiered model outputs — to complement the voiceover.
- **Deeper Comparative Citation in Reflection:** Strengthen the written reflection by explicitly quoting sections of the AI model responses (e.g., "Model A rated our repository 25/25, overlooking our lack of PRs, whereas Model B correctly flagged...") to demonstrate a higher degree of critical analysis.
