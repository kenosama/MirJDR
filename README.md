# MirJDR

Bonjour a toi qui souhaites jouer a MIR sur Foundry, j'espere que ce document pourra t'aider a comprendre comment j'ai procédé a la création des fiches des personnages. 



# Pré-requis:
- Systeme Sandbox, qui m'a permis de construire la dite fiche de personnage. si le fonctionnement du systeme (permettant de creer des fiches de personnage a la carte) vous intéresse, je vous invite a suivre les tuto en anglais sur le github du createur.

- 3 Modules presque indispensable pour creer une fiche de personnage sous Sandbox

  - Sandbox Extensions
  - Sandbox Explorer
  - Custom CSS (si vous voulez modifier en profondeur votre mise en page)


# Fichier à ne pas modifier!!!
Dans l'onglet Personnage et Items, **il y a deux dossiers rouge a ne pas modifier**, si ils sont effacés ou modifié je ne pourrais pas garantir un fonctionnement des fiches de personnages.  les joueurs n'ont pas acces a ces dossiers (sauf si vous leurs donner l'acces) 
![pastouche](https://user-images.githubusercontent.com/38300951/179351833-b196523c-dfdd-4628-9a88-b354747b4042.png)


# Structure de la fiche de personnage.
Afin de comprendre comment fonctionne la dite fiche, nous allons en faire une fictive. 
Dans l'onglet personnages, il y a deux dossier, Joueurs et PNJ. 

1) a leur droite vous avez l'icône ![acteur](https://user-images.githubusercontent.com/38300951/179351964-1bc72b6e-8822-4f79-931a-23d41032bed8.png) cliquez dessus afin de creer un nouvel acteur.

2) Donnez lui un nom (dans notre cas TEST) et cliquez sur creer nouvel acteur. 

3) une nouvelle fenetre apparait. c'est une fiche de personnage vide. il faut donc la lier a modele afin de pouvoir avoir les info nécessaire pour jouer :) a droite vous avez une liste déroulante a coté d'une fleche noire.
Cliquez dessus et choississez Joueurs.  
![liaison](https://user-images.githubusercontent.com/38300951/179352010-8468b93c-a7d3-430e-a670-7d129fa658cf.png)


vous aurez donc des onglets supplémentaires qui se sont ajoutés a la fiche de personnage. 



## Onglet Compétence/inventaire 

![compinv](https://user-images.githubusercontent.com/38300951/179352129-e3ee1794-c435-4eb9-b9a9-48a73fa01ca5.jpg)

Dans cet onglet, on retrouve les information de Rôle, Trauma, Ego, les compétence des différentes voies et l'inventaire. (je n'ai pas fait d'inventaire modulaire car j'aimerais jouer au plus vite et il n'y a pas vraiement d'intéret spécifique pour l'instant dans la version de MIR actuelle, si plus tard, cela devient important, alors je pourrais faire une version modulaire.)



## Onglet Combat/Intrigue

![cobint](https://user-images.githubusercontent.com/38300951/179352196-49075558-50ec-4b4a-9392-416b5f348f9b.jpg)

Dans cet onglet, on a les informations de PV, Classe d'Armure (CA), Esquive, le nombre d'action(s), les Blessures, les armes, armures, les points d'intrigues et les relations. 

Commençons par le plus simple,





**1) Pour rajouter des armes a votre personnage.** 
 
   -Dans l'onglet Items (objet) de FVTT, vous avez un dossier vert COMPENDIUM, ouvrez le.
 
   ![compendium](https://user-images.githubusercontent.com/38300951/179352337-1bc16839-c136-49ea-a9fc-2faae0d43947.jpg)


  -Vous trouverez des sous dossiers Armes, ouvrez le et cliquez-déposez la ou les arme(s) souhaitée(s) dans la fiche de personnage. nous allons pour notre exemple, rajouter une épée et une arme a main nue dans la fiche.

  ![dragarme](https://user-images.githubusercontent.com/38300951/179352361-d3d284f2-2784-4553-922f-dd4d9ad109b4.jpg)


  Vous remarquerez que **les jets d'attaques, de riposte et de dégat** sont cliquable directement via **les icônes de Dés**. ce qui vous fera gagner du temps. 



**2) Pour rajouter une armure a votre personnage:**
-meme principe que les armes, mais dans ce cas ci, chaque armure est unique, c'est a dire qu'un personnage ne pourras pas porter deux armures a la fois. si vous cliquez déposer une deuxieme armure, elle remplacera directement la précédente. (dans la fiche de test, j'ai donné une armure lourde a mon personnage, vous remarquerez que la CA du personnage a changé automatiquement)

![dragarmure](https://user-images.githubusercontent.com/38300951/179352458-0652085f-cc04-428b-814d-d54cbe19c8a4.jpg)


**Les autres valeurs... (et la, les complications commencent :) )** 

Vous avez remarqué que si vous voulez modifier les autres valeurs, cela ne fonctionne pas correctement. 

Comment faisons nous alors :) 

Dans le compendium, il y a un autre dossier vert nommé Persos.

![Citemperso](https://user-images.githubusercontent.com/38300951/179352484-3f318892-2efd-4d51-8f6a-c9e76c382230.jpg)


Cliquez sur le TEST vous verrez dans l'onglet **Mods**, plein de données.

![citemsmods](https://user-images.githubusercontent.com/38300951/179352528-9265a5d4-ec30-4add-b5d0-b941eff12d21.jpg)


Vous pourrez dans l'ordre, 

  - mettre le nombre de **PV max** du perso
  - Afficher le **nombre maximal de Blessures et aggravations** (entre 2 et 4 selon les pré-tirés)
  - Attribuer la **valeur max d'esquive du personnage** *(ce n'est pas affiché sur la fiche mais cela empeche le joueur de donner des valeurs farfelue dans sa fiche (on a tous eu un clampin qui a décidé d'avoir une esquive de 999)*
  - Afficher la **valeur d'Esquive** du personnage *(normalement la meme valeur que la valeur max)*
  - Attribuer le **nombre d'action maximal** du personnage dans la fiche *(de nouveau valeur invisible)*
  - Afficher la **valeur du nombre d'action** dans la fiche.
  - Attribuer le **nombre maximal de Volonté** *(invisible dans la fiche)*
  - Afficher **la valeur de Volonté** dans la fiche.
  - Attribuer **le nombre de défence d'intrigue max** *(invisible dans la fiche)*
  - Afficher **la valeur de défence d'intrigue** dans la fiche.
  - Attribuer **la valeur Max de Sang-froid.** *(a mettre manuellement dans la fiche par apres)*
  - Attribuer **la Race du personnage** entre les 4 disponible (systerin, aniceen, veneatori, illuvetiste) **(attention pas d'accents, pas de majuscule)**. 
  - le **nombre max de savoir errant** affiché dans la fiche du perso. 
  - le **nombre de savoir errant dans la fiche** *(doit etre identique au nombre max)*.
  - la possibilité de rajouter des **informations de Rites** si il sont présents dans la fiche. *valeur 1 pour rajouter*.


Une fois que cela est fait, Cliquez déposez "l'objet" dans la fiche de personnage. automatique les valeurs vont changer selon les valeurs choisies. 

![modified1](https://user-images.githubusercontent.com/38300951/179352734-c040bad9-3387-4500-accb-05d382c81ffd.jpg)

Si vous voulez faire d'autre personnage, dupliquer le test et modifier les valeurs dans les cases en bas a droite.
Noubliez pas de mettre les memes valeurs pour les valeur MAX et les valeurs dans la fiche afin que cela corresponde :) 



# Onglet Stigmates/Savoirs 

![stisav](https://user-images.githubusercontent.com/38300951/179352790-2500dcb3-cb65-45c7-a9e1-44eb0616f930.jpg)


Ici nous pouvons retrouver les informations relatives au stigmates et savoirs, 

lors du placement de la race dans les modificateur du perso 

![citemsmods](https://user-images.githubusercontent.com/38300951/179352528-9265a5d4-ec30-4add-b5d0-b941eff12d21.jpg)

cela indiquera directement la race dans la fiche de perso,

nous trouvons en dessous les aggravations permanentes et mineures. 

les titres sont cliquables afin de pouvoir:

  - pour les aggravation permanentes, savoir quel degré d'affection est effectué sur le personnage. (valeur fixe)
  - pour les aggravations mineures, de rouler le dé afin de jouer de la table aléatoire. (1D6 car 6 possibilité)
Si jamais vous souhaitez modifier les listes, elle sont placées dans l'onglet Tables roulable


# Autres info utiles


## J'aimerais faire une nouvelle arme. 

Afin de faire une nouvelle arme, cliquez-droit l'arme TEST et cliquez sur le duplicata.

Vous verrez 3 données modifiable. 

  - **Prop_tab_arme_CitemMod:** vous permet de lier la compétence liée a l'arme. (les compétences sont rangée dans le dossier rouge, _template PAS TOUCHE >_PROPS > Competence> 

![liste comp](https://user-images.githubusercontent.com/38300951/179352979-070c6420-144e-4394-96fc-344a178ab2f9.jpg)
celle que vous choississez}, de la une fois la compétence choisie, cliquez dessus (par exemple athlétisme qui est dans la voie de la peur) vous devez copier le texte dans le champ.
![key](https://user-images.githubusercontent.com/38300951/179353007-7ef00f41-b2f9-4c06-bdf9-c032f2536218.jpg)

et vous collerez cette valeur "Comp_way_peur_Ath" (la casse est importante), dans le champ texte entre les {} présents. Si vous avez une arme comme main nue qui est divisée par deux, la formulation est différente. (voir dans l'arme susmentionnée) ). 
  - **Trait(s)**: Vous permets d'afficher les traits liés a l'arme
  - **Bonus d'attaque:** Vous permet de modifier le bonus d'attaque de l'arme. 
