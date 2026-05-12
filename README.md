# Xiao Hei Codex Pet

Xiao Hei is a tiny black forest-cat Codex desktop pet inspired by Xiao Hei, the beloved character from the animated film The Legend of Hei. It has oversized cream eyes, pale green inner ears, dark brown outlines, a small cyan mouth, and a cute mysterious expression.

## Contents

- `package/pet.json` - Codex pet manifest.
- `package/spritesheet.webp` - Final 1536 x 1872 animated pet atlas.
- `qa/contact-sheet.png` - Visual contact sheet for every animation row.
- `qa/review.json` - Frame extraction and row-level QA report.
- `qa/validation.json` - Final atlas validation report.
- `docs/generation-notes.md` - Summary of the generation and packaging process.

## Install

Copy the package files into your local Codex pets folder:

```powershell
New-Item -ItemType Directory -Force "$env:USERPROFILE\.codex\pets\nightleaf"
Copy-Item -Force ".\package\pet.json" "$env:USERPROFILE\.codex\pets\nightleaf\pet.json"
Copy-Item -Force ".\package\spritesheet.webp" "$env:USERPROFILE\.codex\pets\nightleaf\spritesheet.webp"
```

Restart Codex Desktop, then choose `Xiao Hei` in the pet or appearance settings.

## Validation

The spritesheet was validated as an RGBA WebP atlas with 8 columns, 9 rows, and 192 x 208 cells. All used frames are non-empty, all unused cells are transparent, and QA reports contain no errors or warnings.
