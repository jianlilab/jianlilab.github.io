# Documents 

This .md file (tries to) explain function of different files in the process of building the lab website.

First written on 10/11/2018 by Haoxue Fan

Last modified on 10/11/2018 by Haoxue Fan

---

 [Folder] _site

generate automatically when run the website on local virtual werver

 [Folder] _includes

 [Folder] _posts

 [Folder] links

 [Folder] _data

* store .yml files related to information displayed on several pages
* it seems that the length of it could be changed (e.g. add a lot of publications / students)
* could write comments inside of it (e.g. if a student leaves, could comment his / her info in the members.yml, and copy-paste it into alumni.yml)

​	alumni.yml

​	- alumni info **(following specific format which should be corresponding to ...)**

​	members.yml

​	- current member info **(following specific format which should be corresponding to …)**

​	nvlinks.yml

​	- info about in which folder the main page of subpages are (index.html) **(NOTE: private is now blank)**

​	publications.yml

​	- publication info **(following specific format which should be corresponding to …)**

 [Folder] _layouts

​	default.html 

​	- how each page is displayed by default (use header.html and footer.html in folder _includes)

​	home.html

​	- specify how homepage is displayed (as we can see, there a pic on top, a *contact info* sidebar.html on right, which also from folder _includes)

​	members.html

​	- specify how member is displayed (as we can see, there a pic on top, an *alumni* sidebar.html on right, which also from folder _includes)

​	post.html

​	postlist.html

 [Folder] research

_config.yml

index.md

* plain text displayed on homepage

 [Folder] static

 [Folder] contact

CNAME

Gemfile.lock

 [Folder] publications

 [Folder] news

news.xml

 [Folder] members

Gemfile

* enable to run on local virtual server (need to be created manually at beginning)

404.md

* plain text displayed when a page couldn't be found (self-tailored 404)

README.md

* introduction and basic instruction about this lab webpage

