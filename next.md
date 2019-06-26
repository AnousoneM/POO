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
