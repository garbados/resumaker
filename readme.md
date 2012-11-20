# RESUMAKER

I hate resumes, so I made robots do them for me.

## Quickstart

You'll need node.js installed

	git clone git@github.com:garbados/resumaker.git
	cd resumaker
	npm install			 # install dependencies
	vi resume.yml		 # enter your data
	node app.js			 # run resumaker

Visit `localhost:3000` in a browser of your choice, print the page as a PDF, and you're good!

## Customize

Mess with these files:

* resume.yml: your data
* views/index.jade: overall layout
* views/_item.jade: per-item layout