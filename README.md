# docs
SynTraffic's Public docs 

## Build and Run the Docs.
The docs are build with Sphinx. It's integrated with the main project Makefile.
`make html` builds the docs and the output is under /build/html/index.html

## Pre-Requisites ##
* Install Sphinx: Install Sphinx and its pre-requisites Python and pip using the instructions here: http://sphinx-doc.org/latest/install.html 

## Resources ##
* Sphinx Config files: Learn about Sphinx config files here: http://sphinx-doc.org/config.html

## Editing and Running docs

To make docs changes, without installing full development environment (e.g., on Mac or Windows:

```
git clone git@github.com:syntraffic/docs.git
cd syntraffic/docs
make html

```
