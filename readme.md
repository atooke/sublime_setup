1. Install following plugings:

Autopep8 – helps format code when you hit save to save time formatting
Autodocstring -  (adds empty docstring to method to save time typing from scratch)
Side bar enhancements– adds more options when you right click over the menu on left
Sublimelinter & sublimelinter-pylint – adds in pylint or flake8 linting on save, needs to be configured
Compare side-by-side – helps see differences between files
Markdown preview – if you are creating markdown files you can preview what they look like in chrome
Jedi – for auto complete
SFTP – upload files to remote server / edit files of remote sever
Isort – sort imports at top of file
brackethighlighter - color codes nested brackets so you can see which belongs to which


2. Install the following in anaconda base install (not virtual env)
* autopep8
* flake8
* pylint
* black
* yapf

3. Update config in sublime for sublime linter:
* sublime text=>preferences=>package settings=>sublime linter=>settings.
* see sublime_linter_settings.txt file in report to copy/paste.
* updater lines 4-5 with the correct path to base anaconda where you installed the additional packages in step2
* This will run flake8 & pylint on save.  Also any errors/warning will add yellow/red circle to line gutter to easily find errors.

4. Setup jedi:
* see file jedi_settings.txt
* change line 9 to correct base anaconda/python installation
