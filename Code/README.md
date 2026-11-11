# Code layout (planned)

| Folder | What goes here | Week |
|---|---|---|
| `pipelines/` | The 8 clean PySpark pipelines (orders, customers, events, ...) | 6 |
| `data_generation/` | Synthetic input tables with controlled traps (non-unique keys, NULLs, events near midnight) | 6 |
| `mutations/` | Change operators: 6 silent-bug types, refactors, intended changes; commit-message generation | 7–8 |
| `harness/` | Runs old and new versions on the same data, computes profiles and diffs, validates expected behavior | 7 |
| `models/` | Rule baseline, GPT prompting, embeddings + LR, CodeBERT fine-tuning | 8–10 |
| `notebooks/` | EDA, experiments and figures | 8–12 |
