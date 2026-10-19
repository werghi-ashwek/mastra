---
'@mastra/core': patch
---

Fixed `createStep(processor)` return typing and `ProcessorStepOutputSchema` / `ProcessorStepOutputType` field types so multiple processor steps can be chained with `.then()` and `.parallel()` without `TS2345` errors. Fixes #27577.
