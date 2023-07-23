# PnamaSQL
exploration de données panama papers


Projets : 5 ans après, nouvelle enquête sur les Panama Papers
  
5 ans après, nouvelle enquête sur les Panama Papers
1. Introduction
Toujours comme hier pendant le cours OpenClassrooms (à relire si tu as un peu oublié), tu es dans la peau d'un journaliste d'investigation du Fronde qui doit ré-enquêter sur les Panama Papers. La revue pense qu'il faut re-sensibiliser le public aux découvertes faites en 2016.

A ce propos, le secrétaire de rédaction t'a retoqué hier ton article car selon lui, "il manque de données quantitatives et précises". Il te demande d'aller directement à la source de l'information, de reprendre toutes les données qui ont été rendues publiques à l'époque et de répondre à une longue liste de questions que se posent les lecteurs. Ces réponses pourront faire l'objet d'une infographie interactive, ce qui "plaira beaucoup plus aux lecteurs que ton histoire incompréhensible d'argent planqué".

2. Le projet
Télécharge la base de données ici et mets-toi dans la peau d'Hercule Poirot 🔎🔎

Voici la liste de questions auxquelles tu dois répondre :

Combien la base de données contient-elle de sociétés offshores différentes dont la source est "Panama Papers" ?
Quel intermédiaire a créé le plus de sociétés offshores ? A-t-on son adresse et son pays ?
Combien la base contient-elle de bénéficiaires avec un nom unique ? Quel est le bénéficiaire dont le nom revient le plus souvent ?
Donner la liste des juridictions avec le nombre d'entreprises offshores enregistrées sur chaque territoire, triée par ordre décroissant.
Regrouper les sociétés offshores par statut, et trier la liste par ordre décroissant.
Trouver la liste des bénéficiaires dont le nom contient "BNP" et ajouter, pour chaque bénéficiaire, le nom des sociétés offshores.
Trouver la liste des sociétés dont la juridiction est "France", "Monaco" ou "Réunion".
Trouver la liste des sociétés dont le pays de l'adresse et le pays de la juridiction sont différents.
Trouver la liste des bénéficiaires qui ont des sociétés au même nom et enregistrée à la même date, trier la liste par odre décroissant.
Donner la liste des intermédiaires qui ont aussi été bénéficiaires, en ajoutant leur nom de bénéficiaire et leur adresse.
Donner le top 10 des bénéficiaires qui ont le plus d'identités différentes (similar name and address) et le nombre d'identités correspondant.
Donner le top 10 des bénéficiaires qui ont le plus de parts toujours valides dans des entreprises offshores (dont la date de fin n'est pas encore passée).
Question bonus : réussir à retrouver dans la base au moins 3 personnalités que tu connais (indice) 😎😎😎
3. Rendu attendu
Un fichier .txt (ou .md) contenant les requêtes SQL qui permettent d'obtenir les infos demandées sur notre BDD.

4. Aller plus loin
Alors tu as aimé te prendre pour Sherlock Holmes pendant 3 heures ? Ca t'a plu de travailler sur de vraies données ? A l'époque, c'était assez novateur comme type de journalisme : c'est une des affaires qui a aidé les grandes rédactions à se tourner davantage vers la Data.
Si cela t'intéresse, voici 2 ressources qui t'en diront plus sur comment ça s'est passé dans la vie réelle :
un journaliste du Monde qui raconte les 9 mois passés à travailler sur cette base de données
un long mémoire dont la thématique était "Les “Panama Papers” marquent-ils l’émergence de pratiques professionnelles et journalistiques nouvelles ?". Tu peux faire des recherchers (Ctrl F) et checker les moments où l'auteur parle de data ou données. Tu verras que la data analyse n'a malheureusement pas été la compétence la plus répandue dans cette affaire ... En fait, si on avait créé la formation Data 5 ans plus tôt, t'aurais vraiment pu être ce journaliste star 😅😅
########################################################################################################################






Projets : Modéliser un système de BI
  
Modéliser un système de BI
1. Introduction
Pour concevoir un bon entrepôt de données, il faut bien comprendre le business concerné. On pourrait faire appel au Data Analyst pour réaliser la modélisation de la base ou pour vérifier que rien n'a été oublié. Avant que ça soit ton tour, profite de ce projet pour t'exercer et devenir un as de la modélisation de systèmes d'info décisionnels 🦁

2. Le projet
2.1. Un système d'info décisionnel pour votre université 🎓🎓
Maintenant que vous savez cruncher les classements mondiaux des universités, vous avez pu transmettre un reporting sur l'évolution des performances de votre Université. Depuis, les équipes veulent améliorer cette performance. Et pour cela, le recteur de l'Université de Strasbourg vous a demandé de mettre en place un système qui lui permettra de prendre des décisions éclairées.

En fait, il cherche à étudier les facteurs influant sur la réussite des candidats aux examens. Pour cela, on vous a chargé de construire un datawarehouse.

Il souhaite pouvoir répondre aux questions suivantes :

Quel est le nombre de réussites aux examens par cours, pour l’année 2020 ?
Quel est le nombre de réussites aux examens d’un cours obligatoire, pour l’année 2020 ?
Quel est le nombre de réussites aux examens par genre (féminin, masculin), entre 2019 et 2020 ?
Combien d’apprenants ayant un âge supérieur à 23 ans ont réussi leurs examens de « BI » ?
Quel est le nombre de réussites aux examens pendant le semestre d’hiver 2020 ?
Pour cela, vous disposez des données suivantes :
Pour chaque examen passé, on connaît l’âge et le genre de l’apprenant, le nom du cours (les cours peuvent être regroupés en cours obligatoire et cours à option), la date de l’examen, la note obtenue et si l’examen est réussi ou non.

Pour l'instant, il vous demande de réfléchir à la conception du système. Vos missions sont les suivantes :

Donner la table principale de l’entrepôt ainsi que les tables dimensions relatives.
Tracer le schéma en étoile dimensionnel.
2.2. Un système décisionnel pour étudier vos ventes 💰💰
Un ami à vous possède une entreprise qui revend du matériel informatique. Il vous demande de l'aider dans la gestion de ses ventes car il n'arrive pas vraiment à piloter son entreprise pour l'instant.

La seule chose dont il dispose est d'un fichier Access qui contient sa base de données.

Pour aider votre ami, vous allez utiliser le logiciel PowerBI Desktop(à télécharger ici). Vous avez choisi PowerBI car il possède une vue dédié à la modélisation : il est donc le logiciel le plus pratique pour modéliser des données.

Vous importez votre fichier sales.db, vous chargez toutes les tables.

😩😩 Que faire si j'ai un Mac et que je ne peux pas télécharger Power BI Desktop ?

PowerBI Desktop est un logiciel de data très répandu sur le marché donc je te conseille de trouver un PC dans ton entourage (à un moment ou un autre, pas obligé que ce soit aujourd'hui) et de te familiariser à son interfance.

En attendant, si tu n'as vraiment pas de PC et que tu ne veux pas t'ennuyer avec des tentatives de virtualisation, tu peux réaliser le projet avec un ERD classique.

Pour en savoir plus sur le fonctionnement de PowerBI, vous pouvez regarder cette vidéo ou la doc de Microsoft, en particulier un tutoriel spécifique à la conception de modèle de données.

Vos missions sont les suivantes :

Déterminer la table fait et les tables dimensions
Créer un modèle relationnel en Etoile
Créer un modèle relationnel en Flocon
Ajouter deux nouvelles mesures : Total_Sales, Total_Costs
Afficher les totaux des ventes par client et par date
Visualiser la moyenne des ventes par catégorie de produit
3. Rendu attendu
Un fichier .pdf contenant les schémas de l'exercice 1.
Un fichier .pbix contenant le schéma et les ajouts effectués sur vos tables de données pour l'exercice 2.
