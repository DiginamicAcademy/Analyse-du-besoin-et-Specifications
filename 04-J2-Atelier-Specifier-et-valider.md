[← Chapitre précédent](03-J2-Cours-Specifier.md) · [Sommaire](Readme.md) · [Chapitre suivant →](A-Projet-Brunel.md)

# Jour 2 · Atelier - Spécifier et valider

> **Jour 2, après-midi - 2 h 25 d'atelier, 45 min de soutenance et de bilan.** Vous transformez la note de cadrage du lot 2 d'hier en dossier de spécifications, en repartant des trois exercices du [cours du matin](03-J2-Cours-Specifier.md) ; vous le faites relire par l'autre équipe, qui a spécifié le même lot ; vous encaissez une demande de changement de Paul Brunel ; puis vous le soutenez.

## 🎯 Objectifs de l'atelier

À la fin de l'après-midi, votre équipe aura :

1. Rédigé les exigences fonctionnelles du projet, identifiées, priorisées, sans ambiguïté.
2. Détaillé les cas d'utilisation principaux, extensions comprises.
3. Formalisé les règles de gestion, dont au moins une en table de décision, et décrit les données de l'objet central.
4. Écrit des exigences non fonctionnelles mesurables, sécurité et données personnelles comprises.
5. Tracé chaque objectif jusqu'aux tests.
6. Fait relire sa spécification et intégré la revue ; analysé l'impact d'une demande de changement.
7. Soutenu son dossier de spécifications devant le groupe.

## Livrables attendus

Tout est rangé dans le dossier `specifications/` du dépôt d'équipe, ou dans la page `J2 - Spécifications` de l'espace partagé, en suivant le plan [B.14](B-Modeles-et-canevas.md).

| # | Livrable | Gabarit | Critère de réussite |
|---|---|---|---|
| 1 | Liste des exigences fonctionnelles | [B.8](B-Modeles-et-canevas.md) | au moins douze exigences ; chacune identifiée, rédigée avec un gabarit EARS, avec sa source et sa priorité MoSCoW ; au moins trois en "Si… alors" |
| 2 | Cas d'utilisation détaillés | B.9 | deux fiches complètes, dont celle du cas principal, en plus d'UC-14 repris de l'exercice 2 ; au moins quatre extensions chacune ; aucun élément d'interface dans le texte |
| 3 | Catalogue des règles de gestion | B.10 | au moins huit règles, avec exemples et source ; la table de décision de l'exercice 3, complétée et mise à jour avec les réponses du commanditaire |
| 4 | Dictionnaire de données | B.11 | l'objet central du projet : au moins dix données, avec format, règles et sensibilité |
| 5 | Exigences non fonctionnelles | B.12 | au moins six, couvrant au moins quatre caractéristiques de l'ISO/IEC 25010, chacune chiffrée ou vérifiable ; sécurité et données personnelles obligatoires |
| 6 | Matrice de traçabilité | B.13 | chaque objectif de la note de cadrage descend jusqu'à au moins un test ; aucune exigence orpheline |
| 7 | Revue croisée | B.15 | la grille remplie par l'autre équipe, et la réponse à chaque remarque : corrigée, refusée avec raison, ou mise en question ouverte |
| 8 | Analyse d'impact de la demande de changement | B.16 | les éléments touchés, identifiés par la matrice ; une estimation ; une recommandation au commanditaire |
| 9 | Dossier assemblé | B.14 | plan suivi, historique des versions tenu, questions ouvertes à jour ; version soutenue marquée `spec-v1.0` |

## Organisation

### Nouveaux rôles

Les rôles tournent : personne ne garde celui d'hier.

| Rôle | Responsabilité |
|---|---|
| Facilitateur·rice et gardien·ne du temps | fait avancer l'équipe, annonce les échéances, lance les mises en commun |
| Gardien·ne du dossier | tient le plan [B.14](B-Modeles-et-canevas.md), l'historique des versions, le registre des questions ; attribue les identifiants ; pose le tag `spec-v1.0` |
| Porte-parole | reçoit la demande de changement, ouvre et conclut la soutenance |

**Tout le monde prend la parole à la soutenance** : chacun·e y présente ce qu'il ou elle a rédigé.

### Le travail en trois pistes

Pour tenir dans le temps, l'équipe se répartit en trois pistes aux étapes 8 et 9, une par personne. Chaque piste suit un fil : celui ou celle qui écrit les cas d'utilisation en tire les tests, celui ou celle qui écrit les règles construit la matrice, celui ou celle qui décrit les données écrit les exigences de sécurité et de données personnelles.

| | Piste 1 - Cas d'utilisation | Piste 2 - Règles | Piste 3 - Données et qualités |
|---|---|---|---|
| **Étape 8** | les deux cas d'utilisation détaillés | le catalogue des règles de gestion, la table de décision | le dictionnaire de données, puis les premières exigences de données personnelles |
| **Étape 9** | les tests : un par exigence, tirés des extensions et des exemples des règles | la matrice de traçabilité, la chasse aux orphelins | les exigences non fonctionnelles |

Les trois pistes partagent **le même glossaire et les mêmes identifiants**. Une règle de gestion découverte en écrivant un cas d'utilisation est annoncée à la piste 2, qui lui donne son numéro : un seul catalogue, une seule numérotation. Une donnée nouvelle est annoncée à la piste 3.

> **Dans une équipe de quatre**, deux personnes prennent la piste 1 : un cas d'utilisation chacune.

## Déroulé

| Horaire | Étape | Durée |
|---|---|---|
| 13:30 | Lancement : retours d'hier, rôles, pistes | 5 min |
| 13:35 | Étape 7 - Les exigences fonctionnelles | 25 min |
| 14:00 | Étape 8 - En trois pistes : cas d'utilisation · règles et table de décision · données | 35 min |
| 14:35 | Pause | 10 min |
| 14:45 | Étape 9 - En trois pistes : tests · traçabilité · exigences non fonctionnelles | 25 min |
| 15:10 | Étape 10 - La revue croisée | 25 min |
| 15:35 | Étape 11 - La demande de changement | 10 min |
| 15:45 | Préparation de la soutenance | 10 min |
| 15:55 | Soutenance | 35 min |
| 16:30 | Bilan du module | 10 min |

> **Si la matinée a laissé de la marge**, commencez l'étape 7 avant le déjeuner. C'est l'étape qui profite le plus d'un peu de temps en plus, et elle conditionne toutes les autres.

---

## Lancement (5 min)

Relisez les retours "je me demande" et "je propose" de la restitution d'hier. Pour chacun : qu'en faites-vous ? Notez la réponse dans le journal de décisions. Si le commanditaire a tranché des questions ouvertes depuis hier, reportez ses réponses dans le registre.

## Étape 7 - Les exigences fonctionnelles (25 min)

Toute l'équipe, à partir de la liste brute des besoins de la note de cadrage, et des six réécritures de l'exercice 1 du matin.

1. **Découpez en domaines** : trois à cinq regroupements cohérents - pour le lot 2, par exemple "interventions", "équipes", "menuiseries", "information" ; le lot 1 avait "demandes", "planning", "paie". Rangez-y d'abord les exigences de l'exercice 1. Chaque domaine a son préfixe d'identifiant. (3 min)
2. **Répartissez les domaines**, un ou deux par personne, et rédigez les exigences avec le gabarit [B.8](B-Modeles-et-canevas.md) et les gabarits EARS : identifiant, énoncé, source, priorité MoSCoW. Chaque besoin brut donne une ou plusieurs exigences ; chaque besoin de base identifié hier en donne au moins une. (15 min)
3. **Relisez-vous en croisé** au sein de l'équipe, avec la liste des mots pièges du cours : un mot piège trouvé, une exigence réécrite. Vérifiez que chaque terme employé est dans le glossaire. (7 min)

> **Attention :** chaque fois que vous hésitez sur ce que le système doit faire, c'est une **question ouverte**, pas une exigence à inventer. Notez-la dans le registre, avec la personne à qui la poser, et écrivez l'exigence avec l'hypothèse la plus prudente, marquée comme telle.

## Étape 8 - En trois pistes (35 min)

### Piste 1 - Les cas d'utilisation détaillés

Avec le gabarit [B.9](B-Modeles-et-canevas.md) :

1. Choisissez, avec l'équipe, **les deux cas d'utilisation** les plus importants : celui qui porte l'objectif principal, et celui où les règles sont les plus nombreuses. UC-14 "Reporter une intervention", de l'exercice 2, est déjà écrit : rangez-le dans le dossier, mettez ses renvois aux règles à jour, et choisissez-en deux autres.
2. Pour chacun : acteurs, objectif, déclencheur, préconditions, garanties, puis le **scénario nominal**, en cinq à neuf étapes.
3. Puis les **extensions** : à chaque étape où le système vérifie, calcule ou attend quelque chose, demandez "Et si… ?". Au moins quatre par cas.
4. Renvoyez aux règles de gestion par leur identifiant, au lieu de les recopier. Une règle manque ? Annoncez-la à la piste 2.

Commencez par le cas principal, et terminez-le avant d'ouvrir le second.

### Piste 2 - Les règles et la table de décision

Avec le gabarit B.10 :

1. **Mettez au propre le catalogue des règles** à partir de l'exercice 2 d'hier et de l'analyse des pièces jointes : identifiant, nom, énoncé, exceptions, **exemples chiffrés**, source, paramètres. Au moins huit règles. Les lignes du tableau blanc font d'excellents exemples.
2. **Reprenez la table de décision de l'exercice 3**, et mettez-la à jour avec ce que le commanditaire a tranché. Complétez-la avec ce qu'elle ne couvre pas encore : le véhicule et le permis C1, les absences accordées du lot 1. Toutes les combinaisons sont examinées ; celles qui posent question vont au registre.

### Piste 3 - Les données

Avec les gabarits B.11 et B.12 :

1. **Décrivez les données de l'objet central** du lot 2 - l'intervention - dans le dictionnaire : au moins dix données, avec leur format, leurs valeurs, leurs règles, et leur sensibilité. Relisez le tableau blanc : il en contient la plupart des colonnes, et, dans ses remarques, une information qui demande une protection particulière.
2. Pour chaque donnée personnelle ou sensible, **écrivez déjà l'exigence** qui la protège : qui la voit, qui la modifie, combien de temps on la garde - ou la question ouverte, si la décision n'appartient pas à l'équipe.

### Mise en commun (incluse dans l'étape 8, 5 dernières minutes)

Chaque piste présente aux deux autres ce qu'elle a produit, en une minute et demie. Vérifiez que les cas d'utilisation citent les bonnes règles, que les règles emploient les données du dictionnaire, et que le dictionnaire couvre ce que les cas d'utilisation manipulent.

## Pause (10 min)

## Étape 9 - En trois pistes (25 min)

### Piste 1 - Les tests

Avec la colonne "Tests" du gabarit B.13 :

1. **Un test au moins par exigence fonctionnelle** - un identifiant et un intitulé suffisent : "T-SOL-03 : solde insuffisant de 0,5 jour, dépôt refusé".
2. Puisez dans **les extensions** de vos cas d'utilisation, et dans **les exemples** des règles de la piste 2 : chaque exemple chiffré est déjà un test.
3. Donnez la liste au fur et à mesure à la piste 2, qui les place dans la matrice.

### Piste 2 - La matrice de traçabilité

Avec le gabarit B.13 :

1. Une ligne par **objectif** de la note de cadrage, puis les besoins qui le servent, les exigences et règles qui y répondent, les cas d'utilisation, et les tests de la piste 1.
2. **Cherchez les orphelins** : une exigence qui ne remonte à rien, un objectif qui ne descend vers rien, une exigence sans test. Pour chacun : on le supprime, on le relie, ou on le signale.

### Piste 3 - Les exigences non fonctionnelles

Avec le gabarit [B.12](B-Modeles-et-canevas.md) :

1. **Parcourez les neuf caractéristiques** de l'ISO/IEC 25010. Pour chacune : une exigence, ou "sans objet", avec une raison.
2. Chaque exigence est **chiffrée** - un seuil, une condition de mesure - ou **vérifiable** par un audit ou un test précis.
3. **Sécurité et données personnelles sont obligatoires** : reprenez et complétez les exigences commencées à l'étape 8.
4. Si le commanditaire a pris des **engagements** envers ses clients - l'information du client cinq jours ouvrés avant la pose, par exemple -, ils deviennent ici des exigences mesurables.

Pendant ce temps, le ou la gardien·ne du dossier vérifie que le plan [B.14](B-Modeles-et-canevas.md) est suivi et passe l'historique à `0.1 - premier jet`.

## Étape 10 - La revue croisée (25 min)

Les deux équipes échangent leurs dossiers. Vous connaissez le projet aussi bien que l'autre équipe : vous saurez repérer ce qu'elle a oublié, et ce qu'elle a vu et pas vous.

1. **Comparez vos deux notes de cadrage**, tous les trois : les objectifs, le périmètre, le glossaire. Notez chaque écart : c'est souvent là que la spécification de l'une des deux est fragile. (3 min)
2. **Relisez son dossier** avec la grille [B.15](B-Modeles-et-canevas.md), chacun·e la partie qui correspond à sa piste - les cas d'utilisation, les règles, les données et les exigences non fonctionnelles -, et les exigences fonctionnelles réparties entre vous trois. Cherchez les défauts de forme - ambiguïtés, mots pièges, exigences non vérifiables ou non singulières, termes absents du glossaire, identifiants manquants - puis de fond : une règle sans exemple, une extension évidente oubliée, une exigence non fonctionnelle sans chiffre. **Au moins trois remarques par personne**, chacune rattachée à un identifiant. Si vous travaillez dans un dépôt, faites-le en commentaires de *pull request*. (12 min)
3. **Récupérez votre dossier** et traitez chaque remarque reçue : corrigée, refusée avec une raison, ou transformée en question ouverte. Mettez à jour l'historique des versions : `0.2 - revue croisée`. (10 min)

> **Une bonne revue est précise et impersonnelle.** "EF-RES-04 : *rapidement* n'est pas vérifiable" aide l'autre équipe ; "c'est flou" ne l'aide pas. On commente le texte, jamais les personnes.

## Étape 11 - La demande de changement (10 min)

À 15:35, Paul Brunel remet au ou à la porte-parole de chaque équipe la même **demande de changement**. C'est un vrai changement, comme il en arrive dans tous les projets : il ne remet pas en cause votre travail, il le met à l'épreuve.

Avec le gabarit [B.16](B-Modeles-et-canevas.md) :

1. **Analysez l'impact** à l'aide de votre matrice de traçabilité : quels objectifs, exigences, règles, données, cas d'utilisation et tests sont touchés ? Y a-t-il des éléments nouveaux à créer ? (6 min)
2. **Estimez** grossièrement l'effort - faible, moyen, fort - et les risques. **Recommandez** une décision au commanditaire : accepter, accepter en partie, reporter, refuser ; avec sa raison. (4 min)

Ne modifiez pas encore la spécification : c'est au commanditaire de décider. Vous présenterez votre analyse à la soutenance.

## Préparer la soutenance (10 min)

Une soutenance de **dix minutes**, suivie de **six minutes de questions**. Montrez le dossier, pas un diaporama : on doit voir les vrais tableaux. Répartissez les sept points entre vous trois : le ou la porte-parole prend les points 1, 2 et 7, et chaque piste présente ce qu'elle a rédigé - la règle (piste 2), le cas d'utilisation et la revue (piste 1), la sécurité et les données personnelles (piste 3).

1. **Le problème et l'objectif principal**, en une minute : la demande, ce que vous avez compris, l'indicateur.
2. **Le périmètre** : une exclusion importante, et pourquoi.
3. **Une règle de gestion** : son énoncé, sa table de décision, et le test qui la vérifie.
4. **Un cas d'utilisation** : son scénario nominal en trente secondes, puis l'extension la plus intéressante.
5. **La sécurité et les données personnelles** : qui voit quoi, et ce que vous n'avez pas le droit de décider seuls.
6. **La revue** : la remarque qui vous a le plus fait progresser.
7. **La demande de changement** : son impact, et votre recommandation.

Avant de soutenir, marquez la version : un tag `spec-v1.0` dans le dépôt, ou une version nommée dans le document partagé.

## Soutenance (35 min)

Deux soutenances de seize minutes, et trois minutes pour changer d'équipe. Le formateur évalue avec la grille [B.18](B-Modeles-et-canevas.md). L'équipe qui écoute note ses retours avec la grille [B.17](B-Modeles-et-canevas.md), et **chacun·e de ses membres pose une question** : elle a spécifié le même lot et relu ce dossier pendant la revue croisée, elle sait où chercher. Après les deux soutenances, Paul Brunel annonce sa décision sur la demande de changement : comparez-la à vos deux recommandations. Les meilleures questions sont celles qu'un jury poserait : "Pourquoi cette règle ?", "Comment le testerez-vous ?", "Qui a décidé de ça ?"

## Bilan du module (10 min)

Chacun·e répond, pour soi, à trois questions : qu'est-ce que je ferai **systématiquement** au début de mon prochain projet ? Quelle technique m'a le plus surpris·e ? Quelle partie de ce dossier vais-je reprendre dans mon dossier de projet ? Le formateur conclut par **trois enseignements** de la session.

---

## Critères de réussite

- [ ] Chaque exigence a un identifiant, une source et une priorité ; aucune ne contient de mot piège.
- [ ] Les exigences "Si… alors" couvrent les principaux cas d'erreur.
- [ ] Les cas d'utilisation ne contiennent aucun élément d'interface, et renvoient aux règles par leur identifiant.
- [ ] Chaque règle de gestion a au moins un exemple chiffré.
- [ ] La table de décision examine toutes les combinaisons ; les combinaisons douteuses sont des questions ouvertes.
- [ ] Le dictionnaire signale les données personnelles et les données sensibles.
- [ ] Chaque exigence non fonctionnelle est chiffrée ou vérifiable ; sécurité et données personnelles sont couvertes.
- [ ] La matrice ne contient ni exigence orpheline, ni objectif sans test.
- [ ] Chaque remarque de la revue a reçu une réponse.
- [ ] L'analyse d'impact s'appuie sur la matrice, et aboutit à une recommandation argumentée.
- [ ] L'historique des versions est tenu ; la version soutenue est marquée.

## Pièges fréquents

| Piège | Comment l'éviter |
|---|---|
| Écrire des exigences de solution : "une base de données", "une page d'accueil" | dire ce que le système fait, pas comment il est construit ; une contrainte réelle s'écrit comme contrainte, avec sa source |
| Inventer les réponses aux questions ouvertes | une hypothèse prudente, marquée comme telle, et une question dans le registre |
| Recopier les règles dans les cas d'utilisation | un renvoi par identifiant ; la règle vit à un seul endroit |
| Des règles sans exemples | l'exemple est ce qui lève l'ambiguïté et deviendra le test |
| Des exigences non fonctionnelles génériques | "sécurisé", "performant" : quel seuil, mesuré comment, pour qui ? |
| Des données sensibles traitées comme les autres | les repérer, restreindre l'accès, poser la question de la durée de conservation |
| Se défendre pendant la revue | noter, répondre par écrit, décider après |
| Modifier la spécification dès la demande de changement | analyser, estimer, recommander ; le commanditaire décide |

## Si vous avez fini en avance

- Écrivez les **scénarios Gherkin** de la règle de votre table de décision : un par colonne de la table, et un cas limite.
- Ajoutez un troisième **cas d'utilisation détaillé** : celui d'un acteur qui n'est pas l'usager principal - le gestionnaire, le valideur, l'administrateur.
- Rédigez le **courriel** au commanditaire qui accompagne la version `spec-v1.0` : ce qui a été fait, ce qui doit être validé, les questions ouvertes à trancher avant le développement, et votre recommandation sur la demande de changement.

---

[← Chapitre précédent](03-J2-Cours-Specifier.md) · [Sommaire](Readme.md) · [Chapitre suivant →](A-Projet-Brunel.md)
