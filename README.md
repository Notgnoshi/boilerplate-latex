# Boilerplate LaTeX Project

Run `make` to compile the document. This uses `latexmk` which runs LaTeX enough times to get table of contents, bibliographies, cross-references, etc. correct. However, it's error messages aren't the best, so if a compilation fails, you can run `make errors` to compile with `pdflatex` for more explicit error messages (lol, explicit error messages for a LaTeX document...).

You can then run `make view` to open your default PDF viewer. If your default PDF viewer is Evince, it will automatically update as you compile.

`make clean` will clean the auxiliary files, but not the `synctex` information or the compiled PDF. Use `make cleanall` to clean all of the auxiliary files.
