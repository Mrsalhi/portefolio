checkpoint 4 - portefolio avec si possible mise en place des different projects via une bdd avec mise en place dun crud (create read update delete)
TABLES DE LA BASES DE DONNEES
USERS
CATEGORIES
WORKS

ID  int , primary key, auto increment
ID int, primary key, auto increment
ID int, primary key, auto increment
NAME varchar, 250, not null
NAME varchar, 250, not null
NAME varchar, 250, not null
PASSWORD varchar,250, not null
SLUG varchar, 250, not null
SLUG varchar, 250, not null
CONTENT longtext
CATEGORIES_ID  int, index
MLD
(modele logique des donnees)
CONTENU
1,1
1,1
0,n
N,0
USERS
CATEGORIES
WORKS

ID  int , primary key, auto increment
ID int, primary key, auto increment
ID int, primary key, auto increment
NAME varchar, 250, not null
NAME varchar, 250, not null
NAME varchar, 250, not null
PASSWORD varchar,250, not null
SLUG varchar, 250, not null
SLUG varchar, 250, not null
CONTENT longtext
CATEGORIES_ID  int, index
CHARTES GRAPHIQUES
COULEURS UTILISEES
#4DB169
#4A73B3
#787687
POLICES D ECRITURES EMPLOYES
ROBOTO, HELVETICA  OU AUTRES PAS ENCORE VRAIMENT DEFINI A VOIR AVEC L4AVANCEMENT DU PROJET
