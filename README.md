Sydroy Rakotonomenjanahary
#300041897

# Devoir1

## Partie A [60 points]: Modèles E-R

### A1 [15 points]: Relations, cardinalité et participation

a) [5 points] Un étudiant peut être supervisé par plusieurs professeurs, et un professeur peut
superviser plusieurs étudiants. Un étudiant a un numéro d'étudiant, un nom et est inscrit dans
un programme spécifique. Un professeur a un numéro d'employé, nom et domaine d'expertise.

![Diagram1](https://github.com/Rjvsydroy/Devoir1/blob/main/diagram1.png?raw=true)

b) [5 points] Toutes les sections de cours doivent être affectées à un cours. Un cours a un code
de département (par exemple CSI ou SEG) et un numéro de cours (par exemple 2532 ou 4105).
Une section de cours est défini uniquement par le nom de la section (par exemple A ou B ou C),
semestre (par exemple hiver), l'année et le cours lui-même. Une section de cours dépend sur le
cours.

![Diagram2](https://github.com/Rjvsydroy/Devoir1/blob/main/diagram2.png?raw=true)

c) [5 points]
Une entreprise a un nom et un quartier général (spécifié par pays). Un conseil d'administration a
un président, un vice-président, et secrétaire (juste leurs noms). Une entreprise peut avoir au
plus un conseil administrateurs (mais il n'en a pas besoin). Tout les conseils d'administration
doivent avoir une et une seule entreprise à gérer.

![Diagram3](https://github.com/Rjvsydroy/Devoir1/blob/main/diagram3.png)

### A2 [30 points]: Conception du système

On vous demande de concevoir une base de données (à l'aide d'un diagramme relationnel)
CorporateBnB, une entreprise qui permet à toutes les personnes ayant un bureau à domicile de
fournir des espaces de réunion à d'autres. Tous les utilisateurs peut s'inscrire à ce service en
fournissant leur nom, email et numéro de téléphone. Un utilisateur peut gérer un espace de
bureau, ou peut louer un espace de bureau. Un bureau a un nom, une adresse et une superficie
totale (en pieds carrés). Chaque bureau a la disponibilité pour quand il peut être loué. La
disponibilité stocke la date et le coût quotidien pour l'utilisation, les heures d'arrivée et de départ
et si cette date est toujours disponible. Lorsqu'un utilisateur loue une propriété, on stock la date
d'arrivée et la date de départ.

Modélisez le système ci-dessus à l'aide d'un diagramme Entité-Relation. Vous devez inclure les
entités, les relations, la cardinalité, la participation et les attributs. Vous n'avez pas besoin de
spécifier les types d'attributs (c'est-à-dire le domaine).

### A3 [15 points]: Algèbre relationnelle

Écrivez des requêtes à l'aide de l'algèbre relationnelle pour les situations suivantes.
a) [7 points] Trouvez tous les espaces de bureau à Ottawa qui sont disponibles le 2 mars 2020.

b) [8 points] Trouvez tous les utilisateurs (nom et email) et les détails de la propriété (nom et
ville) et les informations de location (date et coût quotidien) de toutes les bureaux loués du mois
de janvier 2020.
