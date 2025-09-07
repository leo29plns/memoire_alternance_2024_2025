---
numbersections: true
---

# Avant-propos {-}

En m’immisçant dans la rédaction de ce mémoire, j'ai d'abord pensé à la forme qu'allait prendre celui-ci. En effet, c'est elle qui m'aidera à étayer mon propos. Bien qu'une problématique générale m'aide à guider ce document, il y a également une trame de fond qui était à mon sens très importante : rendre compte d'une évolution dans le temps et des enseignements reçus grâce à l'alternance. Dans ce cas précis alors, il est nécessaire de marquer le contexte : savoir ce qui était, pour comprendre l'avancement.

C'est ainsi que j'ai pris la décision d'opter pour une forme un tant soit peu moins académique pour la rédaction de ce mémoire. Si je pensais hier que la formation MMI ne me transmettrait que des compétences techniques en programmation, j’ai découvert bien davantage : une philosophie de travail, une vision élargie du rôle que je souhaite incarner demain. Si je ne devais choisir qu'un mot pour résumer ce que j'ai appris, je choisirais sans hésitation celui de « créativité ».  
Car oui, c'est bien la créativité qui a guidé toutes ces lignes de code, et non l'inverse. C'est de toutes ces idées nouvelles qu'ont émané un schéma technique qui n'a que pour seul but de desservir cette même créativité.

Voilà donc pourquoi cet écrit reprendra de temps à autres les codes du récit ; toujours dans la même optique : exposer une situation initiale pour aboutir à une situation finale (cf. le schéma narratif).  
Le mémoire étant un exercice de développement de la pensée, ayant pour objectif in fine d'exprimer une opinion [@MemoireEcrit2024], il était pour moi important qu'il soit un reflet personnel, adoptant un style qui m'est propre.

Aussi, cet écrit ne prétend aucunement à une expertise dans un domaine quelconque. C'est un essai invitant à la réflexion et à la remise en question.

# Remerciements {-}

Gaëlle et Michel
Alexis
Mélanie et Julien

# Résumé {-}

Ce mémoire retrace l’expérience d’un étudiant en alternance chez Publicis Sapient entre 2024 et 2025. Il analyse la transformation du métier de développeur web à travers une démarche introspective. La réflexion s’appuie sur la métaphore des cols bleus et des cols blancs et interroge l’influence des _Digital Factories_. À partir d’entretiens, d’observations et de lectures, il met en lumière des enjeux éthiques, organisationnels et identitaires.

# Abstract {-}

This dissertation recounts the experience of a work-study student at Publicis Sapient between 2024 and 2025. It examines the transformation of the web developer profession through an introspective lens. The discussion draws on the metaphor of blue-collar and white-collar workers and questions the influence of _Digital Factories_. Based on interviews, observations, and literature, it sheds light on ethical, organizational, and identity-related challenges.

# Table des matières {-}
::: {#toc}
:::

# Cadre du mémoire {-}

## Contexte général

Le BUT MMI de Champs-sur-Marne impose la réalisation d'une alternance en entreprise pour la troisième année de formation. Cet exercice veut favoriser l'insertion professionnelle des étudiants. Pour rendre compte de cette expérience, les étudiants se soumettent à la rédaction d'un mémoire d'alternance, contexte dans lequel ce mémoire est né.

## Objectifs du mémoire

Ce mémoire a pour objectif premier de montrer une introspection personnelle par la réalisation d'une alternance au sein d'une entreprise. Ce mémoire veut rendre compte d'une progression, d'une évolution personnelle et professionnelle, tout en montrant un parallèle avec la formation étudiée.

## Démarche méthodologique

Pour guider la rédaction de ce document, je me suis appuyé sur des interviews que j'ai réalisées auprès de mes collègues. Celles-ci m'ont aidé notamment à établir la structure de ce document.

Je me suis également appuyé sur des observations personnelles tout au long de mon alternance.

Enfin, j'ai récolté nombre d'informations et de données depuis Internet. La source de ces informations est accessible depuis la bibliographie de ce document.

## Structure du mémoire

### La forme guidée par des valeurs

Vous le comprendrez au cours de votre lecture de ce document : l'éthique est un point important de ma réflexion. Pour être fidèle à cette idée, j'ai décidé de suivre les principes suivants pour guider ma rédaction :

- **Libre** Ce document est distribué sous licence MIT, permettant sa réutilisation dans n'importe quel contexte professionnel ou privé, gratuitement.
- **Transparence** Afin de suivre une logique d'ouverture Open Source, et montrer les procédés de création de ce document, il a été décidé d'ouvrir publiquement le _repository_ git.
- **Accessibilité** Afin d'éviter l'exclusion d'un trop grand nombre de publics, ce document a été réalisé en Markdown et est exporté avec Pandoc. Cela permet de réaliser des exports notamment vers HTML avec une syntaxe compatible avec les lecteurs d'écran par exemple.
- **Approche humaine** Ce mémoire se base sur diverses interviews réalisées avec mes collègues, m'ayant permis de réaliser ainsi la structure de ce document.

## Outils utilisés

Assumant un style d’écriture plus libre, ce mémoire s’appuie cependant sur un cadre rigoureux pour traiter le sujet de manière structurée. Ainsi, ont été utilisés les outils suivants afin d'adopter ce cadre constant.

- **Zettlr** m'a permis de me concentrer sur la rédaction de ce mémoire, avec pour simple outil le Markdown. Cela permet également un export vers divers formats : PDF et HTML entre autres.
- **Zotero** et l'utilisation conjointe de **BetterBibTeX** m'ont permis d'établir une bibliographie rigoureuse, permettant de consulter facilement mes sources, et de les versionner.
- **Git** et **GitHub** ont permis le versionnement intégral de ce mémoire. Par-delà la simple fantaisie du développeur, elle me permet d'assurer de la redondance, et de créer des automatisations pour l'export.
- **ChatGPT**  a été utilisé pour la relecture de ce document, ainsi que pour la réalisation de recherches sur le sujet.

## Utilisation de l'intelligence artificielle

Ce document a été réalisé avec une aide non négligeable de l'intelligence artificielle, notamment grâce à ChatGPT, un outil développé par OpenAI. L'utilisation de cet outil peut paraître incongrue, surtout en considération de mes valeurs morales. Pourtant, l'IA s'impose comme l'outil de demain, et elle en fait une belle démonstration ici. ChatGPT m'a aidé à corriger les fautes d’orthographe qui se sont glissées dans ce document. ChatGPT se trouve être également un formidable moteur de recherche, parvenant à de meilleurs résultats que Google Scholar pour des recherches dans la littérature scientifique. Enfin, cet outil m'a également permis de trouver l'inspiration pour certaines tournures de phrases, certains sujets.  
Cet outil n’a pas remplacé ma réflexion ni mon travail d’écriture, mais il a contribué à en améliorer la clarté et la précision. À votre initiative, je pourrais vous donner davantage de précisions, par souci de transparence.

# Travailler dans le _Digital_

Ça y est, j'y suis ! Après trois mois de travail consécutifs au sein du Groupe Progress, je peux enfin le dire : j'ai réalisé ma première expérience professionnelle.

Comme n'importe quelle expérience professionnelle, on arrive avec des attentes.  
La première d'entre elles est simple, c'est la rémunération pour le travail effectué. C'est la contrepartie pour avoir donné de son temps et de sa force de travail. Le stage n'étant pas le statut professionnel le plus valorisant financièrement parlant, il va de soi que ce n'était pas ma première attente.  
La deuxième attente, moins formelle, est pourtant celle qui avait le plus de sens à mes yeux : l'enrichissement personnel. Celui-ci se matérialise de plein de formes différentes. Peut-être souhaite-t-on développer nos compétences techniques, nos compétences organisationnelles, notre capacité à travailler en groupe ? Mais ces attentes s'accompagnent aussi de celles qui sont implicites. Le travail est aujourd’hui l’un des principaux marqueurs de reconnaissance sociale : c’est souvent la première chose que l'on mentionne en se présentant. Mes amis, ma famille : que vont-ils en penser ?

Bref, vous le comprendrez, cette expérience est à l'origine d'une profonde remise en question de mes aspirations professionnelles, et bien au-delà : ce que je souhaite faire de ma vie. C'est ce qui a, entre autres, constitué le fil conducteur de mon rapport de stage de 2024. 

Je présentais alors au 22 juin de la même année ce travail de réflexion, cet exercice introspectif, devant madame Florence [Bister]{.smallcaps} et monsieur Renaud [Epstein]{.smallcaps}. Au cours de cette soutenance, j'ai pu exprimer le déroulé de mon stage, et surtout, la dissonance entre mes attentes préalables et la réalité du terrain. J'y exprime notamment une reconnaissance somme toute relative au sein de l'entreprise, mais surtout un sentiment de détachement vis-à-vis des autres employés.  
Là n'était pas la question du statut de stagiaire, mais plutôt celle du regard porté aux développeurs. Ce regard comme si le développeur n'était finalement qu'un simple rouage dans une production numérique. Un développeur réduit à une fonction dépersonnalisée.  
Malgré cela, il faut tout de même relativiser : il est aisé de comprendre pourquoi un tel regard nous a été accordé. L'équipe des développeurs travaillait la majorité de son temps sur la correction de bugs. Quand celle-ci ne travaillait pas à corriger un problème, elle travaillait à l'intégration d'une idée déjà toute faite, dont il ne manque plus qu'une solution technique.  
Chaque jour se ressemblait et une certaine routine s'était installée. Le travail portait surtout sur des tâches non automatisables et répétitives.  
Alors, le jour de ma soutenance de rapport de stage, je témoignais de cette perte de sens du métier de développeur. J'ai alors accompagné mon témoignage de questions : est-ce le propre de mon entreprise, est-ce le reflet d'une transformation du métier de développeur ?

Après avoir conclu ma soutenance, et répondu à l'ensemble des questions du jury, vient enfin le temps pour moi de me préparer afin de laisser la place au prochain candidat. Ce moment est souvent accompagné d'un relâchement, l'exercice étant terminé, la pression et le stress diminuent. C'est un moment propice aux discussions officieuses.  
C'est donc en rangeant mes affaires que monsieur [Epstein]{.smallcaps} m'interpelle et me confie : le constat que j'ai posé lui semble intéressant, et remet en perspective le métier de développeur. La phrase suivante a particulièrement retenu mon attention :

> « Finalement, le développeur est en train de devenir presque un ouvrier, à force de tâches répétitives […]  »

Je n'ai pas saisi sur l'instant toute la profondeur de cette réflexion. Pourtant, elle se retrouve aujourd'hui centrale dans mon questionnement.

Le temps a passé, et quelques mois plus tard, me voilà dans une autre entreprise : me voilà à Publicis Sapient. Je découvre alors un univers significativement différent, que ce soit en termes d'échelle, de périmètre de projet, ou même encore de projet en lui-même.  
Une chose a marqué mon arrivée dans cette entreprise : je vais travailler au sein d'une grande équipe appelée la _Digital Factory_, littéralement, « l'usine numérique ».

Ce terme de _Digital Factory_ m'est familier. Il me rappelle un concept vague que j'avais croisé à plusieurs reprises sur internet. La désignation comme telle d'une équipe de développeurs illustre une vision du travailleur comme d'un maillon d'une chaîne de production. Caricaturée, l’usine, c’est là où l’individu devient interchangeable et où chaque geste est compté, chronométré et calibré pour ne servir que le rendement. Le terme de _Digital Factory_ serait-il maladroit ?

Peu importe les intentions qui auraient été prêtées au nom de _Digital Factory_, c'est l'interprétation que l'on en fait qui prévaut, et il semble que ce terme soit galvaudé. Le docteur Fabian [Namberger]{.smallcaps} en propose une illustration dans @DigitalFactoryReview [].  
Fabian [Namberger]{.smallcaps} est chercheur postdoctoral en design urbain à l’Université HafenCity de Hambourg. Son parcours universitaire offre une vision concrète et matérielle de certains concepts parfois plus abstraits. Notamment, ses derniers travaux portent sur l’intégration des plateformes numériques dans l’espace urbain. Cela permet de mettre en relief une économie numérique qui se projette en dehors des écrans. C'est à l'image de sa thèse de doctorat portant sur les activités de l'entreprise de VTC Uber dans la ville de Toronto.

@DigitalFactoryReview [] montre un concept cynique de l'usine numérique, mettant en parallèle les « player-workers » du jeu vidéo _World of Warcraft_ en Chine.

> « While customers from the United States, Europe, Japan and Korea pay a little extra for fast progress through the game, Chinese player-workers spend hours on end on the same repetitive click tasks »

Les travailleurs effectuent des tâches répétitives et routinières dans un environnement analogue, révélant que le numérique repose sur un travail proche de celui d’une usine traditionnelle dans ce cas précis.  

Tout cela m’a ramené à mon échange avec Renaud [Epstein]{.smallcaps} et à cette phrase qui m’avait marqué : le développeur est-il en train de devenir un ouvrier ? La question n’est pas simple, mêlant nature des tâches, considération des pairs et répétition des gestes. Travailler dans une _Digital Factory_ équivaut-il à être un ouvrier ? Travailler à la Digital Factory : col blanc ou col bleu ?

Cette interrogation sur le statut du développeur au sein de la _Digital Factory_ reprend une métaphore sociologique connue : l’opposition entre « col blanc » et « col bleu ». À l'origine, le premier renvoie aux emplois intellectuels ou administratifs qualifiés, où créativité et autonomie occupent une place prépondérante. C'est la fameuse chemise blanche portée dans les bureaux. À l’inverse, le col bleu désigne quant à lui les emplois manuels ou industriels ; qui connotent fortement avec la répétition des gestes, la standardisation des tâches, et avec une certaine subordination hiérarchique. C'est le fameux bleu de travail porté en usine.  
Or, le terme de _Digital Factory_ soulève un paradoxe : le travail des développeurs est à la fois créatif et technique, mais il peut être aussi structuré, répétitif et encadré, rappelant des aspects du travail ouvrier.  
Dès lors, une question survient : la _Digital Factory_ constitue-t-elle une organisation créative et autonome, à l'image des cols blancs, ou bien reproduit-elle les logiques de l'industrie, et le travail routinier propre aux cols bleus ?

# Accéder à l'alternance : un parcours singulier

Il y a une caractéristique propre au BUT MMI[^butmmi], et aux BUT de manière générale : c'est le caractère professionnalisant de la formation. Pour atteindre cet objectif, on propose aux étudiants de s'immiscer dans des applications très concrètes pour se familiariser à leur futur métier. Matériellement, c'est ce que l'on appelle des projets, ou Situation d'Apprentissage et d'Évaluation. Ces projets sont organisés tout au long de l'année, et servent à mettre en pratique la théorie, et même à aller au-delà.

## Prométhée, Swagger… et Alexis [Charpentier]{.smallcaps}

C'est ainsi qu'au cours de ma deuxième année de BUT MMI que j'ai pu travailler avec mon équipe sur la réalisation d'un musée virtuel et d'une plateforme de réservation, du nom de Prométhée. Prométhée est une agence fictive qui souhaite promouvoir le travail de femmes artistes. Au-delà de montrer leur travail, c'est aussi toute une immersion dans l'univers de ces femmes, donnant ainsi un contexte important à leurs œuvres.  
Au sein de l'équipe, j'ai notamment été responsable de la mise en place du site web, ainsi que du système de réservation sous-jacent. C'était un projet ambitieux, peut-être trop, mais qui avait pour aspiration à mettre en place des éléments techniques rigoureux, qui auraient pu naître dans un contexte professionnel. Nous voulions que la boutique puisse théoriquement ouvrir ses portes, preuve de choix techniques robustes.  
Je ne saurais dire si ces objectifs ont été pleinement atteints, mais ils constituaient dans tous les cas notre fil d'Ariane. C'est comme ça que des technologies comme Symfony sont apparues sur notre projet. Attention cependant, une contrainte nous avait été donnée : exposer une API[^api] pour décorréler la partie front-end, à savoir l'interface s'exécutant dans le navigateur d'un visiteur, et le back-end, la partie où tous les traitements logiques des données ont lieu. Là encore, un choix technique a été fait, celui d'adopter des standards du web, avec OpenAPI et de la documentation avec Swagger. 

Le jour de la présentation, j'ai à cœur avec mon équipe de présenter le fruit de notre travail, mais aussi d'expliquer toutes les étapes de réflexion, justifiant ainsi de nos choix techniques.  
Ce jour-là, parmi les personnes dans la salle, se trouve Alexis [Charpentier]{.smallcaps}. Comme j'aime le présenter, Alexis, est à l'origine… mon professeur. Alexis s'est attelé à nous enseigner les bases de React, la technologie front-end la plus répandue dans le monde. React est une bibliothèque JavaScript permettant d'adopter une conception par blocs réutilisables, ou composants, dans les interfaces web ; et de rendre ces blocs réactifs avec leur environnement. Mais outre cette simple technologie, Alexis a eu également à cœur de nous transmettre une philosophie du développement web : une vision de laquelle s'accompagne des bonnes pratiques, un cadre et des pistes de réflexion.  
Si l'on en revient à la présentation, celle-ci se déroule avec succès, et aboutit à des questions posées par le jury. Nous avons même le droit à quelques remarques et gentillesses concernant la réalisation de notre projet. Alexis, même sans être membre du jury, nous adressa quelques compliments, soulignant les pratiques professionnelles ayant été adoptées sur ce projet. Ces remarques font écho auprès de notre groupe, et c'est non sans une petite once de fierté que nous quittons alors la salle.  
C'est à peine après avoir eu le temps de souffler avec l'équipe, et de célébrer comme il se doit la fin de notre projet, qu'Alexis vient me voir. Je tombe des nues. Voilà qu'Alexis me propose un poste en alternance au sein de l'entreprise dans laquelle il travaille. Je fais alors preuve d'une longue hésitation, le temps d'une respiration, pour finalement accepter la généreuse proposition. En effet, le MMI de Champs-sur-Marne ayant pris le parti de l'alternance au cours de la troisième année, il me fallait alors trouver une alternance, et voilà que c'est Alexis qui me la propose. Me voilà donc candidat à Publicis Sapient en qualité de développeur web front-end.

[^butmmi]: Bachelor Universitaire de Technologie - Métiers du Multimédia et de l'Internet.
[^api]: Application Programming Interface, un pont permettant à deux systèmes informatiques d’interagir entre eux.

## L'embauche dans le secteur de la tech : un processus complexe

S'il y a quelques vérités admises sur l'embauche dans le secteur de la tech, elles relèvent avant tout d’un processus long, aux étapes multiples. Malgré le fait qu’une personne m’ait déjà ouvert les portes de l’entreprise, j’ai tout de même dû me soumettre aux exigences portées par le processus d’embauche de l'entreprise.  
Quelques semaines se sont écoulées depuis ma soutenance de fin d'année. Alexis est revenu vers moi, afin de me proposer un entretien sur Discord. Il m'y explique quelles pourront être mes missions, quels pourront être les projets sur lesquels je pourrais travailler. Pour des raisons évidentes d'impartialité, la suite du processus ne se déroulera pas avec Alexis.

C'est Iago [Ducardonnet]{.smallcaps}, mon futur recruteur, qui initiera officiellement mon embauche, par le biais d'un appel téléphonique. L'appel, très succinct, permet à mon recruteur et moi-même de nous présenter. C'est une première étape permettant de planifier un second temps : à nouveau un entretien téléphonique, mais plus long.

Ce second appel n'est pas des moindres :  il est déjà jalonné de questions techniques. C'est avec une voix un peu tremblotante que je tente de répondre aux questions, et que j'essaye également de mettre en exergue ma passion sincère pour le domaine du web.  
Une question a retenu mon attention : « qu'est-ce qu'un hook React ? ». Pris au dépourvu, j'ai joué la carte de l'honnêteté : je ne sais pas. J'ai bien sûr donné quelques exemples des hooks les plus connus : `useEffect`, `useState` ; mais sans savoir précisément comment les expliquer. J'ai beaucoup aimé cette question et les mécanismes qu'elle sous-tend : la capacité d'expliquer. C'est une maxime connue : « ce que l’on conçoit bien s’énonce clairement », en outre, ma capacité à vulgariser démontre une certaine maîtrise du sujet abordé. Pourtant, je n'ai pas réussi à répondre à cette question qui semblait si simple. Les hooks sont en quelque sorte une interface permettant d'accéder à toute la logique réactive d'un composant exposée par React. Ces hooks nous permettent de « brancher » un composant, de le relier à la logique interne de la librairie.  
En dépit de ce léger incident, l'appel a continué son cours, mêlant questions techniques, d'apparence simples, et questions plus générales sur mon parcours.  
Cet exercice oral a démontré une chose : il est particulièrement difficile. Non tant sur la technique, que sur l'exercice humain. Il est difficile de faire transparaître un sourire à travers le téléphone, il est difficile de savoir si la réponse donnée semble satisfaisante. Bref, un exercice dans lequel je n'étais pas très à l'aise, mais fort heureusement, j'apprenais la semaine suivante, la poursuite de mon recrutement avec un entretien en présentiel. 

Me voilà à la troisième étape de mon parcours : l'entretien face au recruteur… ou du moins c'est ce que je pensais. À l'aube de cet entretien, j'avais préparé toutes sortes de projets avec lesquels j'allais pouvoir illustrer mon propos. L'idée était simple, je ne suis même pas encore junior, mes compétences techniques sont donc par extension limitées. Limitées, certes, mais pas dans le temps. C'est le message que je tenais à souligner pour cet entretien. Mon intérêt pour le code remonte à bien plus longtemps que les cours. C'est une réelle curiosité que j'ai acquise et qui me permet d'apprendre, apprendre constamment, apprendre avec rigueur.  
Le jour de l'entretien, je me présente avec quelques 45 minutes d'avance. C'est beaucoup, mais avec les près de 1h45 de transports en commun, je me devais de prévoir de la marge. Cette avance n'a pas joué en ma faveur, c'est pile le temps qu'il faut pour accroître son stress. Il se trouve que, même si les minutes paraissent des heures, l'heure finit quand bien même par arriver. Me voilà donc avec cinq minutes d'avance, devant les portes de Publicis Sapient, avenue de Gambetta, dans le XX^e^ arrondissement de Paris.  
Je fais la rencontre de Saïd [Boufous]{.smallcaps} et Florian [Fanor]{.smallcaps}, tous deux développeurs front-end à Publicis Sapient, Iago ne sera finalement pas là. Cette rencontre peut paraître anodine, mais elle n'en demeure pas moins intimidante : je me retrouve alors seul face à deux personnes que je ne connais pas, dans un environnement que je ne maîtrise pas. De plus, je suis quelque peu introverti. J'ai du mal à lancer ou relancer des conversations, l'exercice devient d'autant plus complexe. Un entretien est avant tout un ressenti entre humains : la relation est-elle fluide ? Tout l'enjeu pour moi est alors à cet instant précis de m'ouvrir aux autres.  
Cependant, ma passion vient me sauver. J'ai pu au cours des années roder un _pitch_ sur mon parcours dans le domaine du web. À mon avantage, je dénote une certaine aisance à parler des sujets qui me tiennent à cœur, ce qui rend l'échange davantage concernant pour Florian et Saïd. Mon _pitch_ est simple, plutôt que de raconter quelles sont mes prétendues compétences, j'aime raconter comment, et à quel âge je suis arrivé dans le développement web. C'est une passion née d'abord de la radio, oui, cette radio FM qu'on écoute sur le poste dans la voiture, sur le transistor dans la cuisine. Plus jeune, je voulais recréer ma propre radio. C'était bien ambitieux de ma part, car irréalisable dans l'état : un émetteur FM coûte bien trop cher. Cela étant… j 'ai la chance d'avoir été contemporain de l'époque de la montée en puissance des radios internet, ou webradios. C'est l'époque notamment de Radionomy, et du lecteur Winamp. Alors, je m'étais lancé dans la création d'une webradio, expliquant notamment mes premières expériences avec le web, les serveurs, le réseau, et bien plus encore. C'est la découverte d'une passion dévorante pour tout ce qui se rapporte de près ou de loin au web. Pour couronner le tout, j'illustre mon parcours par des réalisations passées, académiques, personnelles, et notamment une que j'aime présenter : un site web de réservation pour une cliente. Il est la parfaite illustration d'un projet concret, impliquant système de réservation et de paiement. On peut réserver un appartement en quelques clics. Par-delà l'idée de montrer simplement le site web, j'explique toute la réflexion sous-jacente ayant guidé les choix techniques. Parmi cette liste non exhaustive, on retrouve : blocs visuels volontairement scindés par la ligne de flottaison pour suggérer un scroll dans la page, intégration d'un calendrier interactif, tout en gardant les inputs natifs, afin d'améliorer l'accessibilité de la page, et tant d'autres.  
Finalement, cette épreuve se sera surprenamment bien déroulée. Par chance, Saïd et Florian étaient très à l'écoute et engageaient volontiers la discussion. J'ai pu poser des questions, répondre à des questions, et même visiter tout l'étage du bâtiment dédié à Publicis Sapient. On peut relever qu'il y avait très peu de monde ce jour-ci, en effet, le télétravail était de mise ce vendredi.

Après deux appels téléphoniques et un entretien sur site : nous voilà donc à la fin du processus ? pas vraiment. Il existe en effet une ultime étape : l'entretien en visioconférence avec un directeur technique de haut rang. Pour cette quatrième étape donc, j'ai rendez-vous avec Geoffroy [Vergne]{.smallcaps}, _[Director Engineering Technology](https://www.linkedin.com/company/10801655/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BUgCbiNpzSmSAo2j9GmbxmA%3D%3D)_ à Publicis Sapient France. Là aussi, quelques questions techniques, auxquelles je m'étais préparé. En revanche, il y avait des questions auxquelles je ne m'attendais pas du tout, notamment celle-ci : « si votre carrière devait évoluer au sein de notre entreprise, vers quel type de poste aimeriez-vous progresser ? ». Cette question est difficile, car non seulement elle fait appel à des projections : il faut montrer de l'ambition sans pour autant paraître immodeste, tout en montrant la compatibilité du poste avec l'entreprise donnée. À nouveau, j'ai joué la carte de la transparence : je souhaite évoluer vers un poste qui demande moins de pratique du code, là où vont se dessiner tous les rouages du système ; dans le domaine de l'architecture.  
Et c'est sur cette conversation que finalement nous concluons cet entretien, marquant ainsi la fin d'un long parcours d'embauche.

En somme, ce fut une première à mon égard : suivre un processus d'embauche complexe dans le domaine de la tech. Et encore, en tant qu'alternant, Publicis Sapient a délibérément choisi de ne pas mener de test technique. Cela montre un certain recul de l'entreprise quant au fait que je suis un cursus universitaire, et que je suis en plein apprentissage : la technique passe au second plan. Malgré cela, ce processus n'en demeure pas moins long. Déjà, par le nombre absolu d 'étapes, mais aussi le délai qui s'écoule entre ces étapes, de quelques jours à plusieurs semaines.  
C'est une pratique où la constance est de mise : montrer une motivation sans faille du début à la fin. Fin qui pour moi a été couronnée de succès, presque comme une victoire ! Volonté des entreprises de la tech, ou bien simple fait d'un processus qui se veut exigeant, mais ressort de ce processus un sentiment de fierté. C'est comme arriver le premier lors d'une épreuve d'endurance. Et ce sentiment est loin d'être anodin, même s'il est involontaire, il participe à donner une impression de mérite du poste. Il confère également une forme d'aura à l'entreprise, presque de prestige d'appartenance.  
Rétrospectivement, on peut se questionner sur la légitimité de ce sentiment, ou du moins, sur l'ambivalence portée par celui-ci. C'est un sentiment de fierté, d’accomplissement réel pour le candidat. Mais peut-être aussi qu'il s'agit-là d'une instrumentalisation, faisant naître loyauté, et sentiment d'appartenance. Alors, ce qui pouvait apparaître comme un processus d'embauche exigeant, montre peut-être les contours d'un presque rite d'initiation. 

Cet élément, isolé de son contexte, peut paraître futile, anecdotique. Pourtant, remis dans son ensemble, il dresse un portrait des valeurs portées par l'entreprise, ce qu'on peut aussi appeler la culture d'entreprise. 

> « Organizational culture influences how people interact, how decisions are made (or avoided), the context within which cultural artifacts are created, employee attachment, the organization's competitive advantage, and the internal alignment of its units. »
> @OrganizationalCulture2025 []

Et c'est justement dans cette culture que s'inscrit le travail du développeur. Ainsi, pour comprendre la place du développeur dans l'entreprise, et donc au sein de la _Digital Factory_, il faut d'abord mettre en contexte cette culture d'entreprise : regarder comment l'entreprise décide, organise, et valorise ses collaborateurs.

# Consultant dans un groupe publicitaire au service d’un distributeur électrique

Si vous n'avez pas compris le titre, rassurez-vous, c'est tout à fait normal. Mon alternance m'a amené à travailler pour trois entreprises distinctes. D'abord, Publicis Groupe, c'est tout simplement la maison-mère de Publicis Sapient. Publicis Sapient, ou PS, est quant à elle une entreprise de conseil, ou plus précisément de _consulting_. Ses employés, eux, sont envoyés en mission chez des clients, parmi lesquels figure Sonepar, un distributeur électrique. Ainsi, pour comprendre la culture d'entreprise appliquée au sein de la _Digital Factory_, il faut d'abord comprendre ce qu'elle est dans ces différentes entités.

## Publicis Groupe

### « Si vous attendez que les choses changent, elles changeront sans vous » : l'histoire de Publicis

L'histoire de Publicis est sans conteste un pilier fondateur du groupe. En effet, l'entreprise adopte un narratif au cœur des valeurs de l'entreprise. La figure de ce narratif est Marcel [Bleustein-Blanchet]{.smallcaps}, père fondateur de Publicis, et inventeur de la publicité selon ce récit. C'est lui qui aurait inventé la publicité en France dans les années 1920. Ainsi, en 1926, il fonde la société Publicis, « Publi » étant la publicité, « cis » étant son chiffre porte-bonheur.  
L'entreprise connaît une croissance remarquable, jusqu'en 1940, où son activité sera mise en pause le temps de la guerre. Cela n'empêchera pas l'homme qui a inventé la publicité de rouvrir quelques années après, redonnant un souffle de prospérité pour la marque.  
En 1975 opère un changement important pour Publicis : Maurice [Lévy]{.smallcaps} est nommé directeur général. L'entreprise ayant constitué un capital monétaire important va alors adopter une stratégie de rachat d'autres agences de publicité.  L'entreprise, alors devenue groupe, va entreprendre de nombreuses acquisitions qui n'auront de cesse d'étendre l'entreprise. Elle passera même outre atlantique, rachetant le réseau d'agences de publicité chicagois dénommé Leo Burnett.  
Il faut comprendre aujourd'hui que ce qui fait la renommée de l'entreprise, et ce qui constitue le mastodonte mondial qu'est Publicis, c'est ce mécanisme d'acquisition perpétuel encore de mise aujourd'hui. L'actuel président du groupe, Arthur [Sadoun]{.smallcaps} confirme lui-même cette dynamique dans cette interview accordée à AXA @CornerOffice [] : « The important is to be the only one […] making sure that what we build is unique ». C'est dans cette vision d'être l'unique acteur de marché, que Publicis continue ces acquisitions.
Dans les années 1990, Maurice [Lévy]{.smallcaps} entreprend un virage numérique important pour la marque : selon lui, c'est un domaine porteur dans lequel il est nécessaire d'investir. 

### Aller au-delà de la publicité

À ce jour, le groupe Publicis continue d’œuvrer dans le secteur de la publicité, et plus largement de la communication. Le groupe revendique d’ailleurs être le premier mondial. À l'origine de cette ascension, c'est l'exportation notamment aux États-Unis. C'est sur le nouveau continent que Publicis générera la plus grande part de son chiffre d'affaires, et les exemples ne manquent pas.  
La célèbre campagne « _I'm Lovin' It_ » du fast food américain McDonald's, ou encore _The Force_ de Volkswagen en 2011, mettant en scène un enfant déguisé en Dark Vador démontrent la force d'ancrage de Publicis. Coca-Cola, Disney, Armani, Lancôme et même Pfizer, tous ces géants de l'industrie ont fait appel à Publicis pour gérer leur communication. Selon Publicis, en France, au cours de sa vie, un téléspectateur voit en moyenne une publicité sur trois à la télévision qui est réalisée par une entité du groupe.
Cette omniprésence traduit une influence considérable sur les habitudes de consommation et sur la culture populaire, là où la publicité devient vecteur de récits, d'émotions ; mais aussi de controverse.

La publicité est parfois mal vue. Certaines campagnes soulèvent même des polémiques qui dépassent la simple esthétique de clip. La publicité contribue à façonner nos comportements, nos désirs, et parfois même notre personnalité. Cet article _Manipulation: An integrative framework of unethical influence in marketing_ @arango-kureManipulationIntegrativeFramework2025 [] paru dans la revue _Journal of Business Research_ décrit un phénomène de manipulation. Conditionner le choix du consommateur, sans consentement libre et éclairé, tout en profitant vulnérabilité cognitives :

> « Using this knowledge to influence people’s decision-making can be characterized as manipulation through the exploitation o cognitive vulnerabilities. »

Doit-on alors dépeindre une entreprise malveillante ? Ce portrait à charge est tout de même à mettre en perspective, et il est nécessaire de mentionner toutes les initiatives du groupe pour l'environnement, pour les conditions de travail, et même pour le temps passé sur les écrans !
Cependant, cette charte de l'éthique trouve ses paradoxes : Publicis a aussi effectué sa transition numérique, plus discrètement, vers le marketing d'influence. Tibo Inshape, Squeezie, parmi les youtubeurs cumulant le plus d'abonnés en France, ont signé divers contrats avec la marque du Lion. Cette stratégie tend à viser une cible qui ne consomme plus les médias traditionnels, et sont davantage tournés sur les réseaux sociaux.  
Ce virage numérique est savamment étudié, mesuré, pondéré : chaque commentaire laissé sur une vidéo de ces youtubeurs est analysé, caractérisé, stocké dans une immense base de données. C'est le nouvel or d'Internet, et Publicis compte bien s'en délecter, avec rien moins que le rachat le plus ambitieux du groupe : l'acquisition de l'entreprise Epsilon pour 4,4 milliards de dollars.

En bref, Publicis officie au travers d'agences nombreuses que l'on peut regrouper sous deux catégories : la communication et le numérique. Au cœur de tout cela, un projet _data driven_, au nom sans équivoque : _CoreAI_. L'ensemble est fédéré en quatre hubs distincts :

- Publicis Communications : les agences créatives et de communication, telles que Leo Burnett ou Saatchi & Saatchi ;
- Publicis Media : la stratégie et l’achat média, avec des réseaux comme Médiavision ;
- Publicis Health : la communication dans le secteur de la santé ;
- Publicis Sapient : la transformation numérique et technologique.

Enfin, pour dresser un portrait complet de Publicis, il est nécessaire d'aborder les dernières mouvances stratégiques du groupe, dont la philosophie _Power of One_ fait partie intégrante. Ce principe vise à créer une expertise transversale inter-agences, fédérer pour un même compte les divers savoirs du groupe. Ce concept a même une portée matérielle : le déménagement des agences Publicis parisiennes en un même lieu : le 145 rue de Courcelles dans le XVII^e^ arrondissement de Paris. L'objectif est clair : rapprocher les agences.

## Publicis Sapient

Dans sa quête du marché numérique dans les années 2010, le groupe Publicis réalise un achat stratégique alors sans précédent : l'acquisition de l'entreprise américaine Sapient en octobre 2014, pour la modique somme de 3,7 milliards de dollars.

<!-- TODO: revoir NIGEL VAZ + LISE MALBERNARD -->
### Un ancêtre au nom de « Sapient »

Pour comprendre l'origine de Publicis Sapient, il faut remonter à la fondation de Sapient aux États-Unis, en 1990. Jerry [Greenberg]{.smallcaps} et J. Stuart [Moore]{.smallcaps} entreprennent la fondation d'une entreprise de conseil, ou _consulting_ dans le numérique.

Contrairement à ce que ce nom suggère, une entreprise de conseil ne fait pas que… conseiller. Elle accompagne les organisations dans leurs choix stratégiques mais fournit aussi les moyens concrets de mettre en œuvre ses recommandations. Autrement dit, le livrable ne s’arrête pas à un rapport ou à une présentation : il s’accompagne de ressources humaines, techniques et organisationnelles permettant de traduire les orientations en actions réelles. Chez Publicis Sapient, ce sont parfois les mêmes consultants qui, après avoir conçu la stratégie, participent directement à son exécution aux côtés des équipes clientes.

C’est précisément ce qui fonde la spécificité de Publicis Sapient : son approche du **DBT, _Digital Business Transformation_**. Ce concept désigne un accompagnement global et intégré, allant de la vision stratégique jusqu’à la réalisation opérationnelle, avec un accent marqué sur le numérique. Les programmes de DBT s’appuient sur des équipes pluridisciplinaires – mêlant stratégie, design, ingénierie logicielle et exploitation de la donnée – organisées en **plateaux projets** ou en **feature teams**. Ces interventions s’inscrivent souvent dans la durée (18 mois à plusieurs années) et mobilisent des budgets conséquents, à la hauteur des transformations structurelles opérées.

### À toute allure : le modèle SPEED

Pour répondre à cette ambition, l’organisation interne de Publicis Sapient repose sur les **capabilities** (ou _capas_), regroupées sous le modèle méthodologique **SPEED** :

* **Strategy** : définir la vision business, identifier les leviers de valeur et aligner la stratégie avec la mission de l’entreprise.

* **Product** : concevoir et piloter des produits numériques selon des méthodes agiles (Agile, Lean, DevOps), avec un objectif de valeur et de rapidité.

* **Experience** : créer des expériences utilisateurs engageantes et personnalisées, en mobilisant le design et la recherche centrée sur l’humain.

* **Engineering** : développer des solutions technologiques robustes, évolutives et innovantes, capables de soutenir les transformations à grande échelle.

* **Data & AI** : exploiter la donnée et l’intelligence artificielle pour générer des insights, automatiser des processus et renforcer la prise de décision.

Ces _capas_ structurent les talents de l’entreprise : chacun des collaborateurs est rattaché à une capability, mais les projets mobilisent généralement plusieurs d’entre elles en parallèle. Ainsi, une feature team peut réunir des experts de la donnée, des ingénieurs logiciels, des designers et des consultants en stratégie, travaillant de concert au service du client.

Publicis Sapient se définit ainsi comme le **bras technologique du groupe Publicis**, capable non seulement de conseiller ses clients sur leur transformation numérique, mais aussi de concevoir, développer et déployer les solutions concrètes qui la rendent possible.

Cette approche ambitieuse, fondée sur la complémentarité des _capas_ et sur une exécution intégrée de bout en bout, présente toutefois un revers : son coût particulièrement élevé. Publicis Sapient est reconnu pour sa rapidité d’exécution, sa capacité à atteindre les objectifs fixés, et sa volonté assumée d’être « disruptif » dans les marchés traditionnels. Mais cette efficacité a un prix : les prestations de DBT s’avèrent globalement plus onéreuses que celles proposées par d’autres cabinets de conseil ou agences numériques.

Si certains clients acceptent ce surcoût en échange d’une transformation menée tambour battant, d’autres commencent à en percevoir les limites. C’est notamment le cas de Sonepar, acteur mondial de la distribution de matériel électrique, qui a choisi d’externaliser certaines activités après avoir collaboré avec Publicis Sapient. Ce type de décision illustre un risque pour le modèle : à trop miser sur la vitesse et l’exhaustivité de l’accompagnement, le groupe s’expose à une perception de dépendance coûteuse, susceptible de pousser certains clients à arbitrer entre la qualité du service et la soutenabilité financière.

<!-- TODO: revoir -->
### DBT : le modèle pour éviter un nouveau Kodak

Publicis Sapient évolue sur le marché très concurrentiel du conseil en transformation numérique, où les projets impliquent à la fois stratégie, conception, développement et déploiement opérationnel. Son positionnement repose sur l’approche intégrée du **Digital Business Transformation (DBT)**, qui combine conseil stratégique et exécution opérationnelle. Cette approche, reconnue pour sa rapidité et sa capacité à atteindre les objectifs ambitieux des clients, se distingue toutefois par un coût plus élevé que la moyenne du marché.

Parmi ses principaux concurrents figurent Accenture et Capgemini. Accenture est un leader mondial du conseil et des services technologiques, intervenant sur l’ensemble de la chaîne de transformation des entreprises, de la stratégie à l’intégration de systèmes et aux services gérés. L’entreprise est connue pour sa capacité à mobiliser des ressources globales sur des projets complexes et de grande envergure, offrant un positionnement similaire à Publicis Sapient en termes d’exécution intégrée, mais avec une couverture sectorielle et géographique plus étendue. Capgemini, de son côté, se distingue par son approche modulaire et adaptable, combinant conseil, design et technologie pour proposer des solutions sur mesure. Sa perception sur le marché met en avant une certaine flexibilité et compétitivité tarifaire, tout en restant capable de mener des projets de grande envergure.

Ces acteurs illustrent les standards du marché du conseil numérique : des prestations complètes mêlant stratégie, innovation digitale et mise en œuvre opérationnelle. Publicis Sapient se différencie par son ambition « disruptive » et sa rapidité d’exécution, ce qui attire des clients prêts à investir pour des transformations audacieuses, mais limite parfois son accessibilité pour des entreprises sensibles aux coûts.

<!-- TODO: absolument à revoir PHILIPPE DELPECH -->
## Sonepar

Sonepar, client majeur de Publicis Sapient, est un acteur incontournable de la distribution de matériel électrique à l’échelle mondiale. Contrairement à Publicis Sapient, dont l’activité est centrée sur le conseil et la transformation numérique, Sonepar opère sur un marché industriel et commercial concret : celui de la fourniture de produits électriques aux professionnels et aux entreprises. La collaboration entre les deux entités illustre parfaitement le lien entre un cabinet de conseil technologique et un client ayant besoin d’optimiser ses processus, sa logistique et son expérience digitale. Cette relation permet de comprendre comment les solutions stratégiques de Publicis Sapient sont appliquées dans un contexte opérationnel et sectoriel réel.

### Une entreprise familiale française devenue monde

Fondée en 1969 par la famille Lamirand en France, Sonepar a rapidement étendu ses activités au-delà de l’Hexagone. Dans les années 1980 et 1990, le groupe a amorcé une stratégie d’internationalisation, notamment en Europe, avant de viser plus intensivement le marché nord-américain au cours des deux dernières décennies. Aujourd’hui, les États-Unis représentent un marché central pour le groupe, à l’image de la stratégie de Publicis sur ce continent : il s’agit d’un territoire où la croissance externe et l’implantation locale sont décisives pour asseoir son leadership. L’histoire de Sonepar se caractérise par une succession de rachats d’OpCos dans différents pays, permettant de consolider sa position tout en intégrant progressivement des structures locales dans un réseau global cohérent. Cette stratégie reflète un modèle de croissance par acquisition, similaire à celui de Publicis, où le développement organique se combine à des mouvements ciblés de consolidation.

### Leader mondial de la distribution B2B de matériel électrique

Le cœur de métier de Sonepar est la distribution de matériel électrique et électronique pour les professionnels : équipements de câblage, systèmes d’installation, solutions domotiques et dispositifs de sécurité. Le groupe propose également des services numériques et logistiques, tels que des plateformes e-commerce, des outils de gestion des commandes et des solutions de suivi des stocks, afin d’accompagner ses clients dans la digitalisation de leurs achats et opérations. Cette combinaison de distribution traditionnelle et de services numériques fait de Sonepar un acteur hybride, capable de répondre aux exigences de rapidité et de traçabilité du marché.

La société se distingue par son rythme soutenu d’acquisitions, avec plusieurs entreprises intégrées chaque année dans divers pays. Cette dynamique lui permet de renforcer son maillage territorial et ses compétences sectorielles, mais elle soulève aussi des défis : l’intégration des filiales, l’harmonisation des pratiques et la standardisation des systèmes d’information peuvent générer des frictions, des coûts de transition et des risques opérationnels. De plus, bien que le groupe affiche une forte présence sur le marché américain, cette expansion rapide peut parfois créer une dépendance vis-à-vis des marchés étrangers, avec un impact direct sur la stratégie globale et la résilience financière du groupe.

### Un groupe aux identités plurielles

L’organisation interne de Sonepar repose sur un modèle fédéral, où chaque filiale (_OpCo_) conserve une autonomie relative dans la gestion quotidienne tout en respectant les standards stratégiques et opérationnels du groupe. Cette structure permet de combiner flexibilité locale et efficacité globale, en harmonisant la finance, le numérique et la logistique, tout en conservant une proximité avec le client. Les OpCos sont regroupées sous des directions régionales, chacune supervisant la performance et la mise en œuvre des bonnes pratiques.

Au sein du groupe, des fonctions centrales pilotent les programmes transversaux : la transformation digitale, les systèmes d’information, la supply chain et le développement durable. Cette centralisation vise à standardiser certaines opérations et à maximiser les synergies entre les filiales, mais elle peut parfois entrer en tension avec l’autonomie locale et la réactivité opérationnelle. Enfin, la politique de croissance par acquisition implique une intégration continue de nouvelles structures, ce qui nécessite un équilibre constant entre consolidation des compétences et adaptation aux spécificités locales. Cette approche révèle à la fois la force et les limites du modèle Sonepar : efficace pour créer un réseau mondial dense et compétitif, mais exigeante en termes de coordination, de gouvernance et de coûts.

## Des collaborateurs aux identités multiples

Le statut de consultant confère une double identité, surtout quand le consultant participe à l'élaboration du livrable. Cette identité est d'autant plus complexe quand la maison-mère de l'entreprise de conseil développe elle aussi une identité forte.  
Dans cette identité de dimension trois, on a d'abord Publicis Groupe. Le groupe tend à créer un sentiment d'appartenance, d'unité. J'en ai moi-même fait l'expérience au cours de mon alternance : entre évènement organisé à l'Adidas Arena pour fédérer l'ensemble des agences, ou encore un sweat-shirt unique distribué à tous les collaborateurs de Publicis. On fait partie de cette grande famille qu'est Publicis.  
Mais le groupe Publicis ne pourrait exister sans ses composantes, dont fait partie Publicis Sapient. Là encore, une culture d'entreprise se distingue : je suis un Sapient. Cette identité fédère quant à elle sur les valeurs du consulting, et du numérique. On ne se sent pas communicants, mais acteurs du numérique. Là aussi, nous portons des marqueurs identitaires clairs : vocabulaire interne, méthodologie SPEED, organisation en capabilities, ou encore un discours permanent sur la « disruption » et le DBT. Ces éléments renforcent l'idée d'appartenir à une communauté de pratiques singulière, tournée vers l’innovation numérique et la transformation.
Enfin, nous travaillons chez le client, et même si je n’en ai fait l’expérience qu’une seule année, certains collaborateurs Sapient y restent plusieurs années, accentuant le flou de leur identité professionnelle. Dans ce cadre, on partage des locaux, des projets, et même parfois une partie de la culture du client. On peut finir par se sentir intégré à l’entreprise pour laquelle on est en mission, sans pourtant en être réellement salarié. Cette proximité crée une identité hybride, qui peut être constructive, en ayant une compréhension du client, renforçant un sentiment d'appartenance au projet ; tout en étant une source de confusion. Être à la fois un Publicis, un Sapient et « presque » un Sonepar, c’est jongler avec des repères multiples, créant ainsi un rapport à l'entreprise complexe.

# Premières semaines de travail et considérations éthiques

## _Onboarding_ chez Publicis Sapient

Issu de la culture américaine, _l'onboarding_ est une phase d'intégration pour un nouveau collaborateur au sein d'une entreprise. Plus qu'une simple intégration, c'est un planning savamment orchestré pour amorcer la prise de poste, inculquer les valeurs de l'entreprise et familiariser le collaborateur à son futur environnement de travail.

Pour ma part, ce fut une réelle découverte. Ayant vécu des premiers jours d'intégration somme toute relatifs au cours de mes dernières expériences en entreprise, je découvrais alors tout un univers en faisant mon entrée chez Publicis Sapient.  
Cette semaine _d'onboarding_ a été marquante pour moi. Je me souviens avoir accumulé une telle pression, si intense, qu’elle a fini par éclater en larmes. Mais comment ai-je pu en arriver à là ?

Remontons un peu le temps pour arriver au 9 septembre 2024. À cette date, je découvrais alors le parcours en transports en commun pour la première fois aux heures de pointe. C'est un trajet vacillant entre 1h45 et 2h porte à porte, en fonction de l'encombrement des transports. J'avais bien sûr pris en compte ce temps de trajet, mais le vivre, était bien différent.  
Une fois arrivé, je découvre pleins de nouveaux arrivants, ce qui me rassure dans un premier temps, mais je me rends compte que je suis le plus jeune d'entre tous. C'est anecdotique, mais c'est une source d'anxiété pour moi : suis-je à ma place ? Ai-je les compétences, suis-je bien sûr de comprendre tout ce qui est dit ?

À peine ai-je eu le temps d’assimiler toutes ces choses qu'était venue l'heure du repas, et de ma première rencontre avec mon équipe. Je retrouve alors Alexis, et fait la rencontre de Carla, Mélanie et Julien. Mais une autre personne était également présente ce jour-là : Holger. Si ce nom ne vous semble pas très français de prime abord, c'est normal, car Holger n'est tout bonnement pas français, mais allemand. À peine avais-je eu le temps d'assimiler mon arrivée dans l'entreprise que je devais déjà mettre en pratique mon anglais, lui aussi relatif. L'anglais était pour moi source de défi, mais je ne savais pas qu'il allait se matérialiser aussi vite.  
Comprenez-là que l'exercice était de taille. D'abord, il fallait surmonter ma timidité, car l'entreprise est avant tout une expérience humaine, des humains qui se coordonnent dans un objectif commun. Il me fallait donc m'ouvrir aux autres. De plus, il fallait surmonter la barrière de la langue. Imaginez-moi alors, balbutiant, pour essayer de comprendre ce que me disait Holger. J'avais peur de la première impression que j'allais laisser.

Au fil de la semaine, nous avons assisté à diverses présentations des différentes _capabilities_ de Sapient. Une chose a particulièrement retenu mon attention : les sommes astronomiques avancées. Cela peut paraître illusoire, mais je n'avais jamais été exposé à de pareilles sommes dans un contexte professionnel. Ces montants donnent un sens tangible au projet, tout en étant difficilement concevables à une échelle individuelle. Ceux-ci démontrent à la fois l’étendue des enjeux et la responsabilité que cela implique.

Également, nous avons eu la possibilité d'avoir des visioconférences présentées par Katherine [Gardner]{.smallcaps}. La particularité de celles-ci ? Elles étaient données en anglais. En effet, Publicis est une entreprise internationale. Les _newcomers_, qu'ils viennent d'Allemagne, des États-Unis, d'Inde, ou de partout ailleurs où sont implantés des bureaux de Publicis Sapient, assistent ensemble à ces séances _d'onboarding_. Il n'y a pas de distinction entre ces nouveaux arrivants. Plus encore, je me souviens de cette drôle d'interaction que j'avais eu avec Christophe [Éblé]{.smallcaps}, _newcomer_ en _onboarding_, qui se trouve être aujourd’hui le CTO[^cto] de Publicis Sapient France.  
Ce détail qui n'en est finalement pas un m'a marqué. À Publicis Sapient, on entretien une culture d'entreprise de proximité, où les frontières verticales de la hiérarchie sont floues. On a remplacé un « bonjour » par un « hello » qui est universel. On ne vouvoie pas, mais on tutoie. J'ai mis du temps à m'habituer au tutoiement de la présidente de Publicis Sapient France.

[^cto]: Chief Technology Officer, directeur technique

## Intégration dans l'équipe Watts

Arriver dans l’équipe Watts, c’était franchir une nouvelle étape, et pas seulement sur le plan technique. À l’époque, l’équipe se composait de Julien, lead développeur front-end, Mélanie, développeuse front-end, Holger, architecte front-end venu d’Allemagne, Carla, Product Owner et Project Manager, et Betty, en charge du design de marque et d’interface. Chacun portait une expertise, une personnalité, et une histoire différente.

Pour moi, l’enjeu n’était pas seulement d’apprendre un nouveau stack ou de comprendre les rouages d’un projet complexe : il s’agissait avant tout de m’intégrer dans une équipe déjà soudée, de trouver ma place parmi des profils expérimentés. Ce défi était d’autant plus grand que je suis naturellement timide, et que la prise de parole, l’initiative ou même le simple fait de demander de l’aide me demandaient un effort considérable. Pourtant, l’entreprise, c’est avant tout une expérience humaine : on ne travaille pas seul, on avance ensemble, on partage les réussites comme les difficultés.

Dès les premiers jours, Carla a joué un rôle déterminant dans mon intégration. Son accueil chaleureux, sa disponibilité et sa capacité à mettre à l’aise ont été essentiels pour moi. Elle m’a guidé dans la découverte des rituels de l’équipe : les dailies, les refinements, les plannings, autant de moments où il fallait oser prendre la parole, exposer ses avancées ou ses blocages. Grâce à elle, j’ai pu progressivement dépasser ma timidité, comprendre le fonctionnement collectif et m’ouvrir aux autres. L’équipe Watts, par son écoute et sa bienveillance, m’a permis de transformer ce qui était un défi personnel en une véritable opportunité de croissance, humaine autant que professionnelle.

# Rester SAFe pour collaborer

Dans un projet web, que l'on soit seul, ou à plusieurs, il est important de mettre en place une gestion des tâches à effectuer. Cela permet de tenir des délais temporels, permettant également de tenir un budget. Et c'est en ce sens que la gestion de projet apparaît comme indispensable dans un projet web.

## Agile, mais pas flexible

L'agilité permet aux équipes de s’adapter vite, de collaborer et de livrer de la valeur régulièrement. C'est un standard établi dans le domaine numérique favorisant l'échange plus que le suivi d'un plan rigide et immuable. Pourtant, bien que les règles Agile soient reconnues pour leur efficacité, elles peinent cependant à coordonner des équipes nombreuses. Cela est d'autant plus vrai quand le programme, tel que celui de Sonepar, s'agrandit, et dépasse même les frontières. Comment communiquer efficacement quand les équipes se trouvent à l'autre bout du monde ? Comment s'adapter au changement si celui vient de partout ? C'est de cette problématique de _scalabilité_, ou mise à l'échelle, qu'est né le cadre de travail SAFe.

SAFe, pour _Scaled Agile Framework_ complète Agile à l'aide de sprint et de _program increment_ (PI). SAFe est une sorte de cadenceur à double niveau.  
Le premier donne un rythme pour chaque équipe. L’équipe itère selon ses objectifs, planifie, ajuste et livre régulièrement.  
Le second niveau donne un tempo de travail à toutes les équipes, et fixe leurs dépendances. À la fin de ce _program increment_, l 'équipe A fournira le livrable dont l'équipe B avait besoin, et ainsi de suite entre les équipes. Cela permet d'identifier les dépendances interéquipes, et d'établir un programme qui ne sera pas bloquant.  
Ainsi, chaque équipe adopte une vision claire du programme, et de ses objectifs. Elle sait alors quels sont les points de synchronisation, et peut avancer en toute autonomie.

## SAFe au sein de Sonepar

Concrètement, Sonepar a fait le choix d'organiser des _program increments_ de 5 sprints, sprints dont la durée est établie à 2 semaines. Ces cycles prennent vie à travers ce qu'on appelle des rituels. Ces rituels font partie prenante du cadre de travail, et permettent d'organiser et de conclure sprints et _program increments_. À nouveau, c'est une histoire de rythme.

- Les _Dailys_ sont le pouls quotidien. Chaque matin, l’équipe partage ses avancées, ses blocages et ses priorités. C’est un rituel court mais essentiel pour garder l’alignement jour après jour.
- Le Refinement intervient en milieu de sprint. Il permet de clarifier les besoins futurs, détailler les user stories et s’assurer que le backlog reste prêt à l’emploi. Cette anticipation réduit les imprévus.
- Le _Sprint Planning_ ouvre chaque sprint. L’équipe sélectionne les tâches à livrer et fixe ses objectifs, par exemple développer une nouvelle fonctionnalité. Ce moment trace la feuille de route du cycle de deux semaines.
- La _Demo_ vient en clôture de sprint. Les équipes montrent concrètement ce qu’elles ont réalisé, qu’il s’agisse d’un parcours client ou d’un prototype. C’est l’occasion de recueillir des retours immédiats et d’ancrer la valeur produite.
- La Rétrospective suit la démo. L’équipe analyse ce qui a bien fonctionné et ce qui doit être amélioré, par exemple la communication entre sites éloignés. Ce rituel nourrit l’amélioration continue.
- Enfin, le _PI Planning_ donne le tempo global. Toutes les 10 semaines, l’ensemble des équipes se réunit pendant deux jours pour définir la vision de l’incrément, planifier les dépendances et fixer les jalons. C’est la grande boussole collective.

## SAFe est un _framework_ agile ?

Malgré l'efficacité avérée du _framework_ SAFe, on peut tout de même se demander s'il reste fidèle aux principes Agiles. En effet, Agile tendais à l'effacement des processus rigides pour mettre en avant les individus et leurs interactions. Pourtant, SAFe, rien que par son nom, fixe un cadre travail. De facto, cette structuration introduit une forme de hiérarchie et de planification qui peut sembler contradictoire avec la souplesse originelle de l’Agile. Certains y voient une réinterprétation du manifeste Agile destinée à rassurer les grandes organisations, quitte à s’éloigner des valeurs initiales. SAFe est en plus devenu une valeur marchande : Publicis Sapient propose désormais des formations certifiantes à l’agilité SAFe, formations intégrées à leur offre commerciale.  
Cela transforme la méthodologie en un produit. Pratiques aux valeurs financières ou véritable capacité à améliorer la collaboration ? On peut se demander si SAFe sert encore les individus, ou si c'est un outil de standardisation et de contrôle au service des entreprises.

## L’esprit sous cadran et créativité à la chaîne

Malgré le contenu intellectuel et décisionnel que requièrent les rituels SAFe, la structuration rigoureuse des sprints, _program increments_ et autres cérémonies impose un rythme très codifié. Cette régularité crée une forme de routine qui rappelle, par certains aspects, le travail organisé et répétitif associé aux cols bleus, même si les développeurs restent mobilisés sur des tâches de réflexion et de conception typiques des cols blancs. SAFe illustre ainsi une hybridation : il combine la créativité et l’autonomie intellectuelle attendues dans le conseil et le numérique avec des logiques de coordination et de cadence qui s’apparentent à celles des environnements plus industriels. On y retrouve donc un paradoxe : un travail à la fois intellectuel et fortement structuré, oscillant entre liberté et standardisation.

<!-- TODO: HOY -->
# Storybook, Percy et Sample App : pourquoi et pour qui ?

Dans le cadre d’une _Digital Factory_, la qualité du code et de l’expérience utilisateur est au cœur des préoccupations. Pour y parvenir, nous avons mis en place une **stack technique dédiée à la conception, à la documentation et à la validation visuelle des composants**. Cette stack répond à deux besoins principaux : fournir aux équipes un environnement de développement cohérent et permettre aux clients internes de visualiser et tester les composants avant leur intégration. Elle se compose de **React, Web Components, Storybook, Percy et la Sample App**.

<!-- TODO: HOY -->
## React : le socle de nos composants

React est le framework choisi pour la création de composants réactifs et modulaires. Il permet de gérer facilement l’état, de structurer les interfaces et d’assurer une réutilisabilité maximale. Pour les développeurs, React offre un écosystème mature, une communauté active et des outils de debug performants. Pour les designers et chefs de projet, c’est la garantie que les composants livrés respectent le design system et peuvent évoluer sans risque de régressions fonctionnelles.

<!-- TODO: HOY -->
## Web Components : interopérabilité et standardisation

Parallèlement à React, certains composants sont développés en Web Components via Lit. Cette technologie assure **l’indépendance vis-à-vis du framework**, permettant d’intégrer ces composants dans différents projets, même non React. Les Web Components offrent également des standards web robustes, garantissant la compatibilité et la pérennité des composants. Cela répond à un besoin d’interopérabilité et de portabilité pour l’ensemble de l’organisation.

<!-- TODO: HOY -->
## Storybook : documenter et tester les composants

Storybook est l’outil central de documentation et de développement isolé des composants. Chaque composant est présenté dans un environnement dédié, avec ses différentes variantes (_stories_) et ses interactions possibles. Pour les développeurs, Storybook facilite le test, la débogue et le partage des composants. Pour les designers et Product Owners, il fournit un aperçu clair et accessible de l’UI, sans nécessité de lancer l’application complète.

<!-- TODO: HOY -->
## Percy : vérifier l’intégrité visuelle

Percy complète Storybook en offrant une validation visuelle automatisée. Chaque composant ou interface est comparé à une version de référence pour détecter toute régression visuelle. Cela permet de s’assurer que les changements n’altèrent pas le rendu attendu, garantissant la stabilité visuelle du design system et la confiance des équipes métier.

## Sample App : un terrain de démonstration

Comme l'a formulé mon camarade Dan, au cours de ma formation MMI, « tester, c'est douter ». Cette formulation, bien qu'évidemment ironique, est intéressante pour comprendre que le développeur néglige parfois la phase de tests, notamment celle en conditions réelles.  
Après tout, pourquoi devrions-nous créer des tests alors que chaque composant est documenté, illustré, sandboxé au sein du Storybook ? Malgré toutes les qualités de cet outil, il ne pourra jamais rendre compte d'une expérience de développement complète : des lignes de codes pour intégrer le composant, jusque son fonctionnement en contexte, au sein d'une application.

Et c'est ainsi que la Sample App, ou application de démonstration, est née. Celle-ci remplit deux objectifs : tester une intégration par le code pour les développeurs, et montrer le composant dans un contexte donné.  
En premier lieu, elle sert de bac à sable : le développeur peut y intégrer un composant, comme en production,  afin de vérifier qu’il fonctionne correctement avec les dépendances réelles, et détecter les éventuelles incohérences qui seraient invisibles si le composant est isolé. Par exemple, le composant pourrait mal réagir dans un contexte `grid`, ou `flexbox`, à l'intérieur d'un autre composant, etc.  
Un autre point qui peut échapper au développeur : tous les salariés de l'entreprise ne sont pas développeurs. C'est presque anodin, mais tout le monde n'a pas les compétences et le savoir pour comprendre l'utilité de Storybook. Plus encore, Storybook ne permet pas de se projeter et d'imaginer une plateforme de e-commerce à partir de boutons et d'icônes.  
C'est pour ces raisons que la Sample App est née.

Accessible à toutes les personnes du programme, la Sample App est une plateforme de e-commerce fictive créée en Next.js. Son but : montrer à moindre échelle l'ensemble des composants au travers de pages produits, d'une _homepage_, d'un panier de commande et même de la page « mon compte » pour illustrer les composants de formulaire. Cette Sample App permet à Watts de tester ses composants dans une application. Mais également, elle permet aux développeurs externes de comprendre comment les composants ont été implémentés. Enfin, la Sample App permet à toutes les personnes non-initiées au développement de tester les composants, et de se faire une idée de leur rendu une fois en production, grâce à un contexte cohérent.

# Comprendre puis apprendre, imiter et créer

## Comprendre le Design System

Après une longue semaine d'onboarding, je peux enfin me concentrer sur le travail en substance pour lequel j'ai été recruté. Mon équipe cherche alors dans le sprint en cours quel pourrait être le ticket me permettant de me familiariser avec le Design System. Un ticket a été désigné : _Import new icons_.

Ma toute première mission était donc simple : importer de nouvelles icônes au sein du Design System. En effet, le design system comporte toute une librairie d'icône réalisées par les designers. Parmi elles, on compte l'icône « panier d'achat », l'icône « valider », ou bien encore « supprimer ». Toutes ces icônes sont utilisables par le biais d'un composant nommé `<Icon />`.  
Le processus est donc simple : une fois les icônes crées dans le logiciel graphique Figma, il faut les exporter au format SVG, puis les renommer. Ensuite, elles doivent être ajoutées dans le _Repository_ du Design System, et listées. Je me lance donc dans cette première tâche avec l'aide d'Alexis.  
L'exécution se déroule sans trop d'encombre, et me voilà à créer ma première PR, ou _Pull Request_ dans GitHub. C'est l'étape par laquelle on soumet son travail à la révision. L'objectif est d'avoir un maximum de retours qui pourront, le cas échéant, déceler toutes les problématiques que le code soumis pourrait apporter, afin de les corriger. L'idée étant de _challenger_ le code : discuter de sa pertinence, de sa qualité, et des alternatives possibles.  
Ma première PR créée, et déjà des retours : ça ne va pas. Et pour cause : certaines icônes importées doivent comporter des jetons, ou _tokens_, de couleur. Ces jetons permettent à certaines parties de l'icône d'avoir une couleur définie en fonction du contexte de l'utilisation de l'icône. C'est une couleur variable qu'on peut changer après coup.  
Ce drôle d'incident met en évidence toute la complexité du Design System. Il illustre le désir de transposer une philosophie savamment réfléchie du Design System et transposée en code compréhensible par la machine. Le Design System, ce n'est pas juste la création de boutons et de menus déroulants, c'est la réflexion permettant un compromis lié au contexte d'utilisation du composant, à son intégration, et à l'expérience de l'utilisateur.

## Documenter pour autrui, mais surtout pour soi

Après quelques tickets passés à importer des icônes dans le Design System, me voilà fin prêt à passer un nouveau cap. Je vais faire ce que tout nouvel arrivant réalise dans son équipe : de la documentation. Si je dois être transparent, j'ai d'abord pensé que cette tâche serait simplement longue et rébarbative : sans plus de valeur ajoutée si ce n'est d'ancrer dans le marbre quelques informations déjà connues. Fort heureusement, je me trompais.  
La mission qui m'eut été donnée était la suivante : réaliser des exemples d'implémentation des composants de formulaire de notre Design System avec React Hook Form (RHF). Mais qu'est-ce que React Hook Form ?
RHF est une libraire complémentaire à React permettant de gérer plus facilement des formulaires. En effet, un formulaire pourrait-être géré nativement par le navigateur, mais avec React et son système de DOM virtuel[^dom-virtuel] les choses deviennent moins aisées. Il faut collecter les entrées de l'utilisateur, valider les informations saisies, parfois assembler des morceaux de formulaire issus de pages différentes pour améliorer l'expérience utilisateur, et tant d'autres. Pour résumer, RHF simplifie l'intégration de formulaires avec React.  
En travaillant ce ticket, j'ai appris énormément de choses. D'abord, sur le fonctionnement interne de nos composants. Cela peut paraître anodin, mais il y a une certaine frontière entre survoler du code, et penser le comprendre, et réellement l'implémenter, l'utiliser. Cette expérience m'a permis de découvrir les rouages internes à notre Design System, et de tester nos composants dans un environnement _sandboxé_ : la _Sample App_.  
Par-delà l'apprentissage du fonctionnement de nos propres composants, j'ai aussi appris à rédiger pour autrui, en anglais. La tâche n'est pas simple, il faut placer le curseur entre détail et simplification : ne pas écrire trop pour être lu, sans manquer d'information pour utiliser pleinement le composant.  
Enfin, un apprentissage important que je tire de ce ticket : il ne faut pas prendre les choses pour acquises. Je pensais, à tort, que les développeurs qui allaient utiliser nos composants, consommer notre Design System, sauraient comment utiliser RHF. Pour moi il n'y avait pas d'utilité à documenter ce qui relevait de l'évidence. Et pourtant, une des tâches du Design System est d'uniformiser l'usage. Il y avait donc une réelle valeur ajoutée à cette mission.

## Comprendre pour améliorer

Une étape importante dans l'évolution de mes tâches au sein du Design System aura été d'améliorer les composants alors en place.  
En effet, ce fut ma première occasion de modifier du code React dans le _repo_. Cette action est loin d'être insignifiante : je dois modifier un code existant et fonctionnel, qui est en production, et utiliser à de multiples endroits auprès de notre _consumer_. Il faut comprendre l'existant, ne pas casser la logique en place, et ne pas réinventer la roue. En effet, ce composant existe dans un contexte : celui du Design System tout entier. Alors, pour conserver une certaine homogénéité, il faut s'inspirer des mécanismes déjà en place, comme le méthode de nommage des classes CSS, la manière dont sont gérés les IDs, les variants, etc.  
Je réalisais alors ma première amélioration de l'existant avec le composant `<FilterGroup />`.

<!-- TODO: ajouter une image -->
Le composant `<FilterGroup />` est un élément de formulaire permettant de faire une sélection. _Sous le capot_, autrement dit, dans sa construction interne, le `<FilterGroup />` utilise les éléments HTML natifs suivants :

- `<input type="checkbox">`quand la sélection est un choix multiple, que l'on peut sélectionner plusieurs valeurs à a fois ;
- `<input type="radio">` quand notre sélection n'autorise qu'une seule réponse.

Cette utilisation d'éléments natifs s'inscrit pleinement dans la philosophie assumée du Design System : reposer le plus possible sur des standards du web, et les méthodes natives aux navigateurs. Ce choix s'explique notamment par le fait qu'il existe une diversité de navigateurs qui est telle, que d'adapter une logique fonctionnelle à l'ensemble des navigateurs serait une tâche chronophage.  
Pourtant, il y a un point sur lequel tous les navigateurs doivent se rejoindre : les standards établis par le W3C, ou _World Wide Web Consortium_. Par groupes de travail, le W3C cherche à standardiser, unifier, créer une source de vérité unique que les navigateurs devront implémenter. Ce rôle était essentiel, surtout à la genèse du web : pouvoir discuter le même langage entre clients et serveurs, tout en proposant une évolution continue des standards.  
Reposer sur les règles du W3C, et donc sur les méthodes d'un navigateur, permet d'accroître la pérennité d'une implémentation réalisée. De plus, c'est s'affranchir d'une étape de réflexion complexe pour penser à l'ensemble des cas d'usage, pour prévoir par exemple l'accessibilité. Le W3C, à travers les WCAG, ou _Web Content Accessibility Guidelines_ adapte déjà ses règles pour qu'elles soient conformes à un certain niveau d'exigence en matière d'accessibilité numérique. En outre, reposer sur natif, c'est pérenniser, alléger la dette technique, mais aussi faire le choix d'une accessibilité établie, réfléchie.

Quelles sont les étapes du processus d'amélioration d'un composant ? Prenons l'exemple du `<FilterGroup />`. Au tout départ, il faut déjà exprimer, comprendre un besoin. La demande peut être extérieure au Design System : un _consumer_ peut avoir besoin de modifier un comportement du composant, ou interne au Design System.  
Après coup, si l'idée est retenue, elle va devoir passer une validation importante, ayant lieu dès le design. Est-ce que cette amélioration est conforme aux valeurs et à la philosophie du Design System ? Par exemple, est-elle suffisamment générique ? Si le besoin dépasse le cas isolé, et que la fonctionnalité a bien sa place dans le Design System, alors une première étape de design est lancée, sous la responsabilité de Betty. Toujours avec le `<FilterGroup />`, l'une des propositions d'amélioration était de rajouter des variants de taille pour le composant. Rajouter une taille `s` et une taille `l`.

Une fois le composant designé, vient l'étape d'intégration dans le _repo_. C'est à cette étape que j'interviens. Après avoir ouvert le design sur Figma, je dis analyser le composant, le comprendre dans le moindre détail. Aussi, je dois comprendre ce qui était, pour comprendre les évolutions et les amélioration apportés au composant. Par exemple, déceler quels sont les _tokens_ pour les `border-radiuses`, pour la couleur de fond, pour la taille des bords, les espaces, la taille des textes, et tant d'autres.  
Après cela vient le code. Notre approche par le _Test Driven Development_ nous pousse à concevoir en premier lieu les tests unitaires, ceux qui vont tester la logique interne du composant. Par exemple, ici, je devais créer un test pour m'assurer que le composant recevait bel et bien les classes CSS correspondantes au variant de taille sélectionné, parmi `s`, `m` et `l`.  
Ensuite, il faut adapter la logique dans le fichier de déclaration React. Ajouter un système permettant de choisir un variant grâce à une _props_, et ajouter cette nouvelle caractéristique à l'interface TypeScript du composant. Il faut ajuster en conséquence le fichier CSS, permettant d'appliquer à une classe donnée, les _tokens_ donnés. Par exemple : 

```css
.watts-filter-group {
    display: flex;
    
    &--s {
    	gap: var(--watts-spacing-025);
    }
    
    ...
}
```

Une fois cette étape réalisée, il ne reste plus que quelques étapes. Il faut d'abord ajuster les _stories_ de StoryBook, afin que le composant soit illustré de manière interactive, présenté en démonstration, pour nous et nos _consumers_. Il faut également ajouter une story Percy pour les test visuels. Et enfin, après avoir révisé l'ensemble du code, il faut le soumettre à la révision des pairs par le biais d'une _Pull Request_ sur GitHub.

## Accompagner dans l'usage

Dans le développement web, il y a toutes ces missions auxquelles on pense, développement de code et revue, React, tests unitaires, etc. Mais il y a aussi toutes ces choses qui ne viennent pas directement à l'esprit. L'une d'elles : le support technique pour nos _consumers_. Malgré avoir documenté nos composants, de proposer différents outils pour aider dans l'utilisation de nos composants, mais également en ayant adopté une conception détachée du consommateur final, nous devons tout de même être à l'écoute des retours.

Ces retours prennent forme dans ce qu'on appelle un _channel_ Teams. Il s'agit d'un groupe de discussion où les utilisateurs de Watts peuvent laisser un message, souvent dans l'attente d'un retour de notre équipe. Il s'agit s'agit de la Hotline Watts.  
Ces retours peuvent être distingués en trois catégories : les vrais bugs, les faux bugs, et les demandes d'amélioration.

Tout système logiciel comporte un défaut de fonctionnement n'ayant pas été prévu à l'origine. On ne peut pas l'éviter. Même les libraires écrites en langage bas niveau laissent apparaître quelques bugs, plus ou moins critiques. Notre Design System Watts ne fait donc pas exception. Mais pour cela, il faut être à l'écouter des personnes qui utilisent notre Design System, pour déceler au plus tôt le moindre bug. C'est la loi dite de Linus « _given enough eyeballs, all bugs are shallow_ ». Autrement dit, plus un logiciel est utilisé et relu par des yeux différents, plus on découvre rapidement les défauts, devenant ainsi faciles à corriger.  
C'est pourquoi il est important de répondre activement aux messages laissés dans la Hotline, permettant de garder un contact constant avec nos _consumers_, et de relever le moindre bug provenant de notre librairie.

Mais il arrive parfois de croiser dans la Hotline ce qu'on appelle de faux bugs, ou dit autrement, des faux-positifs. Ces bugs ne proviennent en réalité pas du code produit par Watts, mais d'une erreur d'implémentation. L'utilisateur implémentant le Design System n'a pas utilisé comme il aurait dû l'un de nos composants. Est-ce de sa faute pour autant ? C'est là le principe de remise en question qu'il faut avoir. Premièrement : est-ce que le bug ne viendrait pas de Watts ? Aussi, s'il y a effectivement eu erreur d'implémentation, avons-nous correctement documenté, expliqué, la manière dont il faut utiliser nos composants. Parfois, cette introspection pousse même à revoir la manière dont nous avons conçu les composants.  
Si effectivement le problème vient bien de l'utilisateur, que notre remise en question ne permet pas de remettre en cause notre Design System, alors il nous faut accompagner le _consumer_ pour l'aider au mieux à intégrer nos composants.  
Cette démarche peut paraître étrange : le Design System qui n'est pas censé s'adapter directement à la manière dont il est utilisé. Pourtant, Watts n'est pas dans un Design System publique, il évolue dans un environnement particulier. Watts est soumis aux enjeux de l'entreprise qu'est Sonepar. On ne peut donc pas se permettre de faire une totale abstraction de l'utilisateur : cela irait à l'encontre des logiques de délivrabilité, et par extension, de rentabilité de l'entreprise.

Enfin, il y a les demandes d'amélioration. Là aussi, il faut faire preuve d'ouverture. Il faut concilier la philosophie et les principes fondateurs du Design System, tout en accueillant cette nouvelle demande. Est alors repris un concept d'expérience utilisateur : la demande exprimée par l'utilisateur répond-elle à son besoin ?  
Une phrase que l'on attribue à Henri [Ford]{.smallcaps} est la suivante : «_If I had asked people what they wanted, they would have said faster horses._ ». Les utilisateurs expriment souvent leur besoin par des solutions, sans réellement comprendre le besoin intrinsèque. Ici, les utilisateurs n'avait pas besoin de chevaux plus rapides, mais d'une voiture. Le besoin n'était pas d'aller plus vite, le besoin était de se déplacer plus vite et plus efficacement.  
Et bien c'est ce même exercice auquel notre équipe doit se livrer lors de la suggestion d'une amélioration. À date, notre Design System encourage même les développeurs à challenger les designers lorsqu'ils se retrouvent face à une difficulté technique. Était-ce réellement la bonne chose à utiliser ? Un exemple pourrait être un utilisateur qui demande une nouvelle fonctionnalité dans le composant `<Radio />` : pouvoir cocher plusieurs options en même temps. La solution n'est pas d'implémenter cette fonctionnalité, mais de challenger le besoin, pour finalement comprendre que l'utilisateur devait utiliser un composant `<Checkbox />` dont c'est le comportement par défaut.

## Créer des composants agnostiques

Le Design System Watts est introverti et indépendant. Watts n'aime pas savoir comment il est utilisé, et ne veut pas s'adapter aux autres. Pour reformuler, une caractéristique majeure de notre Design System est de le rendre agnostique. La définition française du terme « agnostique » n'est pas fidèle à son faux-ami outre-atlantique. L'idée de web agnostique apparaît sous une certaine forme de neutralité et d'indépendance à l'extérieure.  
Concrètement, il s'agit de ne pas être dépendant d'une quelconque technologie, pour pouvoir s'adapter à toutes. C'est un peu la même histoire avec l'USB-C : essayer de s'adapter à tous les périphériques, plutôt que de créer un connecteur pour chaque appareil.

Au sein de Watts, l'un des premiers choix techniques fut de réaliser, coder nos composants avec React. React étant la solution la plus simple, la plus répandue, et la plus robuste. C'est un choix par défaut qui fait l'unanimité dans les entreprises.  
Pourtant, ce choix a été remis en question il y près d'un an. En effet : en utilisant react dans notre Design System, on force nos utilisateurs à utiliser React. Et malgré le consensus établi autour de cette technologie, les voix montent pour contester l'hégémonie de librairie créée par Facebook. En ce sens : comment donner du poids à ces contestations, comment expérimenter, si nos choix techniques contraignent à l'utilisation d'une technologie donnée ?

Ainsi, il été fait le choix de créer une seconde libraire de composants, mais avec des composants un peu particuliers : les web components.  
Les web components sont relativement vieux à l'échelle d'internet. En 2011 déjà, Alex [Russell]{.smallcaps} présentait son idée de web components à la Fronteers Conference. De la simple idée est alors née un projet. Pourtant, ce projet a mis du temps pour se concrétiser. Les standards du web évoluent très lentement, et c'est d'ailleurs ce qui en fait l'une de leurs principales qualités, mais est aussi un frein à l'innovation. Aussi stables que les règles du W3C soient, elles sont égalements lentes pour évoluer. En plus de cela, le W3C n'est qu'une première étape, pour ensuite attendre une implémentation du côté des navigateurs. Il suffit de regarder depuis quand existent les spécification du sélecteur CSS `:has` (2013) et de la date de son implémentation officielle dans Firefox (2023).  
Ce délai s'étire davantage pour les web components : les implémentation et les spécifications ne sont toujours pas stables. Même s'il existe un support officiel sur tous les principaux navigateurs depuis 2018, certaines fonctionnalités majeures ne sont pas encore disponibles. Cela n'a pas empêcher des équipes, comme celles de Carbon Design System (IBM), ou Fluent (Microsoft) à adopter les web components dans leurs libraires de composants. Et c'est dans cette lignée que s'inscrit la volonté de watts de créer des web components.

Mais au fait, qu'est-ce que des web components ? Les web components sont natifs aux navigateurs : ils fonctionnent sans librairie externe, et permettent de créer des composants réactifs, réutilisables, et isolés du reste de la page.  
On peut les comparer aux composants React, qui sont eux aussi encapsulés et réutilisables, mais nécessitent l’écosystème React pour fonctionner. Les web components, eux, peuvent s’insérer partout, permettant réactivité et encapsulation sans imposer un choix technique, faisant d'eux des candidats idéal pour un Design System agnostique. Pourtant, ils introduisent une philosophie quelque peu différente des composants react, notamment de leur principe d'isolation, qui sera un défi pour notre équipe.

Et c'est ainsi que j'ai eu l'honneur de travailler à la création de web components pour Watts. L'idée était simple : nous avons un existant en React, et il faut le reproduire le plus fidèlement possible en web components.  
Pour cela, l'équipe avait créé un planning détaillé de l'ordre dans lequel les composants devaient être créés. Grâce à l'expérience acquise avec les React, il était plus simple d'identifier les dépendances entre chaque composant. Par exemple, le composant `<watts-menu></watts-menu>` a lui-même besoin du composant `<watts-button></watts-button>`, intégrant à son tour le composant `<watts-icon></watts-icon>`. C'est enchevêtrement complexe de composants.

Une fois une roadmap établie, il faut ensuite développer, coder les composants. Cette étape n'a pas été simple pour moi, et cela s'explique. Je suis arrivé aux quasi-prémices des Watts web components. Cela implique un faible nombre de composants existants, seulement trois quand j'étais arrivé. Ces trois composants ne peuvent pas refléter l'ensemble des logiques à intégrer dans chaque composant. Je devais donc constamment me renseigner, benchmarquer, pour essayer d'intégrer la solution la plus adéquate, et faisant consensus. Mais comme expliqué précédemment, l'écosystème des web components n'est pas encore tout à fait mature : les exemples manquent, et certaines fonctionnalités ne sont pas encore disponibles.

Il faut alors faire preuve d'originalité et faire des compromis : créer des fonctions de toutes pièces, accepter une différence de fonctionnement avec les composants React.  
L'illustration parfaite est avec le dernier web component sur lequel j'ai travaillé : le bouton radio. Du fait de l'imbrication des web components, et leur principe d'isolation, il était impossible de faire communiquer ces éléments. Là où un bouton radio ne permet de sélectionner qu'une seule option, mon web component permettait de toutes les sélectionner. Alors, nous avons dû faire le choix de créer un composant parent, le `<watts-radio-group></watts-radio-group>`. Ce composant n'a que pour seule fonction de regrouper les `<watts-radio></watts-radio>`, et d’imiter le comportement natif du navigateur avec les input radio : n'avoir qu'une seule option sélectionnée à la fois.

## La mère de toutes mes démos

Imaginez, un alternant à l'expérience professionnelle sans précédent, et à l'anglais balbutiant. Nous étions au tout début de mon alternance, ou presque. J'avais passé à peine plus de deux semaines avec mon équipe. Et voilà que Betty déclare devant l'équipe : « pourquoi Léo tu ne présenterais donc pas ton travail lors de la démo ? ». C'était la pire chose que l'on puisse me proposer.

Les démos font partie des rituels SAFe. La démo est à réaliser une fois par sprint, à la fin de ce dernier. L'idée est très simple : mettre en avant le travail effectué pour montrer aux autres équipes notre travail. Cela permet de montrer une progression, de mettre à jour certaines synchronisations entre les équipes, de soulever les questions s'il y en a, et de comprendre ce que les autres font. C'est pour cela qu'une journée entière est réservée à ces démos.  
Ainsi, le jour qui précède la fin du sprint est alloué aux démos. Celles-ci sont relativement courtes, elles durent 15 minutes, et ne sont que très peu mises en forme. Ce n'est pas une présentation officielle, c'est un rituel SAFe.

Concrètement, ces _meetings_ se déroulent en anglais. Ils ont lieu l'après-midi, en France, pour que le plus grand nombre de nos collaborateurs puissent participer, qu'ils soient outre-atlantique, ou en asie du sud. Avant chaque démo, des membres de l'équipe sont désignés pour présenter leur travail. Ils doivent expliquer succinctement le travail qu'ils ont réalisé (correction de bug, création de feature, etc.), et présenter idéalement une demonstration de leur travail, à travers un partage d'écran.

Quand Betty m'a proposé cet exercice pour la première fois, je ne voulais pas. C'est une d'anxiété qui dépassait mon entendement. Je suis timide, je ne suis pas à l'aise à l'oral sans longue préparation, et j'ai honte de mon anglais. Mais ma timidité était telle, que je n'ai pas pu refuser. Après tout, c'est mon travail, je dois assumer cette tâche. 

Ce n’est pas sans une certaine réticence que je commençais donc à préparer ma présentation, la boule au ventre. Je m'aidais alors de ChatGPT avec des prompts comme « Aide-moi à traduire cette phrase dans un anglais courant, de l'oral, fluide et naturel ». J'imprimais même mon texte, pour être sûr de l'avoir devant les yeux tout en partageant mon écran.  
D'ailleurs, pour éviter l'effet démo, à savoir une démonstration qui rencontre un bug technique, je réalisais alors une présentation sous forme de _slides_ pour montrer des captures d'écran où tout fonctionne. 

Le moment tant redouté arrive. Mon cœur semble vouloir se détacher de ma poitrine, j'ai les mains qui tremble, un teint anormal. Carla, présentatrice de notre démo, m'introduit alors. Après un court temps d'hésitation, je commençais à m'exprimer. Le temps s'était allongé, étiré, chacun de mes mots semblait durer une éternité, en plus d'être écorchés par mon accent... relatif.  
Pourtant, quelle ne fut pas ma surprise de voir tous ces sourires à la fin de ma présentation. Ce que j'oubliais, c'est que j'avais face à moi des êtres humains. Qu'ils viennent des États-Unis, ou bien d'inde, ils ont un cœur ! Et ils savaient que c'était ma toute première présentation.  
Finalement, cette première présentation a été très bien accueillie, j'ai même été félicité. Si on fait preuve de lucidité, cette présentation était imparfaite, des mots me manquaient, d'autres étaient mal prononcés, mais le message était passé. En fait, il faut voir le verre à moitié plein : cette présentation à le potentiel d'être améliorée ! Et c'est même le propre pour le travail d'un alternant. Il jouit d'un statut particulier : l'alternant n'a que peu d'expérience. Il se forme au travers de ses cours et de ses premières expériences professionnelles : il apprend.  
J'ai eu la chance d'avoir face à moi des personnes bienveillantes, qui m'ont encouragé, et qui ont été attentives et compréhensives lors de cette démo.

Le temps a passé, et j'ai pu réaliser de nombreuses autres démos, essayant de me détacher de mes notes, d'être plus spontané, d'améliorer ma prononciation, et surtout, de me porter volontaire pour présenter mon travail. Je dois l'avouer, j'avais même plaisir à réaliser cet exercice lors des derniers mois.

Finalement, pourquoi est-ce que je ne présenterai pas mon travail lors de la démo ? Cette invitation a permis de me lancer, d'oser, de me tromper et de m'améliorer. Briser mes habitudes, m'ouvrir aux autres, pratiquer mon anglais, et vaincre ma peur. C'était la meilleure chose que l'on m'ait proposé. 

## Vers l'évolution du Design System

En somme, j'ai pu réaliser de nombreuses missions au sein de mon équipe Watts, entre documentation et support technique, amélioration de composants existants, et création de nouveaux mécanismes. Pourtant il y une tâche que l'on peut difficilement mesurer, et qui a pourtant été la plus enrichissante pour moi : faire preuve d'initiative, et encourager l'innovation.

En effet, il y a dans tout travail une ambivalence du métier. Se contenter de faire ce qui nous est demandé, mais il y aussi le fait d'aller au-delà. Et je me suis essayé à cela. Mais comment passer outre ? Et bien tout simplement en proposant des améliorations. Mais il y a une chose qu'il faut prendre en compte : avoir le bon état d'esprit.

Quand je suis arrivé dans l'équipe, je dévaluais à bien des égards mon niveau. Peut-être même, avais-je là le syndrome de l'imposteur. Peut-importe le terme pour le définir, à ce moment précis, je considérais mes connaissances comme quasi-nulles, mettant sur un piédestal mes collègues. En effet, quand on se met à travailler avec des personnes qui ont acquis une certaine expérience professionnelle, à travers les entreprises et les années, on présent que notre maigre expérience aurait bien de la peine à s'imposer. De même, leur parcours universitaire démontre à nouveau une supériorité technique, laissant sans-voix la mienne.  
Pourtant, il m'aura fallu du temps pour comprendre que ce n'est pas parce que mon expérience et mes connaissances sont moindres que je ne peux rien apporter. Et au contraire : le web est en constante mouvance. Il suffit de voir comme il a évolué à travers les années pour comprendre que ce qui était valable hier, ne l'est peut-être plus aujourd'hui. Et c'est cette mouvance qui permet aux développeur juniors d'avoir un regard neuf sur le web.  
C'est en comprenant cela que j'ai réalisé que mes idées pouvaient faire sens et qu'elles pouvaient être légitimes.

Je me souviens avoir suggéré à Mélanie une amélioration dans le Design System, et à la manière dont on gérait le fonctionnement du bouton dans le composant `<Menu />`. Sous couvert d'euphémismes, je présentais alors mon idée, pour aborder la problématique autrement. Je découvrais alors avec surprise la réaction de Mélanie, qui en plus de prendre avec sérieux ma suggestion, me complimentait pour avoir fait cette proposition.  
Je réalisais alors que je pouvais moi aussi apporter à mon échelle, contribuer au Design System, en apportant un regard alternatif du fait de mon expérience. C'est un regard complémentaire à celui de la _seniorité_ de mes collègues.

# Bilan après 172 commits

## `git log`

C'est après quelques 172 commits, que je peux enfin dresser le portrait de mon alternance. Une alternance aux débuts singuliers. Grâce à la gentillesse et la bienveillance d'Alexis, me voilà catapulté dans un processus complexe de recrutement. Je découvre non pas une, mais trois entreprises différentes. Cela a créé en moi presque comme une crise identitaire : ai-je ma place ici ? C'est un monde que je connais pas, c'est un ordre de grandeur que je ne connais pas. Plus que des difficultés techniques, j'ai aussi dû affronter mes propres peurs. Aller de l'avant, m'ouvrir aux autres, communiquer. C'est en fait une aventure humaine que j'ai vécu.

Après avoir documenté, débuggué, amélioré, des composants React, j'ai dû créer de toute pièce des web components. J'ai intégré les principes SAFe, participant notamment aux nombreux rituels, slalomant entre _dailies_, _PI Plannings_ et démos. J'ai appris ce qu'était réellement la gestion de projet. Plus que cela, en pratiquant l'anglais, et en combattant ma timidité, j'ai développé mes compétences de communiquant : un comble pour un Publicis.

Cette année Publicis m'aura même permis de découvrir un déménagement d'entreprise, passant des locaux de Gambetta, à ceux de la rue de Courcelles à Paris.

<!-- TODO: illustrer par photo -->

## `git log | grep alternance`

172 commits, plus tard, on se rend également compte d'une chose : la découverte d'un équilibre efficace de l'entreprise à l'école. Le rythme adopté par le BUT MMI de Champs-sur-Marne trouve un bon compromis permettant d'apprendre à l'école, sans décrocher à l'entreprise, et inversement.

À raison d'un jour par semaine, avec également une semaine complète par mois, je pouvais pleinement me concentrer sur le projet universitaire Tous inclus, tout en apprenant en entreprise.  
C'est peut-être même grâce à ce rythme que j'ai pu puiser pleins de bonnes pratiques de mon entreprise, pour les incorporer au projet universitaire. Par exemple, la gestion de projet, les sprints de deux semaines, les technologies utilisées en front-end, la conception orientée Design System, le linting des fichiers de code : tous ont été inspirés de mon alternance à Publicis Sapient.

La semaine entière de cours ne m'a porté préjudice qu'une seule fois. Cette anecdote nous replonge à l'époque où le Design System stockait son _repository_ git sur Azure (service cloud de Microsoft). Je travaillais alors normalement, récupérant le code, et créant de temps à autres des branches distantes pour ajouter des fonctionnalités. Le temps de l'école étant venu, je m'absentais alors une semaine entière.  
Dès mon retour, je vais sur la plateforme pour consulter les évolutions du code en mon absence. Telle ne fut pas ma surprise que de découvrir qu'on m'avait supprimé les droits d'accès au _repository_. J'exprimais alors mon inquiétude auprès de Julien.  
Alors, j'ai vite compris ce qu'il s'était passé. En réalité, en une semaine, le projet complet avait migré sur GitHub, il n'existait donc plus sur Azure, le mystère était donc résolu.
Ce préjudice est à relativiser, tant il ne m'a finalement pas porté… préjudice. En revanche il montre qu'il peut se passer énormément de choses en une semaine. C'est là que l'on comprend qu'une alternance où l'on passe plus d'une semaine à l'école peut s'avérer compliqué pour ne pas manquer de choses en entreprise. 

En somme, j'ai l'impression d'avoir gagné en maturité, en maturité professionnelle notamment. Je me suis formé aux pratiques en entreprise, j'ai gagné en technique, et ai développé mon sens de la communication (avec une nette affirmation de moi-même en anglais !). Mais je pense que ma plus grande leçon aura été ce que j'ai appris sur moi, ce travail introspectif mené tout au long de l'année.

# Le développeur n'est plus un col blanc

La développeur est-il un col blanc ? Au sens sociologique et historique, oui. Il appartient à cette catégorie des cadres et professions intellectuelles supérieures. La définition de l'INSEE est claire, le développeur appartient à ces « professions qui nécessitent des connaissances approfondies et qui, souvent, doivent satisfaire à une exigence de diplômes ou de concours » @Pcs20203CadresProfessionsIntellectuelles [].  
Dans l’imaginaire commun, le col blanc est un salarié qui effectue un travail intellectuel. On le perçoit comme maîtrisant son temps et ses tâches. On lui donne une grande autonomie pour remplir ses responsabilités. Son travail est réflexion et créativité. Il possède un cadre de travail stable, un emploi sécurisé.

Pourtant, il semble que le développeur de la _Digital Factory_ s'éloigne peu à peu de l’image traditionnelle des cols blancs.  
Tout d'abord, plus que jamais, sa productivité est mesurée. L'outil informatique, a permis la créations de pleins de métiers, ainsi que la transformation de nombreux autres. Mais il est également devenue une porte dérobée de notre intimité. Il est un outil de mesure, et est devenu la badgeuse. On ne pointe plus sa carte au début et à la fin de la journée, on se connecte sur Teams, et on garde le voyant vert jusqu'à la fin de la journée.  
Pire encore, l'informatique génère des données, que l'on peu ensuite analyser. Les mathématiques peuvent donc aider à mesurer la productivité, qui au sens de l'entreprise, s'appelle la rentabilité. Les exemples sont nombreux, et pour le développeur, on pourrait citer la mesure de fréquence des _commits_ et _pull requests_. La rapidité d'exécution pour un ticket donné dans Jira. Ce modèle donne des allures de taylorisme : le moindre geste est chronométré et analysé. Cela n'est pas sans rappeler les usines, où est justement né le travail à la chaîne. Et on pourrait même aller plus loin. Sur site, les locaux sont organisés en open space. Bien qu'on puisse trouver nombre de qualités à cette organisation, elle a aussi la fâcheuse tendance à accentuer la surveillance mutuelle et constante.

De plus, il semblerait que Publicis Sapient pratique de _l'offshoring_, en déléguant notamment certaines missions dans des pays où le coup de la main d'œuvre est moins cher, avec par exemple une présence de Publicis Sapient. Les équipes qui travaillent à distance sont mises à disposition sur des projets client, tel que le projet Sonepar.  
Pourtant, il faut être critique : la présence de Publicis Sapient en Inde peut s'expliquer par la présence de Sonepar également en Inde. On y trouverait donc une logique à ce que le consultant soit installé au plus près de son client. Toutefois, on notera que la main d'œuvre pour des ingénieurs logiciel en Inde reste moins chère. Indéniablement, Publicis profite ainsi d'une expertise à moindre coup. Il existe probablement une forme _d'offshoring_.  
Là aussi, on retrouve le propre des usines de production. Prenons l'exemple de Renault, constructeur automobile français historique, produisant ses véhicules dans les usines d'Île-de-France, ou en Normandie. Pourtant, Renault, au début des années 2000, a commencé à délocaliser sa production vers des pays où la production de voitures est moins chère, tel qu'au Maroc. La réduction des coûts s’explique en grande partie par des salaires moins élevés pour les ouvriers.

Le développeur semble aussi avoir des contraintes grandissantes, notamment du fait de l'application du framework SAFe. Le framework impose une cadence de production, cadence comparable à celle des tapis-roulants du travail à la chaîne. Chaque tâche est planifiée à l'avance et chronométrée. Elle s'inscrit dans flux où le rythme global prime sur les initiatives individuelles.

J'ai également pu observer lors de mon alternance des départs de la _Digital Factory_. Des développeurs ont quitté Publicis Sapient : serait-ce là un marqueur d'un turnover élevé ? Marqueur emprunt d'une industrialisation où l'individu est remplaçable. Dans le code, on parle même de _Bus factor. On élimine les rôles clefs, pour que le processus ne s'arrête jamais. On rend un poste remplaçable, si jamais « quelqu'un devait se faire percuter par un bus ».  
Mais cette logique permet aussi _d'onboarder_ facilement de nouvelles personnes, et cela ouvre les portes à un mécanisme de turnover volontaire. On ne cherche plus à garder les développeurs, trop coûteux au fur-et-à-mesure de leur ancienneté, en les remplaçant par de nouveaux développeurs. 

Enfin, comment ne pas parler de l'intelligence artificielle ? Celle-ci est devenu omniprésente, et omnipotente dans le travail du développeur. Sonepar et Publicis Sapient ont trouvé un accord pour intégrer l'IA au coeur du développement. Publicis Sapient travaille même à la réalisation de son propre outil de développement accéléré par l'IA : _Sapient Slingshot_.  
On peut se demander si cette IA n'est pas radicalement en train de changer la manière pour le développeur de créer du code. On peut se demander si la tâche intellectuelle n'est pas reléguée à l'IA, pour n'avoir plus qu'un « actionneur de l'IA » derrière. Le métier de développeur serait finalement très comparable à celui de l'ouvrier.  
Avec des horaires fixes, le développeur se rend à la _Digital Factory_. Il se met en poste, derrière son écran, et guide la machine dans des tâches presque manuelles, avec des clics réguliers, et répétitives.

Finalement, pourrions-nous voir une transformation du métier de développeur ? Le col blanc au sens sociologique ne trouve plus de matérialité dans ce secteur. Les développeurs ne sont manifestement pas des ouvriers. Ils ne travaillent pas à l'usine. Pourtant, il semble que de nouvelles usines aient émergé, sans qu'on les appelle pour autant des usines. Celles-ci créent de la confusion, une ambivalence dans les responsabilités du développeur. Le développeur n'est pas un ouvrier, mais il en porte ses habits.

# La _Digital Factory_ en bleu de travail ?

Les développeurs ne sont manifestement pas des ouvriers au sens strict : ils ne fabriquent pas de pièces à la chaîne et ne manipulent pas de machines physiques. Pourtant, en observant leur manière de travailler, on distingue alors un certain rythme, des processus, et des contraintes imposées. C'est l'apparition des usines 2.0.

Le développeur ne peut pas être un ouvrier : il doit toujours partager, collaborer avec ses collègues, et conserve une dimension intellectuelle dans son métier. La valeur ajoutée d'un développeur se trouve être aujourd'hui l'architecture plus que le code en lui-même. Le développeur conçoit en pensant à l'avenir : il intellectualise le code. Il débat, réfléchit, et essaye avec ses pairs de trouver une solution qui ne soit pas la performante, mais celle qui fera le meilleur compromis. Ces interactions avec ses collègues pour toujours plus challenger le code se trouve avoir encore une forte caractéristique des professions intellectuelles.

De même, le développeur est poussé à se former. Là encore, la définition sociologique épouse parfaitement cette initiative. On souhaite que le développeur acquière davantage de connaissances, qu’il développe ses compétences et partage son expérience. Des moments comme le _Knowledge Exchange Day_ (KED) illustrent parfaitement cette dynamique : ils offrent un espace où chacun peut échanger sur ses pratiques, co-créer, et confronter ses idées. Publicis Sapient organisait ces journées, en encourageant des _speakers_ à présenter certains aspects de leur mission, de rentrer dans la technique, et de partager aux autres leurs savoirs. Typiquement col blanc non ?  
Cependant, Publicis Sapient France tend vers un autre horizon. Depuis le début de 2025, leur fréquence va diminuer, ainsi que leur format : moins d'une fois par mois, et seulement sur une demi-journée.

S'il y a une chose marquante avec la _Digital Factory_, c'est qu'elle engendre des métiers dons la catégorisation est difficile. Les frontières sont bien moins marquées que celles des définitions sociologiques, calquées sur la période de l'industrialisation. Il devient donc impropre de parler de col blanc et de col bleu. Ces termes n'arrivent plus à caractériser, catégoriser fidèlement les différentes professions.  
Là où le col confond nature des tâches et organisation du travail, la capuche, elle, les rassemble. C'est une image bien connue qu'on a des développeurs, vêtus d'un sweat à capuche. C'est d'ailleurs de cette image que l'expression _white_ et _black hat_ s'est transformée en _black & white hood_.  
Peut-être en effet que la profession de développeur est groupe à part entière, à considérer différemment, dans un contexte de mondialisation et d'ère Internet.

Le sweat à capuche est une sorte d'hybridation. Son identité professionnelle se construit au travers du rythme des projets, des interactions avec les pairs, et des rituels partagés. C'est un équilibre entre une certaine autonomie intellectuelle et de la structuration, entre réflexion et cadence imposée.

Les IA sont en train de résoudre des problèmes jusqu'alors insolvables. Les IA seront capables de remplacer des métiers intellectuels, auxquels on prêtait une immunité technologique. Aujourd'hui, ces métiers sont en phase d'être radicalement transformés. Le personnel de ménage n'a pas perdu son métier, seulement le balai. Les développeurs, eux, risquent de voir une partie de leur autonomie intellectuelle absorbée par ce nouvel « aspirateur de données » qu’est l’IA.

# Doit-on fermer les yeux sur l'éthique pour apprendre ?

Mon expérience au sein de la _Digital Factory_ m'a confronté à des dilemmes que je n'avais envisagé. J'ai notamment remis en questions mes valeurs morales, éthiques. Il en ressort une vision moins manichéenne des choses. Ma réponse n'est plus binaire : travailler ou ne pas travailler dans une entreprise avec lesquelles je ne partage pas mes valeurs. 

Cette réponse n'est pas binaire, parce qu'une entreprise ne peut pas partager en intégralité ses valeurs avec moi, et ne peux donc pas non plus être en totale opposition. Il y a donc un certain détachement à adopter, pour ré-envisager cette considération de l'éthique. Publicis Sapient, et Publicis Groupe sont loin, très loins d'être complètement teintées de noir. Bien au contraire, ces entités partagent des objectifs en matière d'inclusion, d'environnement et de santé.  
Pour ne parler que du domaine de la publicité, Marcel [Bleustein-Blanchet]{.smallcaps} disait poétiquement :

> « La publicité c’est comme faire une demande en mariage, et pour réussir en amour il faut y croire. »

L'entreprise croit d'abord dans les produits qu'elle met en avant. En fait, loin de la polarisation à laquelle j'ai été sensible sur le net, la publicité ce n'est pas le bien, ni le mal. La publicité est parfois nécessaire pour se faire connaître, faire connaître un produit. Ce n'est pas cette découverte qui me fera désinstaller _uBlock Origin_, mais elle me fera comprendre que la question est complexe.

Aussi, je commence à reconsidérer mes barrières éthiques, pour prendre en considération un autre facteur : ce que j'apprends. Je pense qu'il aurait été difficile pour moi d'autant apprendre que dans cette entreprise, ce type d'entreprise. Le dilemme change, et met en parallèle considérations éthiques, et transmission de savoirs.  
Je ne saurais dire si cette réflexion n'est que pour rassurer de l'alternance que j'ai réalisé, peut-être est-ce là un biais. Je pense sincèrement en tout cas avoir acquis un regard neuf sur cette question éthique. Publicis Sapient m'a beaucoup apporté.

J'ai appris le front-end. J'ai appris la gestion de projet rapportée au numérique. J’ai découvert une passion sincère pour le développement front. J'ai découvert un nouvel aspect de l'accessibilité numérique. Sur le plan professionnel, Publicis Sapient m'a beaucoup donné. C'est cette rémunération implicite dont je parlais au début de cet écrit. Et cette rémunération dépasse toutes mes attentes. J'ai l'impression d'avoir progressé techniquement, j'ai acquis des compétences et assimilé des méthodologies. J'ai pratiqué sur un projet concret. Cette alternance représente un apprentissage exceptionnel.  
J'aime raconter cet équilibre entre la théorie des cours, et la réalité du terrain en entreprise.

Pour autant, je ne dresse pas un tableau complètement positif de Publicis Sapient. Dépeint de ce constat une absence d'ouverture au monde de l'open source, qu'il s'agisse d'une contribution par le code, ou financière. Mais encore une fois, je peux le comprendre : l’univers Publicis, avec sa structure hiérarchique, et ses enjeux commerciaux, répond à une logique commerciale, une logique de marché. C'est encore une fois le paradoxe de Google : autant que j'aime me séparer des produits de Google, je ne peux nier sa contribution majeure au monde de l'open source, permettant de faire vivre des projets, et même d'initier des projets open source.
J’ai fait de belles rencontres à Publicis Sapient, et j’ai compris l’importance de travailler avec une équipe qui peut prendre le temps de m'expliquer. Je remercie à nouveaux chaleureusement ces personnes, qui ont toutes, sans exception, montré leur bienveillance à mon égard, et qui m'ont poussé à me dépasser.

Et justement, cette expérience humaine m'a fait également reconsidérer mon rapport à l'autre. J'ai appris de moi-même. Et je constate que le code isole. Le télétravail isole. Au-delà des compétences techniques et professionnelles, cette expérience m’a rappelé le besoin d’une dimension plus humaine dans mon travail. L’éthique, la proximité, le sens de la contribution et la liberté d’initiatives sont devenus des moteurs pour moi. 

J'ai découvert en MMI une sympathie pour l'expérience utilisateur (UX). Ce n'est pas un domaine que je connaissais avant d'entrer dans la formation. Pourtant, je crois avoir découvert une nouvelle passion, qui peut-être m'aidera à éclairer mes futures aspirations professionnelles.  
Il y a une caractéristique forte dans l'UX, presque un principe fondateur : l'empathie. Et il y a bien une chose que je dois dire, j'aime cette vision recentrée sur l'autre. Où la technique s'efface pour laisser apparaître des humains. Peut-être est-ce là l'écho de ma peur d'un web qui se robotise, avec tous ces sites web générés par IA. Tous ces posts, toutes ces images, toutes ces vidéos, tous ces sons, générés par IA.

# Annexes {-}

## A. Cahier des charges
## B. Documents techniques
## C. Glossaire
- **MMI** Métiers du Multimédia et de l'Internet. Formation universitaire réalisée au cours d'un BUT.
- **BUT** Bachelor Universitaire de Technologie. Diplôme de l’enseignement supérieur, obtenu après trois années d’études post-bac dans un IUT.
- **IUT** Institut Universitaire de Technologie. Composante d’une université délivrant le BUT.
- **navigateur**
- **consumer** terme utilisé pour désigner un utilisateur, qui va consommer, au sens fig., du code.

## D. Quelques GIFs utilisés

# Bibliographie {-}
::: {#refs}
:::
