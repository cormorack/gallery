[![Build Status](https://travis-ci.org/cormorack/gallery.svg?branch=master)](https://travis-ci.org/cormorack/gallery)
[![Binder](http://binder.pangeo.io/badge.svg)](http://binder.pangeo.io/v2/gh/cormorack/gallery/master)

# gallery

This *gallery notebook repo* loads and runs in binder and/or colab; so this repo is public.  It may of course also 
be cloned for use. The goal here is to introduce regional cabled observatory (RCO) data in relation to other ocean data sources.


### binder and colab

Binder and colab are free services that build a temporary Jupyter notebook environment around the content
found here. Binder and colab environments can both include data and execute code. 
This is analogous to an [Exploratorium](http://exploratorium.com) exhibit: Demonstrate scientific purpose and 
include interactivity. 


#### how to set up binder 

- install the button (and edit it to point correctly) 
- run `pip freeze > requirements.txt` and make that part of the repo... flag need env.yml version of this
- test it


#### How to copy this repo

You may wish to work from this (or another) repo in your own environment; for example a JupyterHub-hosted
notebook environment on the web or on your own computer. 
If you work on a downloaded copy and it is later accidentally deleted you lose that work. We suggest first making 
your own repository (a copy) on GitHub to take advantage of the version control and reliability features. 

This procedure is a bit elaborate so here is the summary first: 

This repository ('repo') is owned by an organization called **Cormorack** (for obscure reasons). 
You make your own copy of this repo: Via *import*. That becomes your stable/safe version. While it 
is on GitHub the code does not actually run. What follows from there is described in the next section.

- Go to github.com
  - If you are reading this you may already *be* at GitHub; any case do make sure you are signed in
  - On the upper-right-corner menu select **Your repositories**
- Create a repository: It will be a copy of this Cormorack repository called 'gallery'; proceed as follows:
  - Click the **New** button. It is green and has a little book icon next to the word 'New'
  - On the ensuing wizard page click the link **Import a repository**
  - On *that* wizard page in the box 'Your old repository's clone URL' type in: http://github.com/cormorack/gallery.git
  - Also:  In the Name box type: gallery
  - Click the **Begin import** button; this will start the process and you are done with this step 


You'll get an email when it is done but it should only take a few moments. To check the results: 
Return to your GitHub home page http://github.com and click on *Repositories*; where *gallery* should 
now be apparent as a link. Click that. You should see a file browser that lists some sub-folders and some 
files including that all-important `d'Orsay.ipynb` notebook file. If you scroll down below the file browser
you'll see... wait for it... ***this message***.


Any modifications you make to this repository are only applied to your copy. They do not affect the original
source repo owned by **Cormorack**. 


#### How to use this repo


This section assumes the previous section went fine and you have your own `gallery` repo here on GitHub.


- Log in to your Jupyter notebook server
- Start a terminal window
- Type in the command `git clone http://github.com/yourusername/gallery.git`
- Return to your notebook server tab in your browser
- Find and open the folder called `gallery`
- Click on the notebook `ocean.ipynb`
