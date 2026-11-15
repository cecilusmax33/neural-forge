# NeuralForge / PromptForge

One app family, one repo. The code itself is not here yet — what is here is the
frozen record of how it evolved in June 2026, so the history is preserved before
any source code lands.

## What these files are

All 9 files in `archive/` are saved web pages (`.mhtml` / `.mht`), not source
code. A page save is a photo of the app, not the app — nothing in them can be
rebuilt or redeployed as-is. They belong here as the archive: the design record
and the Gemini conversations behind each version.

- 7 are saves of Gemini share pages (`gemini.google.com/share/...`).
- 2 are saves of the running PromptForge app itself on Arcada
  (`promptforge-ai-*.arcada.app`).

No secrets were found in any of them (checked 2026-11-13).

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
| `archive/promptforge-battlemode.mht` | PromptForge BattleMode | 2026-06-09 16:07 CDT | https://promptforge-ai-wut2.arcada.app/ |
| `archive/promptforge-battle.mhtml` | PromptForge Battle | 2026-06-14 06:55 CDT | https://promptforge-ai-fvgy.arcada.app/ |
| `archive/neural-forge-v3.mhtml` | NerualForge V3 | 2026-06-20 23:46 CDT | https://gemini.google.com/share/c23b09427b1a |
| `archive/neural-forge-prompt-architect.mhtml` | NeuralForge PromptArchitect | 2026-06-20 23:49 CDT | https://gemini.google.com/share/7198caaf01f2 |

Original filenames were cleaned up on staging (typos and Gemini's save-name
prefixes removed); the content of each file is byte-identical to the upload.
Total archive size: 7,160,040 bytes (~6.8 MB) across the 9 files.

## How versions should live here

- **One app = one repo** (this one). Never one repo per version.
- **Versions = tags / GitHub Releases** inside this repo. When the real source
  exports arrive from AI Studio, the code lands in the repo root and each
  version gets tagged (`v3`, `v3.5`, `v4`, …). GitHub then lets you diff any
  two versions and download any old one.
- The `archive/` folder stays as the record — it is not the code.

## Next step

Export the real source zips from AI Studio for whichever version is current,
and the code goes in here with its version tag. Suggested repo name:
`neural-forge`, private, to match the rest of the fleet.
