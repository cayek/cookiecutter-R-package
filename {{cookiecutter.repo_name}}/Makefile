.PHONY: help rpackage-test rpackage-doc rpackage-install rpackage-

all: help

help:
	@echo 'rpackage-doc - updates documentation, file collation and NAMESPACE.'
	@echo 'rpackage-test - reloads your code, then runs all testthat tests.'
	@echo 'rpackage-install - reinstalls the package, detaches the currently loaded version then reloads the new version with library().'
	@echo 'rpackage-check - updates the documentation, then builds and checks the package.'
	@echo 'rpackage-build - builds a package file from package sources. You can can use it to build a binary version of your package.'
	@echo 'more information here: https://www.r-project.org/nosvn/pandoc/devtools.html'

###############################
## R package

rpackage-doc:
	Rscript -e "devtools::document()"

rpackage-test:
	Rscript -e "devtools::test()"

rpackage-install:
	Rscript -e "devtools::install()"

rpackage-check:
	Rscript -e "devtools::check()"

rpackage-build:
	Rscript -e "devtools::build()"
