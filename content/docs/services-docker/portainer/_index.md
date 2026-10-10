---
isIndex: false
draft: false
title: Portainer
description: Interface de gestion visuelle pour Docker. Permet de gérer les conteneurs, images, réseaux et volumes depuis un navigateur.
icon: brand:portainer
---

{{< badge text="Gestion" state="info" >}}

![Portainer](/images/uploads/docs/portainer.jpg 'Portainer')

## {{< icon icon="info" >}} **Informations générales**

- **Version** : `2.19.4`
- **Image Docker** : [portainer/portainer-ee:latest](https://hub.docker.com/r/portainer/portainer-ee)
- **Ports exposés** : `9000:9000`
- **Volumes** : `/var/run/docker.sock:/var/run/docker.sock`, `./portainer_data:/data`
- **Réseau** : `homelab_network`

## Installation

### Prérequis

{{< alert-block title="info" state="info" icon="info" >}}
- Docker et Docker compose installé et fonctionnel
- Accès au socket Docker (/var/run/docker.sock)
{{< /alert-block >}}

### Déploiement avec Docker Compose

{{< highlight yaml "linenos=inline, hl_lines=3">}}
version: '3.8'
services:
portainer:
image: portainer/portainer-ce:latest
{{< /highlight >}}

### Commande pour démarrer :

{{< highlight yaml >}}
docker-compose -f /chemin/vers/docker-compose.yml up -d
{{< /highlight >}}

## **Configuration**

### Variables d'environnement

Aucune variable d'environnement requise pour Portainer.

## **Utilisation**

- **URL d'accès** : [http://192.168.1.22:9000](http://192.168.1.22:9000)
- **Identifiants par défaut** :
  - Utilisateur : `admin`
  - Mot de passe : À définir lors de la première connexion
- **Commandes utiles** :

  {{< highlight bash>}}
  # Voir les logs

  docker logs portainer

  # Redémarrer le conteneur

  docker restart portainer
  {{< /highlight >}}

## **Liens utiles**

- [Portainer.io](https://www.portainer.io/)
- [Documentation Portainer](https://docs.portainer.io/)
- [Dépôt GitHub](https://github.com/portainer/portainer)
