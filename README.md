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