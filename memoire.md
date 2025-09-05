---
numbersections: true
---

# Avant-propos {-}

En m’immisçant dans la rédaction de ce mémoire, j'ai d'abord pensé à la forme qu'allait prendre celui-ci. En effet, c'est elle qui m'aidera à étayer mon propos. Bien qu'une problématique générale m'aide à guider ce document, il y a également une trame de fond qui était à mon sens très importante : rendre compte d'une évolution dans le temps et des enseignements reçus grâce à l'alternance. Dans ce cas précis alors, il est nécessaire de marquer le contexte : savoir ce qui était, pour comprendre l'avancement.

C'est ainsi que j'ai pris la décision d'opter pour une forme un tant soit peu moins académique pour la rédaction de ce mémoire. Si je pensais hier que la formation MMI ne me transmettrait que des compétences techniques en programmation, j’ai découvert bien davantage : une philosophie de travail, une vision élargie du rôle que je souhaite incarner demain. Si je ne devais choisir qu'un mot pour résumer ce que j'ai appris, je choisirais sans hésitation celui de « créativité ».  
Car oui, c'est bien la créativité qui a guidé toutes ces lignes de code, et non l'inverse. C'est de toutes ces idées nouvelles qu'ont émané un schéma technique qui n'a que pour seul but de desservir cette même créativité.

Voilà donc pourquoi cet écrit reprendra de temps à autres les codes du récit ; toujours dans la même optique : exposer une situation initiale pour aboutir à une situation finale (cf. le schéma narratif).  
Le mémoire étant un exercice de développement de la pensée, ayant pour objectif in fine d'exprimer une opinion [@MemoireEcrit2024], il était pour moi important qu'il soit un reflet personnel, adoptant un style qui m'est propre.

Aussi, cet écrit ne prétend aucunement à une expertise dans un domaine quelconque. C'est un essai invitant à la réflexion et la remise en question.

# Remerciements {-}

Gaëlle et Michel
Alexis
Mélanie et Julien

# Résumé {-}

# Abstract {-}

# Table des matières {-}
::: {#toc}
:::

# Cadre du mémoire {-}

## 1. Contexte général

Je dois faire une alternance après MMI, avec un livrable à la fin : le mémoire + soutenance

## 2. Objectifs du mémoire

Rendre compte d'une progression, d'une évolution personnelle et professionnelle, en se référant à MMI.

## 3. Démarche méthodologique

ITWs + observation + données provenant internet

## 4. Structure du mémoire

### 4.a La forme guidée par des valeurs

éthique...
- Libre
- Transparence (Open Source + bibliographie CSL JSON)
- Accessibilité universelle
- Approche humaine (cf. centré utilisateur / empathie)
- Respect de la vie privée (données personnelles)

### 4.b La rigueur au service de la créativité

Assumant un style d’écriture plus libre, ce mémoire s’appuie cependant sur un cadre rigoureux pour traiter le sujet de manière structurée.

## 4. Outils utilisés

- Zettlr
- Zotero + BetterBibTeX
- Git et GitHub
- ChatGPT pour la relecture uniq. + anonymisation (tout en pensant aux algos, pour ne pas leaker avec des déductions par fingerprint)

# I. Travailler dans le _Digital_

Ça y est, j'y suis ! Après trois mois de travail consécutif au sein du Groupe Progress, je peux enfin le dire : j'ai réalisé ma première expérience professionnelle.

Comme n'importe quelle expérience professionnelle, on arrive avec des attentes.  
La première d'entre elles est simple, c'est la rémunération pour le travail effectué. C'est la contrepartie pour avoir donné de son temps et de sa force de travail. Le stage n'étant pas le statut professionnel le plus valorisant financièrement parlant, il va de soi que ce n'était pas ma première attente.  
La deuxième attente, moins formelle, est pourtant celle qui avait le plus de sens à mes yeux : l'enrichissement personnel. Celui-ci se matérialise de plein de formes différentes. Peut-être souhaite-t-on développer nos compétences techniques, nos compétences organisationnelles, notre capacité à travailler en groupe ? Mais ces attentes s'accompagnent aussi de celles qui sont implicites. Le travail est aujourd’hui l’un des principaux marqueurs de reconnaissance sociale : c’est souvent la première chose que l'on mentionne en se présentant. Mes amis, ma famille : que vont-ils en penser ?

Bref, vous le comprendrez, cette expérience est à l'origine d'une profonde remise en question de mes aspirations professionnelles, et bien au-delà : ce que je souhaite faire de ma vie. C'est ce qui a, entre autres, constitué le fil conducteur de mon rapport de stage de 2024. 

Je présentais alors au 22 juin de la même année ce travail de réflexion, cet exercice introspectif, devant madame Florence [Bister]{.smallcaps} et monsieur Renaud [Epstein]{.smallcaps}. Au cours de cette soutenance, j'ai pu exprimer le déroulé de mon stage, et surtout, la dissonance entre mes attentes préalables et la réalité du terrain. J'y exprime notamment une reconnaissance somme toute relative au sein de l'entreprise, mais surtout un sentiment de détachement vis-à-vis des autres employés.  
Là n'était pas la question du statut de stagiaire, mais plutôt celui du regard porté aux développeurs. Ce regard comme si le développeur n'était finalement qu'un simple rouage dans une production numérique. Un développeur réduit à une fonction dépersonnalisée.  
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

Les travailleurs effectuent des tâches répétitives et routinières dans un environnement analog, révélant que le numérique repose sur un travail proche de celui d’une usine traditionnelle dans ce cas précis.  

Tout cela m’a ramené à mon échange avec Renaud [Epstein]{.smallcaps} et à cette phrase qui m’avait marqué : le développeur est-il en train de devenir un ouvrier ? La question n’est pas simple, mêlant nature des tâches, considération des pairs et répétition des gestes. Travailler dans une _Digital Factory_ équivaut-il à être un ouvrier ? Travailler à la Digital Factory : col blanc ou col bleu ?

Cette interrogation sur le statut du développeur au sein de la _Digital Factory_ reprend une métaphore sociologique connue : l’opposition entre « col blanc » et « col bleu ». À l'origine, le premier renvoie aux emplois intellectuels ou administratifs qualifiés, où créativité et autonomie occupent une place prépondérante. C'est la fameuse chemise blanche portée dans les bureaux. À l’inverse, le col bleu désigne quant à lui les emplois manuels ou industriels ; qui connotent fortement avec la répétition des gestes, la standardisation des tâches, et avec une certaine subordination hiérarchique. C'est le fameux bleu de travail porté en usine.  
Or, le terme de _Digital Factory_ soulève un paradoxe : le travail des développeurs est à la fois créatif et technique, mais il peut être aussi structuré, répétitif et encadré, rappelant des aspects du travail ouvrier.  
Dès lors, une question survient : la _Digital Factory_ constitue-t-elle une organisation créative et autonome, à l'image des cols blancs, ou bien reproduit-elle les logiques de l'industrie, et le travail routinier propre aux cols bleus ?

# II. Accéder à l'alternance : un parcours singulier

Il y a une caractéristique propre au BUT MMI[^butmmi], et aux BUT de manière générale : c'est le caractère professionnalisant de la formation. Pour atteindre cet objectif, on propose aux étudiants de s'immiscer dans des applications très concrètes pour se familiariser à leur futur métier. Matériellement, c'est ce que l'on appelle des projets, ou Situation d'Apprentissage et d'Évaluation. Ces projets sont organisés tout au long de l'année, et servent à mettre en pratique la théorie, et même à aller au-delà.

## II.1 Prométhée, Swagger… et Alexis [Charpentier]{.smallcaps}

C'est ainsi qu'au cours de ma deuxième année de BUT MMI que j'ai pu travailler avec mon équipe sur la réalisation d'un musée virtuel et d'une plateforme de réservation, du nom de Prométhée. Prométhée est une agence fictive qui souhaite promouvoir le travail de femmes artistes. Au delà de montrer leur travail, c'est aussi toute une immersion dans l'univers de ces femmes, donnant ainsi un contexte important à leurs œuvres.  
Au sein de l'équipe, j'ai notamment été responsable de la mise en place du site web, ainsi que du système de réservation sous-jacent. C'était un projet ambitieux, peut-être trop, mais qui avait pour aspiration à mettre en place des éléments techniques rigoureux, qui auraient pu naître dans un contexte professionnel. Nous voulions que la boutique puisse théoriquement ouvrir ses portes, preuve de choix techniques robustes.  
Je ne saurais dire si ces objectifs ont été pleinement atteints, mais ils constituaient dans tous les cas notre fil d'Ariane. C'est comme ça que des technologies comme Symfony sont apparues sur notre projet. Attention cependant, une contrainte nous avait été donnée : exposer une API[^api] pour décorréler la partie front-end, à savoir l'interface s'exécutant dans le navigateur d'un visiteur, et le back-end, la partie où tous les traitements logiques des données ont lieu. Là encore, un choix technique a été fait, celui d'adopter des standards du web, avec OpenAPI et de la documentation avec Swagger. 

Le jour de la présentation, j'ai à cœur avec mon équipe de présenter le fruit de notre travail, mais aussi d'expliquer toutes les étapes de réflexion, justifiant ainsi de nos choix techniques.  
Ce jour-là, parmi les personnes dans la salle, se trouve Alexis [Charpentier]{.smallcaps}. Comme j'aime le présenter, Alexis, est à l'origine… mon professeur. Alexis s'est attelé à nous enseigner les bases de React, la technologie front-end la plus répandue dans le monde. React est une bibliothèque JavaScript permettant d'adopter une conception par bloc réutilisables, ou composants, dans les interfaces web ; et de rendre ces blocs réactifs avec leur environnement. Mais outre cette simple technologie, Alexis a eu également à cœur de nous transmettre une philosophie du développement web : une vision de laquelle s'accompagne des bonnes pratiques, un cadre et des pistes de réflexion.  
Si l'on en revient à la présentation, celle-ci se déroule avec succès, et aboutit à des questions posées par le jury. Nous avons même le droit à quelques remarques et gentillesses concernant la réalisation de notre projet. Alexis, même sans être membre du jury, nous adressa quelques compliments, soulignant les pratiques professionnelles ayant été adoptées sur ce projet. Ces remarques font écho auprès de notre groupe, et c'est non sans une petite once de fierté que nous quittons alors la salle.  
C'est à peine après avoir eu le temps de souffler avec l'équipe, et de célébrer comme il se doit la fin de notre projet, qu'Alexis vient me voir. Je tombe des nues. Voilà qu'Alexis me propose un poste en alternance au sein de l'entreprise dans laquelle il travaille. Je fais alors preuve d'une longue hésitation, le temps d'une respiration, pour finalement accepter la généreuse proposition. En effet, le MMI de Champs-sur-Marne ayant pris le parti de l'alternance au cours de la troisième année, il me fallait alors trouver une alternance, et voilà que c'est Alexis qui me la propose. Me voilà donc candidat à Publicis Sapient en qualité de développeur web front-end.

[^butmmi]: Bachelor Universitaire de Technologie - Métiers du Multimédia et de l'Internet.
[^api]: Application Programming Interface, un pont permettant à deux systèmes informatiques d’interagir entre-eux.

## II.2 L'embauche dans le secteur de la tech : un processus complexe

S'il y a quelques vérités admises sur l'embauche dans le secteur de la tech, elles relèvent avant tout d’un processus long, aux étapes multiples. Malgré le fait qu’une personne m’ait déjà ouvert les portes de l’entreprise, j’ai tout de même dû me soumettre aux exigences portées par le processus d’embauche de l'entreprise.  
Quelques semaines se sont écoulées depuis ma soutenance de fin d'année. Alexis est revenu vers moi, afin de me proposer un entretien sur Discord. Il m'y explique quelles pourront être mes missions, quels pourront être les projets sur lesquels je pourrais travailler. Pour des raisons évidentes d'impartialité, la suite du processus ne se déroulera pas avec Alexis.

C'est Iago [Ducardonnet]{.smallcaps}, mon futur recruteur, qui initiera officiellement mon embauche, par le biais d'un appel téléphonique. L'appel, très succinct, permet à mon recruteur et moi-même de nous présenter. C'est une première étape permettant de planifier un second temps : à nouveau un entretien téléphonique, mais plus long.

Ce second appel n'est pas des moindres :  il est déjà jalonné de questions techniques. C'est avec une voix un peu tremblotante que je tente de répondre aux questions, et que j'essaye également de mettre en exergue ma passion sincère pour le domaine du web.  
Une question a retenu mon attention : « qu'est-ce qu'un hook React ? ». Pris au dépourvu, j'ai joué la carte de l'honnêteté : je ne sais pas. J'ai bien sûr donné quelques exemples des hooks les plus connus : `useEffect`, `useState` ; mais sans savoir précisément comment les expliquer. J'ai beaucoup aimé cette question et les mécanismes qu'elle sous-tend : la capacité d'expliquer. C'est une maxime connue : « ce que l’on conçoit bien s’énonce clairement », en outre, ma capacité à vulgariser démontre une certaine maîtrise du sujet abordé. Pourtant, je n'ai pas réussi à répondre à cette question qui semblait si simple. Les hooks sont en quelque sorte une interface permettant d'accéder à toute la logique réactive d'un composant exposée par React. Ces hooks nous permettent de « brancher » un composant, de le relier à la logique interne de la librairie.  
En dépit de ce léger incident, l'appel a continué son cours, mêlant questions techniques, d'apparence simples, et questions plus générales sur mon parcours.  
Cet exercice oral a démontré une chose : il est particulièrement difficile. Non tant sur la technique, que sur l'exercice humain. Il est difficile de faire transparaître un sourire a travers le téléphone, il est difficile de savoir si la réponse donnée semble satisfaisante. Bref, un exercice dans lequel je n'étais pas très à l'aise, mais fort heureusement, j'apprenais la semaine suivante, la poursuite de mon recrutement avec un entretien en présentiel. 

Me voilà à la troisième étape de mon parcours : l'entretien face au recruteur… ou du moins c'est ce que je pensais. À l'aube de cet entretien, j'avais préparé toutes sortes de projets avec lesquels j'allais pouvoir illustrer mon propos. L'idée était simple, je ne suis même pas encore junior, mes compétences techniques sont donc par extension limitées. Limitées, certes, mais pas dans le temps. C'est le message que je tenais à souligner pour cet entretien. Mon intérêt pour le code remonte à bien plus longtemps que les cours. C'est une réelle curiosité que j'ai acquis et qui me permet d'apprendre, apprendre constamment, apprendre avec rigueur.  
Le jour de l'entretien, je me présente avec quelques 45 minutes d'avance. C'est beaucoup, mais avec les près de 1h45 de transports en commun, je me devais de prévoir de la marge. Cette avance n'a pas joué en ma faveur, c'est pile le temps qu'il faut pour accroître son stress. Il se trouve que, même si les minutes paraissent des heures, l'heure finit quand bien même par arriver. Me voilà donc avec cinq minutes d'avance, devant les portes de Publicis Sapient, avenue de Gambetta, dans le XX^e^ arrondissement de Paris.  
Je fais la rencontre de Saïd [Boufous]{.smallcaps} et Florian [Fanor]{.smallcaps}, tous deux développeurs front-end à Publicis Sapient, Iago ne sera finalement pas là. Cette rencontre peut paraître anodine, mais elle n'en demeure pas moins intimidante : je me retrouve alors seul face à deux personnes que je ne connais pas, dans un environnement que je ne maîtrise pas. De plus, je suis quelque peu introverti. J'ai du mal à lancer ou relancer des conversations, l'exercice devient d'autant plus complexe. Un entretien est avant tout un ressenti entre humains : la relation est-elle fluide ? Tout l'enjeu pour moi est alors à cet instant précis de m'ouvrir aux autres.  
Cependant, ma passion vient me sauver. J'ai pu au cours des années roder un _pitch_ sur mon parcours dans le domaine du web. À mon avantage, je dénote une certaine aisance à parler des sujets qui me tiennent à cœur, ce qui rend l'échange davantage concernant pour Florian et Saïd. Mon _pitch_ est simple, plutôt que de raconter quelles sont mes prétendues compétences, j'aime raconter comment, et à quel âge je suis arrivé dans le développement web. C'est une passion née d'abord de la radio, oui, cette radio FM qu'on écoute sur le poste dans la voiture, sur le transistor dans la cuisine. Plus jeune, je voulais recréer ma propre radio. C'était bien ambitieux de ma part, car irréalisable dans l'état : un émetteur FM coûte bien trop cher. Cela étant… j 'ai la chance d'avoir été contemporain de l'époque de la montée en puissance des radio internet, ou webradios. C'est l'époque notamment de Radionomy, et du lecteur Winamp. Alors, je m'étais lancé dans la création d'une webradio, expliquant notamment mes premières expériences avec le web, les serveurs, le réseau, et bien plus encore. C'est la découverte d'une passion dévorante pour tout ce qui se rapporte de près ou de loin au web. Pour couronner le tout, j'illustre mon parcours par des réalisations passées, académiques, personnelles, et notamment une que j'aime présenter : un site web de réservation pour une cliente. Il est la parfaite illustration d'un projet concret, impliquant système de réservation et de paiement. On peut réserver un appartement en quelques clics. Par-delà l'idée de montrer simplement le site web, j'explique toute la réflexion sous-jacente ayant guidé les choix techniques. Parmi cette liste non-exhaustive, on retrouve : blocs visuels volontairement scindés par la ligne de flottaison pour suggérer un scroll dans la page, intégration d'un calendrier interactif, tout en gardant les inputs natifs, afin d'améliorer l'accessibilité de la page, et tant d'autres.  
Finalement, cette épreuve se sera surprenamment bien déroulée. Par chance, Saïd et Florian étaient très à l'écoute et engageaient volontiers la discussion. J'ai pu poser des questions, répondre à des questions, et même visiter tout l'étage du bâtiment dédié à Publicis Sapient. On peut relever qu'il y avait très peu de monde ce jour-ci, en effet, le télétravail était de mise ce vendredi.

Après deux appels téléphoniques et un entretien sur site : nous voilà donc à la fin du processus ? pas vraiment. Il existe en effet une ultime étape : l'entretien en visioconférence avec un directeur technique de haut-rang. Pour cette quatrième étape donc, j'ai rendez-vous avec Geoffroy [Vergne]{.smallcaps}, _[Director Engineering Technology](https://www.linkedin.com/company/10801655/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base%3BUgCbiNpzSmSAo2j9GmbxmA%3D%3D)_ à Publicis Sapient France. Là aussi, quelques questions techniques, auxquelles je m'étais préparé. En revanche, il y avait des questions auxquelles je ne m'attendais pas du tout, notamment celle-ci : « si votre carrière devait évoluer au sein de notre entreprise, vers quel type de poste aimeriez-vous progresser ? ». Cette question est difficile, car non-seulement elle fait appel à des projections : il faut montrer de l'ambition sans pour autant paraître immodeste, tout en montrant la compatibilité du poste avec l'entreprise donnée. À nouveau, j'ai joué la carte de la transparence : je souhaite évoluer vers un poste qui demande moins de pratique du code, là où vont se dessiner tous les rouages du système ; dans le domaine de l'architecture.  
Et c'est sur cette conversation que finalement nous concluons cet entretien, marquant ainsi la fin d'un long parcours d'embauche.

En somme, ce fut une première à mon égard : suivre un processus d'embauche complexe dans le domaine de la tech. Et encore, en tant qu'alternant, Publicis Sapient a délibérément choisi de ne pas mener de test technique. Cela montre un certain recul de l'entreprise quant au fait que je suis un cursus universitaire, et que je suis en plein apprentissage : la technique passe au second plan. Malgré cela, ce processus n'en demeure pas moins long. Déjà, par le nombre absolu d 'étapes, mais aussi le délai qui s'écoule entre ces étapes, de quelques jours à plusieurs semaines.  
C'est une pratique où la constance est de mise : montrer une motivation sans faille du début à la fin. Fin qui pour moi a été couronnée de succès, presque comme une victoire ! Volonté des entreprises de la tech, ou bien simple fait d'un processus qui se veut exigeant, mais ressort de ce processus un sentiment de fierté. C'est comme arriver le premier lors d'une épreuve d'endurance. Et ce sentiment est loin d'être anodin, même s'il est involontaire, il participe à donner une impression de mérite du poste. Il confère également une forme d'aura à l'entreprise, presque de prestige d'appartenance.  
Rétrospectivement, on peut se questionner sur la légitimité de ce sentiment, ou du moins, sur l'ambivalence portée par celui-ci. C'est un sentiment de fierté, d’accomplissement réel pour le candidat. Mais peut-être aussi qu'il s'agit-là d'une instrumentalisation, faisant naître loyauté, et sentiment d'appartenance. Alors, ce qui pouvait apparaître comme un processus d'embauche exigeant, montre peut-être les contours d'un presque rite d'initiation. 

Cet élément, isolé de son contexte, peut paraître futile, anecdotique. Pourtant, remis dans son ensemble, il dresse un portrait des valeurs portées par l'entreprise, ce qu'on peut aussi appeler la culture d'entreprise. 

> « Organizational culture influences how people interact, how decisions are made (or avoided), the context within which cultural artifacts are created, employee attachment, the organization's competitive advantage, and the internal alignment of its units. »
> @OrganizationalCulture2025 []

Et c'est justement dans cette culture que s'inscrit le travail du développeur. Ainsi, pour comprendre la place du développeur dans l'entreprise, et donc au sein de la _Digital Factory_, il faut d'abord mettre en contexte cette culture d'entreprise : regarder comment l'entreprise décide, organise, et valorise ses collaborateurs.

# III. Consultant dans un groupe publicitaire au service d’un distributeur électrique

Si vous n'avez pas compris le titre, rassurez-vous, c'est tout à fait normal. Mon alternance m'a amené à travailler pour trois entreprises distinctes. D'abord, Publicis Groupe, c'est tout simplement la maison-mère de Publicis Sapient. Publicis Sapient, ou PS, est quant à elle une entreprise de conseil, ou plus précisément de _consulting_. Ses employés, eux, sont envoyés en mission chez des clients, parmi lesquels figure Sonepar, un distributeur électrique. Ainsi, pour comprendre la culture d'entreprise appliquée au sein de la _Digital Factory_, il faut d'abord comprendre ce qu'elle est dans ces différentes entités.

## III.1 Publicis Groupe

### III.1.a « Si vous attendez que les choses changent, elles changeront sans vous » : l'histoire de Publicis

L'histoire de Publicis est sans conteste un pilier fondateur du groupe. En effet, l'entreprise adopte un narratif au cœur des valeurs de l'entreprise. La figure de ce narratif est Marcel [Bleustein-Blanchet]{.smallcaps}, père fondateur de Publicis, et inventeur de la publicité selon ce récit. C'est lui qui aurait inventé la publicité en France dans les années 1920. Ainsi, en 1926, il fonde la société Publicis, « Publi » étant la publicité, « cis » étant son chiffre porte-bonheur.  
L'entreprise connaît une croissance remarquable, jusqu'en 1940, où son activité sera mise en pause le temps de la guerre. Cela n'empêchera pas l'homme qui a inventé la publicité de rouvrir quelques années après, redonnant un souffle de prospérité pour la marque.  
En 1975 opère un changement important pour Publicis : Maurice [Lévy]{.smallcaps} est nommé directeur général. L'entreprise ayant constitué un capital monétaire important va alors adopter une stratégie de rachat d'autres agences de publicité.  L'entreprise, alors devenue groupe, va entreprendre de nombreuses acquisitions qui n'auront de cesse d'étendre l'entreprise. Elle passera même outre atlantique, rachetant le réseau d'agences de publicité chicagois dénommé Leo Burnett.  
Il faut comprendre aujourd'hui que ce qui fait la renommée de l'entreprise, et ce qui constitue le mastodonte mondial qu'est Publicis, c'est ce mécanisme d'acquisition perpétuel encore de mise aujourd'hui. L'actuel président du groupe, Arthur [Sadoun]{.smallcaps} confirme lui-même cette dynamique dans cette interview accordée à AXA @CornerOffice [] : « The important is to be the only one […] making sure that what we build is unique ». C'est dans cette vision d'être l'unique acteur de marché, que Publicis continue ces acquisitions.
Dans les années 1990, Maurice [Lévy]{.smallcaps} entreprend un virage numérique important pour la marque : selon lui, c'est un domaine porteur dans lequel il est nécessaire d'investir. 

### III.1.b Aller au-delà de la publicité

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

## III.2 Publicis Sapient

Dans sa quête du marché numérique dans les années 2010, le groupe Publicis réalise un achat stratégique alors sans précédent : l'acquisition de l'entreprise américaine Sapient en octobre 2014, pour la modique somme de 3,7 milliards de dollars.

<!-- TODO: revoir NIGEL VAZ + LISE MALBERNARD -->
### III.2.a Un ancêtre au nom de « Sapient »

Pour comprendre l'origine de Publicis Sapient, il faut remonter à la fondation de Sapient aux États-Unis, en 1990. Jerry [Greenberg]{.smallcaps} et J. Stuart [Moore]{.smallcaps} entreprennent la fondation d'une entreprise de conseil, ou _consulting_ dans le numérique.

Contrairement à ce que ce nom suggère, une entreprise de conseil ne fait pas que… conseiller. Elle accompagne les organisations dans leurs choix stratégiques mais fournit aussi les moyens concrets de mettre en œuvre ses recommandations. Autrement dit, le livrable ne s’arrête pas à un rapport ou à une présentation : il s’accompagne de ressources humaines, techniques et organisationnelles permettant de traduire les orientations en actions réelles. Chez Publicis Sapient, ce sont parfois les mêmes consultants qui, après avoir conçu la stratégie, participent directement à son exécution aux côtés des équipes clientes.

C’est précisément ce qui fonde la spécificité de Publicis Sapient : son approche du **DBT, _Digital Business Transformation_**. Ce concept désigne un accompagnement global et intégré, allant de la vision stratégique jusqu’à la réalisation opérationnelle, avec un accent marqué sur le numérique. Les programmes de DBT s’appuient sur des équipes pluridisciplinaires – mêlant stratégie, design, ingénierie logicielle et exploitation de la donnée – organisées en **plateaux projets** ou en **feature teams**. Ces interventions s’inscrivent souvent dans la durée (18 mois à plusieurs années) et mobilisent des budgets conséquents, à la hauteur des transformations structurelles opérées.

### III.2.b À toute allure : le modèle SPEED

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
### III.2.c DBT : le modèle pour éviter un nouveau Kodak

Publicis Sapient évolue sur le marché très concurrentiel du conseil en transformation numérique, où les projets impliquent à la fois stratégie, conception, développement et déploiement opérationnel. Son positionnement repose sur l’approche intégrée du **Digital Business Transformation (DBT)**, qui combine conseil stratégique et exécution opérationnelle. Cette approche, reconnue pour sa rapidité et sa capacité à atteindre les objectifs ambitieux des clients, se distingue toutefois par un coût plus élevé que la moyenne du marché.

Parmi ses principaux concurrents figurent Accenture et Capgemini. Accenture est un leader mondial du conseil et des services technologiques, intervenant sur l’ensemble de la chaîne de transformation des entreprises, de la stratégie à l’intégration de systèmes et aux services gérés. L’entreprise est connue pour sa capacité à mobiliser des ressources globales sur des projets complexes et de grande envergure, offrant un positionnement similaire à Publicis Sapient en termes d’exécution intégrée, mais avec une couverture sectorielle et géographique plus étendue. Capgemini, de son côté, se distingue par son approche modulaire et adaptable, combinant conseil, design et technologie pour proposer des solutions sur mesure. Sa perception sur le marché met en avant une certaine flexibilité et compétitivité tarifaire, tout en restant capable de mener des projets de grande envergure.

Ces acteurs illustrent les standards du marché du conseil numérique : des prestations complètes mêlant stratégie, innovation digitale et mise en œuvre opérationnelle. Publicis Sapient se différencie par son ambition « disruptive » et sa rapidité d’exécution, ce qui attire des clients prêts à investir pour des transformations audacieuses, mais limite parfois son accessibilité pour des entreprises sensibles aux coûts.

<!-- TODO: absolument à revoir PHILIPPE DELPECH -->
## III.3 Sonepar

Sonepar, client majeur de Publicis Sapient, est un acteur incontournable de la distribution de matériel électrique à l’échelle mondiale. Contrairement à Publicis Sapient, dont l’activité est centrée sur le conseil et la transformation numérique, Sonepar opère sur un marché industriel et commercial concret : celui de la fourniture de produits électriques aux professionnels et aux entreprises. La collaboration entre les deux entités illustre parfaitement le lien entre un cabinet de conseil technologique et un client ayant besoin d’optimiser ses processus, sa logistique et son expérience digitale. Cette relation permet de comprendre comment les solutions stratégiques de Publicis Sapient sont appliquées dans un contexte opérationnel et sectoriel réel.

### III.3.a Une entreprise familiale française devenu monde

Fondée en 1969 par la famille Lamirand en France, Sonepar a rapidement étendu ses activités au-delà de l’Hexagone. Dans les années 1980 et 1990, le groupe a amorcé une stratégie d’internationalisation, notamment en Europe, avant de viser plus intensivement le marché nord-américain au cours des deux dernières décennies. Aujourd’hui, les États-Unis représentent un marché central pour le groupe, à l’image de la stratégie de Publicis sur ce continent : il s’agit d’un territoire où la croissance externe et l’implantation locale sont décisives pour asseoir son leadership. L’histoire de Sonepar se caractérise par une succession de rachats d’OpCos dans différents pays, permettant de consolider sa position tout en intégrant progressivement des structures locales dans un réseau global cohérent. Cette stratégie reflète un modèle de croissance par acquisition, similaire à celui de Publicis, où le développement organique se combine à des mouvements ciblés de consolidation.

### III.3.b Leader mondial de la distribution B2B de matériel électrique

Le cœur de métier de Sonepar est la distribution de matériel électrique et électronique pour les professionnels : équipements de câblage, systèmes d’installation, solutions domotiques et dispositifs de sécurité. Le groupe propose également des services numériques et logistiques, tels que des plateformes e-commerce, des outils de gestion des commandes et des solutions de suivi des stocks, afin d’accompagner ses clients dans la digitalisation de leurs achats et opérations. Cette combinaison de distribution traditionnelle et de services numériques fait de Sonepar un acteur hybride, capable de répondre aux exigences de rapidité et de traçabilité du marché.

La société se distingue par son rythme soutenu d’acquisitions, avec plusieurs entreprises intégrées chaque année dans divers pays. Cette dynamique lui permet de renforcer son maillage territorial et ses compétences sectorielles, mais elle soulève aussi des défis : l’intégration des filiales, l’harmonisation des pratiques et la standardisation des systèmes d’information peuvent générer des frictions, des coûts de transition et des risques opérationnels. De plus, bien que le groupe affiche une forte présence sur le marché américain, cette expansion rapide peut parfois créer une dépendance vis-à-vis des marchés étrangers, avec un impact direct sur la stratégie globale et la résilience financière du groupe.

### III.3.c Un groupe aux identités plurielles

L’organisation interne de Sonepar repose sur un modèle fédéral, où chaque filiale (_OpCo_) conserve une autonomie relative dans la gestion quotidienne tout en respectant les standards stratégiques et opérationnels du groupe. Cette structure permet de combiner flexibilité locale et efficacité globale, en harmonisant la finance, le numérique et la logistique, tout en conservant une proximité avec le client. Les OpCos sont regroupées sous des directions régionales, chacune supervisant la performance et la mise en œuvre des bonnes pratiques.

Au sein du groupe, des fonctions centrales pilotent les programmes transversaux : la transformation digitale, les systèmes d’information, la supply chain et le développement durable. Cette centralisation vise à standardiser certaines opérations et à maximiser les synergies entre les filiales, mais elle peut parfois entrer en tension avec l’autonomie locale et la réactivité opérationnelle. Enfin, la politique de croissance par acquisition implique une intégration continue de nouvelles structures, ce qui nécessite un équilibre constant entre consolidation des compétences et adaptation aux spécificités locales. Cette approche révèle à la fois la force et les limites du modèle Sonepar : efficace pour créer un réseau mondial dense et compétitif, mais exigeante en termes de coordination, de gouvernance et de coûts.

## III.4 Trois entreprises, trois cultures d'entreprise

### III.4.a Des collaborateurs aux identités multiples

Le statut de consultant confère une double identité, surtout quand le consultant participe à l'élaboration du livrable. Cette identité est d'autant plus complexe quand la maison-mère de l'entreprise de conseil développe elle aussi une identité forte.  
Dans cette identité de dimension trois, on a d'abord Publicis Groupe. Le groupe tend à créer un sentiment d'appartenance, d'unité. J'en ai moi-même fait l'expérience au cours de mon alternance : entre évènement organisé à l'Adidas Arena pour fédérer l'ensemble des agences, ou encore un sweat-shirt unique distribué à tous les collaborateurs de Publicis. On fait partie de cette grande famille qu'est Publicis.  
Mais le groupe Publicis ne pourrait exister sans ses composantes, dont fait partie Publicis Sapient. Là encore, une culture d'entreprise se distingue : je suis un Sapient. Cette identité fédère quant à elle sur les valeurs du consulting, et du numérique. On ne se sent pas communicants, mais acteurs du numérique. Là aussi, nous portons des marqueurs identitaires clairs : vocabulaire interne, méthodologie SPEED, organisation en capabilities, ou encore un discours permanent sur la « disruption » et le DBT. Ces éléments renforcent l'idée d'appartenir à une communauté de pratiques singulière, tournée vers l’innovation numérique et la transformation.
Enfin, nous travaillons chez le client, et même si je n’en ai fait l’expérience qu’une seule année, certains collaborateurs Sapient y restent plusieurs années, accentuant le flou de leur identité professionnelle. Dans ce cadre, on partage des locaux, des projets, et même parfois une partie de la culture du client. On peut finir par se sentir intégré à l’entreprise pour laquelle on est en mission, sans pourtant en être réellement salarié. Cette proximité crée une identité hybride, qui peut être constructive, en ayant une compréhension du client, renforçant un sentiment d’appartenance au projet ; tout en étant une source de confusion. Être à la fois un Publicis, un Sapient et « presque » un Sonepar, c’est jongler avec des repères multiples, créant ainsi un rapport à l'entreprise complexe.

### III.4.b Le développeur, une histoire de cols blancs ?

Historiquement, le métier de développeur dans le conseil numérique s’inscrit dans la catégorie des « cols blancs ». Il est associé à un savoir intellectuel, à une activité de bureau, souvent perçue comme hautement qualifiée et créatrice de valeur ajoutée. Le consultant-développeur ne produit pas un bien matériel tangible, mais façonne des solutions technologiques, des lignes de code, des architectures logicielles : autant d’éléments immatériels qui participent à la transformation des entreprises.  
Cependant, l’immersion prolongée dans les équipes clientes modifie cette perception. En participant à l’exécution opérationnelle des projets, le consultant endosse une posture plus « productive » que strictement stratégique. Il se rapproche ainsi de la figure du col bleu : engagé dans une activité concrète, répétitive parfois, où la valeur se mesure dans la réalisation effective plutôt que dans la seule conception. La routine des sprints agiles, le développement de fonctionnalités précises ou la résolution de bugs rapprochent symboliquement le consultant-développeur d’un rôle d’exécutant, au service d’un cahier des charges défini en amont.  
À l’inverse, d’autres éléments renforcent l’appartenance au monde des cols blancs. Le vocabulaire managérial omniprésent, la place accordée à la stratégie, l’exposition régulière aux directions clients ou aux comités de pilotage maintiennent le consultant-développeur dans une sphère intellectuelle. Même lorsqu’il exécute, il reste porteur d’une légitimité « experte » et d’un capital symbolique qui le distingue d’un simple producteur de tâches techniques. Cette tension illustre bien l’ambivalence identitaire du collaborateur Sapient : oscillant entre conception et exécution, entre posture intellectuelle et contribution pratique, entre col blanc et col bleu.

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

Dès les premiers jours, Carla a joué un rôle déterminant dans mon intégration. Son accueil chaleureux, sa disponibilité et sa capacité à mettre à l’aise ont été essentiels pour moi. Elle m’a guidé dans la découverte des rituels de l’équipe : les dailys, les refinements, les plannings, autant de moments où il fallait oser prendre la parole, exposer ses avancées ou ses blocages. Grâce à elle, j’ai pu progressivement dépasser ma timidité, comprendre le fonctionnement collectif et m’ouvrir aux autres. L’équipe Watts, par son écoute et sa bienveillance, m’a permis de transformer ce qui était un défi personnel en une véritable opportunité de croissance, humaine autant que professionnelle.

## Bilan de cette rentrée

# Rester SAFe pour collaborer

<!-- TODO: introduire la GDP -->

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
- Enfin, le _PI Planning_ donne le tempo global. Tous les 10 semaines, l’ensemble des équipes se réunit pendant deux jours pour définir la vision de l’incrément, planifier les dépendances et fixer les jalons. C’est la grande boussole collective.

## SAFe est un _framework_ agile ?

Malgré l'efficacité avérée du _framework_ SAFe, on peut tout de même se demander s'il reste fidèle aux principes Agiles. En effet, Agile tendais à l'effacement des processus rigides pour mettre en avant les individus et leurs interactions. Pourtant, SAFe, rien que par son nom, fixe un cadre travail. De facto, cette structuration introduit une forme de hiérarchie et de planification qui peut sembler contradictoire avec la souplesse originelle de l’Agile. Certains y voient une réinterprétation du manifeste Agile destinée à rassurer les grandes organisations, quitte à s’éloigner des valeurs initiales. SAFe est en plus devenu une valeur marchande : Publicis Sapient propose désormais des formations certifiantes à l’agilité SAFe, formations intégrées à leur offre commerciale.  
Cela transforme la méthodologie en un produit. Pratiques aux valeurs financières ou véritable capacité à améliorer la collaboration ? On peut se demander si SAFe sert encore les individus, ou si c'est un outil de standardisation et de contrôle au service des entreprises.

## L’esprit sous cadran et créativité à la chaîne

Malgré le contenu intellectuel et décisionnel que requièrent les rituels SAFe, la structuration rigoureuse des sprints, _program increments_ et autres cérémonies impose un rythme très codifié. Cette régularité crée une forme de routine qui rappelle, par certains aspects, le travail organisé et répétitif associé aux cols bleus, même si les développeurs restent mobilisés sur des tâches de réflexion et de conception typiques des cols blancs. SAFe illustre ainsi une hybridation : il combine la créativité et l’autonomie intellectuelle attendues dans le conseil et le numérique avec des logiques de coordination et de cadence qui s’apparentent à celles des environnements plus industriels. On y retrouve donc un paradoxe : un travail à la fois intellectuel et fortement structuré, oscillant entre liberté et standardisation.

<!-- TODO: revoir -->
# Storybook, Percy et Sample App : pourquoi et pour qui ?

Dans le cadre d’une _Digital Factory_, la qualité du code et de l’expérience utilisateur est au cœur des préoccupations. Pour y parvenir, nous avons mis en place une **stack technique dédiée à la conception, à la documentation et à la validation visuelle des composants**. Cette stack répond à deux besoins principaux : fournir aux équipes un environnement de développement cohérent et permettre aux clients internes de visualiser et tester les composants avant leur intégration. Elle se compose de **React, Web Components, Storybook, Percy et la Sample App**.

## React : le socle de nos composants

React est le framework choisi pour la création de composants réactifs et modulaires. Il permet de gérer facilement l’état, de structurer les interfaces et d’assurer une réutilisabilité maximale. Pour les développeurs, React offre un écosystème mature, une communauté active et des outils de debug performants. Pour les designers et chefs de projet, c’est la garantie que les composants livrés respectent le design system et peuvent évoluer sans risque de régressions fonctionnelles.

## Web Components : interopérabilité et standardisation

Parallèlement à React, certains composants sont développés en Web Components via Lit. Cette technologie assure **l’indépendance vis-à-vis du framework**, permettant d’intégrer ces composants dans différents projets, même non React. Les Web Components offrent également des standards web robustes, garantissant la compatibilité et la pérennité des composants. Cela répond à un besoin d’interopérabilité et de portabilité pour l’ensemble de l’organisation.

## Storybook : documenter et tester les composants

Storybook est l’outil central de **documentation et de développement isolé** des composants. Chaque composant est présenté dans un environnement dédié, avec ses différentes variantes (_stories_) et ses interactions possibles. Pour les développeurs, Storybook facilite le test, la débogue et le partage des composants. Pour les designers et Product Owners, il fournit un aperçu clair et accessible de l’UI, sans nécessité de lancer l’application complète.

## Percy : vérifier l’intégrité visuelle

Percy complète Storybook en offrant **une validation visuelle automatisée**. Chaque composant ou interface est comparé à une version de référence pour détecter toute régression visuelle. Cela permet de s’assurer que les changements n’altèrent pas le rendu attendu, garantissant la stabilité visuelle du design system et la confiance des équipes métier.

## Sample App : un terrain de démonstration

Enfin, la Sample App sert de **laboratoire pratique**, montrant les composants en situation réelle. Elle permet aux développeurs de vérifier l’intégration, aux designers de valider le rendu et aux Product Owners de se projeter dans l’expérience utilisateur finale. C’est un outil de communication et de validation, qui complète Storybook et Percy en offrant une perspective concrète du produit.

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

Dans le développement web, 

## La Sample App, pour tester en condition
→ travail de la sample App

## Créer des composants agnostiques
→ création de web components

## La mère de toutes mes démos
→ présentation démo

## Vers l'évolution du Design System
→ Innovation et initiative
→ Volt

# Quand j'ai perdu mes accès à Azure : l'équilibre de l'alternance
→ un équilibre à trouver
→ anecdote
→ un équilibre qui s'est trouvé être relativement bon cours / entreprise

# Bilan après 172 commits
→ Les livrables et réalisations effectuées à ce jour
→ difficultés
→ déménagement

# Le développeur n'est plus un col blanc

Le développeur dans une Digital Factory ne correspond plus exactement à l’image traditionnelle du col blanc. L’arrivée de l’intelligence artificielle a automatisé certaines tâches créatives ou techniques, réduisant la part de réflexion pure et accélérant le rythme de production. Les pratiques de suivi minutieux de la productivité, où chaque commit ou pull request est chronométré et analysé, introduisent une discipline qui rappelle les logiques tayloriennes. L’offshoring renforce cette standardisation, imposant des process stricts pour coordonner des équipes réparties sur plusieurs fuseaux horaires. La répétition des rituels, des sprints et des cérémonies SAFe accentue ce sentiment de cadence imposée, laissant peu de place à l’expérimentation individuelle. Le turnover élevé oblige enfin chaque nouveau collaborateur à intégrer rapidement des pratiques déjà établies, contribuant à la sensation d’un rythme subi plus que choisi.

# La _Digital Factory_ en bleu de travail ?

Pour autant, la Digital Factory n’est pas un atelier industriel au sens classique du terme. Des initiatives comme le Knowledge Exchange Day offrent des espaces où les développeurs peuvent partager des expériences, co-créer des solutions et échanger sur les pratiques. Ces moments introduisent de la flexibilité et de la créativité, rappelant que malgré le rythme soutenu et les rituels codifiés, le travail conserve une dimension intellectuelle et collaborative. La structure de la Digital Factory ne se réduit donc pas à une logique de répétition mécanique ; elle intègre aussi des pratiques qui favorisent l’apprentissage et l’innovation.

# La _Digital Factory_ n'est pas une question de col, mais de sweat à capuche

Au final, la distinction traditionnelle entre col blanc et col bleu perd beaucoup de son sens dans ce contexte. Ce qui définit le développeur dans une Digital Factory n’est pas tant la nature de ses tâches que son positionnement dans l’organisation, sa manière de collaborer et son intégration à la culture de l’équipe. L’identité professionnelle se construit à travers le rythme des projets, les interactions et les rituels partagés. Le symbole du sweat à capuche illustre parfaitement cette hybridation : un équilibre entre autonomie intellectuelle et structuration méthodique, entre réflexion et cadence imposée. La Digital Factory devient alors un espace où l’identité se joue moins sur le type de travail que sur la manière de l’habiter au quotidien.

# Doit-on fermer les yeux sur l'éthique pour apprendre ?

L’expérience dans la Digital Factory m’a confronté à des dilemmes que je n’avais jamais vraiment envisagés. Il serait trop simpliste de réduire la situation à un choix entre bien et mal. Sur le plan professionnel, cette immersion m’a permis d’apprendre énormément, tant sur le front-end que sur la gestion de projet numérique. J’ai découvert une passion sincère pour le développement front et pour les pratiques de la Digital Factory, et je n’aurais probablement jamais progressé aussi vite ailleurs. Les compétences acquises, les méthodologies assimilées et la pratique réelle sur des projets complexes constituent un apprentissage exceptionnel.

Pour autant, cette expérience m’a également révélé les limites de ce modèle. L’ouverture à l’open source, à l’échange en dehors des murs de l’entreprise, est restée restreinte. L’univers de Publicis, avec sa structure hiérarchique et ses enjeux commerciaux puissants, montre à quel point l’apprentissage peut parfois se faire au prix d’une exposition à des logiques de marché et de standardisation. J’ai fait de belles rencontres, et j’ai compris l’importance de travailler avec des équipes talentueuses, mais j’ai aussi pris conscience que je ne souhaite pas faire ce type de carrière toute ma vie.

Au-delà des compétences techniques et professionnelles, cette expérience m’a rappelé le besoin d’une dimension plus humaine dans mon travail. L’éthique, la proximité, le sens de la contribution et la liberté d’initiative sont des critères auxquels je ne peux pas renoncer. Apprendre intensivement dans un cadre aussi structuré est enrichissant, mais la réalisation personnelle et l’épanouissement passent par un équilibre qui dépasse la seule acquisition de savoir-faire. Fermer les yeux sur l’éthique pourrait ouvrir des opportunités d’apprentissage, mais à quel prix sur le plan humain et personnel ?

# Annexes

## A. Cahier des charges
## B. Documents techniques
## C. Glossaire
- **MMI** Métiers du Multimédia et de l'Internet. Formation universitaire réalisée au cours d'un BUT.
- **BUT** Bachelor Universitaire de Technologie. Diplôme de l’enseignement supérieur, obtenu après trois années d’études post-bac dans un IUT.
- **IUT** Institut Universitaire de Technologie. Composante d’une université délivrant le BUT.
- **navigateur**

## D. Quelques GIFs utilisés

# Bibliographie
::: {#refs}
:::
