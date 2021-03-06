.. install.rst

Installation
============


Install using pip
-----------------

::

    pip install prisms-jobs

or, to install in your user directory:

::

   	pip install --user prisms-jobs
   
If installing to a user directory, you may need to set your PATH to find the 
installed scripts. This can be done using:

::

   	export PATH=$PATH:`python -m site --user-base`/bin


Install using conda
-------------------

::

    conda config --add channels prisms-center
    conda install prisms-jobs


Install from source
-------------------

1. Clone the repository:

::

    cd /path/to/
    git clone https://github.com/prisms-center/prisms_jobs.git
    cd prisms_jobs

2. Checkout the branch/tag containing the version you wish to install. Latest is ``v4.0.1``:

::

    git checkout v4.0.1

3. From the root directory of the repository:

::

    pip install .
   
or, to install in your user directory:

::

   		pip install --user .
   
If installing to a user directory, you may need to set your ``PATH`` to find the 
installed scripts. This can be done using:

::   

   		export PATH=$PATH:`python -m site --user-base`/bin



