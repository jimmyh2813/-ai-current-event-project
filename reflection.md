# Reflection

## Part A — AI Grading Reflection

### A1. AI Model 1 — Summary
- **Model:** Gemini
- **Scores:** Content & Presentation 22/25 · GitHub Collaboration 19/25 · AI Evaluation Setup 24/25 · Reflection Quality 21/25 · **Total 86/100 (B+)**
- **Main strengths noted:** Strong prompt contextualization (including the full rubric inside the prompt), a clear societal-impact narrative that avoided technical jargon, and a well-organized README covering all required submission components.
- **Suggested improvements:** Use actual GitHub branches and pull requests instead of committing directly to `main`; add dynamic visuals (pricing trend charts, release timeline diagrams) to the video instead of relying on voiceover + static slides; quote specific lines from the AI responses in the reflection instead of summarizing them.

### A2. AI Model 2 — Summary
- **Model:** ChatGPT
- **Scores:** Content & Presentation 20/25 · GitHub Collaboration 13/25 · AI Evaluation Setup 8/25 · Reflection Quality 16/25 · **Total 57/100**
- **Main strengths noted:** A genuinely current and meaningful topic that connects the release-cadence trend to cost, accessibility, and trust rather than just listing new models; a well-structured script with clear timing markers; a strong, non-yes/no discussion question.
- **Suggested improvements:** Finish the actual deliverables before asking for a grade — at review time the README still had a placeholder YouTube link, the `ai-evaluation` folder only had the prompt template (no completed responses yet), and `reflection.md` was still blank. It also flagged that the script's Grok 4.5 date (July 8) doesn't match the official xAI announcement it found (July 16), and recommended using a solo-project GitHub workflow (Issue → branch → PR → merge) as evidence of process even without teammates.

### A3. Comparison — What Was Similar? What Was Different?
- **Where they agreed:** Both models liked the topic choice and thought it was genuinely current and well-connected to societal impact (cost, access, trust). Both also flagged the same underlying weakness — no branches or pull requests, just direct commits to `main` — as the main GitHub Collaboration deduction.
- **Where they disagreed:** The scores are very different (86 vs. 57), and the reason is almost entirely *timing*, not opinion. Gemini appears to have evaluated the project assuming the described deliverables (`ai-model-1.md`, `ai-model-2.md`, a filled-in `reflection.md`) already existed, while ChatGPT actually checked the live repository at that moment and found the `ai-evaluation` folder still only contained the prompt template and `reflection.md` was still a blank form. ChatGPT also did independent fact-checking (comparing the Grok 4.5 date against xAI's own announcement) that Gemini did not appear to do.
- **Which was more useful, and why:** ChatGPT's feedback was more useful precisely because it was more skeptical — it actually visited the repo links and evaluated what was *really* there instead of taking the README's description at face value, and it caught a factual date discrepancy that needed fixing. Gemini's feedback read more like it assumed the project was fully finished and graded the *plan* rather than the *submission*.

### A4. Do You Agree With the AI's Grade?
- I think ChatGPT's grade was the fairer one **at the time each model reviewed the project** — the repository genuinely was incomplete when I ran the evaluations (I hadn't uploaded the AI responses or filled in this reflection yet), so 57/100 was an accurate snapshot, even if it felt harsh to read. Gemini's 86/100 was overly generous because it didn't verify the actual repo state.
- What surprised me most was that ChatGPT caught a real factual error — the Grok 4.5 release date in my research notes (July 8) doesn't match the date on xAI's own announcement (July 16). I hadn't double-checked that specific date against a primary source, and neither had Gemini.
- Something I think ChatGPT got slightly wrong: it couldn't verify my video's runtime and didn't dock or credit that point, which was reasonable given the tool it had, but it also meant it couldn't confirm the video actually stayed close to the 2:30–3:00 limit.

### A5. What Would You Do Differently?
- If I could redo the project, I would finish and upload **all** deliverables (AI evaluations, reflection, correct README links) *before* asking either AI to grade it, so both evaluations would reflect the same, complete version of the project rather than catching it mid-progress.
- I would also double-check specific dates and benchmark claims against each company's own announcement page before including them in the script — the Grok 4.5 date is the clearest example of a claim I should have verified more carefully.
- One suggestion I would *not* change: both models suggested using GitHub branches and pull requests even as a solo contributor. I think this is worth doing for a real team, but for a one-person project, I don't think a branch → PR → merge cycle by myself for every commit adds real evidence of collaboration — it mostly just adds process for its own sake. I updated my GitHub workflow to at least use Issues properly to track progress, but I didn't force artificial PRs on myself for changes only I was reviewing.

---

## Part B — AI Research Assistance Reflection

### B1. How You Used AI During Research
I used Claude and web search throughout the project to: find and verify recent (2026) AI model release news, draft the research notes and video script, generate the presentation slides, and prepare the AI-evaluation prompt template with the full grading rubric embedded in it.

### B2. What Worked Well
The most useful thing AI did was quickly pulling together a timeline of recent AI model releases (Claude Opus 5, GPT-5.6, Grok 4.5, and others) with real dates and sources, which would have taken much longer to compile by searching manually one article at a time. For example, when I asked for research notes on "AI model releases in the last 6-12 months," it returned a structured timeline with specific dates and a clear explanation of *why* the pattern mattered (price-per-performance competition, tiered model families), not just a list of headlines.

### B3. What Did Not Work Well
The clearest example of AI not being fully reliable was the Grok 4.5 release date. My research notes said July 8, 2026, but when ChatGPT independently checked xAI's own announcement while grading the project, it found the actual date was July 16, 2026. I had not personally verified that date against xAI's own page before including it in the script, so I had to go back and correct/document it after the fact. This showed me that even when AI tools are quoting dates confidently, I still need to spot-check specific factual claims — especially ones I plan to say out loud on camera — against a primary source myself.

### B4. Overall Reflection
Using AI changed the project mainly by speeding up the "first draft" of everything — research notes, script structure, slide layout, and the evaluation prompt — so I could spend more of my own time refining the content and making sure the factual claims held up, rather than starting from a blank page. If I did a similar project again, I would use AI the same way for drafting, but I would build in a dedicated fact-checking pass earlier in the process, rather than only discovering an error because a grading AI happened to catch it. The most important thing this experience taught me about AI as a tool is that its output is much stronger when I treat it as a fast first draft to verify, not a finished answer to trust — the gap between Gemini's 86 and ChatGPT's 57 on the *exact same repository* is itself proof that AI evaluations can vary a lot depending on how carefully the tool actually checks the source material, and the same is true of AI-assisted research.
