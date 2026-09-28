# Product scope

Gen Resume is an English-first resume drafting workflow for people who already have source material. The application extracts page-aware evidence from candidate documents, drafts claims with a local model, checks citations and numbers, then renders a one-page A4 PDF. A person reviews and confirms the draft.

## Current local capabilities

- PDF, DOCX, text, and selected code/project-folder intake
- Optional target job description and keyword coverage view
- Evidence-linked fact extraction and draft review notes
- English resume body with an optional user-confirmed English name
- A4 PDF generation and preview

## Limits

No public generator or paid service is live. Model checking does not establish that every statement is correct. The keyword view is descriptive, not an ATS or hiring outcome prediction. Quality and speed depend on the local model and source document quality. The current implementation targets macOS and requires a locally installed Ollama model.

The public repository contains product documentation only. The source code and internal development material are private while commercial terms and security work are being prepared.
