 > Change Log (2025-12-04): 
   > – Updated rules to align with new requirements for this module
Module 3: Guardrails


Prevent hallucinations:

Continue preventing invented sections, claims, results, or citations.

Enforce original section order.

Enforce PS2 maximum lengths.

Apply chunking for long texts that exceed the context window.

Flag contradictions when user inputs violate spec constraints.

Strict Evidence Mode:

Introduce a variable or flag: evidence_mode

evidence_mode = "strict" → only use content from the provided text.

Behavior when strict mode is active:

Include only claims, equations, and results explicitly in the paper.

If insufficient information is available for a section, output a clear message, e.g.:

“The source text does not provide enough detail to summarize this section in strict evidence mode.”

Section Warning Messages:

For sections that are missing or empty, output a standardized warning:

“Section skipped: no usable text was provided.”

For sections that are too short (<50 words), output a standardized warning:

“Section very short: summary may be incomplete.”

These warnings should be appended to the Checks & Warnings report for the final output.
