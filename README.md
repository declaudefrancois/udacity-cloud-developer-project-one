# Projet: "Déployer un site Web statique sur AWS"

Bonjour cher examinateur , je vous remercie de disposer de votre temps pour examiner nos projets !

Vous trouverez dans ce document les details de mon travail soumis.
Les captures des differentes etapes, dans l'ordre chronologique, figurent egalement dans le meme dossier.

Fait par *Guy Francois de claude NKOUKA*

# Differentes URLs du site 

- [https://d2adgvpozmh769.cloudfront.net](https://d2adgvpozmh769.cloudfront.net "Cliquez pour acceder. Endpoint de la distribution cloudfront.")
  
- [http://project-one-final-301416979435.s3-website.us-east-1.amazonaws.com/](http://project-one-final-301416979435.s3-website.us-east-1.amazonaws.com/ "Cliquez pour acceder. Endpoint du bucket s3")

- [https://project-one-final-301416979435.s3.amazonaws.com/index.html](https://project-one-final-301416979435.s3.amazonaws.com/index.html "Cliquez pour acceder. Endpoint du bucket s3")
 

# Etapes 1. Creation du bucket S3 et ajout des fichiers 


![Creation du bucket via aws console!](/1-bucket-creation.png "Formulaire de creation")

![Bucket S3 cree.](/2-%20Bucket%20created.png "Bucket S3 cree")

![Fichiers ajoutes.](/3-%20Bucket%20files%20uploaded.png "Fichiers ajoutes")




# Etapes 2. Activation de l'hebergement de site statique

![Activation de l'hebergement de sites statique](/4-%20Bucket%20Statique%20web%20hosting.png "Formulaire de creation")

![Activation de l'hebergement de sites statique](/4-%20Bucket%20Statique%20web%20hosting-1.png "Formulaire de creation")




# Etapes 3. Configuration de l'IAM policy

![Configuration de l'IAM policy](/5-%20Bucket%20Access%20policy.png "Configuration de l'IAM policy")




# Etapes 4- Creation de la distribution cloudfront

![Creation de la distribution cloudfront](/6-%20Cloud%20front%20distribution%20creation.png "Creation de la distribution cloudfront")

![Creation de la distribution cloudfront terminee](/7-%20Cloudfront%20Distribution%20created.png "Creation de la distribution cloudfront terminee")
