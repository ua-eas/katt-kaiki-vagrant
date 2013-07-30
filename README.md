# Synopsis

This project should make it very easy to spin up a development environment for the [Kaiki Project](https://github.com/ua-eas/katt-kaikifs). It utilizes (Vagrant)[vagrantup.com] to ensure all development environments are standardized and easily deployed.

# Motivation

We needed a fast way to bring new developers up with a development environment. We also wanted to eliminate log installation steps and ensure everyone has a standard configuration.

# Installation

1. Install [VirtualBox](https://www.virtualbox.org/)

2. Install [Vagrant](vagrantup.com)

3. Download the box from [Google Drive](https://docs.google.com/file/d/0B6IXHSXb1jibSURpUjVwOWFTNWs/edit?usp=sharing)

4. Add the box:

		$ vagrant box add kaikiCrunchBang /path/to/downloaded/kaikiCB-1.0.box
		$ vagrant init kaikiCrunchBanggit 

5. Clone this project

6. Start the box:

		$ cd /path/to/kaiki-vagrant
		$ vagrant up

7. Login to the box as the user vagrant

8. Create an ssh key and register it with your user on github. Follow [these instructions](https://help.github.com/articles/generating-ssh-keys)

9. Clone the (kaikifs project)

		$ mkdir $HOME/code
		$ cd $HOME/code
		$ git clone git@github.com:ua-eas/katt-kaikifs.git kaiki

10. Run bundle install to download all of the required gems

		$ cd $HOME/code/kaiki
		$ bindle install

11. Done! You are now ready to start development on the Kaiki Project


# Contributors

Please do, fork the project and submit pull requests.