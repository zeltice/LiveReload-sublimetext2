LiveReload for Sublime Text 2 (w/o Compass compilation)
=========

A web browser page reloading plugin for the [Sublime Text 2](http://sublimetext.com "Sublime Text 2") editor.

This fork removes the Compass compilation feature from the main branch since many users do not want:
- Automatic config.rb file generation.
- Automatic CSS file generation.
- Redundant SASS/SCSS/Compass compilation.

Installing
-----

1.) Install [Sublime Package Control](http://wbond.net/sublime_packages/package_control "Sublime Package Control"), search for LiveReload and install.

2.) In Sublime Text 2, navigate to Preferences -> Browse Packages.  Find and open "LiveReload" folder.

3.) Replace the contents of livereload_st2.py with the contents of this fork's livereload_st2.py

4.) Close then restart Sublime Text 2.
