---
layout: page
title: DADA
---

Dada pour Demande d’accès aux documents administratifs est un projet de
[Open Knowlege France](France "wikilink").

Le projet DADA et l'association Open Knowledge France sont ouverts à
tous types de contributions. Les besoins exprimés ici à sont à titre
indicatif. Si vous souhaitez donner un coup de main, même temporaire,
n'hésitez pas ! Pour nous contacter : <contact@okfn.fr>

En résumé
=========

**Quoi :** DADA est un service en ligne de demande d'accès aux documents
administratifs non personnels qui permet de suivre et partager
l'évolution et le résultat de sa demande. DADA est la version française
du service [What do They Know](https://www.whatdotheyknow.com/)

**État :** projet relancé en Aout 2015

**Ce qu’il nous manque :** L'équipe Mysociety, qui coordonne le
développement du logiciel Alaveteli, nous conseille d'installer le
logiciel sur une instance dédiée. Nous sommes donc à la recherche d'un
hébergeur pour l'application.

**Équipe:**

-   Sabine Blanc sabine@sabineblanc.net
-   Pierre Chrzanowski @gmail.com
-   Cyril Blaecke
-   Samuel Goeta

Le projet en détail
===================

Objectif général
----------------

La plate-forme Dada vise à promouvoir et faciliter l'application de la
loi du 17 juillet 1978 (loi Cada) qui reconnaît à toute personne le
droit d'obtenir communication des documents détenus par une
administration dans le cadre de sa mission de service public.

Fonctionnalités
---------------

Le service Dada permet:

-   d'identifier plus facilement l'administration qui possède
    l'information désirée
-   de lui soumettre directement la demande en ligne
-   d'accéder aux autres demandes d'information et aux réponses
-   d’accéder aux avis de la CADA

Ressources
----------

Pour faciliter la démarche, DADA s’appuie sur deux ressources :

-   un annuaire de l’administration pour identifier plus facilement
    l’interlocuteur et lui adresser sa demande en ligne,
-   le double historique de la [jurisprudence
    Cada](http://cada.data.gouv.fr/), la commission chargée de veiller à
    l’application de la loi de 1978, et des autres demandes
    d'information et les réponses apportées.

Besoin d'aide
-------------

Nous sommes à la recherche de volontaires pour nous aider sur:

-   Traduction du site en français
-   Création d'un design web spécifique au site
-   Aannuaire de l'administration
-   Aider notre administrateur système
-   Modération et gestion des demandes d'accès

Procédure de demande d'accès
----------------------------

Adapté au contexte français, la démarche du citoyen ayant une demande
suit ce chemin :

![Cliquer pour agrandir](Dada.png "Cliquer pour agrandir")

### Cas d'utilisation (fictif)

-   Monsieur Juste souhaite connaitre la répartition de la Réserve
    Parlementaire. Il effectue une recherche sur le site DADA et trouve
    que ces données sont désormais disponibles sur data.gouv.fr
-   Madame Soleil demande au Ministère du Développement Durable et à
    l'Ademe les données collectées pour la réalisation du rapport "Vers
    un mix électrique 100% renouvelable en 2050". Madame Soleil
    n'obtient pas de réponse après un mois et décide donc de saisir la
    CADA.
-   Monsieur Soucieux demande à la commune de Fontaine (Isère) les
    relevés de pollution de ses rivières. La commune lui répond sur le
    site DADA en transmettant un document PDF contenant les derniers
    relevés.

Le respect de la vie privée
---------------------------

Nous avons rencontré la Cnil pour recevoir des conseils et sécuriser au
mieux juridiquement le dispositif :

-   L’arbre de décision intègre que le document administratif demandé ne
    met personne en cause. Cela a pour avantage d'attirer l’attention du
    demandeur sur ce paramètre légal, et de protéger juridiquement Open
    Knowledge France en faisant inscrire dans ses CGU la responsabilité
    de la requête au demandeur.
-   La base des inscrits sera déclarée à la Cnil.
-   L'adresse électronique du requérant et de l'administration devront
    être masquées.
-   Concernant les cookies, la Cnil met à disposition du code open
    source qu'il faudra reprendre pour être en conformité.
-   Les archives étant sous le régime dérogatoire des données
    culturelles à la loi Cada, elles sont exclues.

Il est préférable de se montrer pédagogique, quitte à charger un peu le
site de rappels juridiques :

-   indiquer aux agents de plutôt répondre avec une signature générique
    et pas en leur nom propre,
-   avertir des réutilisations potentielles et possibles des données
    rendues publiques via Dada,
-   vérifier que les documents ne relèvent pas du secret de la
    correspondance, etc.

Alaveteli
---------

Dada reprend un logiciel open source déjà mis en œuvre dans une
vingtaine de pays, [Alaveteli](http://alaveteli.org/). Son déploiement
sécurisé implique qu’un administrateur système Linux connaissant Ruby on
rails s’y attelle. Vous trouverez [la documentation
ici](http://alaveteli.org/docs/installing/).

Spécifications serveur: Linux, 20GB disk. 2GB RAM.

Dans un futur idéal…
--------------------

A terme, Dada pourra aussi servir à identifier les jeux de données à
ouvrir en priorité.

A l’étranger
------------

Voici quelques exemples de déclinaison d’Alaveteli :

[What do they know](https://www.whatdotheyknow.com/) au Royaume-Uni, où
plus de 240000 demandes ont été faites

[Tuderechoasaber.es](http://www.tuderechoasaber.es/) en Espagne

[Доступ До Правди](https://dostup.pravda.com.ua/list/all) (“Accéder à la
vérité”) en Ukraine

<Category:Projets> [Category:Projets
gelés](Category:Projets gelés "wikilink")
