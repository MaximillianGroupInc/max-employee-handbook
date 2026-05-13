# MaximillianGroup Employee Handbook

California Employee Handbook for MaximillianGroup, Pasadena, California.

## Files

| File | Description |
|---|---|
| `handbook.md` | Source handbook in Markdown (edit this file) |
| `handbook.docx` | Auto-generated Microsoft Word document |
| `handbook.pdf` | Auto-generated PDF document |

## How It Works

The handbook is authored in `handbook.md`. On every push that modifies `handbook.md`, a GitHub Actions workflow automatically:

1. Converts `handbook.md` → `handbook.docx` (Microsoft Word) using [Pandoc](https://pandoc.org/)
2. Converts `handbook.md` → `handbook.pdf` using Pandoc + XeLaTeX
3. Commits the generated files back to the repository
4. Uploads the files as GitHub Actions artifacts (retained for 90 days)

## Editing the Handbook

Edit `handbook.md` directly and push. The DOCX and PDF will be regenerated automatically.

## Manual Trigger

The workflow can also be triggered manually via **Actions → Generate Handbook Documents → Run workflow**.

## Legal Notice

This handbook is for informational purposes only and is not legal advice. Consult a qualified California employment attorney before distributing to employees.
