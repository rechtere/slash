.. Slash documentation master file, created by
   sphinx-quickstart on Fri Feb 22 23:34:56 2013.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

.. container:: row-fluid

   .. container:: span2 visible-desktop
   
     .. container:: brand-logo
        
	.. image:: transparent.png
	   :height: 2em
	   :align: left           

        .. image:: slash-logo.png
           :align: left
	   :width: 120px

   
   .. container:: span10

     .. raw:: html

      <h1>Welcome to Slash</h1>

     Slash is a testing framework written in Python. Unlike many other testing frameworks out there, Slash focuses on building in-house testing solutions for large projects. 
   
     Slash provides several key features:
   
     * A solid execution model based on fixtures, test factories and tests. This provides you with the flexibility you need to express your testing logic.
     * A rich configuration mechanism, helping you setting up your environment parameters and their various flavours.
     * A plugin architecture, greatly simplifying adding extra functionality to your framework.

     .. raw:: html
        
        <h2>Table of Contents</h2>

     .. container:: row-fluid
     
       .. container:: span6
       
         .. toctree::
           :maxdepth: 2
      
           getting_started
           assertions
           configuration
           logging
           hooks
           plugins

       .. container:: span6

         .. toctree::
           :maxdepth: 2

           exceptions
	   test_metadata
           features
           building_solution
	   advanced_usage
           changelog
           development




Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`

