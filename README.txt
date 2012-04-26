
The git_deploy module requires the glip library. git_deploy is tested 
against version 1.0 available at https://github.com/halstead/glip/tree/1.0
All updates to glip are tracked on github. glip is licensed under GPLv2.

To install:
1. Download the zip file from https://github.com/halstead/glip/zipball/1.1
   or run these git commands,
   git clone git://github.com/halstead/glip.git
   cd glip
   git checkout 1.1

2. Place the glip directory at sites/all/libraries/glip so that you have
   sites/all/libraries/glip/lib

An alternative to using git_deploy is to install modules and themes using the
"drush pm-download" command with options "--package-handler=git_drupalorg
--gitinfofile". This performs a git clone and checkout and then inserts the
desired version information into the .info file. The "drush make" command will
automatically write packaging information without additional options.
