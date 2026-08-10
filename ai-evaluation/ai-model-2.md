# AI Evaluation — Model 2: ChatGPT

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

## AI Response (ChatGPT)

I reviewed the public GitHub repository and the linked YouTube page, and I also cross-checked several of the project's current factual claims against current sources. My main caveat is that the repository appears to be unfinished at the time of review, so I would grade what is actually submitted rather than giving credit for items the project says it intends to complete.

### Suggested Grade: 57 / 100

| Category | Score |
|---|---|
| 1. Content & Presentation | 20 / 25 |
| 2. GitHub Collaboration | 13 / 25 |
| 3. AI Evaluation Setup | 8 / 25 |
| 4. Reflection Quality | 16 / 25 |
| **Total** | **57 / 100** |

### 1. Content & Presentation — 20/25

**Strengths**
- The topic is extremely current and clearly falls within the required 6–12 month window. The project focuses on July/August 2026 releases, including GPT-5.6 and Grok 4.5. OpenAI's own release page confirms GPT-5.6 was released July 9, 2026.
- The script has a good structure: hook → concrete example → broader trend → societal impact → discussion question, with clear timing markers in `presentation-materials/video-script.md`.
- The discussion question is strong and directly connected to the thesis.
- The project connects model releases to cost, accessibility, decision fatigue, and safety, rather than simply listing new models.

**Why not full credit**
- The script says Opus 5 is "the fourth major Claude model release in under two months" and that it "roughly doubled its score" — important quantitative claims that need especially strong primary-source citations.
- The script states GPT-5.6 and Grok 4.5 were released July 9 and July 8 respectively. The GPT-5.6 date is confirmed by OpenAI, but the official xAI announcement dates Grok 4.5 to **July 16, not July 8** — this should be corrected or documented.
- Could not independently extract a reliable runtime/transcript from the YouTube page through the available web interface, so no runtime point was awarded or deducted from accessible metadata alone.

### 2. GitHub Collaboration — 13/25

Good organizational choices: separate directories for `research-notes`, `presentation-materials`, `ai-evaluation`, plus `README.md`, `SOURCES.md`, `reflection.md`. Four GitHub Issues were created corresponding to major project stages.

**However:**
- The README still contained a placeholder YouTube link at the time of review, rather than the actual URL.
- The repository has 0 pull requests; only the main branch is visible, no working branches.
- Commit history shows all commits authored by one person; the README explicitly describes this as a "Solo team."
- Issues are mostly task instructions rather than evidence of a completed workflow — e.g., Issue #3 says to obtain evaluations from two AI models, but the linked evaluation files were not present at review time.
- No usable GitHub Discussions activity found.
- Note: the solo-team status itself should not be penalized if genuinely permitted, but branches/PRs/Discussions are assessed independently of team size.

### 3. AI Evaluation Setup — 8/25

The evaluation prompt template itself is well-designed — includes the full rubric and explicitly asks for category scores, overall grade, strengths, and improvements.

**However**, at the time of review, the `ai-evaluation` directory contained only `prompt-template.md` — the completed `ai-model-1.md` and `ai-model-2.md` files described in the README were not yet present. Credit given for designing the evaluation procedure, but not for completing it.

### 4. Reflection Quality — 16/25

`reflection.md` has an excellent structure covering exactly the right questions (model comparisons, agreement/disagreement, what would change, how AI helped, specific examples, lessons learned).

**However**, at review time the file was still a template — sections like A1 still contained "[Write your answer here]" placeholders throughout Parts A and B. Credit given for the correct framework, very little for completed reflection content.

### Specific Strengths
1. **Strong choice of a current and meaningful topic** — connects the "multiple release tiers" trend to cost, accessibility, and trust rather than just listing new models.
2. **Good presentation organization** — unusually well-structured script for a short 2:30–3:00 presentation, with an effective phone-tier analogy for a non-technical audience.
3. **Strong discussion question** — not yes/no, follows directly from the argument, asks about both switching costs and trust.

### Main Areas to Improve
1. **Finish the required deliverables before submission** — README YouTube link placeholder, missing completed AI evaluations, unfilled reflection.md. These directly affect three of the four grading categories.
2. **Improve source verification and factual precision** — good source list overall, but release-date claims (especially the Grok 4.5 date) should be double-checked against official company announcements/system cards.
3. **Make the GitHub workflow demonstrate collaboration, not just task planning** — Issues alone aren't enough; the rubric also asks about branches, pull requests, and Discussions. Even for a solo project, an Issue → branch → work → PR → merge workflow would provide stronger evidence.

### Overall Assessment
"57/100 is my suggested grade for the repository in its current state. I would describe this as a promising project that has a strong concept and a well-planned presentation, but is not yet submission-complete." If the missing AI evaluations and reflection are completed, the README link is fixed, the GitHub workflow is documented, and the release-date claims are corrected, the project "could move substantially higher — potentially into the 80s or 90s."

The model explicitly noted it would not penalize the project simply for being solo, since the README identifies it as such, but would still assess branches/PRs/Issues/Discussions as workflow evidence independent of team size.
