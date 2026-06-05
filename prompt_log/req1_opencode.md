# Requirement 1: QA/QC Job Market 2026+ — Prompt Log / Session

## Session Metadata

- **Student Name**: Dang Truong Nguyen
- **Student ID**: 23127438
- **Date**: 2026-06-02
- **Model**: DeepSeek V4 Flash Free
- **Task**: Requirement 1: QA/QC Job Market 2026+ — Find 10 QA/QC job postings on topcv.vn published within 60 days, ≥3 requiring AI/LLM/automation-AI skills

## Actions Log

| Step | Action | Tool | Description |
| :--- | :--- | :--- | :--- |
| 1 | Search & scrape topcv.vn for QA/QC jobs | Firecrawl API (v2/search + v2/scrape) | Searched topcv.vn for QA/QC job listings using Firecrawl search and scraped individual job pages for full details (description, requirements, salary, deadline). |
| 2 | Initial 10 jobs identified | N/A | Identified 10 QA/QC jobs from topcv.vn. Jobs 2-7 required AI/LLM/automation-AI skills. |
| 3 | Update 23127438.md with Jobs 2-7 | N/A | Filled in Jobs 2-7 with scraped data (description, required skills, salary, screenshot). |
| 4 | Replace Job 3 | N/A | Replaced Job 3 (Automation QC AI Product) with Senior QC Engineer - Warehouse (2182447) per user request. |
| 5 | Replace Job 6 | N/A | Replaced Job 6 (QA Engineer Automation) with Software Testing Engineer - Manual Tester (2181996) per user request. |
| 6 | Replace Job 5 | N/A | Replaced Job 5 (Senior QA/QC Engineer) with Manual Test Engineer Middle-Senior (2158658) per user request. |
| 7 | Add Jobs 8, 9, 10 | N/A | Added 3 more jobs: QA Intern (1649912), Quality Assurance SaaS (2151608), QA Engineer Data Platform AWS ETL (2149906). |
| 8 | Translate all 10 jobs to English | N/A | Translated all Vietnamese content (descriptions, requirements, titles) to English across all 10 jobs. |
| 9 | Add AI Impact Analysis | N/A | Added 1-2 sentence AI Impact Analysis per job post, analyzing how AI/automation affects each role. |
| 10 | Export session JSON | N/A | Exported this session summary to /prompt_log/req1.json |

## Jobs Identification & Analysis

- **Total Jobs Identified**: 10
- **Jobs Requiring AI/LLM/Automation Skills**: 4
- **Target Submission File**: `23127438.md`
- **Screenshots Directory**: `./images/`

### Detailed Jobs List

#### Job 1: QA Manager – Backpack / Technical Bags Manufacturer

- **URL**: [QA Manager – Backpack / Technical Bags Manufacturer](https://www.topcv.vn/viec-lam/qa-manager-backpack-technical-bags-manufactur/2068986.html)
- **Deadline**: 17/06/2026
- **Requires AI Skills**: `No`
- **Screenshot**: `./images/job1.png`
- **AI Impact Analysis**: AI-powered defect prediction and automated visual inspection systems are reducing manual QC checks, but this role's focus on ISO compliance, supplier auditing, and cross-functional leadership remains resilient. AI serves as a force multiplier for data analysis and KPI tracking rather than a replacement.

---
#### Job 2: Lead QA/QC (Exp AI)

- **URL**: [Lead QA/QC (Exp AI)](https://www.topcv.vn/viec-lam/lead-qa-qc-exp-ai/2169227.html)
- **Deadline**: 18/06/2026
- **Requires AI Skills**: `Yes`
- **Screenshot**: `./images/job2.png`
- **AI Skills Details**:
  - Must use AI tools for testing: Cursor, GitHub Copilot, Claude/ChatGPT
  - LLM evaluation frameworks: DeepEval, Ragas, LangSmith, Promptfoo
  - Transition roadmap to AI Quality Engineer / LLM Evaluation Engineer in 12-18 months
  - ML/AI project experience
- **AI Impact Analysis**: This role explicitly requires AI tool proficiency (Cursor, Copilot, LLM evaluation frameworks), positioning it at the forefront of AI-driven QA. The job itself is adapting to include AI evaluation as a core competency rather than an auxiliary skill.

---
#### Job 3: Senior QC Engineer - Warehouse

- **URL**: [Senior QC Engineer - Warehouse](https://www.topcv.vn/viec-lam/senior-qc-engineer-warehouse/2182447.html)
- **Deadline**: 28/06/2026
- **Requires AI Skills**: `Yes`
- **Screenshot**: `./images/job3.png`
- **AI Skills Details**:
  - Apply AI/Agentic AI tools for test generation, validation, and optimization
  - Strong interest in applying AI/LLM/Agentic AI tools
  - Experience with Cursor, Claude, GitHub Copilot, ChatGPT highly preferred
- **AI Impact Analysis**: AI/Agentic AI tools are embedded into every phase of testing — from test generation to defect analysis — making this role a hybrid of traditional QC and AI prompt engineering. The demand for engineers who can validate AI outputs and red-team AI systems is growing rapidly.

---
#### Job 4: Senior QC (Automation)

- **URL**: [Senior QC (Automation)](https://www.topcv.vn/viec-lam/senior-qc-automation/2167401.html)
- **Deadline**: 17/06/2026
- **Requires AI Skills**: `Yes`
- **Screenshot**: `./images/job4.png`
- **AI Skills Details**:
  - AI testing tools: LLM evaluation, synthetic data
  - AI Data Quality Assurance: training data validation, bias/fairness, security compliance
  - AI behavior testing, edge case analysis for AI products
- **AI Impact Analysis**: AI tools (LLM evaluation, synthetic data) are directly incorporated into the testing workflow, requiring the engineer to validate AI behavior alongside traditional functionality. This signals a shift where even automation-focused QC roles must now understand AI model risks and data fairness.

---
#### Job 5: Manual Test Engineer (Middle - Senior)

- **URL**: [Manual Test Engineer (Middle - Senior)](https://www.topcv.vn/viec-lam/manual-test-engineer-middle-senior/2158658.html)
- **Deadline**: 12/06/2026
- **Requires AI Skills**: `No`
- **Screenshot**: `./images/job5.png`
- **AI Impact Analysis**: Although titled 'Manual Test,' the role demands automation scripting and CI/CD integration, reflecting how AI-assisted test generation tools (Copilot, ChatGPT) are raising the baseline expectation even for manual testers. Pure manual testing without automation skills is becoming less viable.

---
#### Job 6: Software Testing Engineer - Manual Tester (Salary $700-$900)

- **URL**: [Software Testing Engineer - Manual Tester (Salary $700-$900)](https://www.topcv.vn/viec-lam/ky-su-kiem-thu-phan-mem-manual-tester-salary-700-900/2181996.html)
- **Deadline**: 29/06/2026
- **Requires AI Skills**: `No`
- **Screenshot**: `./images/job6.png`
- **AI Impact Analysis**: This entry-level manual testing role has the least AI exposure, but AI-powered test case generators and low-code automation platforms are gradually reducing demand for pure manual testing. Upskilling toward automation or AI testing tools would be essential for long-term career growth.

---
#### Job 7: QA/QC Department Head (Mechanical Engineering, Automation) Thu Duc

- **URL**: [QA/QC Department Head (Mechanical Engineering, Automation) Thu Duc](https://www.topcv.vn/viec-lam/truong-phong-chat-luong-qa-qc-co-khi-tu-dong-hoa-thu-duc/2121904.html)
- **Deadline**: 15/06/2026
- **Requires AI Skills**: `Yes`
- **Screenshot**: `./images/job7.png`
- **AI Skills Details**:
  - Electrical - Automation engineering background preferred
  - ISO 9001-2025 standards implementation
  - Automation in mechanical manufacturing context
- **AI Impact Analysis**: AI-driven predictive maintenance and computer vision are transforming mechanical QC, but this management role's emphasis on ISO systems, team leadership, and supplier coordination remains largely human-centric. AI augments data consolidation and reporting but does not replace the strategic oversight this position requires.

---
#### Job 8: QA Intern

- **URL**: [QA Intern](https://www.topcv.vn/viec-lam/thuc-tap-sinh-qa/1649912.html)
- **Deadline**: 26/06/2026
- **Requires AI Skills**: `No`
- **Screenshot**: `./images/job8.png`
- **AI Impact Analysis**: As a junior entry point, this internship is less immediately affected by AI, though familiarity with AI-augmented test management tools is becoming a differentiator. The foundational QA process skills learned here will remain valuable as AI shifts the tester's role from execution to oversight.

---
#### Job 9: Quality Assurance (SaaS)

- **URL**: [Quality Assurance (SaaS)](https://www.topcv.vn/viec-lam/quality-assurance-saas/2151608.html)
- **Deadline**: 01/07/2026
- **Requires AI Skills**: `No`
- **Screenshot**: `./images/job9.png`
- **AI Impact Analysis**: Operating in the SaaS domain, this QA role is moderately impacted by AI — AI-driven test orchestration and synthetic data generation can automate regression suites, but the need for human judgment in requirement analysis, risk assessment, and UX-centered testing persists. Shift-left practices combined with AI tools are the emerging norm.

---
#### Job 10: QA Engineer (Data Platform - AWS - ETL)

- **URL**: [QA Engineer (Data Platform - AWS - ETL)](https://www.topcv.vn/viec-lam/qa-engineerdata-platform-aws-etl/2149906.html)
- **Deadline**: 06/06/2026
- **Requires AI Skills**: `No`
- **Screenshot**: `./images/job10.png`
- **AI Impact Analysis**: AI/ML models are increasingly used for data pipeline monitoring and anomaly detection, which can automate parts of ETL validation. However, this role's deep reliance on SQL, AWS infrastructure knowledge, and domain expertise in banking data systems means AI acts as a productivity accelerator rather than a replacement.


## Tools Used

- Firecrawl API (v2/search - web search with scrape)
- Firecrawl API (v2/scrape - full page content extraction + screenshots)
- File editing (edit tool)
- File reading (read tool)
- File writing (write tool)
