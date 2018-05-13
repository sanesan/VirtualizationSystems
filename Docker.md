# Docker Installation.

## 1. Update the installed packages and the repositories:

<code>sudo apt-get update</code>
 
![sudo apt-get update!](https://github.com/sanesan/docker4linux/blob/master/img/1.PNG)

## 2. Install the necessary packages:

<code>sudo apt-get install apt-transport-https ca-certificates curl software-properties-common</code>

![sudo apt-get install apt-transport-https ca-certificates curl software-properties-common!](https://github.com/sanesan/docker4linux/blob/master/img/2.PNG)

## 3. Add Docker's official GPG key:

<code>curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -</code>

And verify that we have the key:

<code>sudo apt-key fingerprint 0EBFCD88</code>

![keyofdocker!](https://github.com/sanesan/docker4linux/blob/master/img/3-1.PNG)

## 4. Add the Docker repository:

Execute <code>lsb_release -cs</code> to see our distribution, in this example we have <code>xenial</code>.

<code>sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu xenial stable"</code>

![xenial!](https://github.com/sanesan/docker4linux/blob/master/img/4-1.PNG)

Update the repositories again:

<code>sudo apt-get update</code>

## 5. Install Docker:

<code>apt-get install docker-ce</code>

![docker-ce!](https://github.com/sanesan/docker4linux/blob/master/img/5-1.PNG)

Check that Docker is installed correctly
<code>sudo docker run hello-world</code>

![hello-world!](https://github.com/sanesan/docker4linux/blob/master/img/5-2.PNG)
