# NeuralForge

**About this repository.** NeuralForge is an AI prompt-engineering and
app-building workbench developed by Cecil Tindell (Catalyst Vector AIA)
through a series of iterative versions built with Google AI Studio / Gemini
in June 2026. This repository is the permanent home for the NeuralForge app
family: it preserves the design record of every major version and will hold
the production source code as official exports are published.

One app, one repo. The code itself is not here yet — what is here is the
frozen record of how it evolved in June 2026, so the history is preserved before
any source code lands.

## What these files are

All 6 files in `archive/` are saved web pages (`.mhtml`), not source
code. A page save is a photo of the app, not the app — nothing in them can be
rebuilt or redeployed as-is. They belong here as the archive: the design record
and the Gemini conversations behind each version. All 6 are saves of Gemini
share pages (`gemini.google.com/share/...`).

No secrets were found in any of them (checked 2026-11-13).

**Split note (2026-11-15):** the PromptArchitect save and the two PromptForge
deployment saves (Battle, BattleMode) were moved to the separate
`PromptForge` repository at Cecil's direction.

## Version index

Ordered by the date each page was saved. Note the version labels do not follow
save order exactly — V3 was saved June 20, after the V4 saves from June 7.
The labels below come from the original filenames; the dates and source links
come from inside each saved file.

| File | Version / label | Saved | Source |
| --- | --- | --- | --- |
| `archive/neural-arena.mhtml` | Neural Arena | 2026-06-07 09:04 CDT | https://gemini.google.com/share/4debeb257b5b |
| `archive/neural-battle-arena.mhtml` | NEURAL Battle Arena | 2026-06-07 09:09 CDT | https://gemini.google.com/share/3d6093ec5d3a |
| `archive/neural-forge-v4.mhtml` | NEURAL FORGE V4 | 2026-06-07 09:13 CDT | https://gemini.google.com/share/08d56a037aa1 |
| `archive/neural-forge-v3.5.mhtml` | NEURAL FORGE V3.5 | 2026-06-07 09:17 CDT | https://gemini.google.com/share/b5e116fdce03 |
| `archive/neural-forge-v4o.mhtml` | NEURAL FORGE V4.o | 2026-06-07 09:19 CDT | https://gemini.google.com/share/42dfe53fe8be |
| `archive/neural-forge-v3.mhtml` | NerualForge V3 | 2026-06-20 23:46 CDT | https://gemini.google.com/share/c23b09427b1a |

Original filenames were cleaned up on staging (typos and Gemini's save-name
prefixes removed); the content of each file is byte-identical to the upload.
Total archive size: 5,957,605 bytes (~5.7 MB) across the 6 files.

## How versions should live here

- **One app = one repo** (this one). Never one repo per version.
- **Versions = tags / GitHub Releases** inside this repo. When the real source
  exports arrive from AI Studio, the code lands in the repo root and each
  version gets tagged (`v3`, `v3.5`, `v4`, …). GitHub then lets you diff any
  two versions and download any old one.
- The `archive/` folder stays as the record — it is not the code.

## Next step

Export the real source zips from AI Studio for whichever version is current,
and the code goes in here with its version tag.

## Repository history

| Date | Change |
| --- | --- |
| 2026-11-15 | Repository created and the 9-save archive published in three batches with this index. |
| 2026-11-15 | PromptArchitect and the two PromptForge deployment saves moved to the separate `PromptForge` repository at the owner's direction; index updated to the remaining 6 saves. |
| 2026-11-15 | Professional description and history sections added, per the owner's standing rule that every repository change is documented in context. |
