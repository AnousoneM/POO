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

## Exercice 8
Sous ***Visual Studio*** :
1. Déclarer un nouvel objet : **CompteLaManu** puis l'instancier avec la classe **Compte Bancaire**.
2. *Affecter* les valeurs suivantes aux *attributs* de l'objet créé :
* **titulaire** = LaManu.
* **solde** = 2000.
* **devise** = euros.
3. Appeler la méthode **créditer** avec comme *paramètre* un **montant** de **19** euros.
4. Afficher via *Console.WriteLine()* : Le **titulaire**, le **solde** et la **devise** du **CompteLaManu**. (EX. *Le solde du compte de LaManu est de 2019 euros*).  
