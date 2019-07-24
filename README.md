# PHP : Memo



## Les balises PHP

```php
<?php /* code PHP */ ?>
<?= "texte PHP" ?>
```



## Les variables

### Déclaration de variable

```php
$varName; // Déclare la variable dans PHP
$varName = "Hello PHP"; // Déclare la variable dans PHP et lui affecte une chaine de caractère
```

### Utilisation de variable

```php
echo $varName;
```

### Vérification de variable

```php
isset($varName);
```

### Desctruction de variable

Deux façon de détruire une variable :

```php
unset($varName);
$varName = null;
```



## Les constantes

### Déclaration de constante

```php
define("CONST_NAME", "Hello PHP");
```

### Utilisation de constante

```php
echo CONST_NAME;
```

### Vérification de constante

```php
defined("CONST_NAME");
```



## Les opérateurs

### Les opérateurs d'affectation

| Opérateur | Symbole | Utilisation | Description
|:-|:-:|:-:|:-
| Affectation | `=` | `$a = 42` | Affecte une valeur à une variable

### Les opérateurs arithmétiques

| Opérateur | Symbole | Utilisation | Description
|:-|:-:|:-:|:-
| Addition | `+` | `$a + $b`
| Soustraction | `-` | `$a - $b`
| Multiplication | `*` | `$a * $b`
| Division | `/` | `$a / $b`
| Identité | `+` | `+$a` | Convertit `$a` en Integer ou Float
| Négation | `-` | `-$a` | Donne la valeur inverse de `$a`
| Modulo | `%` | `$a % $b` | Retourne l'entier restant d'une division
| Exponentiel | `**` | `$a ** $b` | Retourne l'exposant