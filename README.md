# detai-skill-client

Reusable local client system for stable Detai skill invocation through deterministic gateway, workflow registry, adapter registry, wrapper layer, schema contracts, fixtures, validators, audit logs, and execution gates.

## Current build state

```text
Current step: Step 026 - Candidate Script Bucketing
Previous step: Step 025 - Wrapper / Schema Draft Plan
Final target: reusable installable local skill client system
execution_enabled = false
formal_business_use = false
```

## Current boundary

The user confirms business-level adapter -> module relationships only. The system owns module -> script -> entrypoint -> wrapper -> schema -> fixture -> execution gate.

`supporting_helper`, `unknown_or_mixed`, `test_or_regression`, `diagnostic_or_debug`, `reference_or_contract`, and `data_profile` are not user-facing adapters.

## Upload note

This repository was initialized from the uploaded `detai-skill-client.zip`. Dependency/runtime folders such as `.venv`, `node_modules`, `__pycache__`, and `data/runtime` are intentionally excluded from source control.

The current ChatGPT GitHub connector supports UTF-8 file writes. Binary assets from the uploaded archive are tracked in `SOURCE_UPLOAD_NOTE.md` and should be pushed with normal git from the clean source zip when binary upload support is available.
