# blast-binder

[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/fomightez/blast-binder/master?filepath=BLAST%20on%20Command%20Line%20and%20Integrating%20with%20Python.ipynb)

*tl;dr:*  
Click any `launch binder` badge on this page to run command line-based BLAST inside your browser.

------

***BLAST: a software suite.***

This repository is for running BLAST in Jupyter environment provided by [MyBinder.org](https://mybinder.org/).  
Additionally, having BLAST working inside the Jupyter environment with interactive Python adds some convenient features that are illustrated. A utility script for moving command line-based BLAST results into Python is demonstrated.  

-------

Software
--------

The BLAST software is available directly from the authors at <a href="???">?????</a>.

The BLAST software is described in [this ???](???).

Users should cite:
???

The copyright information for the software is available ????.

***Clarifying Software Attribution: I, Wayne, am not involved in the BLAST software at all. Those listed above are the developers and distributors of BLAST. See their materials. I simply set up this repository to make the software useable on the command line without installation headaches.***

I, Wayne, did code a Python-based utility for use with the results from command line BLAST; it is available [here](https://github.com/fomightez/sequencework/tree/master/blast-utilities) and utilized in the notebooks in this repository to process the results and allow easily converting the results to other forms.

Usage
-----

This repository is set up to allow running the command line version of BLAST software after pressing the `launch binder` button above or below. The target use case is when you want to run custom BLAST or process a lot of sequences.

In the notebooks that can be launched, I have added some examples illustrating how to use the program and process the results easily with Python and convert to other forms.

Obviously, web-based BLAST is also available. Here are some of my favorite web-based BLAST resources:

* [NCBI's main BLAST page](https://blast.ncbi.nlm.nih.gov/Blast.cgi)
* [Saccharomyces Genome Database web interface](https://www.yeastgenome.org/blast-sgd)


Technical Details
-----------------

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site for more information about Binder.

Developed mainly from combining much of the binderized repo from [here](https://github.com/fomightez/qgrid-notebooks) with the ability to also run [PatMatch](https://github.com/fomightez/patmatch-binder).

Click this button below to begin using BLAST (or PatMatch, as well):

[![Binder](http://mybinder.org/badge.svg)](http://beta.mybinder.org/v2/gh/fomightez/blast-binder/master?filepath=BLAST%20on%20Command%20Line%20and%20Integrating%20with%20Python.ipynb)
