#------------------------------------------------------------------------------
# Makefile
#
# Simple makefile for installing the scripts.
#------------------------------------------------------------------------------

# Target for the executable
all:

install:
	install -d $(PREFIX)/bin
	install -m 755 boosted_regression_tree/*.py $(PREFIX)/bin
	install -m 755 burn_threshold/*.py $(PREFIX)/bin
	install -m 755 seasonal_summary/*.py $(PREFIX)/bin
	install -m 755 *.py $(PREFIX)/bin

clean:

