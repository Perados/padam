# Instructions et conseils g�n�raux :
- Un projet Django, h�berg� sur Github, avec une BDD sqlite (commit�e), est attendu.
- Il n'y a pas de deadline, mais id�alement le projet ne devrais pas prendre plus de 2 jours � r�aliser.
- Mettre l'accent sur le back-end. Le front-end est moins important pour le poste en question.
- Ne pas h�siter � utiliser des m�canismes propres � Django si besoin il y a (ex : signaux, override de save(), CBVs, etc.).
- Ne pas h�siter � laisser des commentaires (ou un document) pour expliquer les choix techniques (eg: expliquer les b�n�fices / contraintes de telle ou telle solution)
- Certains aspects sont volontairement vagues pour laisser une libert� de choix.
- Si vous ne disposez que de peu de temps pour r�aliser l'exercice, concentrez-vous sur la qualit� plut�t que la quantit�. A l'inverse, si vous avez du temps, tout bonus sera appr�ci�.
- Ne pas h�siter � nous poser des questions si besoin (david@padambus.com).

# Exercice :
- Sur la th�matique de Padam, cr�er un syst�me de r�servation tr�s simplifi� permettant � un client de r�server une voiture pour effectuer un trajet.

## Le site devra permettre � un client :
- de s'inscrire, se connecter, se d�connecter.
- de cr�er, voir, et supprimer des r�servations.

## Pour cadrer et simplifier l'exercice, on partira des principes suivants :
- Un trajet est possible avec n'importe quel point de d�part/arriv�e sur Terre, et est disponible � tout moment (cependant, la voiture doit bien-s�r �tre disponible � ce moment l�).
- Une voiture n'accepte qu'un seul client par trajet.
- Une r�servation est gratuite (ne n�cessite pas de paiement).
- Il n'est pas n�cessaire de permettre la cr�ation de voitures via le site. A la place, on pourra par exemple en cr�er quelque-unes directement en base de donn�es.