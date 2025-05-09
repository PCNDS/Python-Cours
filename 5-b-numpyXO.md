

---

## Fonction numpy : array

### Exercice 1 : Créer un tableau numpy à partir d'une liste

<details><summary>Solution</summary>

```python
import numpy as np
# Création d'un tableau numpy à partir d'une liste
arr = np.array([1, 2, 3, 4])
print(arr)
```

</details>

---

### Exercice 2 : Créer un tableau 2D numpy de forme (2, 3) avec des valeurs de 1 à 6

<details><summary>Solution</summary>

```python
import numpy as np
# Création d'un tableau 2D numpy
arr = np.array([[1, 2, 3], [4, 5, 6]])
print(arr)
```

</details>

---

### Exercice 3 : Créer un tableau numpy à partir d'une liste de nombres flottants [1.1, 2.2, 3.3]

<details><summary>Solution</summary>

```python
import numpy as np
# Création d'un tableau numpy avec des flottants
arr = np.array([1.1, 2.2, 3.3])
print(arr)
```

</details>

---

## Fonction numpy : arange

### Exercice 1 : Créer un tableau numpy avec des valeurs de 0 à 9

<details><summary>Solution</summary>

```python
import numpy as np
# Création d'un tableau avec arange de 0 à 9
arr = np.arange(10)
print(arr)
```

</details>

---

### Exercice 2 : Créer un tableau numpy avec des valeurs de 5 à 15

<details><summary>Solution</summary>

```python
import numpy as np
# Création d'un tableau avec arange de 5 à 15
arr = np.arange(5, 16)
print(arr)
```

</details>

---

### Exercice 3 : Créer un tableau numpy avec des valeurs de 0 à 20 avec un pas de 2

<details><summary>Solution</summary>

```python
import numpy as np
# Création d'un tableau avec arange de 0 à 20 avec un pas de 2
arr = np.arange(0, 21, 2)
print(arr)
```

</details>

---

## Fonction numpy : linspace

### Exercice 1 : Créer un tableau numpy avec 5 valeurs également espacées entre 0 et 1

<details><summary>Solution</summary>

```python
import numpy as np
# Création d'un tableau avec linspace de 0 à 1 avec 5 valeurs
arr = np.linspace(0, 1, 5)
print(arr)
```

</details>

---

### Exercice 2 : Créer un tableau numpy avec 10 valeurs également espacées entre 1 et 10

<details><summary>Solution</summary>

```python
import numpy as np
# Création d'un tableau avec linspace de 1 à 10 avec 10 valeurs
arr = np.linspace(1, 10, 10)
print(arr)
```

</details>

---

### Exercice 3 : Créer un tableau numpy avec 3 valeurs également espacées entre -1 et 1

<details><summary>Solution</summary>

```python
import numpy as np
# Création d'un tableau avec linspace de -1 à 1 avec 3 valeurs
arr = np.linspace(-1, 1, 3)
print(arr)
```

</details>

---

## Fonction numpy : dot

### Exercice 1 : Calculer le produit scalaire de deux vecteurs

<details><summary>Solution</summary>

```python
import numpy as np
# Définition des deux vecteurs
v1 = np.array([1, 2, 3])
v2 = np.array([4, 5, 6])
# Calcul du produit scalaire avec dot
result = np.dot(v1, v2)
print(result)
```

</details>

---

### Exercice 2 : Calculer le produit matriciel de deux matrices 2x2

<details><summary>Solution</summary>

```python
import numpy as np
# Définition des matrices 2x2
m1 = np.array([[1, 2], [3, 4]])
m2 = np.array([[5, 6], [7, 8]])
# Calcul du produit matriciel avec dot
result = np.dot(m1, m2)
print(result)
```

</details>

---

### Exercice 3 : Calculer le produit scalaire de deux vecteurs orthogonaux

<details><summary>Solution</summary>

```python
import numpy as np
# Définition de deux vecteurs orthogonaux
v1 = np.array([1, 0])
v2 = np.array([0, 1])
# Produit scalaire doit être zéro
result = np.dot(v1, v2)
print(result)  # Affiche 0
```

</details>

---

## Fonction numpy : sqrt

### Exercice 1 : Calculer la racine carrée de 16

<details><summary>Solution</summary>

```python
import numpy as np
# Calcul de la racine carrée d'un nombre
result = np.sqrt(16)
print(result)
```

</details>

---

### Exercice 2 : Calculer la racine carrée d'un tableau

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau de nombres
arr = np.array([1, 4, 9, 16])
# Calcul de la racine carrée pour chaque élément
result = np.sqrt(arr)
print(result)
```

</details>

---

### Exercice 3 : Calculer la racine carrée d'un nombre flottant 2.25

<details><summary>Solution</summary>

```python
import numpy as np
# Calcul de la racine carrée d'un flottant
result = np.sqrt(2.25)
print(result)
```

</details>

---

## Fonction numpy : sin

### Exercice 1 : Calculer le sinus de 0

<details><summary>Solution</summary>

```python
import numpy as np
# Calcul du sinus de 0
result = np.sin(0)
print(result)
```

</details>

---

### Exercice 2 : Calculer le sinus d'un tableau d'angles en radians [0, π/2, π]

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau d'angles en radians
arr = np.array([0, np.pi/2, np.pi])
# Calcul du sinus pour chaque angle
result = np.sin(arr)
print(result)
```

</details>

---

### Exercice 3 : Calculer le sinus de π/4

<details><summary>Solution</summary>

```python
import numpy as np
# Calcul du sinus de π/4
result = np.sin(np.pi/4)
print(result)
```

</details>

---

## Fonction numpy : cos

### Exercice 1 : Calculer le cosinus de 0

<details><summary>Solution</summary>

```python
import numpy as np
# Calcul du cosinus de 0
result = np.cos(0)
print(result)
```

</details>

---

### Exercice 2 : Calculer le cosinus d'un tableau d'angles en radians [0, π/2, π]

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau d'angles en radians
arr = np.array([0, np.pi/2, np.pi])
# Calcul du cosinus pour chaque angle
result = np.cos(arr)
print(result)
```

</details>

---

### Exercice 3 : Calculer le cosinus de π/4

<details><summary>Solution</summary>

```python
import numpy as np
# Calcul du cosinus de π/4
result = np.cos(np.pi/4)
print(result)
```

</details>

---

## Fonction numpy : sum

### Exercice 1 : Calculer la somme des éléments d'un tableau

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau simple
arr = np.array([1, 2, 3, 4])
# Calcul de la somme des éléments
result = np.sum(arr)
print(result)
```

</details>

---

### Exercice 2 : Calculer la somme des éléments d'un tableau 2D

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau 2D
arr = np.array([[1, 2], [3, 4]])
# Calcul de la somme de tous les éléments
result = np.sum(arr)
print(result)
```

</details>

---

### Exercice 3 : Calculer la somme des éléments d'un tableau avec un axe spécifié (axe 0)

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau 2D
arr = np.array([[1, 2], [3, 4]])
# Somme des éléments selon l'axe 0 (colonnes)
result = np.sum(arr, axis=0)
print(result)
```

</details>

---

## Fonction numpy : mean

### Exercice 1 : Calculer la moyenne des éléments d'un tableau

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau simple
arr = np.array([1, 2, 3, 4])
# Calcul de la moyenne
result = np.mean(arr)
print(result)
```

</details>

---

### Exercice 2 : Calculer la moyenne des éléments d'un tableau 2D

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau 2D
arr = np.array([[1, 2], [3, 4]])
# Calcul de la moyenne de tous les éléments
result = np.mean(arr)
print(result)
```

</details>

---

### Exercice 3 : Calculer la moyenne des éléments d'un tableau avec un axe spécifié (axe 1)

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau 2D
arr = np.array([[1, 2], [3, 4]])
# Moyenne selon l'axe 1 (lignes)
result = np.mean(arr, axis=1)
print(result)
```

</details>

---

## Fonction numpy : average

### Exercice 1 : Calculer la moyenne pondérée des éléments d'un tableau

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau de valeurs
arr = np.array([1, 2, 3, 4])
# Tableau des poids
weights = np.array([0.1, 0.2, 0.3, 0.4])
# Calcul de la moyenne pondérée
result = np.average(arr, weights=weights)
print(result)
```

</details>

---

### Exercice 2 : Calculer la moyenne pondérée avec des poids égaux

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau de valeurs
arr = np.array([1, 2, 3, 4])
# Poids égaux
weights = np.array([1, 1, 1, 1])
# Calcul de la moyenne pondérée (équivalente à mean)
result = np.average(arr, weights=weights)
print(result)
```

</details>

---

### Exercice 3 : Calculer la moyenne pondérée d'un tableau 2D avec un axe (axe 0)

<details><summary>Solution</summary>

```python
import numpy as np
# Tableau 2D
arr = np.array([[1, 2], [3, 4]])
# Poids pour chaque ligne
weights = np.array([0.5, 0.5])
# Moyenne pondérée selon l'axe 0 (colonnes)
result = np.average(arr, axis=0, weights=weights)
print(result)
```

</details>

---

N'hésitez pas à copier-coller ce contenu dans un fichier `.md` pour un rendu parfait sur GitHub !

