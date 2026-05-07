---
marp: true
paginate: true
theme: gaia
backgroundColor: #FFFFFF
---


# Introduction aux algorithmes  
### *Immersion DWWM – Niveau débutant*

---

<!-- paginate: true -->
# Objectifs de la séance

- Comprendre ce qu’est un **algorithme**
- Visualiser la logique grâce à des **schémas**
- Découvrir les notions de **variables**, **conditions**, **boucles**
- S’entraîner avec quelques **exercices pratiques**
- Se projeter dans la formation **DWWM**

---

# C’est quoi un algorithme ?

> **Une suite d’instructions simples, ordonnées, permettant de résoudre un problème.**

Exemples du quotidien :
- suivre une recette  
- utiliser un GPS  
- trier des objets  
- faire une liste de courses  

---

# Schéma : un algorithme, c’est quoi ?

```
+-------------------+
|   Problème à      |
|     résoudre      |
+---------+---------+
          |
          v
+-------------------+
|  Suite d'étapes   |
|   (instructions)  |
+---------+---------+
          |
          v
+-------------------+
|    Résultat       |
+-------------------+
```

➡️ On part d’un problème → on applique une méthode → on obtient un résultat.

---

# Les briques de base

## 1. Les instructions  
→ actions simples

```
Afficher "Bonjour"
Demander l'âge
Calculer total = prix * quantité
```

---

## 2. Les variables  
→ des boîtes où l’on stocke des informations

```
+----------+       +----------+
|  âge     |  -->  |   25     |
+----------+       +----------+
```

---

## 3. Les conditions  
→ “si… alors…”

```
        +----------------------+
        |   âge >= 18 ?        |
        +----------+-----------+
                   |
        +----------+-----------+
        |                      |
       Oui                    Non
        |                      |
        v                      v
"majeur"                "mineur"
```

---

## 4. Les boucles  
→ répéter une action

```
+-------------------------------+
| compteur = 1                  |
+---------------+---------------+
                |
                v
      +------------------+
      | afficher compteur|
      +--------+---------+
               |
               v
      +------------------+
      | compteur = +1    |
      +--------+---------+
               |
               v
     Recommencer tant que
       compteur <= 5
```

---

# Exemple : faire un café

**Algorithme :**

1. Prendre une tasse  
2. Mettre la tasse sous la machine  
3. Insérer une capsule  
4. Appuyer sur le bouton  
5. Attendre  
6. Boire le café  

---

# Diagramme : faire un café

```
[Début]
   |
   v
Prendre une tasse
   |
   v
Mettre sous la machine
   |
   v
Insérer capsule
   |
   v
Appuyer bouton
   |
   v
Attendre
   |
   v
Boire café
   |
   v
[Fin]
```

---

# Exemple informatique

**Problème :** dire si une personne est majeure.

```
Début
 |
 v
Demander âge
 |
 v
Si âge >= 18 ?
 |        |
Oui      Non
 |        |
 v        v
Afficher  Afficher
"majeur"  "mineur"
 |
 v
Fin
```

---

# Exemple de boucle

**Compter de 1 à 5**

```
compteur = 1
Tant que compteur <= 5
    afficher compteur
    compteur = compteur + 1
Fin Tant que
```

---

# Ce qu’on attend de vous

- Curiosité  
- Motivation  
- Capacité à raisonner étape par étape  
- Pas besoin d’être “bon en maths”  
- Juste envie d’apprendre et de comprendre  

---

# Exercices

## Exercice 1 : Algorithme du quotidien  
Décrire les étapes pour **se préparer le matin**.  
Objectif : 8 à 12 étapes.

---

## Exercice 2 : Condition simple  
Écrire un algorithme qui :

> Demande un nombre et dit s’il est **pair** ou **impair**.

Indice : utiliser le test  
```
si (nombre % 2 == 0)
```

---

## Exercice 3 : Boucle  
Écrire un algorithme qui :

> Affiche les nombres de 10 à 1 (à l’envers).

---

## Exercice 4 (optionnel – logique)  
On veut un algorithme qui :

> Demande l’âge et affiche :  
> - “Enfant” si âge < 12  
> - “Adolescent” si 12 ≤ âge < 18  
> - “Adulte” si âge ≥ 18  

Créer le diagramme correspondant.

---

# Conclusion

- Un algorithme = **une méthode pour résoudre un problème**  
- Les schémas aident à comprendre la logique  
- Les bases : **instructions, variables, conditions, boucles**  
- Vous êtes prêts pour aller plus loin dans l’immersion DWWM  

---

Si tu veux, je peux aussi te générer :  
une version **avec couleurs et thèmes Marp personnalisés**  
une version **avec des exercices corrigés**  
une version **plus orientée pseudo-code**