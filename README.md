# docker

Docker est une plateforme logicielle qui permet de développer, déployer et exécuter des applications dans des conteneurs logiciels. Un conteneur est une instance d'une image Docker, qui est un modèle de logiciel préconfiguré comprenant tout ce dont l'application a besoin pour fonctionner, y compris le code de l'application, les bibliothèques et les dépendances.

Les principaux avantages de Docker sont l'agilité, la portabilité et l'efficacité. Les conteneurs Docker permettent aux développeurs de créer facilement des applications qui peuvent être exécutées sur n'importe quel serveur, quelle que soit la configuration du système d'exploitation. Cela signifie que les applications Docker peuvent être développées sur un ordinateur local et déployées sans modification sur un serveur de production, ce qui rend le processus de développement et de déploiement plus rapide et plus facile.

En outre, les conteneurs Docker sont très légers et utilisent moins de ressources que les machines virtuelles, ce qui les rend plus efficaces et faciles à gérer en production.

Voici quelques-uns des principaux concepts de Docker :

Images Docker : modèle de logiciel préconfiguré utilisé pour créer des conteneurs.
Conteneurs Docker : instance d'une image Docker exécutant du code.
Registre Docker : référentiel centralisé pour stocker et gérer les images Docker.
Docker Engine : logiciel qui exécute les conteneurs Docker.
Docker Compose : outil pour définir et exécuter des applications à l'aide de plusieurs conteneurs Docker.
Docker Swarm : outil de gestion de cluster pour exécuter des conteneurs Docker sur plusieurs serveurs.

# Télécharger une image depuis le Docker Hub

Qu'est-ce que Docker Hub ?
Moyeu Docker (https://hub.docker.com ) est un référentiel en ligne d'images Docker.

# Qu'est-ce qu'une image ?

Les principales entités de Docker sont les conteneurs . Un conteneur est un logiciel qui émule une machine complète avec des bibliothèques et du code préinstallés. Les conteneurs permettent de distribuer des applications logicielles avec tout l'environnement dont elles ont besoin pour fonctionner. En empaquetant une application dans un conteneur, nous pouvons l'exécuter sur n'importe quel ordinateur sans avoir besoin d'une configuration spéciale, ce qui rend l'application parfaitement portable.

Une image Docker (parfois aussi appelée image de conteneur ) est un fichier qui est essentiellement un instantané d'un conteneur. Les images sont créées avec la buildcommande, et elles produiront un conteneur lorsqu'elles seront lancées avec run.

# installation

sudo apt-get remove docker docker-engine docker.io

sudo apt-get update

sudo apt-get install apt-transport-https ca-certificates curl software-properties-common

curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -

sudo apt-key fingerprint 0EBFCD88

sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu \
xenial \
stable"

sudo apt-get update

sudo apt-get install docker-ce

sudo docker run hello-world
