# Déploiement d’une Application WordPress sur ECS

## Coûts estimation :

## Fonctionnalités :
- Déploiement d’une application front-end et back-end
- Auto scaling
- Load Balancing
- Persistance des données

## Services :
- **VPC (Virtual Private Cloud)** : Fournit un réseau isolé dans le cloud, permettant de définir des sous-réseaux, des règles de sécurité, et des connexions à Internet.
  
- **SUBNET (Sous-réseau)** : Divise un VPC en segments plus petits pour organiser les ressources et gérer la sécurité.

- **INTERNET GATEWAY** : Permet la communication entre les ressources dans un VPC et Internet.

- **EIP (Elastic IP)** : Adresse IP statique qui peut être associée à une instance pour la rendre accessible sur Internet.

- **ALB (Application Load Balancer)** : Distribue le trafic entrant entre plusieurs cibles (instances EC2, conteneurs, etc.) et permet de gérer le routage basé sur le contenu.

- **ACL (Access Control List)** : Définit des règles de sécurité pour contrôler le trafic entrant et sortant au niveau des sous-réseaux.

- **NAT (Network Address Translation)** : Permet aux instances dans un sous-réseau privé d'accéder à Internet sans exposer leurs adresses IP.

- **ROUTE (Table de routage)** : Définit les règles de routage pour diriger le trafic entre les sous-réseaux et vers Internet.

- **SECURITY GROUP** : Agit comme un pare-feu virtuel pour contrôler le trafic entrant et sortant des instances.

- **CLOUDMAP** : Service de découverte de services qui permet aux applications de trouver et de se connecter à d'autres services.

- **ROUTE 53** : Service DNS qui permet de gérer les noms de domaine et de diriger le trafic vers les ressources AWS.

- **ECS (Elastic Container Service)** : Service d’orchestration de conteneurs qui facilite le déploiement et la gestion d'applications conteneurisées.

- **Task** : Unité de travail dans ECS qui définit un ensemble de conteneurs à exécuter ensemble.

- **Task Definition** : Modèle qui définit les paramètres pour les tâches ECS, y compris les images de conteneur, les ressources, et les configurations réseau.

- **SECRET MANAGER** : Service qui permet de stocker et de gérer les secrets (comme les mots de passe et les clés API) de manière sécurisée.

- **IAM (Identity and Access Management)** : Gère les utilisateurs, les rôles, et les permissions pour contrôler l'accès aux ressources AWS.
  - **Permission** : Définir ce que les utilisateurs et les rôles peuvent faire avec les ressources AWS.

- **CLOUDWATCH** : Service de surveillance qui collecte et suit les métriques, les journaux, et les événements pour les ressources AWS.
  - **Container Insight** : Outil de surveillance pour les conteneurs.
  - **Logs Groups** : Regroupe les journaux pour une gestion et une analyse centralisées.

- **LIGHTSAIL** : Service simplifié pour déployer des applications et des sites Web en utilisant des instances virtuelles.

- **S3 (Simple Storage Service)** : Service de stockage d'objets pour stocker et récupérer des données à tout moment.

- **EBS (Elastic Block Store)** : Fournit un stockage de blocs persistant pour les instances EC2.

- **EFS (Elastic File System)** : Système de fichiers évolutif qui peut être monté sur plusieurs instances EC2.

- **DLM (Data Lifecycle Manager)** : Automatisation de la gestion des sauvegardes et des snapshots pour les volumes EBS.
  
