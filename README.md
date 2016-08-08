# jekyll-ion-site

Code for lab webpage, built with jekyll using the Ion theme.

## To get started:

* Clone the git into your own repo.
* Install Jekyll

     gem install jekyll

## To update:

* Add person, post, or publication to the _posts/ folder.
  * Set YAML front matter appropriately (see XXXX-YY-ZZ* templates)
  * Name files as YYYY-MM-DD-Title.md
* Build site

     jekyll build

* Copy site to server (see me for hostname and password)

     rsync -av _site/* HOSTNAME:~/web/

* Check online to confirm changes




