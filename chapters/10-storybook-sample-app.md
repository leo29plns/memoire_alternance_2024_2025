\newpage

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
