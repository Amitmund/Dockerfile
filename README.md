# Dockerfile collection.

## Quick note on this repo

…or create a new repository on the command line

echo "# Dockerfile" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/Amitmund/Dockerfile.git
git push -u origin master

…or push an existing repository from the command line

git remote add origin https://github.com/Amitmund/Dockerfile.git
git push -u origin master

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

## All the Dockerfile are under the sub-directory of this repo.


## Example of building image from github docker file. ##
docker build -t "amit_ubuntu_apache" git://github.com/Amitmund/docker_ubuntu_apache/
[or]
docker build -t "amit_ubuntu_apache" github.com/Amitmund/docker_ubuntu_apache/


### Not yet got the luck to directly call the subfolder repo Dockerfile
