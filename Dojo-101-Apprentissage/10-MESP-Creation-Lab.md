# Mettre en place un environnement de test (Lab)

Ce lab vous servira pour les mises en situations professionnelles

Durée estimée: 2 jours

Ce contenu est publié sous licence "GNU GENERAL PUBLIC LICENSE Version 3" et les sources sont sur le projet Github Dojo-101, merci d'en tenir compte dans vos usages.

## Ressources

[Gestes professionnels](https://github.com/Aif4thah/Dojo-101)
[VulnerableLightApp](https://github.com/Aif4thah/VulnerableLightApp)
[Badblood](https://github.com/davidprowe/BadBlood)
[ISO Microsoft](https://www.microsoft.com/fr-fr/evalcenter)
[ISO Linux Debian](https://www.debian.org/index.fr.html)

## Contexte

1. Installer 3 machines virtuelles (VM) : Un contrôleur de domaine (Windows Serveur) + 1 Windows + 1 Linux
2. Faire les mises à jour de sécurité
3. Pour la Workstation Windows: Joindre le domaine
4. Créer un utilisateur admin (root/administrateur) et un utilisateur standard et local sur chaque machine
5. Mettre en place les services sur l’AD et configurer la Workstation pour leur utilisation
    * DNS : celui de votre Domaine AD
    * Web : VulnerableLightApp : le service doit être disponible sur la boucle locale de votre machine Windows ou Linux.
    * SSH et WinRM : accessible aux administrateurs uniquement sur Windows et Linux
    * Partage SMB: un partage "Readonly" accessible à tous en lecture, un partage "rw" accessible à tous en lecture et écriture sur le serveur Windows

6. execution du script badblood: `. ./invoke-badblood.ps1`

## Modalités pédagogiques

Binôme ou seul (au choix)

## Modalités d'évaluation

Fourniture d'un script ou des captures d'écran qui présente : 
* le statut des services installés (DNS, Web, Partage, SSH / WinRM)
* le nombre d'utilisateurs contenus dans l'AD

## Livrables

* le script, le cas échéant
* le résultat du script ou les captures d'écran

## Critères de performance

Le lab est opérationnel

## Pour finir

Si vous avez apprécié ce cours et souhaitez valoriser votre travail, n'hésitez pas à ajoutez une ⭐ au [projet](https://github.com/Aif4thah/Dojo-101)