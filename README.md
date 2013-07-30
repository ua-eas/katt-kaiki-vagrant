Synopsis

This project should make it very easy to spin up a development environment for the (Kaiki Project)[https://github.com/ua-eas/katt-kaikifs]. It utilizes (Vagrant)[vagrantup.com] to ensure all development environments are standardized and easily deployed.

Motivation

We needed a fast way to bring new developers up with a development environment. We also wanted to eliminate log installation steps and ensure everyone has a standard configuration.

Installation

1. Install (VirtualBox)[https://www.virtualbox.org/]
2. Install (Vagrant)[vagrantup.com]
3. Download the box from Google Drive https://docs.google.com/file/d/0B6IXHSXb1jibSURpUjVwOWFTNWs/edit?usp=sharing
4. Add the box:
```
$ vagrant box add kaikiCrunchBang /path/to/downloaded/kaikiCB-1.0.box
```
5. Clone this project
6. Start the box:
```
$ cd /path/to/kaiki-vagrant
$ vagrant up
```

Contributors

Please do, fork the project and submit pull requests.