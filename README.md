# formation-deep-learning
Les bases du Deep Learning en Intelligence Artificielle.

## Théorie de Hebb

![image](images/7.png)

## Le Perceptron (1957)

![image](images/8.png)

![image](images/9.png)

## Perceptron Multi-Couche

![image](images/10.png)

## Forward Propagation

   Consiste à faire circuler les données de la **première couche** jusqu'à la **dernière couche** pour afin produire une sortie **y**.

   ![image](images/4.png)
## Cost Function

Elle permet de calculer la moyenne des erreurs de notre modèle.

![image](images/5.png)
## Backward Propagation

   Qui consiste à determiner comment la **sortie du réseau** varie
   en fonction des **paramètres (w, b)** présents dans **chaque couche**. Pour cela on calcule une chaine de gradient à savoir comment la sortie de la dernière couche varie en fonction de l'avant dernière, puis comment la sortie de l'avant dernière varie en fonction de l'avant avant dernière ainsi de suite jusqu'à la dernière couche.

   ![image](images/2.png)

## Gradient Descent

   Grâce aux gradients, on peut alors mettre à jour les **paramètres (w, b)** de **chaque couche** de telle sorte à ce qu'ils **minimisent** l'erreur entre **la sortie** du modèle et la **réponse attendue**.

   ![image](images/3.png)

   ## Résumé 
   Pour développer et entrainer un **Réseau de Neurones Artificiels**, on répète en boucle les quatre étapes suivantes:

   ![image](images/6.png)

   ## Le Perceptron

   ![image](images/11.png)
   
   ## Modèle Linéaire

   ![image](images/12.png)

   ![image](images/13.png)

   ![image](images/14.png)

   La fonction de faire cette transformation en probabilité est appélée **Sigmoïd**

   ![image](images/15.png)

   Exemple 1:

      ![image](images/16.png)

   Exemple 2:

      ![image](images/17.png)

   ## La Loi de Bernoulli

   ![image](images/18.png)

   ![image](images/19.png)

   ## Résumé d'un Neurone

   ![image](images/20.png)

   ## La Fonction Coût

   ![image](images/21.png)

   ## Démonstration de la Fonction Coût

   ### Vraisemblance

   ![image](images/22.png)

   Exemple: Si une plante est toxique et que notre modèle nous donne une probabilité de 0.8

   ![image](images/23.png)

   Alors pour calculer la vraisemblance de notre modèle nous allons nous servir  de la loi de **Bernoulli**

   ![image](images/25.png)

   * Si le résultat de notre modèle est proche de 100% ce qui signifie que notre modèle à une vraisemblable proche de 100%

   ![image](images/26.png)

   * Sinon si le résultat de notre modèle est proche de 0% ce qui signifie que notre modèle à une vraisemblable proche de 0%

   ![image](images/27.png)

   ### Problème de la Vraisemblance 
   
   Comme les probabilités sont des nombres inférieure à 0, alors plus on fait le produit des nombres inférieur à 0 plus on tend vers 0.

   ![image](images/28.png)

   ![image](images/29.png)

   Pour eviter que la vraisemblance de notre modèle ne converse vers 0, on l'applique le logarithme.

   ![image](images/31.png)

   Comme La fonction logarithme est une fonction monotône croissante alors elle conserve l'ordre de nos termes.

   ![image](images/32.png)

   Cela signifie que lorsqu'on cherche le maximum de nos  vraisemblances, il sufit de chercher le maximum du log de la vraisemblance. voir graphique
   
   ![image](images/33.png)
   
   Alors par deduction on aura:

   ![image](images/34.png)

  Pour la formule de log loss:
  Au fait on veut maximiser la vraisemblance or en mathématique il n'existe pas de fonction de maximisation mais il n'existe que des fonctions de minimisation par conséquent on essaie de prendre l'inverse de la fonction de minisation. C'est à dire qu'on multiplie par (-1) puis on normalise par (1/m).

  ![image](images/35.png)

  ![image](images/36.png)

  ## Origine de Log Loss
  La fonction **Log Loss** elle tire son origine de la maximisation de la vraisemblance(**Likelihood**)


## Descent de Gradient

![image](images/38.png)

## Gradient de Descent en Mathématique

![image](images/39.png)

* Si la dérivée est négative ça nous indique que la dérivée diminue lorsque **w** augmente.

![image](images/40.png)

* Si la dérivée est positive ça nous indique que la dérivé augmente lorsque **w** augmente.

![image](images/41.png)

* **Descente de Gradient**

![image](images/42.png)

* en répetant cette formule, le gradient descent jusqu'au minimum de notre fonction.

![image](images/43.png)

## Pratique Cours Suivant

![image](images/44.png)

## Quelques dérivées Utiles pour le Cours

![image](images/45.png)

## Demonstration de la Descente de Gradient

![image](images/gradient_descente_demo.jpg)

## Vectorisation

![image](images/46.png)

![image](images/47.png)

## Exemple en Python

![image](images/48.png)

## Utilité des Vecteurs

![image](images/49.png)

## Matrices

![image](images/50.png)

## Exemple 

![image](images/51.png)

## Les Opérations Matricielles à Connaître en Deep Learning

![image](images/52.png)

### 1. Les Additions  et Soustractions

![image](images/53.png)

### 2. La Transposition

![image](images/54.png)

### 3. La Multiplication

![image](images/56.png)

![image](images/57.png)


### Exercice

![image](images/58.png)

## Vectorisation des Equations de Deep Learning

![image](images/59.png)

## Dataset 
A la base, on a un Dataset de de x1 et x2 variables indépendantes et y variable dépendante.

![image](images/61.png)

## Vectorisation du Dataset

![image](images/62.png)

### Vectorisation de Z

![image](images/63.png)

### Vectorisons nos Equations

![image](images/64.png)

### Vectorisation de A

![image](images/65.png)

### Vectorisation de la Fonction Coût

![image](images/66.png)

![image](images/67.png)

![image](images/68.png)

### Vectorisation de la Descente de Gradient

![image](images/69.png)

![image](images/70.png)

![image](images/71.png)

* Au en Python, il nous reste qu'à calculer W et B.

![image](images/72.png)

### Vectorisation des Gradients

![image](images/73.png)

![image](images/74.png)

![image](images/75.png)