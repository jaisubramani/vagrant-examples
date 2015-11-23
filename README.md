# vagrant-examples
To demonstrate different kinds of Vagrantfile

## prerequisites

* vagrant (1.7.4)
* virtualbox (5.0.6)

### 1. apache

standup an apache server (for directory browsing)

#### usage

`$ cd apache`

`$ vagrant up`

open the browser and hit [port 8080](http://localhost:8080)

### 2. gitlab

standup a gitlab instance

#### usage

`$ cd gitlab`

`$ vagrant up`

open the browser and hit [port 9080](http://localhost:9080)

refer [gitlab documentation](https://about.gitlab.com/downloads/#ubuntu1404) for login credentials

### 3. jenkins

standup a jenkins instance using custom settings (private_network, memory and cpus)

#### usage

`$ cd jenkins`

`$ vagrant up`

open the browser and hit [192.168.56.10:8080](http://192.168.56.10:8080)

### 4. multi-machine

standup multi-machine environment for web and db tiers using ngnix and mysql

#### usage

`$ cd multi-machine`

`$ vagrant up`

or

`$ vagrant up web01 db01`

open the browser and hit [192.168.75.10](http://192.168.75.10)
