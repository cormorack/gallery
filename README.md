[![Build Status](https://travis-ci.org/cormorack/gallery.svg?branch=master)](https://travis-ci.org/cormorack/gallery)
[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/cormorack/gallery/master)

# gallery

These are the gallery notebooks. They are intended to run in binder... once we get that debugged. Since binder
is copying files from GitHub (and does not know my GitHub credentials) this repo has to be public. 

"Gallery" notebooks reside between the RCO website (polished, interactive, plus static content) and more 
quotidian ocean data science notebooks (with lots of detail added). 


### binder

What is binder? It is a free service that builds a temporary Jupyter notebook environment. It does this based on
a repository such as **cormorack/gallery**. That is: The binder environment can include data and
can execute code; which one is free to modify. Since binder builds a *copy* it does not affect the source material.
It is somewhat analogous to an Exploratorium exhibit: Demonstrating a scientific purpose, including some 
interactivity, but not intended as an extended working environment. binder environments evaporate after a
certain amount of time. 

#### how to set up binder 

- install the button (and edit it to point correctly) 
- run `pip freeze > requirements.txt` and make that part of the repo
- test it
