# crave-tracker
A simple front-end only craving tracker

## Running

You can it straight from https://ippo615.github.io/crave-tracker

### Locally

To run it locally: clone the repo and serve the files with your
webserver of choice (I like python):

	git clone https://github.com/ippo615/crave-tracker.git
	cd crave-tracker
	python -m SimpleHTTPServer 8080

Then (for the example above) open http://localhost:8080/ in your
browser.

## Modifying

Everything that you should modify is in `index.html` (sorry). `libs/`
contains the used libraries:

 - [jquery](http://jquery.com/) for stuff
 - [localForage](https://github.com/mozilla/localForage) for offline data storage
 - [moment.js](http://momentjs.com/) for dealing with time
 - [SemanticUI](http://semantic-ui.com/) for user interface
