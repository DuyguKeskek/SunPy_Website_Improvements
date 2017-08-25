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

**First Month**

I used sphinx-bootstrap-theme as a basis of my project. I started implementing the navbar sections and put all the contents in the new website. Sphinx uses restructuredText as its markup language and I used RST for the entire website. I added a scrolling sidebar for navigation between headlines. At the end of the first month, the structure of the website was nicely prepared for revisions and improvements.

**Second Month**

The second month, I started to work on the blog section and used Ablog. However, the struggle was real, Ablog was full of bugs and it was the only option for blogging with Sphinx. Then, my mentors fixed the Ablog and did the magic. After that, I implemented the blogging system and made it possible for someone to write their own blog posts easily. Additionally, I integrated DISQUS to the blog and enabled commenting on the posts. At the end of the 2nd month, I made a lot of meetings with my mentors and started to work on the documentation theme.

You can have a look at the SunPy website repo below :

**SunPy Website**

* `Website Repo <https://github.com/DuyguKeskek/sunpy-website>`_
* `My contributons to the website <https://github.com/DuyguKeskek/sunpy-website/commits?author=DuyguKeskek>`_

**Final Month**

The final month, I used SunPy Sphinx Theme as a theme for the documentation and fixed a lot of issues that is related to docs. I made the documentation theme and also the website consistent throughout the final month and also fixed some bugs. I can comfortably say that the website is based on Sphinx and fully consistent ! The website gone live with the release of SunPy 0.8 and I'm really happy to see it.

You can have a look at the SunPy Sphinx Theme repo here :

**SunPy Sphinx Theme**

* `Theme Repo <https://github.com/sunpy/sunpy-sphinx-theme>`_
* `My contributons to the theme <https://github.com/sunpy/sunpy-sphinx-theme/commits?author=DuyguKeskek>`_

**Work Left**

There are still some issues on the list and there will always be since the website still needs improvements and fixes. I plan to work on these issues after the GSoC and contribute to open source !

* `Issues <https://github.com/sunpy/sunpy-sphinx-theme/issues>`_

Blog
----

Here are the blog posts about the development process I wrote during GSoC.

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

This website is created using `SunPy Sphinx Theme <https://github.com/sunpy/sunpy-sphinx-theme>`_

.. toctree::
   :maxdepth: 2
   :caption: Contents:
