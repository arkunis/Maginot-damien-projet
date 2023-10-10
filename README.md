# BatSite
## Index
Dans la conception du site web, je suis partie sur le thème de gotham dans l'univers **batman**.  
Sur mon **index.html** je suis partie sur une disposition en flex pour avoir 4 images au total. 
![2 images qui se superpose](https://i.postimg.cc/25WL6ttp/2023-10-10-11-49-01-GOTHAM-Opera.png)
>J'ai fixé la taille des articles avec un ID #slides pour qu'il y est seulement 2 images l'une a coté de l'autre.

Pour ajouter un effet et ne pas laisser la page sans vie, il y a un *:hover* sur les images, qui, quand on passe la souris dessus nous affiche un brève description tout en déplaçant l'image vers le haut en y ajoutant un **hidden** pour la cacher.
![mon hover](https://i.postimg.cc/zG8RBpr3/2023-10-10-11-55-01-GOTHAM-Opera.png)
 Pour encore mettre du dynamisme dans la page, un effet *jittery* à été placé sur mes boutons avec comme indication un mouvement de grossissement et de gauche à droite via des **@keyframes**
 ## Page_1
Pour la mise en page du thème principal, j'ai pensée à un style "minimaliste" en séparant mes différentes sections de manière distinct.

### En premier lieu on y trouve le **header**
![bat header](https://i.postimg.cc/xdKfzV32/2023-10-10-11-59-37-GOTHAM-Opera.png)J'ai ajouté un flex pour que mon **H1** et mon alert soit centré et espacé (*space-between*)
Pour la zone *alert*, un effet de défilement de texte à été posé sur la balise *div*.
### Le menu
![Bat menu](https://i.postimg.cc/Wby2zLH5/2023-10-10-11-59-49.png)
Pour la barre de navigation du site, tout en restant minimaliste, j'y est posé des titres et des balises *a* pour les rendre cliquable. Le disposition est mis en `flex-direction:column;`. Pour plus de décoration, un personnage a été attaché sur le coin gauche du site tout au long de la navigation (*qui s'enlèvera en version mobile*). 
### Le contenu (main)
![Bat Contenu](https://i.postimg.cc/BvzSLWbS/2023-10-10-11-59-57-Window.png)
Le contenu à été le plus "dur" à réaliser. Il se compose de 3 parties :

 1. Le titre
 2. Le contenu (texte)
 3. Image
#### le titre :
Pour le titre, un background noir (*qui se fond avec la couleur du html*) suit le texte jusqu'à un certain pourcentage. Un léger effet d'ombrage sur celui-ci pour apporter une dimension "3D".
#### Le contenu
Le contenu est basé sur du flex tout comme le titre. Il comporte donc 1 partie texte et l'autre pour l'image.
![différentes section flex](https://i.postimg.cc/wMZG8p6r/2023-10-10-13-27-05-GOTHAM-Opera.png)

Comme on peut le voir sur l'image du dessus, une *class* (*.droite et .gauche*) qui prend le contrôle sur le contenu pour afficher le texte à droit ou à gauche de l'image.
![Div gauche conteneur](https://i.postimg.cc/2jd5TSSM/2023-10-10-13-29-01-GOTHAM-Opera.png)
Pour changer le texte d'emplacement, un `flex-direction:row-reverse;`est utilisé dans .batarticle2 pour inverser de place le texte et l'image. 
#### L'image
Pour l'image, la classe *.droite img* et *.gauche img* sont là pour limiter la taille de l'image et ainsi éviter une mauvaise adaptation des différents formats d'image que l'on pourrait rencontrer.

## Metropolise
![Version blanche du site](https://i.postimg.cc/G3MSYk1p/2023-10-10-13-37-17-Window.png)
Pour la page_3, j'ai voulu rendre le coté héro qui sauve le monde ave un thème blanc (signe de pureté). Pour cela; j'ai ajouté un *id* à ma balise *html* pour ensuite lui donner les différentes couleurs souhaité.
![VSCode](https://i.postimg.cc/Fsk5HPJv/2023-10-10-13-41-01-pages-css-Formation-DEV-Visual-Studio-Code.png)
## Le responsive
Pour l'adaptation responsive, tout mes blocs flex en *raw* sont passé en *column* pour rendre la superposition des images et du texte visible sur tout les périphériques.
![responsive batsite](https://i.postimg.cc/CK56c7p5/ezgif-com-gif-maker.gif)
Comme on peut le voir sur le Gif au-dessus, les personnages sont enlevé avec un `display:none;`et le menu ne comporte que les objets cliquable.
### Le responsive de l'index.html
Pour l'index.html, les effets sont retiré et il ne reste que les images en version cliquable.
![bat index](https://i.postimg.cc/gJNV1FyP/2023-10-10-13-49-40-GOTHAM-Opera.png)

 
