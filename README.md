# GC lease regression diagrams

English PNG exports of the interactive HTML explainer used for the Moby
snapshot lease regression investigation. Each image compares the same
forced checkpoint before and after the relevant correction.

- gc-pr-before-after.png: shared source snapshot under cache GC.
- gc-pr-handoff.png: durable-to-mirrored ownership handoff.

These illustrate local overlay2 regression fixtures, not a captured
production trace. The handoff comparison applies the reference-map
corrections in both variants and isolates mutex scope.
