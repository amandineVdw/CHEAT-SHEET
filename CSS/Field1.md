# CSS CHEAT SHEET

## CSS TEMPLATE -SQUELETTE

```
/* Reset margin and padding for all elements */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
}

header, nav, footer {
    background-color: #333;
    color: white;
    padding: 1em;
}

nav ul {
    list-style-type: none;
}

nav ul li {
    display: inline;
    margin-right: 1em;
}

nav ul li a {
    color: white;
    text-decoration: none;
}

main {
    flex: 1;
    display: flex;
    padding: 1em;
}

section {
    flex: 3;
    padding: 1em;
}

aside {
    flex: 1;
    padding: 1em;
    background-color: #f4f4f4;
    margin-left: 1em;
}

footer {
    text-align: center;
}

```
<br>

## RESET des marges et des paddings :
```
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

```
*  Cette règle CSS réinitialise toutes les marges et les paddings à zéro pour tous les éléments (*).
* box-sizing: border-box permet de définir la largeur et la hauteur des éléments en incluant les bordures et les paddings, ce qui facilite le contrôle de la mise en page.



## RESPONSIVE Design - Requête de média

**Résumé et usage des media queries**  
Ces media queries permettent de modifier la taille de la police en fonction de la largeur de l'écran, ce qui améliore la lisibilité et l'expérience utilisateur sur différents appareils. En adaptant la taille de la police, vous assurez que le texte reste lisible et bien proportionné, peu importe la taille de l'écran.

```
/* Définir une taille de police de base pour les petits écrans */
html {
    font-size: 12px;
}

/* Appliquer des tailles de police spécifiques en fonction de la largeur de l'écran */
@media (min-width: 576px) {
    html {
        font-size: 14px;
    }
}

@media (min-width: 768px) {
    html {
        font-size: 16px;
    }
}

@media (min-width: 992px) {
    html {
        font-size: 18px;
    }
}

@media (min-width: 1200px) {
    html {
        font-size: 20px;
    }
}

```

### Explication
** Requête de média pour min-width: 1200px : **  
* **Signification** : Si la largeur de l'écran est d'au moins 1200 pixels, alors la taille de la police pour l'élément <html> sera définie à 20 pixels.
* **Usage typique** : Cette règle est destinée aux très grands écrans, tels que les moniteurs de bureau de grande taille.



## FLEXBOX FROGGY - 

```
https://flexboxfroggy.com/#fr
```

## GRID GARDERN- 

```
https://cssgridgarden.com/#fr
```

## CODEPIP- 
```
https://codepip.com/games/
```


## TRICKS - 

1- **Box Shadow Effect Adding shadows to elements can enhance their depth and visual appeal.**
```
.box {
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}
```
*This code creates a subtle shadow around the .box element, enhancing its visual layering.
<br>


2- **Smooth Transition Animations CSS transitions are a simple way to enhance web page interactivity.**
```
.button {
  transition: background-color 0.3s ease;
}
.button:hover {
  background-color: #3498db;
}
```
*The button’s background color smoothly transitions to a new color when hovered over.
<br>


