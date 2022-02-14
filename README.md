# formation-deep-learning
Les bases du Deep Learning en Intelligence Artificielle.


## Forward Propagation
   Consiste à faire circuler les données de la **première couche** jusqu'à la **dernière couche** pour afin produire une sortie **y**.

   ![image](images/4.png)
## Cost Function

## Backward Propagation

   Qui consiste à determiner comment la **sortie du réseau** varie
   en fonction des **paramètres (w, b)** présents dans **chaque couche**. Pour cela on calcule une chaine de gradient à savoir comment la sortie de la dernière couche varie en fonction de l'avant dernière, puis comment la sortie de l'avant dernière varie en fonction de l'avant avant dernière ainsi de suite jusqu'à la dernière couche.

   ![image](images/2.png)

   Grâce aux gradients, on peut alors mettre à jour les **paramètres (w, b)** de **chaque couche** de telle sorte à ce qu'ils **minimisent** l'erreur entre **la sortie** du modèle et la **réponse attendue**.

   ![image](images/3.png)

## Gradient Descent
   