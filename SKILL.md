---
name: cn2en_med_diy
description: "医学学术写作中译英专用技能，特别适用于叙述性综述（narrative review）。当用户需要将中文医学段落翻译成出版级英文时使用此技能。触发词：医学翻译、中译英、医学论文翻译、clinical translation、medical translation、翻译这段医学内容、帮我把这段翻成英文、narrative review 翻译、医学学术翻译"
version: 1.0.0
base_dir: C:\Users\G1381\.workbuddy\skills\cn2en_med_diy
---

# Cn2en Med Diy

## Overview

This skill provides a structured two-step workflow for translating Chinese medical academic text into publication-quality English. It is specifically designed for narrative reviews and clinical research content, ensuring terminological accuracy, stylistic consistency, and adherence to medical academic conventions.

## When to Use This Skill

Trigger this skill when the user:
- Requests translation of Chinese medical or clinical research text into English
- Mentions "医学翻译", "中译英", "医学论文翻译"
- Uses phrases like "translate this medical text", "help me translate this paragraph"
- Needs publication-quality English output for academic medical writing
- Is working with narrative reviews, clinical trials, or medical research content

## Translation Workflow

To translate Chinese medical text, follow this two-step process:

### Step 1: Style Assessment

First, perform a comprehensive style assessment of the Chinese paragraph:

1. **Determine text characteristics**:
   - Text type (e.g., narrative review, clinical trial report, case study)
   - Communicative purpose (e.g., inform, persuade, summarize evidence)
   - Register (formal academic, technical, etc.)

2. **Identify stylistic features**:
   - Level of formality
   - Typical sentence structures
   - Use of technical terminology
   - Tone (objective, cautious, assertive, etc.)
   - Conventions specific to outcome metrics in clinical research

3. **Define translation style**: Based on the assessment, specify the translation approach (e.g., precision-focused, formal, impersonal, consistent terminology, clear numerical expression)

4. **Create terminology table**: List all key Chinese medical or statistical terms found in the paragraph. For each term:
   - Provide the proposed English equivalent
   - When multiple plausible translations exist, give a brief justification (e.g., adherence to CONSORT terminology, common usage in oncology trials, preference for MeSH terms)

Present the terminology as a table or bullet list.

### Step 2: Translation

Using the style definition and terminology choices from Step 1 as guidance, translate the paragraph into publication-quality English. Ensure that:
- All medical terms are accurately translated
- Numbers and statistical expressions are correctly rendered
- The English reads naturally while preserving the original meaning
- The academic tone is maintained throughout

## Output Format

Always structure the response with two clearly labeled sections:

```
### Style Assessment

[Style assessment content including terminology table]

### English Translation

[Publication-quality English translation]
```

## Examples of Trigger Phrases

- "帮我把这段医学内容翻译成英文"
- "Translate this paragraph about clinical trials"
- "我需要把这段医学综述翻译成英文"
- "Can you translate this medical text for publication?"
- "这段中文医学内容请帮我翻成英文"

## Notes

- This skill is optimized for narrative reviews and clinical research writing
- Pay special attention to CONSORT, PRISMA, and other reporting guideline terminology
- When in doubt about terminology, prefer MeSH terms or terminology commonly used in high-impact medical journals
- Maintain consistency in terminology throughout the translation
