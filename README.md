ownCloud Markdown Editor
=================

Extends the texteditor in ownCloud with a live preview for markdown files

![Markdown Editor](http://i.imgur.com/Iot1pBd.png)

Requirements
---

Currently this requires ownCloud and the texteditor app to be installed from git master or git stable5 or any future release (after 2013-04-24) of oC 5 or higher.

Installation
---

- Clone the app into the **/var/www** directory:

    ``git clone https://github.com/icewind1991/owncloud-markdown.git``


- Link the app ownCloud's apps folder as 'files_markdown':

  ``ln -s /var/www/owncloud-markdown /var/www/owncloud/apps/files_markdown``

- Activate the App.