# POO

> Découverte de la Programmation Orientée Objet  

Pour la réalisation de vos diagrammes de classe, il faudra au préalable installer :  

* **StarUML** ( http://staruml.io/download ).  

***Penser à respecter l'utilisation de l'anglais dans tous les exercices.***  
***Pour les exercices, les attributs seront de type PRIVATE et les méthodes seront de type PUBLIC.***  

> **INSTANCIER** : Au final, c bien pratique un objet :)

## Exercice 1
Sous ***StarUML***, créer la classe : **Compte Bancaire** avec les éléments suivants :

Attributs :
* **titulaire** de type *string*.
* **solde** de type *integer*.
* **taux d'intérêt** de type *integer*.
* **devise** de type *string*. (*exemple de devise : euros*)

Méthodes :
* **créditer** qui prendra comme paramètre un **montant** de type *integer*.
* **débiter** qui prendra comme paramètre un **montant** de type *integer*.

## Exercice 2
> Après avoir réalisé des modélisations ***UML*** *simples*, nous allons nous baser sur notre diagramme pour créer une classe en **PHP**, dans une page **"bankAccount.php"**.

Via votre ***IDE***, créer la classe : **Compte Bancaire** selon le diagramme de classe précédemment créé dans l'**exercice 1**.

## Exercice 3
Dans la classe: **Compte Bancaire** modifier les méthodes suivantes :
* **créditer** : Faire en sorte que la méthode **crédite** le **solde** du **montant** saisi en paramètre. (EX. *Rajouter(250) = Solde + 250*)
* **débiter** : Faire en sorte que la méthode **débite** le **solde** du **montant** saisi en paramètre. (EX. *Soustraire(250) = Solde - 250*)

## Exercice 4
Dans la classe: **Compte Bancaire** mettre en place des **getters** et des **setters** pour :
- Afficher les **attributs**.
- Attribuer une valeur aux **attributs**.

## Exercice 5
Dans la classe: **Compte Bancaire** mettre en place **une méthode de construction magique** pour que nous puissions définir lors de **l'instanciation** de l'objet :
* Le **titulaire** du compte.
* Le **solde**.
* Le **taux d'intérêt**.
* La **devise**.

## Exercice 6
> Il est temps de tester notre classe ! Nous allons donc instancier notre premier objet :)

Dans une page ***index.php*** :
1. *Charger votre classe* **"bankAccount.php"**.
2. Déclarer un nouvel objet : **Compte d'Ariel** puis l'instancier avec la classe **Compte Bancaire**.
3. *Affecter* les valeurs suivantes aux *attributs* de l'objet créé :
    * **titulaire** = Ariel.
    * **solde** = 10000.
    * **taux d'intérêt** = 1.9%.
    * **devise** = euros.
4. Afficher les attributs de l'objets via un **echo**. (Ex. Bonjour **Ariel**, vous venez d'ouvrir un compte avec un taux d'intérêt de **1.9%** et vous y avez déposé un montant de **10000** euros ...)

5. Appeler la méthode **créditer** avec comme *paramètre* un **montant** de **1250** euros.

6. Afficher le nouveau **solde** du compte via un **echo**. (Ex. Vous venez de créditer votre compte de **1250** euros et votre nouveau solde est de ...).

7. Appeler la méthode **débiter** avec comme *paramètre* un **montant** de **500** euros.

8. Afficher le nouveau **solde** du compte via un **echo**. (Ex. Vous venez de débiter votre compte de **500** euros et votre nouveau solde est de ...).
