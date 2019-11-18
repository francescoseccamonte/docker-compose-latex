### Work on your LaTex files inside a docker container

The docker-compose file allows to start a container containing a full texlive installation.
It mounts the current directory under `/content`

Usage: `docker-compose run latex /bin/bash`
