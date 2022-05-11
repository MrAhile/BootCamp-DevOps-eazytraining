FROM ubuntu:18.04
MAINTAINER : williams-ahile (williams14.ahile@gmail.com)

RUN apt-get update

#Création d'un reseau [reseau_local] de type bridge pour les conteneur [ubuntu1 & ubuntu2]
RUN docker network create --driver=bridge --subnet=192.168.2.0/24 reseau_local

#Affichage des conteneurs en services
RUN docker ps
