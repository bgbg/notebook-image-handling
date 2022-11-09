# Handle images in Jupyter notebook.

Frequently, we want to re-use images generated in a Jupyter notebooks.
To do that, one may either copy the image to the clipboard and save it elsewhere
or, alternatively, make sure to call `fig.savefig` every time a figure is created.
This package aims to make the later process simpler and with fewer boilerplate code.
At the beginning of a notebook,  instantiate a handler object. You may specify a unique 
location for the saved figures. If you don't a sensible default location will be choosen. 
Then, by simply calling the object, a numbered figure file  will be created andthe figure 
will be displayed in  the notebook.

That's it! As simple as that!

See the demo for a more detailed examples.
