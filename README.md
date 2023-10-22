# Description
Cette configuration Terraform déploie une infrastructure Azure typique pour une machine virtuelle Linux, avec un groupe de ressources, un réseau virtuel, un sous-réseau, une adresse IP publique, un groupe de sécurité réseau, un compte de stockage et une machine virtuelle basée sur Ubuntu.

- Un groupe de ressources dans la région spécifiée.
- Un réseau virtuel avec un sous-réseau.
- Une adresse IP publique pour la machine virtuelle.
- Un groupe de sécurité réseau avec une règle SSH entrante.
- Une interface réseau reliée au sous-réseau et à l'adresse IP publique.
- Un compte de stockage pour les diagnostics de démarrage.
- Une machine virtuelle Linux basée sur Ubuntu, configurée pour autoriser le trafic SSH entrant et personnalisable avec le nom d'utilisateur.

[Infrastructure](https://github.com/e180175/cloud_siem_soar/blob/master/infrastructure.png)
