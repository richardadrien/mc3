Webpage of the MC3 team, I3S.  

[https://github.com/richardadrien/mc3/](https://github.com/richardadrien/mc3/)

Adapted from 

[https://kevin.perrot.pages.lis-lab.fr/canawww/](https://kevin.perrot.pages.lis-lab.fr/canawww/)

with the geneoristy of Kévin Perrot 

# How-to

1. Touch one the following files:
  * ``_posts/2023-11-01-home.md``: main page (markdown)
  * ``_bibliography/references.bib``: bibtex entries (please follow the file's **conventions**)
  * ``_data/seminars.yml``: seminars (yaml)
  * ``slides/``: put the slides here, named ``yyyymmdd-Surname.pdf`` (and copy this name under field ``slides:`` in ``seminars.yml``).
2. Push your modifications, the website rebuilts automagically after ``~1`` minute.

# Technical details

Other files that may be touched:
* ``_includes/copyright.html``: the copyright sidebar is here
* ``_includes/custom-nav-links.html``: to add links to home in the sidebar
* ``_config.yml``: jekyll config file, sidebar title and subtitle are here

Other files that cannot be touched, adapted from hydedout: 
* ``_includes/sidebar-icon-links.html``: hacked from hydeout to remove sidebar incons
* ``_layouts/post.html``: hacked from hydeout to make a single post as the home page
* ``index.html``: almost empty index needed by hydeout
