# SVN - Docker mod for code-server

This mod installs subversion into code-server, to be installed/updated during container start.

In code-server docker arguments, set an environment variable `DOCKER_MODS=robomagus/mods:code-server-svn`

If adding multiple mods, enter them in an array separated by `|`, such as `DOCKER_MODS=linuxserver/mods:code-server-python3|robomagus/mods:code-server-svn`
