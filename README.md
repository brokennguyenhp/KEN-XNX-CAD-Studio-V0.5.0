# KEN XNX CAD Studio V0.5.0

A browser-based prototype for interactive industrial line layout planning and customs-dossier preparation.

## Project status

This repository is being initialized. The V0.5.0 feature scope is:

- Interactive SVG layout editor for placing and moving equipment.
- Conveyor and connection records.
- Document register with evidence links.
- Draft analysis report and export.
- Local snapshots and audit log.
- Demo role selector (not production security).
- GitHub Actions workflow for basic repository checks.

## Important limitations

- Document records/evidence links are a registry, not automatic OCR or reliable extraction from PDFs/Excel.
- Generated customs analysis and Mẫu 01 outputs are drafts and require human review against source documents and current rules.
- The role selector is a UI demonstration, not authentication or authorization.
- Layouts are planning illustrations, not certified engineering drawings.
- Do not upload confidential shipment documents or credentials to a public repository.

## Running

Open `index.html` in a modern browser if present. No server-side service is implied by this prototype.

## Roadmap

- V0.2: interactive CAD placement, connections and drawing export.
- V0.3: document import/register and device evidence mapping.
- V0.4: draft customs analysis and Mẫu 01 exports.
- V0.5: GitHub Actions, snapshots, audit-log UI and role-demo UI.

## Disclaimer

This tool supports preparation and review. It does not replace professional engineering review, customs advice, or official acceptance by Vietnamese Customs.
