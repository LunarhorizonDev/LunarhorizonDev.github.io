PSEUDOLAB BTS SIO — V2

PRÉSENTATION PseudoLab BTS SIO est un mini-laboratoire pédagogique
d’algorithmique destiné aux étudiants de BTS SIO.

L’objectif est de permettre aux étudiants de pratiquer le pseudo-code de
manière progressive et intensive directement dans leur navigateur :
écrire, exécuter, observer, corriger et recommencer.

Cette version V2 constitue le prototype du futur module Algorithmique /
Pseudo-code de SIO Lab.

FONCTIONNALITÉS - 10 missions progressives - Éditeur de pseudo-code
intégré - Exécution et validation automatique - Affichage des
variables - Trace d’exécution - Indices et corrections - Progression
sauvegardée dans le navigateur - Mode entraînement libre - Aide
syntaxique - Mission professionnelle ARENA CLUB - Niveaux progressifs -
Barre d’insertion rapide

BARRE D’INSERTION RAPIDE ← LIRE AFFICHER CONSTANTE + - * / = >= <= SI SI
/ SINON VRAI FAUX

Exemple :

DEBUT LIRE prix LIRE quantite total ← prix * quantite AFFICHER total FIN

Exemple avec une condition :

DEBUT LIRE age

    SI age >= 18 ALORS
        AFFICHER "Majeur"
    SINON
        AFFICHER "Mineur"
    FIN SI

FIN

PROGRESSION 1. Affichage 2. Variables 3. Entrées utilisateur 4. Calculs
5. Constantes 6. Conditions simples 7. SI / SINON 8. Débogage 9. Calcul
conditionnel 10. Mise en situation professionnelle

UTILISATION LOCALE Télécharger ou cloner le dépôt, puis ouvrir
index.html dans un navigateur récent.

Aucune installation supplémentaire n’est nécessaire pour cette version.

PUBLICATION AVEC GITHUB PAGES PseudoLab V2 est une application
HTML/CSS/JavaScript autonome.

Pour le dépôt utilisateur LunarhorizonDev.github.io, placer index.html à
la racine si PseudoLab doit devenir la page principale :

LunarhorizonDev.github.io/ ├── index.html └── README.txt

Si le dépôt héberge déjà un autre site, utiliser plutôt un sous-dossier
:

LunarhorizonDev.github.io/ ├── index.html ├── README.txt └── pseudolab/
└── index.html

Dans ce second cas, PseudoLab sera publié sous le chemin /pseudolab/.

Dans GitHub : 1. Ouvrir le dépôt. 2. Aller dans Settings. 3. Ouvrir
Pages. 4. Configurer le déploiement depuis la branche main si
nécessaire. 5. Sélectionner le dossier racine approprié. 6. Enregistrer
et attendre la publication.

DONNÉES ET PROGRESSION Dans la V2, la progression est enregistrée
localement dans le navigateur.

Il n’y a donc actuellement : - aucun compte étudiant ; - aucune base de
données ; - aucune synchronisation entre appareils.

Effacer les données locales du navigateur peut supprimer la progression.

ÉVOLUTION : SIO LAB PseudoLab a vocation à devenir le premier
laboratoire de SIO Lab.

Modules envisagés : - Algorithmique / Pseudo-code - HTML / CSS -
JavaScript - PHP - SQL - Débogage - Git - Cybersécurité

Principe pédagogique :

EXPÉRIMENTER → COMPRENDRE → S’ENTRAÎNER → RÉSOUDRE → SOUMETTRE →
RECEVOIR UN FEEDBACK → CORRIGER → FAIRE VALIDER → PROGRESSER

PUBLIC BTS SIO — option SLAM Algorithmique et programmation

STATUT Version : V2 Statut : prototype pédagogique fonctionnel Usage :
pédagogique
