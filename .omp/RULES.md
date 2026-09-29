# Mandatory PDF generation

After every permitted résumé-content edit, generate `main.pdf` from the repository root with:

```sh
devcontainer exec --workspace-folder . xelatex -interaction=nonstopmode -halt-on-error main.tex
```

Run the command twice. Do not report completion unless both invocations succeed and produce `main.pdf`.
