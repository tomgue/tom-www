---
isIndex: false
draft: true
title: Portainer
description: Interface de gestion visuelle pour Docker. Permet de gérer les conteneurs, images, réseaux et volumes depuis un navigateur.
icon: brand:portainer
---

## Portainer

{{< badge text="Gestion" state="info" >}}

Interface de gestion visuelle pour Docker. Permet de gérer les conteneurs, images, réseaux et volumes depuis un navigateur.

## 📌 \*\*Informations générales\*\*

- \*\*Version\*\* : \`2.19.4\`
- \*\*Image Docker\*\* : [\`portainer/portainer-ce:latest\`](https://hub.docker.com/r/portainer/portainer-ce)
- \*\*Ports exposés\*\* : \`9000:9000\`
- \*\*Volumes\*\* : \`/var/run/docker.sock:/var/run/docker.sock\`, \`./portainer_data:/data\`
- \*\*Réseau\*\* : \`homelab_network\`
- \*\*Documentation officielle\*\* : [Portainer Docs](https://docs.portainer.io/)

***

## 🛠 \*\*Installation\*\*

### Prérequis

- Docker installé et fonctionnel
- Accès au socket Docker (\`/var/run/docker.sock\`)

### Déploiement avec Docker Compose

\`\`\`yaml
version: "3.8"
services:
  portainer:
    image: portainer/portainer-ce:latest\`\`\`

{{< icon icon="link" >}}

Liens utiles
