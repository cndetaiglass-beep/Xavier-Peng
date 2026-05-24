# Source upload note

The uploaded archive `detai-skill-client.zip` was received and inspected.

## Clean source handling

The archive contains generated dependency/runtime folders that should not be committed:

```text
backend/.venv/
frontend/node_modules/
__pycache__/
data/runtime/
*.pyc
*.log
```

A clean source zip was generated locally with those folders excluded:

```text
detai-skill-client-step026-clean.zip
```

## Current GitHub status

This repository has been initialized for ongoing `detai-skill-client` updates. The GitHub connector available in this session supports UTF-8 file writes through the repository contents API, so binary assets from the original archive are not safely committed through this connector in this turn.

Binary assets found in the clean source tree:

```text
skill_source/detai-glass-workflow/modules/product-scale/assets/detai-drawing-template-a2.pdf
skill_source/detai-glass-workflow/modules/product-orthographic-view-reconstructor/assets/locked-success-example.png
skill_source/detai-glass-workflow/modules/product-orthographic-view-reconstructor/assets/reference-output.png
skill_source/detai-glass-workflow/modules/glass-cost-physical-model/assets/#U5254#U9664#U76f4#U63a5#U6750#U6599_#U6210#U672c#U51fa#U6599#U91cf#U7269#U7406#U7ea6#U675f#U6a21#U578b.xlsx
```

## Current build state

```text
Step 026: Candidate Script Bucketing
module_count = 8
adapter_count = 8
script_candidate_count = 56
execution_enabled = false
formal_business_use = false
```

## Next source-control action

Use the clean source zip as the source of truth for a normal git push when binary upload is available. Ongoing text-source updates can be maintained through this repository connector.
