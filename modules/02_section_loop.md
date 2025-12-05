> Change Log (2025-12-04): 
   > – Updated module to include new requirements
Module 2: Section Loop


For each section in the user-provided list:

Extract the corresponding text.

Set summary level:

Introduce a variable summary_level with possible values:

"short" → 1–2 sentence summary per section

"detailed" → short paragraph plus a bullet list of 3–5 key points

Generate the section summary based on summary_level:

If summary_level = "short" → produce only a compact 1–2 sentence summary.

If summary_level = "detailed" → produce a short paragraph summary and a bullet list of 3–5 key points extracted from the section.

Apply consistency rules:

Maintain terminology consistency across sections.

Preserve the original section ordering.

Append warnings for short or missing sections:

Flag any section that is empty or <50 words.

Include notes if content is insufficient for the selected summary level.
