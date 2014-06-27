# Docker presentation
*Easy start and do basic Docker stuff for presentations*

## Installation

### Linux
Install Docker for your flavor - [installation instructions](https://docs.docker.com/installation/).

### Mac OS X - Vagrant

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

	git clone git@github.com:jacksoncage/docker-presentation.git
	cd docker-presentation
	vagrant up && vagrant ssh

### Mac OS X - boot2docker

 * Download the latest release of the [Docker for OSX Installer](https://github.com/boot2docker/osx-installer/releases)
 * Run the installer, which will install VirtualBox and the Boot2Docker management tool. 
 	![1](http://cl.ly/image/0C2r113u3W04/osx-installer.png "1")
 * Run the Boot2Docker app in the Applications folder
 	![1](http://cl.ly/image/1E2i1y1K2n1m/osx-Boot2Docker-Start-app.png "1")

## Start playing 

`docker pull ubuntu` and try it out by doing `docker run -t -i ubuntu bash`