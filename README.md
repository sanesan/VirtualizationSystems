# Docker4Drupal

## 1. Actualizamos los paquetes instalados y los repositorios:

<code>sudo apt-get update</code>
 
![sudo apt-get update!](https://github.com/sanesan/docker4drupal/blob/master/img/1.PNG)

## 2. Instalamos los paquetes necesarios:

<code>sudo apt-get install apt-transport-https ca-certificates curl software-properties-common</code>

![sudo apt-get install apt-transport-https ca-certificates curl software-properties-common!](https://github.com/sanesan/docker4drupal/blob/master/img/2.PNG)

## 3. Agregamos la clave GPG oficial de Docker:

<code>curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -</code>

Y verificamos que tenemos la clave:

<code>sudo apt-key fingerprint 0EBFCD88</code>

![keyofdocker!](https://github.com/sanesan/docker4drupal/blob/master/img/3.PNG)

## 4.
