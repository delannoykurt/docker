# docker

learning docker

# Télécharger une image depuis le Docker Hub

Qu'est-ce que Docker Hub ?
Moyeu Docker (https://hub.docker.com ) est un référentiel en ligne d'images Docker.

# Qu'est-ce qu'une image ?

Les principales entités de Docker sont les conteneurs . Un conteneur est un logiciel qui émule une machine complète avec des bibliothèques et du code préinstallés. Les conteneurs permettent de distribuer des applications logicielles avec tout l'environnement dont elles ont besoin pour fonctionner. En empaquetant une application dans un conteneur, nous pouvons l'exécuter sur n'importe quel ordinateur sans avoir besoin d'une configuration spéciale, ce qui rend l'application parfaitement portable.

Une image Docker (parfois aussi appelée image de conteneur ) est un fichier qui est essentiellement un instantané d'un conteneur. Les images sont créées avec la buildcommande, et elles produiront un conteneur lorsqu'elles seront lancées avec run.