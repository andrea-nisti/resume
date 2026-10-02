## install and build
1. `git submodule update --init --recursive`
2. `devcontainer up --workspace-folder .`
3. `devcontainer exec --workspace-folder . xelatex -interaction=nonstopmode -halt-on-error main.tex`
4. profit
