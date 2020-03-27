# oxyjeuneV2
Modifications
=============

### Attention bien respecter l'ordre des branches lors des pullRequest ###
1. LogoPage
2. ContactPage
3. RentBike
 


Modification faites le 04/03/2020 à 15H (par _**parzival**_).
-----

Modif des branches **entityRepo** et **entity**
- modification puis migration des classe _restore_ et _restoreCategory_ en BDD.

    >NB : Si vous avez d'autre entité a créer au niveau de l'id il faut mettre un _ entre chaque mot exemple :
    $id_UnNom_UnSecondNom et autant de fois qu'il faut sinon vous ne pourrez pas faire votre `doctrine:migrations:migrate` 
    et aussi a savoir `doctrine:migrations:migrate peut être remplacer par `d:m:m`.

- Pull de la branche **entityRepo** sur **entity** puis suppresion de **entityRepo**.

- Installation du bundle web-server avec la commande `composer req web-server-bundle`.

- Mise en place de _bootstrap_ et _fontawesome_

------

Modification faites le 05/03/2020 à 13H (par _**parzival**_).
---
- Création branche **homePage** depuis **develop**.

    - Integration page d'accueil
    - Importation des différentes photos pour le projet
    - Creation footer
    
Modification du 17/03/2020 à 15H (par _**parzival**_). 
---
- Création branche **contactPage** depuis **develop**.

    - Integration page de contact
    - Installation du bundle swift_Mailer `composer req symfony/swiftmailer-bundle`
    
- Création branche **RentBikePage** depuis **develop**.

    - Integration page de location de vélos
    - Création dossier admin
      - CRUD BrandController
      - CRUD ModelController
      - CRUD CategoryController
      - CRUD ProductController
    - Installation de la librairie VichUploader pour l'ajout des photos `composer req vich/uploader-bundle` 
    et de LiipImagine pour la gestion de la taille des images `composer req liip/imagine-bundle`
    
Modification du 20/03/2020 à 11H (par _**parzival**_). 
---
  - Merge de la branche **RentBikePage** sur la branche **develop**
  - Creation branche **RestorePage** depuis la branche **develop**
 
Modification du 25/03/2020 à 11H (par _**parzival**_). 
---
  - Creation branche **adviceAndPartnerPage** depuis la branche **develop**
  - Création branche **proPage** depuis la branche **develop**
    


 
# laFabricDesSublime
