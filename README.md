# CSS Grid

## CCS Grid, kézako ?

La _**grille CSS**_ (*CSS Grid*) est une méthode CSS accepté par la majeur partie des navigateurs web depuis 2017 et qui permet d'établir rapidement et facilement len *layout* (mise en page) d'une page web reposant sur le principe d'une grille.
Il s'agit donc d'une fonctionnalité relativement récente.  
En facilitant la conception du layout, elle nous permet de se passer de certain framework (ex.: [Bootstrap](https://getbootstrap.com/ "Lien pour obtenir Bootstrap") ) ou de créer une multitude de *div/span* associés à du CSS en *code spaghetti* dans l'unique but de simplement mettre en forme une page web...  

Puisque les grilles CSS nécessite simplement d'utiliser quelques divs imbriqués auxquelles ont attribu une classe, et quelques règles en CSS, elles sont très faciles à utiliser.  


Pour vous faciliter la tâche j'ai, placé quelques exemples sur ce *repository*.
Pour les récupérer, exécutez simplement les commandes suivantes :  
```
git clone https://github.com/Steve-VE/CSS-Grid.git
cd CSS-Grid
git branch -a
git checkout step-01
```

Il ne vous reste plus qu'à naviguer entre les différents exemples...  
``` git checkout step-01 ```  
``` git checkout step-02 ```  
``` git checkout step-03 ```  
``` git checkout step-04 ```  
``` git checkout step-05 ```  
``` git checkout step-06 ```  

Amusez-vous et modifiez les à votre guise. Essayez de modifier les différents paramètres, de modifier la CSS et l'HTML à votre guise, pour voir comment la grille se comporte.  



## Comment créer une grille CSS ?
  
Pour créer une grille en CSS, rien de plus simple... Il vous suffit d'appliquer la propriété `display: grid` à l'élément qui contiendra votre grille :  
``` css
.container {
  display: grid;
}
```
Il reste alors à définir comment vous voulez "découper" votre grille, et le tour est joué, ses sous-éléments se placeront dans la grille.
``` css
.container {
  display: grid;
  
  grid-template-columns: 30% 60%;
  
  grid-template-rows: 50px 80% 50px;
}
```
Mais ça, ce n'est que l'introduction... Il y a bien des choses à faire et à apprendre à propos des grilles CSS, mais rien de bien compliqué :smiley:



## Où en apprendre d'avantage ?

Je vous conseille de vous rendre sur [Scrimba](https://scrimba.com/ "Lien vers Scrimba") :uk:, une plateforme de cours interactifs, vous pourrez trouver un [cours](https://scrimba.com/g/gR8PTE "Lien vers le cours") vraiment complet à ce sujet.  


## Utilisation concrète

Si vous suivez le cours ci-dessus, vous ferez comment il est possible de créer assez simplement une [galerie d'images](https://scrimba.com/p/pWqLHa/cBq3PsP "Lien vers le cours") où chaque élément trouve sa place, ou encore comment [mettre en page facilement un article](https://scrimba.com/p/pWqLHa/cdp76sD "Lien vers le cours").  
  
Les grilles CSS peuvent avoir des utilisations plus surprenantes et créatives que de simplement servir à établir le layout d'une page web.  
Le designer *Benjamin De Cock* en fait une belle démonstration lors d'une [conférence](https://www.dotconferences.com/2017/11/benjamin-de-cock-css-grid-in-production "dotCSS 2017 - Benjamin De Cock - CSS Grid in Production") à l'occasion du [dotCSS 2017](https://www.dotcss.io/ "Lien vers dotCSS")
  
    
## Ressources et informations supplémentaires
- [Grid by Example](https://gridbyexample.com/ "Lien vers Grid by Example") :uk: : Une bibliothèque d'exemples, de cours et d'articles en sujet avec les grilles CSS... C'est un peu la caverne d'*Ali Baba* version *CSS Grid*.

### Twitter 
- [Benjamin De Cock](https://twitter.com/bdc "Lien vers le twitter de Benjamin De Cock") :uk:
- [Per Harald Borgen](https://twitter.com/perborgen "Lien vers le twitter de Per Harald Borgen") :uk:
