# HTML - CHEAT-SHEET

## Squelette de base - template

```
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Document</title>
</head>
<body>
    <h1>Bonjour, monde!</h1>
</body>
</html>
```
<br>

-**EXPLICATIONS**
```
    <meta charset="UTF-8">
```
* La balise <meta charset="UTF-8"> est utilisée dans le document HTML pour spécifier l'encodage des caractères utilisés dans la page.
  
```
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
```
* En résumé, la balise <meta http-equiv="X-UA-Compatible" content="IE=edge"> aide à garantir que les pages web sont affichées de manière optimale dans Internet Explorer, en utilisant le moteur de rendu le plus à jour.  

```
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
```
* Responsibe Design: Adaptation des pages web à différentes tailles d'écran (mobiles, tablettes, ordinateurs).
* Expérience utilisateur : Amélioration de la lisibilité et de la navigation sans besoin de zoomer ou de faire défiler horizontalement.
*Compatibilité mobile : Les appareils mobiles utilisent cette balise pour déterminer comment rendre les pages web correctement.
* Paramètres supplémentaires (facultatifs) :
    - maximum-scale=1.0 : Empêche de zoomer au-delà de 1.0.
    - user-scalable=no : Empêche tout zoom sur la page.
 
## Corriger l'importation des polices Google Fonts :
```
<link href="https://fonts.googleapis.com/css?family=Reem+Kufi|Roboto:300" rel="stylesheet">
```
* Signification : Cette ligne tente d'importer les polices de caractères Reem Kufi et Roboto avec une variante de poids de 300 depuis Google Fonts.
* Problème : L'utilisation du caractère | (pipe) dans l'URL est incorrecte et provoque une erreur. Comme mentionné précédemment, il faut remplacer | par &family= pour séparer les familles de polices.
<br>


**CORRECTION**
```
<link href="https://fonts.googleapis.com/css2?family=Reem+Kufi&family=Roboto:wght@300&display=swap" rel="stylesheet">
```

## Importation des polices Google Fonts - code dans css :
```
<link href="https://use.fontawesome.com/releases/v5.13.1/css/all.css" rel="stylesheet">
```
* Signification : Cette ligne importe les icônes de Font Awesome, version 5.13.1, depuis le site officiel de Font Awesome. Les icônes de Font Awesome sont souvent utilisées pour ajouter des icônes vectorielles sur les pages web.
* Usage : Font Awesome est une bibliothèque populaire d'icônes qui permet aux développeurs d'ajouter facilement des icônes à leurs sites web.
  <br>

```
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">
```
* Signification : Cette ligne importe les icônes de Font Awesome, version 6.0.0, depuis le CDN (Content Delivery Network) de Cloudflare (cdnjs). Cela permet d'utiliser les icônes mises à jour de la version 6.0.0 de Font Awesome.
* Usage : Similar to the second line, but it uses a newer version (6.0.0) of Font Awesome, which may include new icons and features not available in the older version.


