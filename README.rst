.. image:: docs/_static/img/logo/480px-Open-ZFS-Secondary-Logo-Colour-halfsize.png
.. highlight:: sh

OpenZFS Documentation
=====================

Public link: https://openzfs.github.io/openzfs-docs/

Building Locally
----------------

Install Prerequisites
~~~~~~~~~~~~~~~~~~~~~

::

   # For Debian based distros
   sudo apt install pip3
   # For RPM-based distros
   sudo yum install python3-pip

   pip3 install -r docs/requirements.txt
   # Add ~/.local/bin to your $PATH, e.g. by adding this to ~/.bashrc:
   PATH=$HOME/.local/bin:$PATH

Build
~~~~~

::

   cd docs
   make html
   # HTML files will be generated in: _build/html
