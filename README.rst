Convore: Python API Wrapper
===========================

::

	 .d8888b  .d88b.  88888b.  888  888  .d88b.  888d888  .d88b.  
	d88P"    d88""88b 888 "88b 888  888 d88""88b 888P"   d8P  Y8b 
	888      888  888 888  888 Y88  88P 888  888 888     88888888 
	Y88b.    Y88..88P 888  888  Y8bd8P  Y88..88P 888     Y8b.     
	 "Y8888P  "Y88P"  888  888   Y88P    "Y88P"  888      "Y8888  
                                                              


Overview
--------

This is going to be awesome, and modeled after the excellent github2 module. 

Usage
-----

Hmm.. ::

	>>> from convore import Convore
	>>> convore = Convore('username', 'password')
	
	>>> convore.groups
	[<group id='123'>, ...]
	
	convore.groups[id] ?
	
	convore.groups.create(name, decription=None, slug=None)
	
	


Installation
------------

To install tablib, simply: ::

	$ pip install convore
	
Or, if you absolutely must: ::

	$ easy_install convore

But, you really shouldn't do that.
   
Contribute
----------

If you'd like to contribute, simply fork `the repository`_, commit your changes to the **develop** branch (or branch off of it), and send a pull request. Make sure you add yourself to AUTHORS_.


Roadmap
-------
- Documentation
- Write it!
- Test it!
- Fo shizzle

.. _`the repository`: http://github.com/kennethreitz/python-convore
.. _AUTHORS: http://github.com/kennethreitz/python-convore/blob/master/AUTHORS
