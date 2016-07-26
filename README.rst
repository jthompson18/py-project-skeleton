=========================
 py-project-skeleton
=========================

This is a light weight python playground for small projects and explorations.

Project Setup
=============

Instructions
------------

#. Clone the template project, replacing ``my-project`` with the name of the project you are creating::

        git clone https://github.com/jthompson18/py-project-skeleton.git my-project
        cd my-project

#. Install homebrew_, pip_ and virtualenv_::

        ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
        sudo chown -R $USER:admin /usr/local
        sudo easy_install pip
        sudo pip install virtualenv

#. Create a new virtual environment for your project:

   With virtualenv_::

       virtualenv env
       source env/bin/activate

   If you are new to virtual environments, please see the `Virtual Environment section`_ of Kenneth Reitz's Python Guide.

#. Install the project's development and runtime requirements::

        pip install -r requirements-dev.txt

#. Test with ipython (optional)::
        
        ipython is installed in the previous step. In your env run:

        1. run ipython (the following steps are in ipython)
        2. from playground import helloWorld as hW
        3. hW.helloWorld()

        The line `Hello World!` should print in your terminal. To quit ipython just type `exit` and press the return key

**Project setup is now complete!**

Dependencies
------------

This project's requirements-dev.txt file contains a handful of data analytics and mathematics libraries.
If other dependencies are needed make sure your virtualenv is activated run `pip install package_name && pip freeze > requirements-dev.txt`.
This should install the package and update the requirements-dev.txt file.

The Pre installed dependencies are:
		
		numpy
		scipy
		mympy
		matplotlib

.. _homebrew: http://brew.sh/
.. _pip: https://pip.pypa.io/en/stable/
.. _virtualenv: http://www.virtualenv.org/en/latest/
.. _Virtual Environment section: http://docs.python-guide.org/en/latest/dev/virtualenvs/


Opening Issues
==============

Templates

- `New Issue`_
- `Feature Request`_

.. _New Issue: https://github.com/jthompson18/COMP330/issues/new?body=%23%23%23%20Description%20of%20issue%0A%0A%0A%23%23%23%20Reproduction%20Steps%0A%0A%0A%23%23%23%20Actual%20behavior%2Fresult%0A%0A%0A%23%23%23%20Expected%20behavior%2Fresult%0A%0A%0A%23%23%23%20Affected%20Org%2C%20Group%2C%20Account%0A%0A%0A%23%23%23%20Additional%20info%20(browser%20detail%2C%20etc)%0A%0A%0A
.. _Feature Request: https://github.com/jthompson18/COMP330/issues/new?body=%23%23%20Description%0A%0A%0A%23%23%20Reason%0A%0A%0A%23%23%20Background%0A%0A%0A

