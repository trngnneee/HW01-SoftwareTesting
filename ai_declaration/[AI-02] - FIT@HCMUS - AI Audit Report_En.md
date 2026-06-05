Faculty of Information Technology (FIT) – Ho Chi Minh City University of Science (HCMUS)

CS423 / CSC13003 – Software Testing (AI-augmented · 2026)

AI POLICY · TEMPLATES — 2026 v1.0

# AI Audit Report — 5-section Template per Artifact

Mandatory appendix for every AI-assisted homework (HW#01–HW#06, and Seminar).

Adapted from Med Kharbach, PhD (2026) — AI Use Policy Templates for Higher Education. CC BY-NC-SA 4.0. This adaptation is prepared for FIT@HCMUS – CS423 / CSC15003 Software Testing course.

## 1. Student Information

| Field | Value |
| --- | --- |
| Student name (printed): | DANG TRUONG NGUYEN |
| Student ID: | 23127438 |
| Class / Cohort: | 23KTPM3 |
| Assignment ID (e.g., HW#00, HW#02): | HW01 |
| Assignment date: | 05/06/2026 |
| AI tool(s) used: | ChatGPT, OpenCode (DeepSeek V4 Flash Free) with firecrawl for AI skill |
| AI tool(s) used: | [X] Yes  [ ] No |

## 2. Instructions (read before filling)

- Add one row per AI-generated artifact (test case, script, checklist, OpenAPI spec, JMeter plan, etc.).
- Paste the verbatim prompt — DO NOT paraphrase.
- Paste the verbatim AI output (or include a labelled screenshot in the report).
- Tag the verdict: VALID / INVALID / INCOMPLETE.
- Reasoning must cite a course slide, ISTQB section, or technical RFC.
- Show the corrected artifact with the change highlighted.
- Sample rows are in italic — replace them before submission.

## 3. Audit Table — one row per artifact

| (1) Prompt + Tool | (2) AI Output | (3) Verdict | (4) Reasoning (ISTQB) | (5) Student Fix |
| --- | --- | --- | --- | --- |
| Tool: OpenCode
Time: 15:00 02/06/2026
Prompt:
“Find 10 QA/QC job postings on topcv.vn published within 60 days, with ≥3 jobs requiring AI/LLM/automation-AI skills. Export descriptions, required skills, salary, screenshots, and AI impact analysis.” | Generated 10 QA/QC job postings with AI analysis, screenshots, translated descriptions, and AI impact assessment. Included jobs requiring Cursor, GitHub Copilot, Claude/ChatGPT, LLM evaluation frameworks, and AI testing tools. | INCOMPLETE | AI successfully collected and translated job postings, but several outputs required manual correction and replacement (Jobs 3, 5, and 6 were unsuitable initially with expired date). The tool failed Boundary Value validation for “published within 60 days” consistency and role relevance, requiring iterative refinement. In addition, the screenshot is inaccessible, required manually work. | Replaced incorrect job entries manually, validated publication dates, verified AI-skill requirements, and refined job relevance. Manually take screenshot of the job with login status of my account. Added corrected QA/QC positions and ensured ≥3 jobs explicitly required AI/LLM/automation-AI competencies. Exported finalized dataset into 23127438.md and export the session into /prompt_log/req1.json |
| Tool: OpenCode
Time: 15:30 02/06/2026
Prompt:
“Find 20 software defects from 2022–2026, including ≥5 AI/LLM-related defects. For each defect provide source link, description, severity, consequences, solution, and one AI bias/hallucination instance.” | Generated 20 software defect cases covering cybersecurity, automotive, aviation, cloud infrastructure, and AI/LLM incidents. Included defects such as CrowdStrike outage, Log4Shell, Tesla Autopilot recall, ChatGPT hallucinations, Gemini bias, EchoLeak prompt injection, and many-shot jailbreaking. Added severity levels, source links, and AI bias/hallucination annotations. | INCOMPLETE | AI successfully collected a broad range of defects and met the minimum requirement for AI/LLM-related incidents. However, several entries mixed vulnerabilities, recalls, and operational failures without clear defect categorization. According to ISTQB Defect Classification principles, defects should be consistently categorized by origin, impact, and failure type. Some AI incidents also lacked concrete remediation details or verified root-cause analysis, requiring manual validation to avoid hallucinated or weakly sourced conclusions. | Manually reviewed all 20 defects, verified source credibility, standardized severity classifications, and refined descriptions to align with ISTQB defect terminology. Added clearer remediation steps, validated AI hallucination/bias examples, and ensured ≥5 defects explicitly involved AI/LLM behavior or prompt-injection risks. Exported finalized content into 23127438.md and export the session into /prompt_log/req2.json |
| Tool: ChatGPT
Time: 4:45 05/06/2026
Prompt:
“Design 15 QA test cases for the Leobog HI75C Pro keyboard in markdown table format using Objective / Input / Steps / Expected / Actual / Verdict. Include RGB and knob functionality test cases.” | Generated 15 structured QA test cases for the Leobog HI75C Pro keyboard, including typing validation, RGB lighting behavior, knob rotation controls, connectivity checks, and edge-case scenarios. Produced markdown table formatting and explained TBD (“To Be Determined”). Updated TC04 to validate RGB switching using the rotary knob. | INCOMPLETE | AI successfully generated comprehensive functional test cases and adapted scenarios after user feedback. However, some cases lacked explicit requirement traceability and hardware specification validation. The AI initially assumed standard keyboard layouts without verifying the actual HI75C Pro hardware configuration. | Manually reviewed keyboard specifications and corrected assumptions about missing keys. Refined TC04 to specifically test knob-based RGB switching behavior. Added clearer preconditions, requirement alignment, and hardware-based validation to reduce false positives during execution. |

## 4. Summary of AI Accuracy

Aggregate the verdicts from Section 3 and complete the table below.

| Metric | Count | Percentage |
| --- | --- | --- |
| Total AI-generated artifacts audited | 3 | 100% |
| VALID (correct, accepted as-is) | 0 | 0% |
| INVALID (wrong; rejected) | 0 | 0% |
| INCOMPLETE (acceptable after edits) | 3 | 100% |

## 5. Conclusion — When should AI be used (or not)?

Write 80–150 words describing patterns you observed. Where did AI shine? Where did AI fail? What is your recommendation for using AI in this kind of work in the future?

AI which I use, for example ChatGPT or OpenCode with DeepSeek V4 Flash model provides a strong and fast repetitive research and document generation, which build a foundation ground for my work initially, it give me idea on how I perform test case for my keyboard, or repeat the process that I search the job on TopCV, then crawl the information of that into my document. However, to meet the requirements, in some case AI makes mistake because it assume the context as usual, for example the keyboard with default layout which contains the PrcSrc button or it collect the job that is already expired at 02/05/2026. My recommendation for using AI is build a framework for the AI job first, for example, I find a job first, then setup data field that I need to collect, then use AI for that repetitive work. But in the final, I will check for that job again because AI can make mistake with some specific requirement, for example job date range.

## 6. Mandatory Disclosure (paste verbatim)

"[Test cases / script / dataset / report] was initially generated by [AI tool name]; I reviewed and modified [section X], added [edge cases Y, Z]; [section W] was written entirely by me. The detailed AI Audit Report is attached as Appendix A. I confirm I did not use AI to generate any artifact listed in the prohibited category."

## Signature

| Student name (printed): | DANG TRUONG NGUYEN |
| --- | --- |
| Student ID: | 23127438 |
| Class / Cohort: | 23KTPM3 |
| Course: | CS423 / CSC13003 – Software Testing |
| Instructor: | Msc. Tran Thi Bich Hanh |
| Date: | 05/06/2026 |
| Signature: | ![signature](./signature.png) |

## References

- Kharbach, M. (2026). AI Use Policy Templates for Higher Education. CC BY-NC-SA 4.0.
- ISTQB Foundation Level Syllabus (latest version).
- Hardman, P. (2025). A Post-AI Learning Taxonomy.
- Fuster Rabella, M. (2025). OECD Education Working Paper No. 338.
- Perkins, M., Roe, J., & Furze, L. (2025). AI Assessment Scale.
- Anthropic (2025). Building reliable AI test agents — engineering blog.
- DeepEval & Promptfoo documentation — testing frameworks for LLM systems.