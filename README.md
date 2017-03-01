# Html-Css

[Les balises Html]( http://41mag.fr/liste-des-balises-html5)

** Installer des guides dans atom **

“install a package” Indent guide improved

Ouvrir Explorer > CePc > C: > Xampp > Htdocs
(C:\xampp\htdocs)

Créer un dossier nommé “DashboardXampp”
On déplace tous les fichiers et dossiers de Htdocs dans DashboardXampp. Sert à rendre Htdocs exploitable.

Dans Htdocs on crée un dossier :

Html-Css
Atom >File>open folder
C:\xampp\htdocs\Html-Css
Atom
sur le dossier Html-Css clic droit New file >index01.html

Dans index01.html :    
 ```html
<!DOCTYPE Html>
:<html>
<head>
</head>
<body>
</body>
</html>```

**Indentation** : Manière de structurer les choses pour clarifier son travail.
Nécessaire pour le travail à plusieurs
Permet de se repérer plus facilement dans la hiérarchie.

**Head  / Métadonnées** : informations en arrière plan.
Informations fonctionnelles de la page
** Titre ** = ```<title>```

** Type de caractères ** = ```<meta charset=”utf-8”>```

**Feuilles de styles** = ```<link rel="stylesheet" href="/css/style.css">```

**Frameworks** = ```<link> / <script>```

**Body** : Contenu visible du site

**Header** : Informations de fonctionnement relatives au site (menu, barre de recherche, Log in, logo ou nom du site)

**Footer** : Bas de page (coordonnées, navigation secondaire, etc…)

**Div** : Bloc d’éléments→ permet de manipuler un ensemble d'éléments.

<u>Section, Article, Div</u>
Ensemble d'éléments syntaxiques permettant de manipuler un bloc.

Ces 3 éléments représentent la même chose mais correspondent à des niveaux de représentation différents.
Section sera utilisé pour un grand ensemble, div pour un ensemble plus ou moins grand de type indéfinis et article pour un bloc contenant un article (sous-titre, paragraphe.)

<u>! ne pas oublier d’enregistrer et de recharger la page pour avoir un visuel de son code!</u>

#### Base html

```html
<html>
  <head>
    <meta charset="utf-8">
    <title>Text</title>
  </head>

  <body>
    <header>
      <nav>
      </nav>
    </header>
  <footer>
  </footer>
  </body>
</html>```

**Header** = titre, navigation (avec **nav**), haut de page

**body** = corps de la page

**Footer** = réseaux sociaux, contact, bas de page.


** Insérer une image: **
```html <img src="img/xx.jpg" alt="Logo xx"> ```


### Les commentaires:
  Les commentaires servent à noter des informations textuels au milieu du code sans perturber son exécution. Ils peuvent également servir à masquer une partie du code sans avoir à effacer son contenus.

+ commentaires en html : ```<!--  Zone de commentaire -->  ```
+ commentaire en CSS : ```/*  Zone de commentaire   */```

**Atom**

** Ctrl+Maj+/ pour mettre en pause une ligne (commenter une ligne sur Atom) **

Déplacer un paragraphe d’un emplacement à un autre:
+ ctrl + flèche haut / bas.

Retour à la ligne
+ View/Toggle Soft Wrap

**Xampp**
control pannel (conflit avec skype)

Start Apache pour lancer un émulateur sur navigateur.
Taper 'localhost' dans la barre d'adresse du navigateur.

#### Lexique :

Définitions générales Css :

** Class ** : Éléments central du html / css, les classes permettent de sélectionner plusieurs éléments et de leur appliquer du style dans l’ensemble.
On définit à travers les classes, des propriétés communes à plusieurs éléments.

** Id ** : Identité de la balise, l’attribut ID permet d’identifier un balise précisément. Elle va nous permettre d’appliquer du style qui ne doit apparaître que sur cet élément.

** Typo / Font / Police de caractère ** :
La police de caractère correspond à ce que l’on nomme en css la font-family.
Ce sont les visuels de caractère qui vont nous permettre de changer l’affichage du texte.

On peut les récupérer sur  google font ou Dafont et les charger via un système de balise ```<link>``` ou directement dans le css via ce que l’on appel les media queries

*** Terminologies Html / Css *** :

``` <head> ``` : Le head contient toutes les ``` <meta> ``` ou métadonnées. Ce sont les informations structurelles de la page qui n'apparaîtront pas directement à l'écran mais qui sont nécessaires pour le bon fonctionnement de la page.

``` <body> ``` : Représente le corps de la page HTML.(un seul par document)

```<header>``` : Partie haute de la page web/html. Contient en général le ```<h1>``` et la navigation ```<nav>```

```<link>```  : balise servant à charger du contenus CSS -- police + feuille de style

```<p>``` définit un paragraphe.

```<span>``` : pour sélectionner une partie du texte que l’on veut modifié.

```<strong> / <b>``` : affiche un texte en gras.
```<u>``` : souligne un texte.

```<i>``` : affiche le texte en italique.

```<em>``` : italique ou gras pour un texte ( dépend du navigateur ).

```<div>``` :définit une division ou une section,appelé aussi calque

```.container``` : la classe container va nous servir à définir un espace donné qui contient les données dans une partie de la page. C’est une classe que l’on définit soi même.

```attributs``` : les attributs sont les informations notées

```float``` → left / right :
Mettre une image en habillage du texte
positionner un élément à droite ou à gauche d’un autre.

inconvénients : sort du flux → certaines propriétés ne fonctionnent pas et les éléments ne sont plus relatifs entre eux

```font-family``` :change la police de caractères

```display``` : 	
```inline``` : aligne les éléments les uns à la suite des autres.

```block``` : réserve tout l’espace disponible sur la ligne, illustré par une marge qui remplis l’espace.

```inline-block``` : lorsque des éléments inline-block sont côte à côte, ils se mettent à la suite et ensemble, forment un block.
