# Résumé editing guidance

- `Awesome-CV/**` is infrastructure and is never editable for résumé-content requests.
- Editable résumé prose is limited to the root `main.tex` and `sections/*.tex` source files, and only to human-readable text inside existing LaTeX arguments, such as the text inside `\item{...}`, headings, roles, employer names, locations, dates, and prose paragraphs.
- Keep every LaTeX control sequence, brace, environment, macro name, formatting argument, package, document-class setting, spacing rule, page-geometry setting, font, color, section order, and `\input` structure unchanged.
- Preserve existing escaping and syntax, including `\&`, braces, and command delimiters.
- Keep changes narrowly limited to the text requested by the user. Do not rewrite unrelated résumé content.
- Before changing a claim, preserve its factual scope; do not invent technologies, metrics, deployment status, titles, ownership, or outcomes.
