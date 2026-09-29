# Résumé editing guidance

- Route every résumé-content request to `resume-content-editor`.
- Route an explicit pagination or page-flow request to `resume-pagination-editor`.
- `Awesome-CV/**` is infrastructure and is never editable unless the user separately authorizes template work.
- Keep each change narrowly limited to the request; do not alter unrelated résumé content or layout behavior.
- Preserve factual scope. Do not invent technologies, metrics, deployment status, titles, ownership, or outcomes.
- Each specialized agent defines its exclusive edit boundary. Do not combine content and pagination work in one agent task.
