.. include:: cyverse_rst_defined_substitutions.txt
.. include:: custom_urls.txt

|CyVerse_logo|_

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`_

**Introduction**
=================

Various types of molecular interactions are principal determinants of the system-scale behaviour of the cell. These interactions include protein–protein interaction, metabolic, signaling and transcription-regulatory networks. Recent innovations and continuing falling costs of technologies have enabled researchers to catalogue the component molecules of these networks not only at a genome-wide scale but also under a large number of different experimental conditions (e.g. time points, cell types, stimuli and treatments). In this tutorial, we will use Discovery Environment apps to analyze a sample dataset of five transcription factors that control the rate of ~14k genes. 

Some experience with python programming and command-line is required to follow this tutorial. Download code and sample data for this tutorial from the `github repo <https://github.com/enggiqbal/Webinar-NetworkAnalysis.git>`_.

----

Learning Objectives
--------------------

- Intro to network analysis and visualization
- Why networks are difficult to visualize and understand
- Powerful combination of tools and techniques to do network analysis
- How to manipulate, slice, and dice networks in order to analyze large networks
- Using CyVerse Discovery Environment apps to do network analysis and visualization

----

Tutorial Maintainer(s)
------------------------

Who to contact if this guide needs fixing. You can also email
`learning@CyVerse.org <learning@CyVerse.org>`_

.. list-table::
    :header-rows: 1

    * - Maintainer
      - Institution
      - Contact
    * - Iqbal Hossain
      - CyVerse / UA
      - hossain@arizona.edu
    * - Reetu Tuteja
      - CyVerse / UA
      - reetututeja@cyverse.org
----

.. toctree::
	:maxdepth: 2

	Step One <step1.rst>
  Perform network analysis using Discovery Environment VICE app <step2.rst>
  Further Reading <step3.rst>
	
..
	#### Comment:This tutorial can have multiple pages. The table of contents assumes
	you have an additional page called 'Step One' with content located in 'step1.rst'
	Edit these titles and filenames as needed ####


Prerequisites
-------------

Downloads, access, and services
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need access to the following services/software*

..
	#### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Prerequisite
      - Preparation/Notes
      - Link/Download
    * - CyVerse account
      - You will need a CyVerse account to complete this exercise
      - |CyVerse User Portal|
    * - Cyberduck
      - Standalone software for upload/download to Data Store
      - |Download Cyberduck|

Platform(s)
~~~~~~~~~~~

*We will use the following CyVerse platform(s):*

 ..
   #### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Platform
      - Interface
      - Link
      - Platform Tour
    * - Data Store
      - GUI/Command line
      - |Data Store|
      - |Data Store Guide|
    * - Discovery Environment
      - Web/Point-and-click
      - |Discovery Environment|
      - |Discovery Environment Guide|

Application(s) used
~~~~~~~~~~~~~~~~~~~
..
	#### Comment: these tables are examples, delete whatever is unnecessary ####

**Discovery Environment App(s):**

.. list-table::
    :header-rows: 1

    * - App name
      - Version
      - Description
      - App link
      - Notes/other links
    * - Jupyterlab-GraphViz
      - 1.0
      - JupyterLab with Graphviz package 
      -	|CyVerse_launch|
      - |Original App Documentation|



Input and example data
~~~~~~~~~~~~~~~~~~~~~~

*In order to complete this tutorial you will need to have the following inputs prepared*

..
	#### comment: delete any row not needed in this table ####

.. list-table::
    :header-rows: 1

    * - Input File(s)
      - Format
      - Preparation/Notes
      - Example Data
    * - query.cyjs
      - Cytoscape json
      - Data downloaded from ConnecTF
      - iplantcollaborative > example_data > Network_analysis_webinar

----

**Fix or improve this documentation**

- Search for an answer:
  |CyVerse Learning Center|
- Ask us for help:
  click |Intercom| on the lower right-hand side of the page
- Report an issue or submit a change:
  |Github Repo Link|
- Send feedback: `learning@CyVerse.org <learning@CyVerse.org>`_

.. comment:

   Uncomment the below and fix with this repo's information if citing

   **Citation**

   You may cite this work as:
   [Repository Title]
   [Author(s)]
   [Repository Release Version]
   [DOI: Zenodo DOI link (generated from Github Release/Zenodo)]
----

|Home_Icon|_
`Learning Center Home <http://learning.cyverse.org/>`__


.. Comment: Place Images Below This Line
   use :width: to give a desired width for your image
   use :height: to give a desired height for your image
   replace the image name/location and URL if hyperlinked


 .. |Clickable hyperlinked image| image:: ./img/IMAGENAME.png
    :width: 500
    :height: 100
 .. _CyVerse logo: http://learning.cyverse.org/

 .. |Static image| image:: ./img/IMAGENAME.png
    :width: 25
    :height: 25



.. Comment: Place URLS Below This Line

   # Use this example to ensure that links open in new tabs, avoiding
   # forcing users to leave the document, and making it easy to update links
   # In a single place in this document

   .. |Substitution| raw:: html # Place this anywhere in the text you want a hyperlink

      <a href="REPLACE_THIS_WITH_URL" target="blank">Replace_with_text</a>


.. |Github Repo Link|  raw:: html

   <a href="FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX_FIX" target="blank">Github Repo Link</a>

.. |Download Cyberduck| raw:: html

   <a href="https://cyberduck.io/" target="blank">Download Cyberduck</a>

.. |Original App Documentation|  raw:: html

   <a href="https://cyverse-network-analysis-tutorial.readthedocs-hosted.com/en/latest/step2.html" target="blank">Original App Documentation</a>

.. |CyVerse_launch| raw:: html

   <a href="https://de.cyverse.org/de/?type=apps&app-id=ccb0264c-6c8e-11eb-94c7-008cfa5ae621&system-id=de" target="blank">CyVerse launch</a>
