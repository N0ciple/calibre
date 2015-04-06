
#  « Le Monde » pour liseuse

La recette ci-dessous permet de générer des fichiers `epub` ou `mobi` pour pouvoir lire le journal _Le Monde_ sur liseuse.

### Installation 
1. Dans Calibre, ouvrez le menu déroulant sous l'icône orange.
2. Sélectionnez "Ajouter une source personnalisez d'information".
3. Choisissez "Charger une recette depuis un fichier".
4. Sélectionnez le fichier `***.recipe` préalablement téléchargé.
5. Choisissez "Ajouter la recette" et fermez la fenêtre.

### Configuration
1. Dans Calibre, cliquez sur l'icône orange.
2. Sélectionnez "Personnalisé" puis la recette concernée.
3. Indiquez l'adresse et le mot de passe de votre compte abonné.
4. Si souhaité, planifiez le téléchargement du journal.

Il suffit alors de sélectionner "Télécharger maintenant", ou si les planifications ont été paramétrées d'ouvrir le menu déroulant sous l'icône orange et de choisir "Télécharger toutes les sources d'information planifiées".

### Utilisation en ligne de commande

Il est également possible d'utiliser cette recette en ligne de commande. Cela permet, avec un serveur ou un Raspberry Pi, de récupérer puis de servir le journal pour votre liseuse, soit _via_ le navigateur pour Kobo, soit _via_ mail pour Kindle. Il suffit pour cela de télécharger `***.recipe` et exécutez dans le même dossier : `ebook-convert "***.recipe" "***.epub"  --username "adresse" --password "motdepasse"`. 

--- 

# « Le Monde »  for eReader

This recipe allows you to generate `epub` or `mobi` files in order to read _Le Monde_ on your eReader.

### Installation 
1. In Calibre, open the drop-down menu under the orange icon.
2. Select "Add custom news sources dialog".
3. Choose "Load recipe from file".
4. Select `***.recipe`, previously downloaded.
5. Choose "Add recipe" and close the window.

### Configuration
1. In Calibre, select the orange icon.
3. Select "Custom" then the recipe.
4. Provide your account email and password.
5. If desired, you can schedule downloads.

Then you only need to select "Download now". If scheduling is on, you can also select "Download all scheduled news sources" in the drop-down menu under the orange icon.

### Command line usage
It is also possible to use this recipe from the command line. This allows a server or a Raspberry Pi, to retrieve and serve the newspaper to Kobo browser or via email for Kindle. Simply download `***.recipe` and run in the same folder : `ebook-convert "***.recipe" "***.epub" --username "youremail" --password "yourpassword"`. 



