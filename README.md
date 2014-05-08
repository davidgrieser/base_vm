# Setup

## Prerequisites

You need to have installed the following:

* VirtualBox 4.2+
* Vagrant 1.4+
* Git 1.7+

## Pre-Install

Clone this repo:

```
git clone git@github.com:davidgrieser/link_manager.git
```

## Installation 

Open up a terminal and type the following:

```
vagrant up
vagrant ssh
cd /vagrant
```

## Verification

This should put you into the local directory that Vagrant was started in.

* ruby 2.1.1
* Rails 4.1.1

To confirm this you can use the following commands:

```
ruby -v
rails -v
```

