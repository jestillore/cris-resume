Run `xelatex resume.tex`

OR

Run `docker run --rm --user $(id -u):$(id -g) -i -w "/doc" -v "$PWD":/doc thomasweise/texlive make`
