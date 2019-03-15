# Recap de la semaine

  

## Php: Hypertext Preprocessor.

1.  La syntaxe
    
2.  Les variables
    
3.  Les conditions
    
4.  Les tableaux
    
5.  Les boucles
    

  
  

### 1. La syntaxe:

  
```php
<?php // La balise d’ouverture

echo ‘Hello’; //La balise pour afficher du texte

// La balise de fermeture (optionnelle)
?>
```
  

Nous allons devoir placer tout notre code PHP au sein d’une balise <?php ?> afin que celui-ci soit bien reconnu en tant que code PHP.

  
  

### 2. Les variables:

  

On se sert d’une variable pour associer une valeur un à un nom.

Pour déclarer une variable en Php on utilise le symbole dollar “$”.


Il existe deux grandes familles de types de données :

    scalaire
    composé

Les variables scalaires sont des variables ne contenant qu'une seule valeur à la fois. Elles sont composées des types suivants :

    *Entier (nombre sans virgule) : c'est le type integer.
    Réel (nombre à virgule. En php, le séparateur décimal est en fait un point) : c'est le type float.
    *Booléen (2 valeurs, vrai ou faux) : c'est le type boolean.
    Chaîne de caractères (valeurs encadrées par des simples quotes ou des doubles quotes) : c'est le type string

Les variables composées sont des variables comportant plusieurs éléments.

    *Tableaux : c'est le type array
    *Objets : c'est le type object


  

### 3. Les conditions:

  

Une condition peut être écrite en PHP sous différentes formes. On parle de structures conditionnelles.

Les conditions principales sont if/else/elseif et switch.

Cette condition va nous permettre d’exécuter un bloc de code si un test est validé, ou ne rien exécuter dans le cas contraire.

L’instruction switch va nous permettre d’effectuer différentes actions en fonction de différents cas. En cela, le switch va poursuivre le même but que les structures conditionnelles.

Il va pouvoir être intéressant d’utiliser un switch lorsque l’on souhaite traiter beaucoup de cas différents.

  
  
  

### 4. Les tableaux:

  

Un tableau est une variable qui va contenir plusieurs valeurs.

  

Il existe des tableaux associatifs, il s’agit d’un tableau qui va associer des clefs textuelles (plutôt que numériques) à ses différentes valeurs.

```
$weapons = ['weapon_one' => 'whip', 'weapon_two'=>'gun', 'weapon_three'=>'saber'];
```

  

Il y a aussi les tableaux multidimensionnel c’est un tableau contenant lui même un ou plusieurs autres tableaux en valeurs.

Nous allons pouvoir avoir plusieurs « dimensions » de tableaux multidimensionnels.

On appelle tableau à deux dimensions un tableau contenant lui même un ou plusieurs autres tableaux.

  

### 5. Les boucles:

  

Les boucles vont nous permettre d’exécuter plusieurs fois un bloc de code tant qu’une condition donnée est vérifiée.

  

-   La boucle while (« tant que ») ;
    
-   La boucle for (« pour ») ;

```php
<?php
for ($i=5; $i<9; $i++) {
	    echo $i;
}
?>
```

-   La boucle foreach (« pour chaque ») ;





