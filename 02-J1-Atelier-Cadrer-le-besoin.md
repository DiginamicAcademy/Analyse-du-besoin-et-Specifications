[← Chapitre précédent](01-J1-Cours-Analyser-le-besoin.md) · [Sommaire](Readme.md) · [Chapitre suivant →](03-J2-Cours-Specifier.md)

# Jour 1 · Atelier - Cadrer le besoin

> **Jour 1, après-midi - 2 h 25 d'atelier, 30 min de restitution et de bilan.** Vous cadrez entièrement le **lot 2 du projet Brunel**, le planning des chantiers de pose ([annexe A](A-Projet-Brunel.md)), en repartant des trois exercices du [cours du matin](01-J1-Cours-Analyser-le-besoin.md) : retrouver le problème derrière la demande, et poser le cadre dans lequel vous spécifierez demain.

## 🎯 Objectifs de l'atelier

À la fin de l'après-midi, votre équipe aura :

1. Distingué, dans le dossier du lot 2, ce qu'elle sait, ce qu'elle suppose et ce qu'elle ignore, et interrogé le commanditaire.
2. Extrait des pièces jointes les données, les règles et les questions qu'elles contiennent, et relevé leurs contradictions.
3. Formulé le problème réel et des objectifs mesurables.
4. Délimité le périmètre, et listé les contraintes, les hypothèses et les risques.
5. Construit le glossaire métier du projet.
6. Assemblé une note de cadrage, prête à servir de base aux spécifications.

## Livrables attendus

Tout est rangé dans le dossier `cadrage/` du dépôt d'équipe, ou dans la page `J1 - Cadrage` de l'espace partagé. Les supports papier sont photographiés et ajoutés.

| # | Livrable | Gabarit | Critère de réussite |
|---|---|---|---|
| 1 | Tri "ce qu'on sait / ce qu'on suppose / ce qu'on ignore" | [B.1](B-Modeles-et-canevas.md) | au moins cinq hypothèses identifiées comme telles ; les questions pour le commanditaire en découlent |
| 2 | Compte rendu de l'entretien avec le commanditaire | B.2 | ses objectifs, ses contraintes, sa définition du succès ; les réponses reformulées ; ce qui reste ouvert |
| 3 | Analyse des pièces jointes | B.3 | les quatre pièces analysées, en partant de l'exercice 2 ; chaque écart entre le tableau blanc et les consignes de pose relevé |
| 4 | Énoncé du problème, bête à cornes, objectifs | B.4 | un problème sans solution dedans ; trois objectifs SMART, avec leur valeur de départ |
| 5 | Périmètre, contraintes, hypothèses, risques | B.5 | trois colonnes de périmètre, dont au moins quatre exclusions ; contraintes réglementaires comprises ; trois risques avec leur réponse |
| 6 | Glossaire métier | B.6 | au moins dix termes définis, dont les trois de l'exercice 3 et au moins trois autres ambiguïtés levées |
| 7 | Note de cadrage | B.7 | les livrables 2 à 6 assemblés, avec la liste brute des besoins et le registre des questions ouvertes |
| 8 | Première entrée du journal de décisions | B.1 | les décisions du jour, leur raison, leur auteur |

## Organisation

### Un projet, deux équipes

- **Deux équipes de trois**, sur le **même lot** et avec le **même commanditaire**. Chaque équipe produit **son propre dossier**.
- **Ce qui se fait à six** : la liste des questions, l'entretien avec le commanditaire, le point de l'étape 6, la restitution. À six, on forme un seul groupe, pas deux équipes face à face : tout le monde pose au moins une question, et tout le monde entend les mêmes réponses.
- **Ce qui se fait chacun de son côté** : tout le reste. Deux équipes qui partent des mêmes faits ne prennent pas les mêmes décisions - un périmètre, une définition, un objectif. Ces écarts seront comparés à la restitution, puis à la revue croisée de demain.
- Les **corrections des exercices du matin** sont votre base commune. Vous pouvez les reprendre telles quelles, les corriger, ou les contredire : dites-le dans le journal de décisions.

### Les rôles, tournants

Trois rôles, un par personne. Ils changent de main demain, et encore pendant la soutenance : tout le monde y prendra la parole.

| Rôle | Responsabilité |
|---|---|
| Facilitateur·rice et gardien·ne du temps | fait avancer l'équipe d'étape en étape, distribue la parole, annonce les échéances, coupe les débats qui s'enlisent et les note dans le registre des questions |
| Scribe | tient le dépôt ou l'espace d'équipe, et le journal de décisions ; note l'entretien mot pour mot |
| Porte-parole | veille à ce que les questions de l'équipe figurent dans la liste commune, puis mène la restitution |

Un rôle n'est pas un métier : tout le monde lit, analyse et rédige. Le rôle dit seulement qui veille à quoi.

### Le dépôt d'équipe

Si votre équipe le peut, ouvrez dès maintenant un **dépôt Git** d'équipe, avec un fichier Markdown par livrable :

```text
README.md                 le projet, l'équipe
journal.md                journal de décisions et registre des questions ouvertes
cadrage/
  entretien.md            compte rendu de l'entretien avec le commanditaire
  analyse-documentaire.md
  note-de-cadrage.md      problème, objectifs, périmètre, contraintes, risques
  glossaire.md
specifications/           demain
```

Demain, ce dépôt accueillera les spécifications, la revue croisée se fera en *pull request*, et la version soutenue sera marquée d'un tag. Sinon, un document partagé fait l'affaire, à condition d'en activer l'historique des versions.

## Déroulé

| Horaire | Étape | Durée |
|---|---|---|
| 13:30 | Lancement : équipes, rôles, dépôt | 10 min |
| 13:40 | Étape 1 - Préparer l'entretien | 25 min |
| 14:05 | Étape 2 - L'entretien avec Paul Brunel | 25 min |
| 14:30 | Étape 3 - Le problème et les objectifs | 15 min |
| 14:45 | Pause | 10 min |
| 14:55 | Étape 4 - Le périmètre, les contraintes, les hypothèses, les risques | 20 min |
| 15:15 | Étape 5 - Le glossaire | 10 min |
| 15:25 | Étape 6 - Les besoins, le point avec Paul Brunel, la note de cadrage | 20 min |
| 15:45 | Préparation de la restitution | 10 min |
| 15:55 | Restitution | 20 min |
| 16:15 | Bilan de la journée | 10 min |

Le formateur joue **Paul Brunel**, le commanditaire. Il rencontre **les six ensemble**, deux fois : pour un entretien de vingt minutes à l'étape 2, et pour un point de sept minutes à l'étape 6. Ce sont les deux seules occasions de l'interroger aujourd'hui. Il répond à ce qu'on lui demande, défend sa demande initiale, et ne révèle que ce qu'une bonne question va chercher.

> **Si la matinée a laissé de la marge**, commencez l'étape 1 avant le déjeuner : lisez le dossier complet du lot 2. Vous gagnerez du temps pour le tableau blanc, qui en mérite.

---

## Comment lire les étapes

Chaque étape dit :

- **ce que vous produisez** : un fichier, ou une partie de fichier, avec son gabarit de l'annexe B ;
- **ce que vous faites**, en actions courtes et minutées ;
- **un exemple**, qui montre la forme attendue. Les exemples portent sur le **lot 1**, les absences, déjà traité dans le cours : à vous de faire la même chose pour le **lot 2**. Ne recopiez pas leur contenu.

---

## Étape 1 - Préparer l'entretien (25 min)

**Vous produisez :** `cadrage/analyse-documentaire.md` (gabarit [B.3](B-Modeles-et-canevas.md)), le tri dans `journal.md` (gabarit [B.1](B-Modeles-et-canevas.md)), et **la liste commune des questions**, écrite à six.

1. **Relisez les corrections des trois exercices du matin.** Notez ce que vous gardez, et ce qui vous gêne. (4 min)
2. **Lisez l'[annexe A](A-Projet-Brunel.md) en silence**, stylo en main. Soulignez les chiffres. Entourez les solutions. Mettez un "?" sur ce qui n'est pas clair. (6 min)
3. **Analysez les pièces jointes, une par personne.** (8 min)
   - Personne 1 : les articles 2 et 3 des consignes de pose (pièce jointe 2).
   - Personne 2 : le tableau blanc (pièce jointe 3). Comparez chaque ligne aux six articles. Chaque écart est une règle enfreinte, une donnée qui manque, ou une question.
   - Personne 3 : le courriel et les verbatims (pièces jointes 1 et 4). Cherchez ce qui se contredit.
4. **Triez en trois listes** : ce qu'on sait, ce qu'on suppose, ce qu'on ignore. Écrivez **six questions** pour Paul Brunel : une sur ses objectifs, une sur ce qui ne doit pas arriver, une sur une exception, une sur un chiffre qui manque, une sur une contradiction, une libre. (3 min)
5. **À six, faites une seule liste de questions.** Mettez vos douze questions au tableau. Supprimez les doublons. Rangez-les dans l'ordre où vous les poserez : les objectifs d'abord, les détails ensuite. Écrivez à côté de chaque question le prénom de qui la pose : **chacun·e pose au moins une question**. (4 min)

**Exemple (lot 1)**

```markdown
# Analyse documentaire

## Règlement intérieur, article 12
| Ce qu'on lit | Type | Ce qu'on en tire |
|---|---|---|
| "au moins quinze jours avant" | règle | RG-03 : délai de prévenance |
| "le responsable accorde" | acteur, étape | qui accorde quand le responsable est absent ? |
| "sauf événement familial" | exception | quels événements ? liste à demander |

# Journal - tri et questions

## On sait
- Environ 400 demandes d'absence par an, la moitié en mars-avril.
## On suppose
- Tous les poseurs ont un smartphone.
## On ignore
- Le format d'import du logiciel de paie.

## Questions pour Paul Brunel - liste commune des six
| # | Question | Type | Qui la pose |
|---|---|---|---|
| 1 | Dans un an, qu'est-ce qui vous ferait dire que c'est réussi ? | objectif | Inès |
| 2 | Qu'est-ce qui ne doit surtout pas arriver ? | à éviter | Hugo |
| 3 | Qui accorde une absence quand le responsable est lui-même absent ? | exception | Sarah |
| 4 | Combien de demandes refusez-vous par an ? | chiffre | Malik |
| 5 | Le règlement dit quinze jours, Sandrine dit qu'elle accepte huit : qui a raison ? | contradiction | Chloé |
| 6 | Les intérimaires sont-ils concernés ? | libre | Tom |
```

> **Attention :** ne demandez pas à Paul Brunel comment il voit son écran ou son GPS. Demandez-lui **ce que ça doit changer** : "Le GPS, il vous aurait servi à quoi, la semaine dernière ?"

## Étape 2 - L'entretien avec Paul Brunel (25 min)

**Vous produisez :** `cadrage/entretien.md` (gabarit [B.2](B-Modeles-et-canevas.md)).

1. **L'entretien dure 20 minutes. Les six sont ensemble, autour d'une même table, avec Paul Brunel.** Ce n'est pas deux équipes face à face : c'est un seul groupe qui mène un seul entretien.
2. **Les questions suivent la liste commune.** Chacun·e pose la sienne quand son tour arrive. Une des deux personnes chargées du temps tient la liste et annonce la question suivante.
3. **Tout le monde peut relancer**, à tout moment : "Combien ?", "Et si… ?", "Un exemple ?". Une bonne relance vaut mieux que la question suivante. "Vous avez dit que l'atelier, c'est une autre histoire : que se passe-t-il quand Karim dit que c'est prêt, et que ça ne l'est pas ?"
4. **Reformulez au moins deux réponses** : "Si je comprends bien, …". Notez s'il valide.
5. **Les deux scribes notent mot pour mot**, chacun·e pour son équipe.
6. **Le compte rendu se fait en 5 minutes, chaque équipe de son côté.** Séparez ce qu'il a dit de ce que vous avez compris. Vous avez entendu les mêmes réponses : vous ne les comprendrez pas forcément de la même façon.

**Exemple (lot 1)**

```markdown
# Entretien avec Paul Brunel - [date], 14:05

## Ce qu'il a dit
- "Les congés, c'est Sandrine qui sait. Moi, je ne veux plus de chantier sans équipe."
- "Quatre chantiers l'an dernier. Dont un chez notre plus gros client."

## Ce que nous avons compris (reformulations validées)
- Son vrai souci n'est pas le formulaire : c'est que le planning ignore les absences.
  Validé : "Oui, c'est exactement ça."

## Règles et exemples recueillis
- Deux absents dans une équipe de fabrication : c'est lui qui décide.

## Décisions prises en séance
- Les intérimaires sont hors périmètre.

## Questions restées ouvertes
- Q-04 : qui remplace un responsable absent ? À poser à Sandrine.
```

## Étape 3 - Le problème et les objectifs (15 min)

**Vous produisez :** les parties "Problème" et "Objectifs" de `cadrage/note-de-cadrage.md` (gabarit [B.4](B-Modeles-et-canevas.md)).

1. **Réécrivez l'énoncé du problème** de l'exercice 1, avec ce que l'entretien et le tableau blanc vous ont appris. Chiffrez les conséquences. Relisez : s'il contient "écran", "application" ou "GPS", il contient une solution. (6 min)
2. **Remplissez la bête à cornes** : à qui l'outil rend-il service ? Sur quoi agit-il ? Dans quel but ? (3 min)
3. **Écrivez trois objectifs SMART** : un indicateur, une valeur de départ, une cible, une échéance. Si la valeur de départ manque, ajoutez une question au registre. (6 min)

**Exemple (lot 1)**

```markdown
## Le problème
Le problème de la circulation des demandes d'absence, sur papier et par ressaisies,
affecte les conducteurs de travaux, la responsable paie et tous les salariés,
ce qui a pour conséquence 4 chantiers démarrés avec une équipe incomplète l'an dernier,
3 h de ressaisie par semaine et 2 erreurs de paie en douze mois.
Une solution réussie permettrait de connaître les absences dès qu'elles sont accordées,
et de ne les saisir qu'une fois.

## Bête à cornes
- À qui rend-il service ? Aux salariés, aux responsables d'équipe, à la responsable paie.
- Sur quoi agit-il ? Sur les demandes d'absence et le planning des équipes.
- Dans quel but ? Que chaque absence, demandée une fois, soit connue à temps
  de ceux qui planifient et de ceux qui paient.

## Objectifs
| # | Indicateur | Départ | Cible | Échéance |
|---|---|---|---|---|
| O1 | temps de ressaisie de la responsable paie | 3 h par semaine | moins de 45 min | 31 mars |
| O2 | chantiers démarrés avec une équipe incomplète | 4 par saison | 0 | saison avril-octobre |
| O3 | erreurs de paie dues à une absence | 2 en douze mois | 0 | six premiers mois |
```

## Pause (10 min)

## Étape 4 - Le périmètre, les contraintes, les hypothèses, les risques (20 min)

**Vous produisez :** les parties "Périmètre", "Contraintes", "Hypothèses et risques" de la note de cadrage (gabarit [B.5](B-Modeles-et-canevas.md)), et une photo du diagramme pieuvre.

1. **Dessinez le diagramme pieuvre** sur une feuille : le futur outil au centre, tous les éléments de son environnement autour. Pensez aux personnes, aux logiciels (dont l'outil du lot 1), aux règlements, aux lieux, aux véhicules, au matériel. Cherchez ceux que personne n'a cités. (5 min)
2. **Remplissez les trois colonnes du périmètre** : dedans, dehors, plus tard. Au moins **quatre exclusions**. Tranchez deux questions : la fabrication en atelier est-elle dedans ? Et la géolocalisation ? (6 min)
3. **Listez les contraintes** : réglementaires, organisationnelles, techniques, de calendrier, de budget. (4 min)
4. **Écrivez trois hypothèses et trois risques.** Pour chaque risque : probabilité, impact, réponse. (5 min)

**Exemple (lot 1)**

Le diagramme pieuvre du lot 1 est dans le cours, partie 5.2. Pour le reste :

```markdown
## Périmètre
| Dedans | Dehors | Plus tard |
|---|---|---|
| demander, accorder, refuser une absence | le calcul de la paie | les heures récupérées |
| l'export vers le logiciel de paie | la planification des chantiers | les intérimaires |

## Contraintes
- Réglementaire : RGPD, les absences pour maladie sont des données de santé.
- Organisationnelle : le CSE est informé avant la mise en service.

## Hypothèses
- H1 : le logiciel de paie sait importer un fichier CSV. À vérifier avec l'éditeur.

## Risques
| Risque | Probabilité | Impact | Réponse |
|---|---|---|---|
| Les poseurs n'utilisent pas l'outil | moyenne | fort | les associer ; saisie possible par le conducteur |
```

> **Les données personnelles ne sont pas une case à cocher.** Le tableau blanc en contient une très sensible : laquelle ? Qui doit y avoir accès ? Et les numéros personnels des poseurs, aujourd'hui dans un groupe WhatsApp ? Notez-le : demain, ce seront des exigences.

## Étape 5 - Le glossaire (10 min)

**Vous produisez :** `cadrage/glossaire.md` (gabarit [B.6](B-Modeles-et-canevas.md)), avec au moins dix termes.

1. **Repartez des six termes de l'exercice 3.**
2. **Relevez les autres mots du métier** dans le dossier et vos notes : les personnes, les objets, les états, les décisions, les périodes. Par exemple : équipe, chef de pose, véhicule, report, jour ouvré. (3 min)
3. **Cherchez les pièges** : le même mot employé différemment par Paul, les consignes et les verbatims. (3 min)
4. **Définissez chaque terme**, avec le mot à éviter et un exemple. Pour chaque ambiguïté : une décision dans le journal, ou une question à Paul. (4 min)

**Exemple (lot 1)**

```markdown
| Terme | Définition | À éviter | Exemple |
|---|---|---|---|
| Absence | toute période non travaillée, quel qu'en soit le motif | "congé" | Léa, absente du 14 au 18 avril |
| Jour ouvré | du lundi au vendredi, hors jours fériés | "jour ouvrable" | une semaine de congé = 5 jours ouvrés |
| Accorder | décision du responsable d'équipe d'autoriser une demande | "valider" | le responsable de Léa accorde sa demande |
```

## Étape 6 - Les besoins, le point avec Paul Brunel, la note de cadrage (20 min)

**Vous produisez :** la note de cadrage complète, `cadrage/note-de-cadrage.md` (gabarit [B.7](B-Modeles-et-canevas.md)), et l'entrée du jour dans `journal.md`.

1. **Listez les besoins**, par personne concernée. Une phrase par besoin, avec sa source : l'entretien, une pièce jointe, un verbatim, ou "déduit par l'équipe". (6 min)
2. **Marquez au moins trois besoins de base** : personne ne les a dits, mais sans eux le projet échoue. Puis choisissez les **trois questions** qui changent le plus votre cadrage. (2 min)
3. **Le point avec Paul Brunel dure 7 minutes, à six, comme l'entretien.** Mettez vos deux fois trois questions en commun et retirez les doublons. Chaque question est posée par une personne différente. (7 min)
4. **Assemblez la note de cadrage** : vous avez déjà tout. Ajoutez les besoins, le registre des questions ouvertes avec les réponses du point, et l'entrée du journal. (5 min)

**Exemple (lot 1)**

```markdown
## 9. Liste brute des besoins
| # | Qui | Besoin | Source | De base ? |
|---|---|---|---|---|
| B3 | conducteur de travaux | connaître les absences accordées de ses poseurs | entretien | |
| B6 | salarié | que son solde soit juste | déduit par l'équipe | oui |

## 11. Questions ouvertes
| # | Question | À qui | Réponse |
|---|---|---|---|
| Q-04 | Qui accorde quand le responsable est absent ? | Sandrine | son suppléant désigné (point de 15:33) |

# Journal de décisions
| Date | Décision | Raison | Par |
|---|---|---|---|
| [date] | les intérimaires sont hors périmètre | moins de 5 % des absences | Paul Brunel, entretien |
```

> **Si le temps manque**, gardez dans l'ordre : l'énoncé du problème, les exclusions du périmètre, les écarts du tableau blanc, le glossaire. Le reste peut se compléter demain matin.

## Préparer la restitution (10 min)

Vous présentez **six minutes, sans diaporama** : montrez la note de cadrage, le tableau ou le mur. Le ou la porte-parole ouvre et conclut ; les deux autres présentent un point chacun. Cinq points, une ou deux phrases chacun :

1. **La demande** de Paul Brunel, puis **le problème réel**.
2. **L'objectif principal**, avec son indicateur et sa cible.
3. **Une exclusion** du périmètre, et pourquoi.
4. **La trouvaille** des pièces jointes : une règle enfreinte, une contradiction, un chiffre qui change tout.
5. **La question ouverte** la plus importante.

**Exemple (lot 1)**

> 1. "Paul nous a demandé une application de congés. Le vrai problème : les chantiers démarrent sans équipe complète, parce que le planning ignore les absences."
> 2. "Objectif : zéro chantier incomplet sur la saison, contre quatre l'an dernier."
> 3. "Nous excluons le calcul de la paie : c'est le métier du logiciel de paie."
> 4. "Le règlement dit quinze jours de délai ; dans le tableur, un tiers des demandes arrivent plus tard."
> 5. "Qui accorde une absence quand le responsable est absent ? Paul doit trancher."

## Restitution (20 min)

Chaque équipe dispose de **six minutes de présentation et de quatre minutes de retours**. L'autre équipe note ses retours avec la grille [B.17](B-Modeles-et-canevas.md) - chacun·e au moins un "j'aime", un "je me demande" et un "je propose" :

- **J'ai aimé…** : ce qui est clair, convaincant, bien fondé ;
- **Je me demande…** : ce qui n'est pas étayé, ce qui reste flou ;
- **Je propose…** : une piste concrète pour demain.

Les retours portent sur le travail, jamais sur les personnes. L'équipe qui présente écoute et note, sans se justifier : elle en tiendra compte demain.

Après les deux présentations, le formateur relève au tableau **les écarts entre vos deux cadrages** : un objectif différent, une exclusion que l'une a faite et pas l'autre, un mot défini autrement. Chaque écart est une décision que l'une des équipes a prise, ou une question à poser au commanditaire.

## Bilan de la journée (10 min)

Le formateur dégage **trois enseignements** de la journée : ce que les équipes ont bien fait, ce qui a souvent coincé, ce qui servira demain. Chacun·e note, pour soi, **une** chose qu'il ou elle ferait différemment face à un vrai client.

---

## Critères de réussite

- [ ] Les hypothèses du dossier ont été identifiées, et soumises au commanditaire.
- [ ] Le compte rendu d'entretien distingue ce qui a été dit de ce qui a été compris.
- [ ] Chaque pièce jointe a été analysée ; chaque ligne du tableau blanc a été confrontée aux consignes ; les contradictions sont relevées.
- [ ] L'énoncé du problème ne contient aucune solution ; ses conséquences sont chiffrées.
- [ ] Les objectifs sont SMART, et leur valeur de départ est connue ou mise en question.
- [ ] Le périmètre exclut explicitement au moins quatre éléments ; la fabrication et la géolocalisation sont tranchées, ou en question.
- [ ] Les données personnelles, et les plus sensibles d'entre elles, sont repérées.
- [ ] Le glossaire lève au moins six ambiguïtés, dont les trois du matin.
- [ ] Chaque besoin a une source ; au moins trois besoins de base sont identifiés.
- [ ] Le registre des questions ouvertes dit à qui poser chaque question.

## Pièges fréquents

| Piège | Comment l'éviter |
|---|---|
| Recopier la demande du commanditaire comme objectif | un objectif dit ce qui change, avec un chiffre ; un écran n'est pas un objectif |
| Recopier la correction du matin sans la relire | c'est un point de départ, écrit avant l'entretien ; l'entretien l'a peut-être rendue fausse |
| Lire le tableau blanc en diagonale | c'est là que les consignes sont enfreintes ; confrontez-le ligne à ligne |
| Ne relever que le cas général | pour chaque règle : "Et si… ?" |
| Résoudre soi-même les ambiguïtés | une ambiguïté se fait trancher par le commanditaire ; en attendant, c'est une question ouverte |
| Un périmètre sans exclusions | ce qui n'est pas exclu par écrit sera réclamé |
| Oublier ceux qui ne sont pas utilisateurs | le client, la paie, l'atelier, l'agence d'intérim, le CSE, l'outil du lot 1 |
| Attendre l'autre équipe, ou la copier | vous avez entendu les mêmes réponses ; vos décisions sont à vous, et les écarts sont précieux |

## Si vous avez fini en avance

- Menez l'exercice des **cinq pourquoi** sur le "GPS des camions", s'il n'a pas été fait pendant la marge du matin, un·e équipier·ère jouant Paul Brunel avec les éléments du dossier.
- Classez vos besoins selon le **modèle de Kano** : lesquels sont de base, de performance, d'enthousiasme ? Y a-t-il des besoins **inversés** dans la demande du commanditaire ?
- Rédigez le **courriel** que vous enverriez ce soir à Paul Brunel : le compte rendu de l'entretien, vos reformulations, et vos questions ouvertes, classées par urgence.

---

[← Chapitre précédent](01-J1-Cours-Analyser-le-besoin.md) · [Sommaire](Readme.md) · [Chapitre suivant →](03-J2-Cours-Specifier.md)
