# Development Notes

## Local workflow

- Keep model/provider credentials outside source control.
- Keep datasets and generated artifacts separate from application code.
- Test retrieval independently from generation.
- Record changes to prompts and retrieval settings.
- Prefer small, reviewable changes.

## GenAI checklist

- Verify retrieved context is relevant.
- Avoid presenting generated text as a clinical diagnosis.
- Add explicit fallback behavior when retrieval is insufficient.
- Measure latency and retrieval quality when changing the pipeline.
