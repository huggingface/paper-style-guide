# 🤗 Paper Style Guide


(Work in progress, send a PR!)

## Libraries to Know

* [booktabs](https://nhigham.com/2019/11/19/better-latex-tables-with-booktabs/)
* [natbib](https://es.overleaf.com/learn/latex/Bibliography_management_with_natbib)
* [cleveref](http://tug.ctan.org/tex-archive/macros/latex/contrib/cleveref/cleveref.pdf)
* Either [seaborn](https://seaborn.pydata.org/), plotly or [altair](https://altair-viz.github.io/) for graphs
* [algorithmicx](https://ctan.mirrors.hoobly.com/macros/latex/contrib/algorithmicx/algorithmicx.pdf)
* [rebiber](https://github.com/yuchenlin/rebiber) for automatically standarized bib update

## General

* When in doubt use sections -> Introduction, Background, Model, Training, Methods, Results, Discussion, Conclusion.
* Tables should always follow this [guide](https://people.inf.ethz.ch/markusp/teaching/guides/guide-tables.pdf) 
* Tables / Figures should always float. Never inline in the text.
* When using natbib, \citet is for when the citation is a noun, and \citep is for when it is at the end. 
* Captions should be short but fully self-explanatory of the columns / rows. They should not use 1st person.
* Abstracts should be 1 paragraph. When in doubt -> Context, Problem, Idea 1, Idea 2, Results. 
* Section titles should be starting-caps. 
* The goal of related work is not just to list papers, but to explicitly make claims as to how your work differs from each one.
* Figures should have a white background and large fonts. Do not screenshot! Generate a high-res, pdf output. 
* Use present tense (almost) everywhere.
* You do not need a summary paragraph at the end of your intro. 
* All empirical results must be in a table or figure. 
* Methods section should not introduce new modeling. Enumerate the tasks, baselines, hyperparameters.
* Results section should not introduce new tasks or models. Summarize the tables. 
* Any non-trivial notation should be introduced as early possible. Ideally background.
* 8 pages is an extremely hard limit. 
* Always use \`\` '' for quotes not " ". 
* Use bold sparingly. Opt for italics for new technical terms.


## Small Tips

* Turn off `\usepackage[review]{emnlp}` to `\usepackage[]{emnlp}` while editing to fix overleaf linking.
* Use `\newcommand{\todo}[1]{{\small\color{red}{\bf [*** Todo: #1]}}}` for inline comments.



## Links

* Rational Reconstruction https://web.stanford.edu/class/cs224u/readings/shieber-writing.pdf
* ICML paper blog https://icml.cc/Conferences/2002/craft.html

## Exercises

* What are the 3 contributions of the paper? 
* Do my experiments convincingly prove each of these are true?
* Can I cut anything that does not satisfy these?
* Would someone who has not read a paper in 2 years understand what is happening?
