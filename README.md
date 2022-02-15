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