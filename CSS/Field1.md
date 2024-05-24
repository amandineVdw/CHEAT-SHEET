# CSS CHEAT SHEET

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
