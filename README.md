


![Licence GPL-3.0](https://img.shields.io/badge/Licence-GPL_3.0-red)


# mail-server-cloud

Effectuer rapidement la configuration d’un serveur de messagerie hébergé dans le cloud AWS


Pourquoi choisir AWS?

Il est important de prendre conscience des différences qui existent entre l’informatique en cloud et les environnements traditionnels.
Les points de différence incluent l’automatisation, l’évolutivité, les bases de données, les types de ressources et les composants flexibles, 
le tout disponible dans AWS.
Il va sans dire que développer une compréhension approfondie du concept avant de décider en faveur de la migration vers AWS est essentiel 
pour profiter des avantages à court et à long terme.


## Langage

 - :white_check_mark: SHELL


## Pré-requis
Vous aurez besoin d'un compte AWS : https://aws.amazon.com/fr/ ainsi qu'un nom de domain.
Nous recommendons d'enregistrer le nom de domaine auprès d'AWS gràce au service "Amazon Route 53".

Route 53 est un service Web qui est un système de noms de domaine (DNS) hautement disponible et évolutif.


## Objectifs

À partir d'un script (.sh) préalablement disponible dans le bucket S3 et téléchargé dans la machine "EC2" lors de son lancement; 
nous mettrons en place l'environnement du serveur de mails.



## Technologies & Services

Liste des technologies AWS utilisées :

- AWS EC2 (serveur mails)
- Amazon Linux 2 OS
- AWS S3
- AWS Route 53
- AWS Elastique IP (Adresse IP publique)



## Ressources

- https://docs.aws.amazon.com/
- https://wp-cli.org/fr/
- https://www.google.com/
