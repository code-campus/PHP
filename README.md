# PHP : Memo


## Les balises PHP

```php
<?php /* code PHP */ ?>
<?= "texte PHP" ?>
```


## Les variables

### Déclaration

```php
$varName; // Déclare la variable dans PHP
$varName = "Hello PHP"; // Déclare la variable dans PHP et lui affecte une chaine de caractère
```

### Utilisation

```php
echo $varName;
```

### Vérification

```php
isset($varName);
```

### Desctruction

Deux façon de détruire une variable :

```php
unset($varName);
$varName = null;
```