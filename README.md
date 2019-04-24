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


#### How to get your own copy of this repo

This procedure is a bit elaborate so here is the summary first: 
We'd like you to have access to a data visualization / interpretation notebook called `d'Orsay.ipynb`. 
This notebook lives in a repository ('repo') owned by an organization called **Cormorack** (for obscure reasons). 
You *could* just go grab the notebook file from here but you would also have to grab a bunch of other files 
that it uses; so this would be tedious. Much better is if you make your own copy of this repo. This is an *import*. 

- Go to github.com
  - If you are reading this you are actually already there...  
- Sign in if you are not automatically signed in
- Create a repository: It will be a copy of this Cormorack repository called 'gallery'; proceed as follows:
  - Left side top: Click the **New** button. It is green and has a little book icon next to the word 'New'
    - If you do not see this button: 
      - Click on the word Repositories at the top of the page and it should show up; maybe at the upper right
  - On the ensuing wizard page click on the link **Import a repository**
  - On *that* wizard page in the box 'Your old repository's clone URL' type in: http://github.com/cormorack/gallery.git
  - Also in the Name box type: gallery
  - Click the **Begin import** button; this will start the process and you are done with this step 

You'll get an email when it is done but it should only take a few moments. To check the results: 
Return to your GitHub home page http://github.com and click on *Repositories*; where *gallery* should 
now be apparent as a link. So click on that. You should see a file browser that lists some sub-folders and some 
files including that all-important `d'Orsay.ipynb` notebook file. If you scroll down below the file browser
you'll see... wait for it... ***this message***.
