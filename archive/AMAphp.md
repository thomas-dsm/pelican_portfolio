Title: AMAphp
Date: 2020-12-2 15:00
Modified: 2020-12-2 15:00
Category: amap
Tags: amap, publishing, 2lo, auvergne
Slug: amaphp
Authors: DA SILVA MENDONCA Thomas
Summary: présentation de l'application AMAphp

##AMAPHP

Cette situation professionnelle prend place dans le contexte AMAP. Dans ce cadre, nous travaillons pour le compte de la société 2lo. Le client est le réseau AMAP-Auvergne. 

![Amaphp](./theme/images/AMAphp.png)

La société de services 2lo est spécialisé dans le développement logiciel,, l'ingénierie réseau et l'hébergement web.

Son client : ici le réseau AMAP Auvergne
Basé sur des partenariats innovants et responsables entre paysans et consommateurs, le contrat AMAP est devenu un levier politique et citoyen pour qu'une autre dynamique agricole puisse exister à travers des circuits courts et des engagements environnementaux.
Le mouvement des AMAP représente une véritable opportunité pour l’agriculture régionale : le principe du contrat AMAP repose sur des principes de solidarité, de salaire décent pour les paysans partenaires, de transparence, de respect de l'environnement et de proximité. 

###Liste des paysans partenaires
![listecontat](./theme/images/listecontrat.png)
###Contrat en cours entre mangeurs et paysans partenaires
![listepaysans](./theme/images/listepaysans.png)

 Cette application est partagée sous une licence éducative propriétaire, afin de se prémunir d'un partage incontrôlé des versions modifiées.

L'étude de la base de données de l'application sert de support à un TP SQL pour la formation SLAM (Bloc 2 du référentiel).

Nous avons travailler afin à faire évoluer cette application dans le cadre de missions réalisées en AP (ateliers de professionnalisation) spécialisé SLAM (Solutions Logicielles et Applications Métiers)

Dans une première mission, au second semestre, nous devons résoudre des incidents déjà repérés sur la version 1a de l'application. Cette version de l'application repose sur une classe PDO pour l'accès aux données.

Dans une seconde mission, au troisième semestre, nous avons fait évoluer l'application à travers de plusieurs projets en parallèle. Le travaille a été réalisé à partir de la version 2c de l'application. 

![authentificationAmap](./theme/images/AMAphp2.png)

Cette itération repose notamment sur Doctrine DBAL et les symfony forms. Une couche de sécurité a été implémentée. Une authentification est désormais nécessaire pour accéder à une grande partie du contenu. Les autorisations sont réparties dans deux catégories : utilisateur et administrateur. 

