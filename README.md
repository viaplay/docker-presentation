# Docker presentation
*Presentaion for Viaplay Tech at 2014-01-10*

## Installation
### Linux
Install Virtualbox based off the [installation instructions](https://www.virtualbox.org/wiki/Linux_Downloads).

### MacOS

#### Install Homebrew
First, install [Homebrew](http://brew.sh/).

	ruby -e "$(curl -fsSL https://raw.github.com/mxcl/homebrew/go)"

#### Install Virtualbox and Vagrant
Install VirtualBox and Vagrant using [Brew Cask](https://github.com/phinze/homebrew-cask).

	brew tap phinze/homebrew-cask
	brew install brew-cask
	brew cask install virtualbox
	brew cask install vagrant

#### Check out the repository

	git clone git@github.com:viaplay/docker-presentation.git
	cd docker-presentation
	vagrant up && vagrant ssh


## Start playing 

`docker pull ubuntu` and try it out by doing `docker run -t -i ubuntu /bin/bash`