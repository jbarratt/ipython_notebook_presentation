Welcome to the materials for the IPython Notebook presentation!

You won't find a typical slide deck here; much of the presentation consisted of live demos.

However, all of the notebooks demonstrated during the session are included.

[View the slides online](https://rawgit.com/jbarratt/ipython_notebook_presentation/linuxcon/Presentation.slides.html#/). This is a reveal.js HTML presentation.

You can also clone the repository, then just open up Presentation.slides.html in your browser. However, the demo links to the live notebooks will not work.

If you would like to open pre-rendered copies of them you can do so at [nbviewer](http://nbviewer.ipython.org/), but many of these demos only make sense to run 'live.'

If you want to go any further than that, you'll need to install IPython Notebook.

There are a variety of methods, depending on your tolerance for hackishness.

The official page at 

    http://ipython.org/install.html 

has good suggestions for various platforms. If you're set up with pip, you can just

    $ pip install ipython[all]

To get up and running for the full presentation mode:

1. get 2 terminal prompts going (I use tmux, but suit yourself)
2. cd into the directory where you unpacked this archive
3. In one of them, run

    $ ipython notebook

    This should open up a new browser window showing the list of all the notebooks. You can then click on them to explore.

4. In the other, run

    $ ipython nbconvert --to slides --post serve

    This will open up the slide deck in your browser. The live notebook links will most likely be working at this point.


Feel free to contact me at jbarratt@serialized.net with any questions or if there are notebooks you'd like to see expanded in some way.
