# Minimal makefile for Sphinx documentation
#

# You can set these variables from the command line.
SPHINXOPTS    =
<<<<<<< HEAD
SPHINXBUILD   = sphinx-build
SPHINXPROJ    = CluSim
SOURCEDIR     = .
BUILDDIR      = .
=======
SPHINXBUILD   = python3 -msphinx
SPHINXPROJ    = clusim
SOURCEDIR     = source
BUILDDIR      = build
>>>>>>> init-edits

# Put it first so that "make" without argument is like "make help".
help:
	@$(SPHINXBUILD) -M help "$(SOURCEDIR)" "$(BUILDDIR)" $(SPHINXOPTS) $(O)

.PHONY: help Makefile

# Catch-all target: route all unknown targets to Sphinx using the new
# "make mode" option.  $(O) is meant as a shortcut for $(SPHINXOPTS).
%: Makefile
	@$(SPHINXBUILD) -M $@ "$(SOURCEDIR)" "$(BUILDDIR)" $(SPHINXOPTS) $(O)