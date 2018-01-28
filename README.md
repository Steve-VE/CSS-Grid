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

