Programming StyleThe website exhibits "good" programming style, although definitely not the only way to do things.

Some of the programming design decisions reflected:

The architecture adheres more to the "model-view-adapter" convention, where the view is unaware of the source of data and the model is unaware of how any data might be presented. The controllers are go-betweens.
A "master template" lets each controller focus only with building its part of a webpage.
A base controller takes care of assembling finished pages, using the master template.
Using the template parser eliminates PHP code from the views, where possible.
Mock data for the recent news and most recently active threads, means that the website can be tested locally, without needing access to the live forum database.
View fragments are used to style single "records" on their own, improving cohesion.
The CodeIgniter4 project folder is assumed to be at the same level as this project folder, and managed independently.
An ".htaccess" file is incorporated, to configure Apache to remove index.php from any URLs.
Sitemap
The site has a simple structure ... basically two-level (homepage and then content pages). There are a couple of additional pages, for related but subordinate information, accessible from the footer navbar.
Appropriate comments are found in each of the controllers
Project Folders
/application	the obvious
/data	zipped files for downloading, avatars
/public	the served face of the website
/public/assets CSS, javascript & media /public/user_guide Symbolic link to the current CI user guide (v3) /public/userguide2 Placeholder for the CI2 user guide /public/userguide3 Placeholder for the CI3 user guide /tests Provision for unit testing (not used) /writable Writable folder for temporary files
You may have noticed that there is no system folder. That is on purpose ... the website assumes that the CodeIgniter4 framework has been installed locally at the same level as the website project.
License
Please see the license agreement
Resources
User Guide
Community Forums
Community IRCAcknowledgement
The CodeIgniter Project would like to thank the Reactor Engineers, EllisLab, all the contributors to the CodeIgniter project, and you, the CodeIgniter user.

This repository is maintained by James Parry, Project Lead.
