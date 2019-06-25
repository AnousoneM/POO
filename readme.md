# POO

> Découverte de la Programmation Orientée Objet : Définir les comportements d'un objet.
> De la conception à la création ...  

Pour la réalisation de vos diagrammes de classe, il faudra au préalable installer :  

* **StarUML** ( http://staruml.io/download ).  

***Penser à respecter l'utilisation de l'anglais dans tous les exercices.***  
***Pour les exercices, les attributs seront de type PRIVATE et les méthodes seront de type PUBLIC.***  

> Commençons par une petite introduction simple via un diagramme de classes et une petite notion d'héritage ;)

## Exercice 1
Sous ***StarUML***, créer la classe : **Employé**.  

Un **Employé** aura comme attributs :
* un **nom** de type *string*.
* un **prénom** de type *string*.
* un **salaire** de type *integer*.

## Exercice 2
Sous ***StarUML***, rajouter à la classe : **Employé**, la méthode suivante :
* **travailler**.

## Exercice 3
Sous ***StarUML***, créer la classe : **Cadre** qui hérite de la classe **Employé**.  

Un **Cadre** aura comme attribut :
* une **prime** de type *integer*.

## Exercice 4
Sous ***StarUML***, rajouter à la classe : **Cadre**, la méthode suivante :
* **avoir des responsabilités**.

## Exercice 5
Sous ***StarUML***, dans **Tools**, rajouter l'extension **PHP** et générer les classes dans un fichier "laManu.php".


## Exercice NEW
Sous ***StarUML***, créer la classe : **Compte Bancaire** avec les éléments suivants :

Attributs :
* **titulaire** de type *string*.
* **solde** de type *double*.
* **devise** de type *string*. (*exemple de devise : dollars*)

Méthodes :
* **créditer** de type *void*, qui prendra comme paramètre un **montant** de type *double*.
* **débiter** de type *void*, qui prendra comme paramètre un **montant** de type *double*.

## Exercice 6
> Après avoir réalisé des modélisations ***UML*** *simples*, nous allons créer une classe dans **Visual Studio**, dans une **application console**.

Sous ***Visual Studio***, créer la classe : **Compte Bancaire** selon le diagramme de classe précédemment créé dans l'**exercice 5**.

## Exercice 7
Sous ***Visual Studio***, dans la classe: **Compte Bancaire** modifier les méthodes suivantes :
* **créditer** : Faire en sorte que la méthode **crédite** le **solde** du **montant** saisi. (EX. *Rajouter(250) = Solde + 250*)
* **débiter** : Faire en sorte que la méthode **débite** le **solde** du **montant** saisi. (EX. *Soustraire(250) = Solde - 250*)

## Exercice 8
Sous ***Visual Studio*** :
1. Déclarer un nouvel objet : **CompteLaManu** puis l'instancier avec la classe **Compte Bancaire**.
2. *Affecter* les valeurs suivantes aux *attributs* de l'objet créé :
* **titulaire** = LaManu.
* **solde** = 2000.
* **devise** = euros.
3. Appeler la méthode **créditer** avec comme *paramètre* un **montant** de **19** euros.
4. Afficher via *Console.WriteLine()* : Le **titulaire**, le **solde** et la **devise** du **CompteLaManu**. (EX. *Le solde du compte de LaManu est de 2019 euros*).  

