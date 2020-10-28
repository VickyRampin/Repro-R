# Reproducibility with R

An embedded session for the Data Science for Social Impact class.

[![forthebadge](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://forthebadge.com) [![forthebadge](https://forthebadge.com/images/badges/cc-sa.svg)](https://forthebadge.com)

## Build our book locally
1. Fork, clone or download this project
2. Install R & RStudio
3. Install the bookdown, RMarkdown, and tinytex packages in RStudio with the following two commands in the R terminal:
	* `install.packages(c("rmarkdown", "bookdownplus", "tinytex", "webshot"))`
	* `tinytex::install_tinytex()`
	* `webshot::install_phantomjs()`
	* You can also click Tools > Install Packages and type the package names (make sure "install dependencies" is checked) separated by commas.
4. Go to the project folder and double click `Repro-R.Rproj` to start RStudio
5. Run this command in the R Console after RStudio opens: `bookdown::render_book('index.Rmd', 'all')`
6. Go to the folder `_book` in the project folder and click `index.html` to view the book locally in your browser.