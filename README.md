# docs
SynTraffic's Public docs 

## Build and Run the Docs.
The docs are built with Sphinx for readthedocs (RTD). It's integrated with the main project Makefile.
`make html` builds the docs and the output is under /build/html/index.html

## Pre-Requisites ##
* Install Sphinx: Install Sphinx and its pre-requisites Python and pip using the instructions here: http://sphinx-doc.org/latest/install.html 

## Resources ##
* RTD: All our help files are hosted by readthedocs: https://read-the-docs.readthedocs.org/en/latest/getting_started.html
* Sphinx Config files: Learn about Sphinx config files here: http://sphinx-doc.org/config.html
* Sphinx theme for RTD: https://github.com/snide/sphinx_rtd_theme

## Editing and Running docs

To make docs changes, without installing full development environment (e.g., on Mac or Windows:

```
git clone git@github.com:syntraffic/docs.git
cd syntraffic/docs
make html

```
