# This project uses ladoc (a fork of github.com/LADI/ladoc-py )
# Eventually, just changing theme from ladi to othere one may
# make the rules here usable with other asciidoc-py and maybe even asciidoctor

.PHONY: README.html
README.html:
	asciidoc -b html5 -a icons -a data-uri --theme ladi -o README.html README.adoc
