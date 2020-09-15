# git-learning
## Clone
  Cloning remote repo to local<br>
 ```
 git clone https://github.com/sraja9580/git-learning
 ```

Copy the appropriate docker-compose binary from GitHub:

sudo curl -L https://github.com/docker/compose/releases/download/3.3/docker-compose -o /usr/bin/docker-compose

NOTE: to get the latest version (thanks @spodnet): sudo curl -L https://github.com/docker/compose/releases/latest/download/docker-compose-$(uname -s)-$(uname -m) -o /usr/local/bin/docker-compose

Fix permissions after download:

sudo chmod +x /usr/bin/docker-compose

Verify success:

docker-compose version
