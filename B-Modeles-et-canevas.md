[← Chapitre précédent](A-Projet-Brunel.md) · [Sommaire](Readme.md) · [Chapitre suivant →](C-Glossaire-et-ressources.md)

# Annexe B - Modèles et canevas

Ces gabarits se recopient tels quels dans le dépôt ou l'espace d'équipe. Les blocs en Markdown se collent directement dans un fichier ; les tableaux se remplissent ligne à ligne. Chacun indique quand il sert.

| Gabarit | Sert à | Quand |
|---|---|---|
| B.1 | Journal de décisions, tri du brief, registre des questions ouvertes | J1 → J2 |
| B.2 | Guide d'entretien de cadrage et compte rendu | J1, étape 2 |
| B.3 | Grille d'analyse documentaire | J1, étape 2 |
| B.4 | Énoncé du problème, bête à cornes, objectifs SMART | J1, étape 3 |
| B.5 | Périmètre, contraintes, hypothèses, risques | J1, étape 4 |
| B.6 | Glossaire métier | J1, étape 5 |
| B.7 | Note de cadrage | J1, étape 6 |
| B.8 | Liste des exigences | J2, étape 7 |
| B.9 | Fiche de cas d'utilisation | J2, étape 8 |
| B.10 | Règle de gestion et table de décision | J2, étape 8 |
| B.11 | Dictionnaire de données | J2, étape 8 |
| B.12 | Exigences non fonctionnelles | J2, étape 9 |
| B.13 | Matrice de traçabilité | J2, étape 9 |
| B.14 | Plan du dossier de spécifications | J2 |
| B.15 | Grille de revue d'une spécification | J2, étape 10 |
| B.16 | Demande de changement et analyse d'impact | J2, étape 11 |
| B.17 | Grille de retours | restitution, soutenance |
| B.18 | Grille d'évaluation de la soutenance | J2, soutenance |

---

## B.1 - Journal de décisions, tri du brief, registre des questions ouvertes

**Le tri du brief**, en trois colonnes de post-its ou en trois listes :

| Ce qu'on sait | Ce qu'on suppose | Ce qu'on ignore |
|---|---|---|
| un fait, un chiffre, avec sa source | une croyance sans preuve, y compris une affirmation du commanditaire | une question sans réponse |

**Le journal de décisions et le registre des questions**, dans un fichier `journal.md` :

```markdown
# Journal - [projet], équipe [nom]

## Décisions

| N° | Date | Décision | Raison | Décidé par |
|---|---|---|---|---|
| D-01 | | | | équipe / commanditaire |

## Hypothèses

| N° | Hypothèse | À vérifier auprès de | Statut |
|---|---|---|---|
| H-01 | | | ouverte / confirmée / infirmée |

## Questions ouvertes

| N° | Question | Pourquoi elle compte | À poser à | Pour quand | Réponse |
|---|---|---|---|---|---|
| Q-01 | | | | | |
```

Une décision prise par l'équipe sur un point qui relève du métier n'est pas une décision : c'est une hypothèse. Elle va dans le deuxième tableau.

---

## B.2 - Guide d'entretien de cadrage et compte rendu

**Avant l'entretien**, choisissez six questions au plus, dont au moins une par ligne en gras.

| Pour obtenir… | Questions possibles |
|---|---|
| **les objectifs** | "Dans un an, qu'est-ce qui vous ferait dire que c'était une réussite ?" · "Comment le mesurerez-vous ?" · "Combien est-ce aujourd'hui ?" |
| l'existant | "Montrez-moi comment vous faites aujourd'hui." · "Racontez-moi la dernière fois que ça s'est mal passé." |
| les règles | "Comment décidez-vous de… ?" · "Qui a le droit de… ?" · "Qu'est-ce qui est interdit ?" |
| **les exceptions** | "Et quand ça ne se passe pas comme d'habitude ?" · "Quel est le cas le plus compliqué que vous ayez vu ?" |
| **les chiffres** | "Combien par jour, par mois, en période de pointe ?" · "Combien de personnes ?" |
| les priorités | "Si on ne pouvait faire qu'une seule chose, ce serait laquelle ?" |
| **les limites** | "Qu'est-ce qui ne doit surtout pas arriver ?" · "Qu'est-ce que l'outil ne doit pas faire ?" |
| les acteurs | "Qui d'autre faut-il voir ?" · "Qui fera le travail en plus ? Qu'en pense-t-il ?" |

**Pendant l'entretien** : une personne mène, une note mot pour mot, les autres relancent. Reformulez : "Si je comprends bien…". Demandez un exemple chiffré à chaque règle.

**Le compte rendu**, le jour même :

```markdown
# Compte rendu - entretien de cadrage

- Date, durée :
- Interlocuteur : [nom, rôle]
- Pour l'équipe : [noms]

## Ce qu'il a dit
- …

## Ce que nous avons compris (reformulations validées)
- …

## Règles et exemples recueillis
- …

## Décisions prises en séance
- …

## Questions restées ouvertes → registre (B.1)
- Q-… :
```

---

## B.3 - Grille d'analyse documentaire

Une grille par document.

```markdown
# Analyse - [nom du document]

- Nature : formulaire / tableur / règlement / courriel / export / autre
- Source, date, version :
- Est-il appliqué tel quel ? oui / non / à vérifier

## Données
| Donnée | Ce qu'elle signifie | Format, valeurs observées | Remarque |
|---|---|---|---|

## Règles
| N° provisoire | Règle, telle que lue | Où (article, colonne, case) | Ambiguïté |
|---|---|---|---|

## Acteurs et étapes
1. …

## Volumes
- …

## Questions et contradictions
- [avec une autre pièce, avec l'entretien, avec elle-même]
```

Ce qu'il faut regarder de près : les cases "autre" ; les champs calculés ; les cellules remplies à la main ou colorées ; les remarques en texte libre - souvent des règles non écrites, parfois des données qui n'ont rien à y faire ; les incohérences d'une ligne à l'autre.

---

## B.4 - Énoncé du problème, bête à cornes, objectifs SMART

```markdown
## Énoncé du problème
Le problème de …
affecte …
ce qui a pour conséquence … [chiffré]
Une solution réussie permettrait de …

## Bête à cornes
- À qui rend-il service ? …
- Sur quoi agit-il ? …
- Dans quel but ? …

## Objectifs
| N° | Objectif | Indicateur | Valeur de départ | Cible | Échéance |
|---|---|---|---|---|---|
| O1 | | | | | |
```

Vérifiez : l'énoncé ne contient aucune solution ; chaque objectif a une valeur de départ, ou une question ouverte pour la mesurer.

---

## B.5 - Périmètre, contraintes, hypothèses, risques

**Le diagramme pieuvre** : le futur outil au centre, et autour, tous les éléments de son environnement. Pour chacun : une fonction principale le relie-t-elle à un autre élément ? Une fonction contrainte l'impose-t-elle ?

| Fonction | Formulation | Éléments reliés | Principale ou contrainte |
|---|---|---|---|
| FP1 | permettre à … de … | | principale |
| FC1 | respecter / s'adapter à … | | contrainte |

**Le périmètre :**

| Dans le périmètre | Hors périmètre | Plus tard, peut-être |
|---|---|---|
| | au moins quatre éléments | |

**Les contraintes :**

| Type | Contrainte | Source |
|---|---|---|
| Réglementaire | | |
| Données personnelles | | |
| Organisationnelle | | |
| Technique, systèmes existants | | |
| Calendrier, budget | | |

**Les risques :**

| Risque | Probabilité | Impact | Réponse |
|---|---|---|---|
| | faible / moyenne / forte | faible / moyen / fort | |

Les hypothèses vont dans le journal (B.1).

---

## B.6 - Glossaire métier

```markdown
# Glossaire

| Terme | Définition | À ne pas confondre avec / termes à éviter | Exemple | Source |
|---|---|---|---|---|
| | | | | |
```

Règles : un terme par notion, une notion par terme ; les termes à éviter sont listés, pour qu'on les repère dans les textes ; un exemple par terme ; chaque définition se fait valider par le métier. Les noms du code reprendront ces termes.

---

## B.7 - Note de cadrage

```markdown
# Note de cadrage - [projet]
Version : 0.1 · Date : · Rédigée par :

## 1. Contexte
[en cinq lignes : l'organisation, ce qui se passe aujourd'hui]

## 2. La demande
[telle que formulée par le commanditaire]

## 3. Le problème
[l'énoncé, B.4]

## 4. Objectifs
[le tableau, B.4]

## 5. Parties prenantes
| Partie prenante | Rôle dans le projet | Ce qu'elle attend | Ce qu'elle redoute |
|---|---|---|---|

## 6. Périmètre
[les trois colonnes, B.5]

## 7. Contraintes
[B.5]

## 8. Hypothèses et risques
[B.1, B.5]

## 9. Liste brute des besoins
| N° | Partie prenante | Besoin | Source | De base ? |
|---|---|---|---|---|
| B1 | | | entretien / pièce jointe / verbatim / déduction | oui / non |

## 10. Comment nous avons recueilli le besoin
[qui, quelle technique, quels documents]

## 11. Questions ouvertes
[renvoi au registre, B.1 ; les cinq plus importantes recopiées ici]
```

---

## B.8 - Liste des exigences

```markdown
# Exigences fonctionnelles - domaine [nom], préfixe EF-[XXX]

| Id | Exigence | Source | Priorité | Statut |
|---|---|---|---|---|
| EF-XXX-01 | Quand …, le système doit … | B3, entretien du … | Must | proposée |
```

**Les gabarits EARS :**

| Gabarit | Forme |
|---|---|
| Permanente | Le système doit `<réponse>`. |
| Sur événement | Quand `<déclencheur>`, le système doit `<réponse>`. |
| Sur état | Tant que `<état>`, le système doit `<réponse>`. |
| Indésirable | Si `<situation indésirable>`, alors le système doit `<réponse>`. |
| Optionnelle | Lorsque `<option présente>`, le système doit `<réponse>`. |

**Les statuts :** proposée, validée, abandonnée, remplacée par… Un identifiant ne se réutilise jamais.

**Avant de passer à la suite**, relisez chaque exigence : un seul "doit" ; aucun mot piège - rapide, facile, intuitif, sécurisé, gérer, etc., et/ou, si possible ; chaque terme figure dans le glossaire ; une source.

---

## B.9 - Fiche de cas d'utilisation

```markdown
## UC-nn - [Verbe + complément]

- **Acteur principal :**
- **Acteurs secondaires :**
- **Objectif :**
- **Déclencheur :**
- **Préconditions :**
- **Garanties en cas de succès :**
- **Garanties minimales :**

### Scénario nominal
1. L'acteur …
2. Le système …
3. …

### Extensions
- **2a.** [condition] : [ce qui se passe]. [Retour à l'étape n / reprise à l'étape n / fin.]
- **\*a.** À tout moment, …

### Règles de gestion
RG-…, RG-…

### Exigences non fonctionnelles
ENF-…

### Fréquence
…

### Questions ouvertes
Q-…
```

Vérifiez : le nom est un objectif d'acteur, pas un écran ; aucun bouton, aucun menu, aucune couleur ; chaque étape où le système vérifie quelque chose a son extension ; les règles sont citées, pas recopiées.

---

## B.10 - Règle de gestion et table de décision

```markdown
### RG-nn - [Nom court]

- **Énoncé :**
- **Exceptions :**
- **Exemples :**
  - [cas nominal, chiffré]
  - [cas limite, chiffré]
  - [cas refusé, chiffré]
- **Source :**
- **Paramètres :** [valeurs susceptibles de changer, et qui peut les changer]
- **Utilisée par :** UC-…, EF-…
```

**La table de décision :**

| | R1 | R2 | R3 | R4 |
|---|---|---|---|---|
| **C1** - [condition] | oui | oui | non | non |
| **C2** - [condition] | oui | non | oui | non |
| **A1** - [action] | ✓ | | | |
| **A2** - [action] | | ✓ | ✓ | |
| **A3** - [action] | | | | ✓ |

Avec *n* conditions binaires, 2ⁿ combinaisons. Un tiret "-" signale une condition sans importance pour cette colonne, et permet de fusionner des colonnes. Chaque colonne donne au moins un cas de test ; chaque colonne douteuse, une question ouverte.

---

## B.11 - Dictionnaire de données

```markdown
# Dictionnaire de données - [objet]

| Donnée | Définition | Type et format | Obligatoire | Valeurs ou règle | Exemple | Personnelle ? Sensible ? | Conservation |
|---|---|---|---|---|---|---|---|
| | | | oui / non / calculée / si … | | | non / oui / **sensible** | durée, ou Q-… |
```

Les types courants : texte (longueur maximale), entier, décimal (précision), montant (devise), date, date et heure, booléen, liste de valeurs (énumérées), référence à un autre objet, fichier (formats, taille maximale).

Une donnée **sensible** au sens du RGPD - santé, origine, opinions, convictions, orientation sexuelle, données biométriques, entre autres - appelle une exigence de sécurité dédiée, et une question sur sa nécessité même.

---

## B.12 - Exigences non fonctionnelles

| Caractéristique ISO/IEC 25010 | Id | Exigence | Mesure ou vérification | Source |
|---|---|---|---|---|
| Aptitude fonctionnelle | ENF-APT-01 | | | |
| Efficacité de performance | ENF-PERF-01 | | seuil, centile, conditions de mesure | |
| Compatibilité | ENF-COMP-01 | | | |
| Capacité d'interaction - utilisabilité, accessibilité | ENF-INT-01 | | tâche, public, temps, taux de réussite ; référentiel RGAA | |
| Fiabilité | ENF-FIA-01 | | disponibilité, plage horaire, période | |
| Sécurité | ENF-SEC-01 | | qui voit quoi ; authentification ; journalisation | |
| Maintenabilité | ENF-MAINT-01 | | | |
| Flexibilité | ENF-FLEX-01 | | environnements visés | |
| Sûreté | - | sans objet, ou … | | |

Ajoutez les exigences qui relèvent de la **protection des données personnelles** - minimisation, droits d'accès, durée de conservation, information des personnes - en sécurité, ou dans une rubrique à part. La **sobriété** - le référentiel général d'écoconception de services numériques (RGESN) - peut y trouver place aussi.

---

## B.13 - Matrice de traçabilité

| Objectif | Besoin | Exigences et règles | Cas d'utilisation ou story | Tests |
|---|---|---|---|---|
| O1 - | B… | EF-…, RG-… | UC-… | T-… : [intitulé] |

**Les contrôles :**

- chaque objectif a au moins une exigence et un test ;
- chaque exigence remonte à un besoin, ou à une contrainte ;
- chaque règle de gestion a au moins autant de tests que de colonnes dans sa table de décision ;
- les orphelins sont supprimés, reliés, ou signalés.

---

## B.14 - Plan du dossier de spécifications

```text
specifications/
  00-historique.md          versions, dates, auteurs, changements, validations
  01-contexte-objectifs.md  repris de la note de cadrage
  02-glossaire.md
  03-acteurs-et-droits.md   qui fait quoi, qui voit quoi
  04-exigences.md           exigences fonctionnelles, par domaine
  05-cas-d-utilisation.md   fiches détaillées
  06-regles-de-gestion.md   catalogue et tables de décision
  07-donnees.md             dictionnaire de données
  08-exigences-nf.md        exigences non fonctionnelles et contraintes
  09-interfaces.md          échanges avec les systèmes existants
  10-maquettes.md           renvoi aux maquettes, par cas d'utilisation
  11-tracabilite.md         matrice
  12-questions-ouvertes.md
```

Dans un document unique, les mêmes parties deviennent des sections. **Les acteurs et droits** se présentent en matrice :

| Action ou donnée | [Acteur 1] | [Acteur 2] | [Acteur 3] |
|---|---|---|---|
| | créer, consulter, modifier, supprimer - ou rien | | |

---

## B.15 - Grille de revue d'une spécification

À remplir par l'équipe relectrice. Chaque remarque est rattachée à un identifiant.

**Les contrôles de forme :**

- [ ] Chaque exigence a un identifiant, une source, une priorité.
- [ ] Aucune exigence ne contient de mot piège.
- [ ] Chaque exigence est singulière : un seul "doit".
- [ ] Chaque exigence dit quoi, pas comment.
- [ ] Chaque terme métier employé est dans le glossaire, et employé dans ce sens.
- [ ] Les exigences non fonctionnelles sont chiffrées ou vérifiables.

**Les contrôles de fond :**

- [ ] Les cas d'erreur sont couverts : au moins une exigence "Si… alors" par domaine.
- [ ] Chaque règle de gestion a des exemples, dont un cas limite.
- [ ] La table de décision examine toutes les combinaisons.
- [ ] Les cas d'utilisation ont des extensions là où le système vérifie quelque chose.
- [ ] Les données sensibles sont repérées et protégées.
- [ ] Aucune exigence ne contredit le périmètre ou une autre exigence.
- [ ] Un développeur qui n'a pas assisté aux entretiens pourrait coder à partir de ce dossier.

**Les remarques :**

| N° | Identifiant visé | Remarque | Gravité | Réponse de l'équipe auteure |
|---|---|---|---|---|
| 1 | EF-… | | bloquante / importante / mineure | corrigée / refusée, parce que… / question ouverte Q-… |

---

## B.16 - Demande de changement et analyse d'impact

```markdown
# DC-nn - [titre]

## La demande
- Demandée par :            Date :
- Ce qui change :
- Pourquoi :
- Urgence :

## L'analyse d'impact (par l'équipe)
| Élément touché | Identifiants | Nature de l'impact |
|---|---|---|
| Objectifs | O… | |
| Exigences | EF-…, ENF-… | modifiée / nouvelle / supprimée |
| Règles de gestion | RG-… | |
| Données | | |
| Cas d'utilisation | UC-… | |
| Maquettes | | |
| Tests | T-… | |
| Systèmes existants | | |

- Effort estimé : faible / moyen / fort
- Risques :
- Ce qui devient plus difficile, ou impossible :

## La recommandation de l'équipe
accepter / accepter en partie / reporter / refuser - parce que …

## La décision (par le commanditaire)
- Décision :            Date :
- Version de la spécification qui l'intègre :
```

---

## B.17 - Grille de retours

| J'ai aimé… | Je me demande… | Je propose… |
|---|---|---|
| ce qui est clair, convaincant, bien fondé | ce qui n'est pas étayé, ce qui reste flou | une piste concrète pour la suite |

Un retour par case au moins. On commente le travail, jamais les personnes.

---

## B.18 - Grille d'évaluation de la soutenance

Chaque critère est noté de 0 à 3 : **0** absent · **1** esquissé · **2** satisfaisant · **3** remarquable.

| # | Critère | Ce qu'on attend | Note |
|---|---|---|---|
| 1 | **Besoin reformulé** | le problème réel est distingué de la demande ; il est étayé par les faits du dossier et l'entretien | /3 |
| 2 | **Objectifs et périmètre** | objectifs SMART avec valeur de départ ; exclusions explicites et justifiées | /3 |
| 3 | **Recueil et analyse** | les pièces jointes ont été exploitées ; contradictions et règles cachées relevées ; glossaire qui lève des ambiguïtés | /3 |
| 4 | **Qualité des exigences** | identifiées, sourcées, priorisées ; non ambiguës, vérifiables, singulières ; cas d'erreur couverts | /3 |
| 5 | **Cas d'utilisation** | complets, sans interface, riches en extensions, reliés aux règles | /3 |
| 6 | **Règles de gestion et données** | règles avec exemples ; table de décision complète ; dictionnaire avec formats et sensibilité | /3 |
| 7 | **Exigences non fonctionnelles** | mesurables ; sécurité, droits d'accès et données personnelles traités ; ce qui n'appartient pas à l'équipe est mis en question | /3 |
| 8 | **Traçabilité** | chaque objectif descend jusqu'au test ; pas d'orphelin | /3 |
| 9 | **Revue et changement** | remarques de la revue traitées ; analyse d'impact appuyée sur la matrice, recommandation argumentée ; versions tenues | /3 |
| 10 | **Soutenance** | claire, dans le temps, toute l'équipe s'exprime ; réponses précises aux questions | /3 |
| | **Total** | | **/30** |

**Repères :** en dessous de 12, les compétences visées ne sont pas encore démontrées ; de 12 à 20, elles le sont en partie ; au-delà de 20, elles le sont.

---

[← Chapitre précédent](A-Projet-Brunel.md) · [Sommaire](Readme.md) · [Chapitre suivant →](C-Glossaire-et-ressources.md)
