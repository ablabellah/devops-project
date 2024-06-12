# my-first-project
Dans ce projet, nous utilisons trois outils DevOps : Docker, Vagrant et Ansible.
Nous les installerons tous les trois dans une machine virtuelle que nous
appellerons la machine serveur. Notre objectif est de créer automatiquement deux
environnements, test et prod, avec Vagrant, et de créer dans ces deux
environnements deux conteneurs contenant une application web avec Apache.
Nous créerons le Dockerfile dans la machine serveur en utilisant comme image
de base "httpd" provenant du registre public Dockerhub. Ensuite, nous utiliserons
Ansible pour lancer la création des conteneurs via le Dockerfile dans les deux
environnements, puis nous stockerons l'image dans un registre privé.
