# Tutorial of a multi-directory IPython notebook

This repo contains IPython notebooks that demostrate how the new web services and URL scheme work for multidirectory support.

The current branch for this version of IPython is found [here.](https://github.com/Zsailer/ipython/tree/multidir)

###Steps to begin testing this feature
To test this service, checkout this branch and download this repository. The notebooks in the root directory tell the story behind designing a multi-directory IPython web-service. You can view them on NBViewer below.

* [Multi-directory IPython notebook](http://nbviewer.ipython.org/urls/raw.github.com/Zsailer/multidir_ipynb_tutorial/master/Multi-directory%2520IPython%2520notebook.ipynb)
* [Web service design](http://nbviewer.ipython.org/urls/raw.github.com/Zsailer/multidir_ipynb_tutorial/master/Web%2520service%2520design.ipynb)

Go ahead and try to navigate through your directories! 

###How to use it
The main points here:

* The dashboard has the ```/tree``` tag in the URL. To navigate into sub-directories, simply add the folder name after this tag (i.e. ```tree/foo/bar```).
* When you open a notebook, the ```/notebooks``` tag is added to the front of URL. Notebooks in sub-directories have the path and notebook name (NO notebook ID!) in the URL as well (i.e. ```notebooks/path/to/notebook.ipynb```).