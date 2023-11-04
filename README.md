# canawww

Webpage of the CANA team, LIS.  
[https://cana.lis-lab.fr/](https://cana.lis-lab.fr/)  
[https://kevin.perrot.pages.lis-lab.fr/canawww/](https://kevin.perrot.pages.lis-lab.fr/canawww/)

# how-to

1. Touch one the following files:
  * ``_posts/2013-09-01-cana.md``: main page (markdown)
  * ``_bibliography/references.bib``: bibtex entries (please follow the file's **conventions**)
  * ``_data/seminars.yml``: seminars (yaml)
2. Push your modifications, the website rebuilts automagically after ``~1`` minute.

# technical details

Other files that may be touched:
* ``.gitlab-ci.yml``: gitlab file to auto run jekyll at each push
* ``_config.yml``: jekyll config file
* ``_layout/index.html``: main page layout
* ``_includes/sidebar.html``: the side bar is here
* ``_sass/hydeout/_variables.scss``: main css
* ``slides/``: put the slides here, named ``yyyymmdd-Surname.pdf`` (and copy this name under field ``slides:`` in ``seminars.yml``).

# TODO
* add abstracts with a box similar to .bib


