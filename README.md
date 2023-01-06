![docker](https://guides.hexlet.io/assets/images/docker/docker.png)
# Docker
Docker est une plateforme logicielle qui permet de développer, déployer et exécuter des applications dans des conteneurs logiciels.

Les principaux avantages de Docker sont l'agilité, la portabilité et l'efficacité. Les conteneurs Docker permettent aux développeurs de créer facilement des applications qui peuvent être exécutées sur n'importe quel serveur, quelle que soit la configuration du système d'exploitation. Cela signifie que les applications Docker peuvent être développées sur un ordinateur local et déployées sans modification sur un serveur de production, ce qui rend le processus de développement et de déploiement plus rapide et plus facile.
En outre, les conteneurs Docker sont très légers et utilisent moins de ressources que les machines virtuelles, ce qui les rend plus efficaces et faciles à gérer en production.
Voici quelques-uns des principaux concepts de Docker :

# Docker hub
Docker Hub est une plateforme en ligne qui permet aux utilisateurs de partager et de télécharger des images Docker. 

![](https://t1.daumcdn.net/cfile/tistory/99684B395C9AA5A816)

# Dockerfile
Un Dockerfile est un fichier textuel qui contient les instructions nécessaires pour construire une image Docker. Chaque instruction du Dockerfile crée une couche dans l'image. Un Dockerfile commence généralement par définir à partir de quelle image il va hériter, puis ajoute des fichiers, exécute des commandes, et configure des paramètres de l'environnement. Une fois que vous avez écrit votre Dockerfile, vous pouvez utiliser la commande docker build pour l'utiliser pour créer une image Docker.

# Qu'est-ce qu'une image ?
Images Docker : modèle de logiciel préconfiguré utilisé pour créer des conteneurs.
Une image Docker (parfois aussi appelée image de conteneur ) est un fichier qui est essentiellement un instantané d'un conteneur. Les images sont créées avec la buildcommande, et elles produiront un conteneur lorsqu'elles seront lancées avec run.

# Qu'est-ce qu'un conteneur ?
Conteneurs Docker : instance d'une image Docker exécutant du code.
Les principales entités de Docker sont les conteneurs . Un conteneur est un logiciel qui émule une machine complète avec des bibliothèques et du code préinstallés. Les conteneurs permettent de distribuer des applications logicielles avec tout l'environnement dont elles ont besoin pour fonctionner. En empaquetant une application dans un conteneur, nous pouvons l'exécuter sur n'importe quel ordinateur sans avoir besoin d'une configuration spéciale, ce qui rend l'application parfaitement portable.

![](https://miro.medium.com/max/1400/0*D4DUZT7y-JD2qyWP.png)

# Qu'est-ce qu'un registre docker ?
Registre Docker : référentiel centralisé pour stocker et gérer les images Docker
Un registre Docker est un serveur qui contient des images Docker. Les utilisateurs peuvent utiliser ces images pour déployer des conteneurs sur leur propre ordinateur ou sur des serveurs. Les registres Docker sont accessibles via une URL et peuvent être publics ou privés. Docker Hub est l'un des registres Docker publics les plus populaires, mais il existe également d'autres registres publics tels que quay.io et docker.io. Les utilisateurs peuvent également créer leur propre registre privé en utilisant des outils tels que Docker Trusted Registry ou en hébergeant leur propre registre sur un serveur.
![](https://i.ytimg.com/vi/SEpR35HZ_hQ/maxresdefault.jpg)

# Qu'est-ce que docker engine ?
Docker Engine : logiciel qui exécute les conteneurs Docker.
Docker Engine est une technologie de conteneurisation open source pour créer et conteneuriser vos applications. Docker Engine agit comme une application client-serveur avec :

- Un serveur avec un processus démon de longue durée dockerd.
- API qui spécifient les interfaces que les programmes peuvent utiliser pour parler et instruire le démon Docker.
- Un client d'interface de ligne de commande (CLI) docker.

# Qu'est-ce que docker compose ?
Docker Compose : outil pour définir et exécuter des applications à l'aide de plusieurs conteneurs Docker.
Docker Compose est un outil qui vous permet de définir et d'exécuter plusieurs conteneurs Docker en même temps. Vous pouvez utiliser Docker Compose pour définir les conteneurs de votre application dans un fichier docker-compose.yml, puis utiliser une seule commande pour créer et démarrer tous les conteneurs en même temps. Cela peut être utile lorsque vous avez une application qui utilise plusieurs conteneurs, comme un conteneur de base de données et un conteneur d'application web, par exemple. Vous pouvez utiliser Docker Compose pour facilement gérer l'ensemble de votre application dans un seul endroit.
