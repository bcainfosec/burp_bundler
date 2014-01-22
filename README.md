# Burp Suite Professional

## Java AppBundler script for Mac

Burp Bundler is an ant script to build a Mac application bundle using Java 7 with high resolution support for Retina displays.

### Dependencies
* [Burp Suite](http://portswigger.net/burp/download.html) or [Burp Suite Pro](https://pro.portswigger.net/users/)
* [Java AppBundler jar](https://java.net/downloads/appbundler/) in the ./lib directory
* Oracle Java 7

## Installation
0. Clone project

		git clone git@github.com:bcainfosec/burp_bundler.git

0. Change directory to project

		cd burp_bundler

0. Copy Burp Suite jar to current directory
0. Download appbundler-1.0.jar to lib directory

		curl https://java.net/downloads/appbundler/appbundler-1.0.jar -o lib/appbundler-1.0.jar

0. Run ant

		ant

0. If multiple versions of java are installed, it may require setting JAVA_HOME to 1.7

		JAVA_HOME=`/usr/libexec/java_home -v 1.7` ant

0. Move application bundle from dist/ directory to /Applications

		mv dist/Burp\ Suite\ Professional.app /Applications/

## Add Functionality
0. Fork
0. Add features
0. Send pull request

## TODO
* Get high res icons
