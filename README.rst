======================
Practical GIT Tutorial
======================

Homepage for the Practical GIT Tutorial documentation

This project holds the source code of the documentation publically available at the following URL:


   http://www.great-a-blog.co/practical-git-tutorial/


How to edit documentation ?
===========================

I'm not a good technical writer. That's a job and some are paid for this talent. My main goal is just
to help GIT user to quickly learn this tool.

Also, I'm not native english speaker. If you find mistakes, please send me at least an email. You
can use this address: gaetan [ at ] xeberon.net

How to fork?
------------

To fork this documentation and edit it, simply:

- fork this project (https://github.com/Stibbons/practical-git-tutorial)
- edit your changes
- submit to me a Pullrequest (https://help.github.com/articles/creating-a-pull-request)

That's all. Once accepted, the official documentation will be automatically updated.

Compilation requirements
------------------------

- I use sphinx-builder to build this documentation (http://sphinx-doc.org/index.html)
- with the cloud theme (http://pythonhosted.org/cloud_sptheme/cloud_theme.html)
- I've added the bash script and batch files to support Linux, Mac OS (with homebrew) and Windows compilations.
- The easiest is to use the ``requirements.txt`` file: ``pip install -r requirements.txt``
- On windows you need msysw to have the unix tools like ``bash``, ``make``...

How automatic compilation of the documentation is done?
=======================================================

This github project is linked to the Read my Doc service, which triggers a rebuild of the online
documentation when changes are merged.

A travis build is also triggered (I prefere the notification from travis-ci).

Used online services
--------------------

- GitHub: https://github.com/Stibbons/practical-git-tutorial/
- Read the Docs: https://readthedocs.org/projects/practical-git-tutorial/
- Travis-CI: https://travis-ci.org/Stibbons/practical-git-tutorial


Which tool to edit reStructuredText ?
=====================================

I mainly use Sublime Text 3 as my main editor and its quite usefull reStructuredText plugin

- Sublime Text 3: http://www.sublimetext.com/
- reStructuredText plugin: https://github.com/dbousamra/sublime-rst-completion


Edition tips
============

- Try to keep files short. Reading a loooooooooong file is annoying. Don't try to detail everything.
  Just stick to the essential matters.
- Keep organised. Chapters are splitted in different files, once by section, this helps finding where to
  modify when a change is to be done. Keep the same structure.


References for this documentation
=================================

- TBD
