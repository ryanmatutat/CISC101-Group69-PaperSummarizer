# CISC101-Group69-PaperSummarizer

This repository contains the full meta-prompt and specifications for an AI system that summarizes multi-section academic papers. The goal is to produce short, accurate section summaries and a coherent overall summary based strictly on the source text.

Repository Components

1. Summarizer Specification
Defines the required behavior of the system, including:
Inputs (paper + sections)
Outputs (≤150-word section summaries, ≤500-word unified summary)
Constraints: consistent terminology, original section order, no external information.

2. System Prompt
The complete meta-prompt controlling the summarizer’s tone, process, and formatting. It explains how the model should read the paper, extract key points, and structure the output.

3. Section Summary Rules
Guidelines for producing each section summary, covering word limits, what to extract, and how to maintain clarity and consistency.

4. Unified Summary Rules
Instructions for generating the final paper-level summary: synthesis across sections, 500-word cap, use of established terminology, and no new information.

5. Formatting Requirements
Rules for headings, order, conciseness, and neutral academic style to ensure clean, standardized output.
