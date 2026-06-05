# Requirement 2: 20 Software Defects 2022–2026 — Prompt Log / Session

## Session Metadata

- **Student Name**: Dang Truong Nguyen
- **Student ID**: 23127438
- **Date**: 2026-06-05
- **Model**: DeepSeek V4 Flash Free
- **Task**: Requirement 2: 20 Software Defects 2022–2026 — Find 20 software defects (≥5 AI/LLM-related), each with source link, description, severity, consequences, solution, and 1 identified AI bias/hallucination instance.

## Actions Log

| Step | Action | Tool | Description |
| :--- | :--- | :--- | :--- |
| 1 | Web search for major software defects 2022-2026 | WebSearch (deep) | Searched for major software defects across 2022-2026 including CrowdStrike, Log4Shell, XZ backdoor, Citrix Bleed, Tesla Autopilot, Boeing MCAS, and AI/LLM incidents. |
| 2 | Web search for AI/LLM-specific defects | WebSearch (deep) | Searched for AI hallucination, prompt injection, and bias incidents including ChatGPT lawyer fake cases, Google Gemini bias, Apple Intelligence errors, Air Canada chatbot liability, EchoLeak, and many-shot jailbreaking. |
| 3 | Web search for automotive and hardware defects | WebSearch (deep) | Searched details for Tesla Autopilot recall, Toyota brake software defect, AMD Zen 2 information leak, and Boeing 737 MAX MCAS. |
| 4 | Web search for Apple Intelligence bias study and ChatGPT defamation case | WebSearch (deep) | Searched for the AI Forensics Apple Intelligence bias study (2026), the Mark Walters v. OpenAI defamation case, and supplementary details on prompt injection vulnerabilities. |
| 5 | Write comprehensive 20-defect markdown file | Write file | Created 20_Software_Defects_2022_2026.md with all 20 defects organized in table format with AI bias/hallucination annotations. |
| 6 | Merge content into 23127438.md | Edit file | Merged all 20 defects into the existing 23127438.md following the established format (Defect N: source link, description, severity, consequences, solution, AI bias/hallucination). |
| 7 | Export session JSON | Write file | Exported this session summary to prompt_log/req2.json |

## Defects Summary

- **Total Defects Identified**: 20
- **AI Defects**: 9
- **Non-AI Defects**: 11
- **AI Bias/Hallucination Instances**: 20
- **Target Submission File**: `23127438.md`

### Detailed Defects List

| # | Name | Year | Type | Source | Severity |
| :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | CrowdStrike Falcon BSOD Global Outage | 2024 | Non-AI (memory corruption) | [Source Link](https://www.crowdstrike.com/wp-content/uploads/2024/08/Executive-Summary_Root-Cause-Analysis_Channel-File-291.pdf) | Critical – 8.5M devices crashed; $5.4B losses |
| 2 | Log4Shell – Apache Log4j RCE | 2021–2022 | Non-AI (RCE vulnerability) | [Source Link](https://nvd.nist.gov/vuln/detail/CVE-2021-44228) | Critical – CVSS 10.0; billions of devices affected |
| 3 | XZ Utils Backdoor – Supply Chain Attack | 2024 | Non-AI (supply chain) | [Source Link](https://securelist.com/xz-backdoor-story-part-1/112354/) | Critical – CVSS 10.0; major Linux distros compromised |
| 4 | Citrix Bleed – Comcast Xfinity Data Breach | 2023 | Non-AI (session hijacking) | [Source Link](https://www.cloudskope.com/breaches/comcast-xfinity-data-breach-2023) | Critical – CVSS 9.4; 35.9M records exposed |
| 5 | Tesla Autopilot Recall – 2M Vehicles | 2023 | Non-AI (ADAS software) | [Source Link](https://static.nhtsa.gov/odi/rcl/2023/RCLRPT-23V838-8276.PDF) | High – 2,031,220 vehicles; 13+ fatal crashes |
| 6 | Boeing 737 MAX MCAS – Fatal Flight Control Defect | 2020–2024 | Non-AI (flight control software) | [Source Link](https://www.seattletimes.com/seattle-news/times-watchdog/the-inside-story-of-mcas-how-boeings-737-max-system-gained-power-and-lost-safeguards/) | Catastrophic – 346 deaths; $20B+ cost |
| 7 | Toyota Corolla Cross Hybrid Brake Software Defect | 2024 | Non-AI (automotive software) | [Source Link](https://static.nhtsa.gov/odi/rcl/2024/RCAK-24V708-2799.pdf) | High – 42,199 vehicles recalled |
| 8 | Microsoft SharePoint Server Deserialization RCE | 2025 | Non-AI (RCE vulnerability) | [Source Link](https://nvd.nist.gov/vuln/detail/CVE-2025-53770) | Critical – CVSS 9.8; active global exploitation |
| 9 | AMD Zen 2 Information Leak – VZEROUPPER | 2023 | Non-AI (hardware microcode) | [Source Link](https://github.com/google/security-research/security/advisories/GHSA-v6wh-rxpg-cmm8) | High – CVSS 7.1; cross-VM leakage on EPYC |
| 10 | PHP mysqlnd Heap Buffer Over-read | 2024 | Non-AI (information disclosure) | [Source Link](https://github.com/php/php-src/security/advisories/GHSA-h35g-vwh6-m678) | Medium-High – CVSS 6.6 |
| 11 | Palo Alto PAN-OS Out-of-bounds Write | 2024 | Non-AI (memory corruption) | [Source Link](https://www.cisa.gov/known-exploited-vulnerabilities-catalog) | Critical – CVSS 10.0; nation-state exploitation |
| 12 | ChatGPT Lawyer Fake Cases – AI Hallucination in Court | 2023 | AI – Hallucination | [Source Link](https://www.legaldive.com/news/chatgpt-fake-legal-cases-generative-ai-hallucinations/651557/) | Medium – $5,000 fine; ethical sanctions |
| 13 | Google Gemini – Race-swapped Historical Images | 2024 | AI – Bias | [Source Link](https://blog.google/products-and-platforms/products/gemini/gemini-image-generation-issue/) | Medium – PR crisis; feature paused |
| 14 | Apple Intelligence – Fake News Summaries | 2025 | AI – Hallucination | [Source Link](https://www.bbc.com/news/articles/cq5ggew08eyo) | Medium – Misinformation attributed to news brands |
| 15 | Air Canada Chatbot Hallucination – Legal Liability | 2024 | AI – Hallucination/Liability | [Source Link](https://www.bbc.com/travel/article/20240222-air-canada-chatbot-misinformation-what-travellers-should-know) | Low-Medium – CAD $812 award; precedent-setting |
| 16 | OpenAI ChatGPT Defamation – Mark Walters | 2023–2025 | AI – Hallucination/Defamation | [Source Link](https://www.abajournal.com/web/article/creator-of-chatgpt-isnt-liable-for-embezzlement-hallucinations) | Medium – Defamation lawsuit; dismissed |
| 17 | Apple Intelligence – Systematic Bias Study | 2026 | AI – Bias | [Source Link](https://the-decoder.com/apple-intelligence-pushes-hallucinated-stereotypes-to-millions-of-devices-unprompted/) | Medium – Systematic bias on millions of devices |
| 18 | EchoLeak – Microsoft 365 Copilot Zero-Click Prompt Injection | 2025 | AI – Prompt Injection | [Source Link](https://arxiv.org/html/2509.10540) | Critical – CVE-2025-32711; zero-click data exfiltration |
| 19 | GPT-4 Fine-tuning API – Safety Guardrail Bypass | 2023 | AI – Security | [Source Link](https://arxiv.org/abs/2312.14302) | Critical – Safety alignment subversion |
| 20 | Many-shot Jailbreaking – Long-context Attack | 2024 | AI – Jailbreak/Security | [Source Link](https://proceedings.neurips.cc/paper_files/paper/2024/file/ea456e232efb72d261715e33ce25f208-Paper-Conference.pdf) | High – Systematic safety bypass |

## Tools Used

- WebSearch (deep) – multiple queries
- Read file (read tool)
- Write file (write tool)
- Edit file (edit tool)
