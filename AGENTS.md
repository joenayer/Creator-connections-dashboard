# Agent instructions

Read [`.ai-os/README.md`](.ai-os/README.md), [`README.md`](README.md), and the relevant portion of [`index.html`](index.html) before changing this repository.

- Keep uploaded marketplace reports in the browser unless the task explicitly introduces a reviewed storage design.
- Treat CSV cells, filenames, creator names, product identifiers, and formulas as untrusted data. Escape rendered values and prevent spreadsheet-formula injection in any export.
- Never commit customer, creator, order, revenue, or report data. Use synthetic fixtures for testing.
- Preserve filtering, sorting, totals, date handling, and offline use after changes. Verify with a bounded synthetic report.
- Never commit secrets. Do not deploy or publish unless the task explicitly authorizes it.

The repository is the source of truth for project behavior. Joel AI OS supplies shared working preferences only.
