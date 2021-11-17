## Les variables 

 - Espace pour stocker une donnée
 - caractérisée par son nom  <!-- .element: class="fragment" data-fragment-index="1" -->
   - que des chiffres, des lettres et des tirets soulignés <!-- .element: class="fragment" data-fragment-index="2" -->
   - pas d'espace, de point, de tiret, de caractère spécial <!-- .element: class="fragment" data-fragment-index="3" -->
   - ne doit pas commencer par un chiffre <!-- .element: class="fragment" data-fragment-index="4" -->

---
<!-- .slide: data-auto-animate -->
## Les variables

Affectation : mettre une valeur dans la variable

```python
a = 5 
```

---
<!-- .slide: data-auto-animate -->

## Les variables 

Seconde variable, à partir de la première

```python
a = 5 
b = a + 3 # b vaut 8
```

---
<!-- .slide: data-auto-animate -->

## Les variables 

Modification de a 

```python
a = 5 
b = a + 3 # b vaut 8
a = a + 1 # maintenant a vaut 6
```


---
<!-- .slide: data-auto-animate -->
## Les variables 

On peut aussi mettre du texte, avec les guillemets.

```python
a = 5 
b = a+3 # b vaut 8
a = a + 1 # maintenant a vaut 6
monTexte = "Bonjour !"
```

---

## Les types 

Les variables ont un type, c'est à dire une certaine nature. 

Les types de bases sont : <!-- .element: class="fragment" data-fragment-index="0" -->
 - int <!-- .element: class="fragment" data-fragment-index="1" -->
 - float <!-- .element: class="fragment" data-fragment-index="2" -->
 - str <!-- .element: class="fragment" data-fragment-index="3" -->
 - bool <!-- .element: class="fragment" data-fragment-index="4" -->


---

## Les types

Ici, a est un nombre entier

```python
a = 3 # a est un entier (int)
```

<!-- .slide: data-auto-animate -->

---

## Les types 

b est un nombre flottant (c'est à dire décimal)

**attention** : le séparateur est le point (pas la virgule)

```python [2]
a = 3 # a est un entier (int)
b = 5.3 # b est un nombre "flottant" (float)
```

<!-- .slide: data-auto-animate -->

---

## Les types 

chaine est une chaine de caractère (str)

```python [4]
a = 3 # a est un entier (int)
b = 5.3 # b est un nombre "flottant" (float)
chaine = "Bonjour !" # une chaine de caractère (string)
```

<!-- .slide: data-auto-animate -->

---

## Les types 

verite est un booléen (bool)

```python [5]
a = 3 # a est un entier (int)
b = 5.3 # b est un nombre "flottant" (float)
chaine = "Bonjour !" # une chaine de caractère (string)
verite = True # un booleen (bool) vaut True ou False
```

<!-- .slide: data-auto-animate -->
