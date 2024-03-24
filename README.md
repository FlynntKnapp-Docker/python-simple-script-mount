# Docker Python Simple Script Mount Current Directory

Mount current directory in a Docker container.

1. `docker run -it -v $(pwd):/app -w /app python:3 bash`
1. `python goodbuy.py`

## Start Contianer and Install and Run `htop`
1. `docker run -it -v $(pwd):/app -w /app python:3 bash`
1. `apt-get update`
1. `apt-get install -y htop`
1. `htop`
