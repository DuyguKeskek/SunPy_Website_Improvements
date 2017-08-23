Introduction
============

The SunPy website and the SunPy documentation do not have a consistent theme. This project would design a new look for both the website and the documentation and then implement this as a general website theme and as a sphinx theme for the documentation.

Objective
---------

This project will design a new look for the SunPy website, and implement this as a HTML/CSS theme which can be used by the current Jekyll website, and any future technology used by the website.

Once this is done a sphinx theme will be developed that has the same design as the SunPy website, and can be used by the main SunPy documentation and any SunPy affiliated packages.

Extensions
----------

As extensions to this project any of the following things could be implemented:

* Implement a registry of SunPy Affiliated packages on the website.
* Move away from Jekyll to a Python based static site generator. (Sphinx, Nikola, Pelican etc.)
* Write a sphinx extension that maintains an up to date list on the main website of the instruments and data products supported by the sunpy library.
* Improve the content of the SunPy website.

Milestones
----------

GSoC 2017 Coding Starts
~~~~~~~~~~~~~~~~~~~~~~~

* Have evaulated which tools will be used to undertake the project in collaboration with the mentors.

GSoC 2017 Midterm
~~~~~~~~~~~~~~~~~

* Have designed and implemented the website theme.

GSoC 2017 Final
~~~~~~~~~~~~~~~

* Have created the sphinx theme and finished any extensions to the base project.


Google Summer of Code Contribution
==================================

Code
----

During GSoC, I worked on two different repos and had write access to push commits into them. 

To see the commits done, please follow the links.

**SunPy Website**

* `Website Repo <https://github.com/DuyguKeskek/sunpy-website>`_
* `My contributons to the website <https://github.com/DuyguKeskek/sunpy-website/commits?author=DuyguKeskek>`_

**SunPy Sphinx Theme**

* `Theme Repo <https://github.com/sunpy/sunpy-sphinx-theme>`_
* `My contributons to the theme <https://github.com/sunpy/sunpy-sphinx-theme/commits?author=DuyguKeskek>`_

Blog
----

Here is the blog posts I wrote during GSoC.

* `Congratulations ! Your proposal has been accepted…WUT ? <https://medium.com/@duygukeskek/congratulations-your-proposal-has-been-accepted-wut-b9f255139d8>`_
* `Good Bye Community Bonding Period ! <https://medium.com/@duygukeskek/good-bye-community-bonding-period-446b01e03813>`_
* `First 2 weeks of GSoC in a nutshell <https://medium.com/@duygukeskek/first-2-weeks-of-gsoc-in-a-nutshell-4ce7878a932e>`_
* `A new website, A better SunPy ! <https://medium.com/@duygukeskek/a-new-website-a-better-sunpy-3b3ca34b6970>`_
* `It’s the time for the Documentation Theme <https://medium.com/@duygukeskek/its-the-time-for-the-documentation-theme-acd6da85c9fc>`_
* `SunPy Website Improvements <https://medium.com/@duygukeskek/sunpy-website-improvements-70e58abbb28>`_

Accessing the project
=====================

* `Google Summer of Code Page <https://summerofcode.withgoogle.com/projects/#5460790269181952>`_
* `SunPy Website <http://sunpy.org/>`_


Using the theme
===============

To use the theme, simply put this line in your conf.py ::

	from sunpy_sphinx_theme.conf import *

.. toctree::
   :maxdepth: 2
   :caption: Contents:
