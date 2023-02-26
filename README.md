# Kubernetes-setup
- Before configuring Kubernetes, the Virtual Datacenter (vDC) must be configured. This can be viewed as a group of computers that can communicate with one another across a network. If you don't have a physical infrastructure built up or a cloud infrastructure set up, you can build up vDC on PROFITBRICKS for a hands-on approach.
## Prerequisite

 ### Installing Docker: 
- On every Kubernetes instance, Docker is necessary. The steps to install Docker are listed below.

#### Step 1: 
 Log on to the machine with the root user account.

#### Step 2: 
Update the package information. Make sure that the apt package is working.
#### Step 3: 
Run the following commands.

``$ sudo apt-get update``


```$sudo apt-get install apt-transport-https ca-certificates```
#### Step 4: 
Add the new GPG key.

``` $ sudo apt-key adv --keyserver hkp://ha.pool.sks-keyservers.net:80 \ --recv-keys 58118E89F3A912897C070ADBF76221572C52609D```
#### Step 5: 
Update the API package image.

```$ sudo apt-get update```
- You can begin the actual installation of the Docker engine once the aforementioned processes have been finished. .however, you should first make absolutely sure that the kernel version you are using is accurate.

## Install Docker Engine

Run the following commands to install the Docker engine.

#### Step 1:
Logon to the machine.

#### Step 2: 
Update the package index.

```$ sudo apt-get update```

#### Step 3: 
Install the Docker Engine using the following command.

```$ sudo apt-get install docker-engine```

#### Step 4: 
Start the Docker daemon.

```$ sudo apt-get install docker-engine```

#### Step 5: 
To very if the Docker is installed, use the following command.

```$ sudo docker run hello-world```
