# CV

My curriculum vitae, written in TeX.

##### "Forked" from https://github.com/natashapetrus/resume

* Run `git remote add upstream https://github.com/natashapetrus/resume` to allow pulling changes from the original repository
* Run `git pull upstream master` to pull the changes

### Current Setup

#### Dependencies

* [TeX Live](https://www.tug.org/texlive/) (full scheme, or just install basic/custom scheme with a few additions below)
* [fontawesome](https://www.ctan.org/pkg/fontawesome) (included in TeX Live full package)
    * Or, run `tlmgr install fontawesome`
* [latexmk](https://www.ctan.org/pkg/latexmk)
    * Check that latexmk.exe exists under /bin/win32
    * If missing, run `tlmgr install latexmk`
    * Used to compile and preview .pdf file when editing via Visual Studio Code
* If missing any other package/library, simply run `tlmgr install {libname}`

#### Editor // Compiler

Visual Studio Code ♡ [LaTeX Workshop](https://marketplace.visualstudio.com/items?itemName=James-Yu.latex-workshop)
