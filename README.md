python-dev
==========

python development related resources

INSTALLATION  (WINDOWS)
============================

1. install python :
    python.org (2.7)

2. install pip :
    download http://python-distribute.org/distribute_setup.py
    python distribute_setup.py
    https://raw.github.com/pypa/pip/master/contrib/get-pip.py
    python get-pip.py

3. install virtual env\n
    pip install virtualenv

You only need python + pip + virtualenv in the global enviroment. \n
Install everything else on virtual env.

4. create and activate a virtualenv)
    virtualenv default
    \default\Scripts\activate

MACHINE LEARNING TOOLCHAIN (numpy + scipy + scikit-klearn + pylab + ipython) on virtualenv

5. pip install ipython

6. numpy/scipy/scikit-learn on virtualenv
   ( pip install numpy doesnt work, see:
   http://stackoverflow.com/questions/6114115/windows-virtualenv-pip-numpy-problems-when-installing-numpy )
    download numpy installer (numpy.org)
    extrace the *-sse3-* installer using 7zip
    easy_install extracted installer previous step
    same for scipy as numpy (installer from scipy.org)
    download scikit-learn installer
    easy_install scikit-learn installer

7. downlaod matplotlib installer from http://matplotlib.org/downloads.html
   easy_install matplotlib installer



HAPPY MACHINE LEARNING !!!!!
