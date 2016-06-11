# svg_demo

Simple demonstration of using Snap.svg library in a test environment.
It is also a simple example for how to use Bower.

SVG + Javascript + HTML + CSS + Python

This was created to make a minimal example for making a web page with CSS that also uses Snap.

A small python web server is also included.
This project can be tested without Python, though. 
Just point a web browser at the file eyes_example.html.

This repo can be installed with bower, or downloaded with git.

## Git
```bash
git clone "https://github.com/tomacorp/svg_demo.git"
```

If you already have the Snap.svg dependency, this is ready to use.
Otherwise, go get Snap. Or, use Bower, which can download the
dependencies for you.

## Bower
```bash
bower install svg_demo
```



On OS X, this is an easy way to open the web page:
```bash
cd svg_demo
open eyes_example.html
```
Otherwise, open the file with the web browser.

There is also a small web server. Requires python and Flask.
```bash
python server.py
```
This opens a web server on localhost port 8003:
http://localhost:8003/

