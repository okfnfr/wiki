Le calculateur de domaine public est un projet de [ Open Knowledge
France](France "wikilink")

Le [Calculateur du Domaine Public](http://calculateurdomainepublic.fr)
permet de renouer avec la problématique de l’appropriation des œuvres
par les usagers et d’accompagner la réflexion du ministère de la Culture
et de la Communication sur la protection et la valorisation du domaine
public numérique et l’enjeu des métadonnées culturelles. C'est un projet
open source: [voir le github](https://github.com/okfn/pdcalc).

Introduction
============

Les technologies numériques permettent desormais au public d’accéder à
un grand nombre de contenus et données culturelles. Cependant, le statut
juridique de l’oeuvre, qui permet de savoir si il est possible de la
réutiliser ou de l’exploiter, est bien souvent manquant ou peu clair.
Les calculateurs de domaine public visent à rendre plus facile pour tout
le monde pour établir si oui ou non une œuvre est dans le domaine public
dans une juridiction donnée. Les calculateurs de domaine public sont
élaborées par le Groupe de travail du domaine public de l' Open
Knowledge Foundation . Ils s'appuient sur deux pièces importantes de
l'information:

Les lois nationales du droit d'auteur
=====================================

Les calculateurs de domaine public sont liés avec les organigrammes
nationales sur le copyright développés dans le cadre du projet Europeana
, qui représente la fourniture du droit d'auteur sous la forme d' un
arbre de décision ( au format Graphmlz ) . Pour un aperçu de tous les
territoires actuellement disponibles pour les calculateurs de domaine
public , consultez la liste de toutes les organigrammes mis en œuvre .

Ces diagrammes sont convertis ( avec le Graphml2json.rb de script) dans
des fichiers JSON simples qui décrivent le régime national du droit
d'auteur . Ces fichiers peuvent être traitées par les calculateurs du
domaine public, mais subsistent indépendamment du code sous-jacent. Les
fichiers doivent être augmentées en ajoutant des requêtes spécifiques à
chaque décision de l'écoulement. Le calculateur offre un ensemble de
requêtes de base simples qui peuvent être étendues .

Métadonnées bibliographiques
============================

Fichiers de métadonnées décrivent les caractéristiques essentielles d'un
travail à partir d'un point de vue bibliographique , ce qui inclut des
informations sur le travail lui-même ( date de création, date de la
première publication , etc ) et son auteur ( personne morale, personne
physique , date de son décès , etc) .

Les calculateurs de domaine public peuvent prendre métadonnées
bibliographiques dans RDF (xml , n3 , tortue ) et les formats BibJSON .

<Category:Projets> [Category:Projets
actifs](Category:Projets actifs "wikilink")
