Tao of Ruby
===========

A hand-wavy talk about some old man's philosophical mumbo-jumbo.

setup
=====

    rbenv local 1.9.3-p429 # if you use rbenv
    gem install bundler
    bundle
    rake generate

commands
========

`rake generate` will generate slides/slides.html from slides/slides.md

`rake` will start a filesystem watcher to auto-gen the slides when slides/slides.me changes.

notes
=====

* you will need ruby 1.9.3 ...ruby 2.0 breaks sass, apparently.
* `init.txt` - speaker setup reminders
* `todo` - the blueprint

editing
=======

* slides/css/slides.css
* slides/slides.md
