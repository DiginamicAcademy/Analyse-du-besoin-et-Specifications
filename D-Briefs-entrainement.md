[← Chapitre précédent](C-Glossaire-et-ressources.md) · [Sommaire](Readme.md)

# Annexe D - Briefs pour s'entraîner

Ces quatre briefs ne font pas partie du déroulé : pendant le module, tout le monde travaille sur le [projet Brunel](A-Projet-Brunel.md). Ils servent à s'entraîner seul·e ou à plusieurs, après le module, à refaire la démarche complète sur un autre sujet, ou à préparer une autre session. Chacun a ses pièces jointes, et le guide d'animation contient la fiche de son commanditaire et sa demande de changement. Les organisations, les personnes et les chiffres sont fictifs ; les situations, elles, sont très ordinaires.

## Comment lire un brief

Un brief est écrit par quelqu'un qui croit savoir ce qu'il veut. Il contient, comme dans la vraie vie :

- une **demande**, qui est presque toujours une solution ;
- des **faits** et des **chiffres**, qui disent où est le vrai problème ;
- des **pièces jointes** - un courriel, un extrait de règlement, un extrait de tableur, des verbatims - qui contiennent les règles, les données et les contradictions ;
- des **non-dits** : ce qui va de soi pour le commanditaire, et qui n'est écrit nulle part.

Lisez tout, deux fois. Les pièces jointes ne sont pas des annexes décoratives : c'est là que vous trouverez la matière de vos spécifications.

## Ce que le commanditaire attend de vous

- Qu'on ait compris **son problème**, et pas seulement sa demande.
- Qu'on lui dise **clairement ce qui sera fait et ce qui ne le sera pas**.
- Qu'on lui pose **les bonnes questions**, celles qui l'obligent à décider, plutôt que de décider à sa place.
- Qu'on lui remette un document **qu'il peut relire, comprendre et valider**, et sur lequel une équipe de développement pourra travailler sans revenir le voir chaque jour.

Le commanditaire est joué par le formateur. Il répond à ce qu'on lui demande, défend sa demande initiale, et ne cède que devant un fait.

## Les quatre briefs en un coup d'œil

| | Organisation | Commanditaire | La demande | Ce qui rend le sujet intéressant |
|---|---|---|---|---|
| **D.1** | Thermi'Services, entretien et dépannage de chaudières | Franck Dumas, gérant | un site de prise de rendez-vous et le suivi GPS des techniciens | des formules de contrat aux délais différents, des qualifications, la géolocalisation des salariés |
| **D.2** | L'Épi, épicerie sociale et solidaire | Hélène Roux, présidente | une carte à QR code et une application de commande | un calcul d'éligibilité, des plafonds, des données très personnelles, un public peu équipé |
| **D.3** | Lycée Marie-Curie, stages des étudiant·e·s de BTS | Sophie Lambert, directrice déléguée aux formations | une plateforme d'offres de stage | des conventions à cinq signatures, des règles du Code de l'éducation, des acteurs extérieurs |
| **D.4** | Festival des Rives, bénévoles | Julien Ferrand, coordinateur des bénévoles | une application mobile avec chat, badges et classement | des contraintes d'affectation, des mineur·e·s, un réseau saturé, des contreparties |

---

## D.1 - Thermi'Services : l'entretien et le dépannage des chaudières

> **Le service :** planifier les visites d'entretien annuel et les dépannages, et tenir les engagements des contrats.
> **Commanditaire :** Franck Dumas, gérant.

### Le contexte

Thermi'Services est une entreprise de chauffage de vingt et une personnes : quatorze technicien·ne·s, deux assistantes de planification - Nathalie et Mélanie -, un comptable, le gérant et trois personnes au magasin de pièces. Elle intervient dans un rayon de quarante kilomètres autour de la ville, pour **4 200 clients sous contrat d'entretien**, des particuliers pour l'essentiel.

L'entretien annuel des chaudières de 4 à 400 kW est une obligation réglementaire, et le client doit recevoir une **attestation d'entretien** dans les quinze jours suivant la visite. Les pompes à chaleur, de plus en plus nombreuses, ne peuvent être entretenues que par des technicien·ne·s titulaires d'une attestation d'aptitude à la manipulation des fluides frigorigènes : cinq sur quatorze l'ont.

Aujourd'hui, les clients appellent ; les assistantes fixent les rendez-vous dans un tableur partagé, en tenant compte de ce qu'elles savent des zones, des qualifications et des habitudes de chacun. Les technicien·ne·s remplissent sur place un carnet autocopiant ; Mélanie ressaisit les attestations le soir.

### Ce qu'on a observé

- **9 400 appels** par an, dont 38 % entre octobre et décembre.
- **Une visite d'entretien sur onze échoue** : le client est absent. Le rendez-vous a souvent été fixé par téléphone trois mois plus tôt, sans aucun rappel.
- En hiver, le délai moyen d'un dépannage est de **3,5 jours ouvrés**, y compris pour les clients de la formule Sérénité, qui promet 24 heures.
- **6 % des attestations** partent au-delà de quinze jours, ou jamais.
- Quand une assistante est absente, l'autre ne retrouve pas les informations "qu'elle a dans la tête" : quel technicien pour quelle marque, quel client prévenir par sa fille, quel code de portail.
- Trois technicien·ne·s ont dit au gérant qu'ils démissionneraient s'ils étaient "fliqués" par GPS.

### Pièce jointe 1 - Le courriel du commanditaire

> **De :** Franck Dumas · **Objet :** Projet informatique
>
> Bonjour,
>
> Comme je vous l'ai dit au téléphone, je veux moderniser la boîte. Il me faut un site où les clients prennent eux-mêmes leur rendez-vous, comme Doctolib, et une appli avec GPS pour que je voie où sont mes gars en temps réel. Et que ça fasse les factures, tant qu'on y est. Les filles au planning sont débordées, ça les soulagera.
>
> L'idéal serait que ce soit prêt pour octobre, avant la saison. Vous me direz combien.
>
> Franck

### Pièce jointe 2 - Conditions générales du contrat d'entretien (extrait)

> **Article 3 - Visite annuelle.** La visite d'entretien est réalisée une fois par an, dans une fenêtre comprise entre deux mois avant et un mois après la date anniversaire du contrat. La date est fixée d'un commun accord.
>
> **Article 4 - Formules.**
> - *Essentiel* : la visite annuelle. Les dépannages sont facturés et réalisés sans délai garanti.
> - *Confort* : la visite annuelle ; le déplacement et la main-d'œuvre des dépannages sont inclus ; intervention sous 48 heures ouvrées.
> - *Sérénité* : les prestations Confort, et les pièces hors corps de chauffe ; intervention sous 24 heures, 7 jours sur 7, du 1er novembre au 31 mars.
>
> **Article 6 - Absence du client.** Tout rendez-vous qui n'a pas été annulé au moins 24 heures à l'avance donne lieu à la facturation d'un déplacement de 39 € TTC.
>
> **Article 7 - Ordre de traitement.** Les demandes d'intervention sont traitées dans leur ordre d'arrivée. Les clients de plus de 75 ans, ou en situation de handicap, privés de chauffage, sont traités en priorité.
>
> **Article 9 - Attestation.** L'attestation d'entretien est remise au client dans les quinze jours suivant la visite.

### Pièce jointe 3 - Extrait du tableur de planning

| Date | Tech. | Client | Ville | Type | Formule | Créneau | Statut | Remarques |
|---|---|---|---|---|---|---|---|---|
| 14/10 | Hugo | Petit J. | St-Jean | ENT | Confort | 8h-10h | FAIT | vieille chaudière italienne, Hugo seulement |
| 14/10 | Kévin | Moreau A. | Aubry | DEP | Sérénité | 10h-12h | FAIT | appelé à 7h, plus d'eau chaude |
| 14/10 | Kévin | Benali S. | Aubry | ENT | Essentiel | 14h-16h | ABS | 2e fois absent, facturer ? |
| 14/10 | Inès | Garnier L. | Mornay | PAC | Sérénité | 8h-12h | FAIT | |
| 15/10 | Hugo | Lefèvre M. | Pontet | DEP | Confort | ? | ATT | 82 ans, sourde, appeler sa fille 06… |
| 15/10 | Paul | Roussel C. | St-Jean | ENT | Confort | 10h-12h | ANN | code portail 1234B, chien |
| 15/10 | - | Diaz R. | Mornay | DEP | Essentiel | - | ATT | pas urgent, client pénible |

### Pièce jointe 4 - Verbatims

> **Nathalie, assistante :** "Un client qui prend rendez-vous tout seul, il ne sait pas si c'est une pompe à chaleur ou une chaudière à condensation. Et moi je sais que chez M. Petit, il faut envoyer Hugo, parce qu'il est le seul à connaître sa vieille chaudière italienne."
>
> **Kévin, technicien :** "Le GPS, s'il sert à prouver que je suis passé quand le client dit que non, je veux bien. S'il sert à me surveiller pendant ma pause déjeuner, je m'en vais."
>
> **Une cliente, dans un avis en ligne :** "Trois jours sans chauffage avec un bébé, alors que j'ai le contrat le plus cher."
>
> **Le comptable :** "Les factures, on les fait dans notre logiciel de gestion. Il marche très bien. Ce qui ne marche pas, c'est qu'on ne sait pas quoi facturer : personne ne me dit qu'un client était absent."

### Les acteurs pressentis

Les clients particuliers, selon leur formule ; les assistantes de planification ; les technicien·ne·s, qualifié·e·s ou non pour les pompes à chaleur ; le comptable ; le gérant.

### Le système d'information existant

| Système | Ce qu'il sait | Comment on lui parle |
|---|---|---|
| Logiciel de gestion commerciale "GestiPro" | clients, contrats, formules, factures | export et import de fichiers CSV ; pas d'API |
| Tableur de planning partagé | rendez-vous, affectations, statuts, remarques | saisie à la main |
| Carnets autocopiants | rapports d'intervention, attestations | papier, ressaisi le soir |
| Téléphones professionnels des technicien·ne·s | - | smartphones Android fournis par l'entreprise |

### Les contraintes

- La **géolocalisation des salarié·e·s** est strictement encadrée : finalité légitime et proportionnée, information préalable des salarié·e·s et consultation du comité social et économique, pas de suivi en dehors du temps de travail.
- Certaines remarques du tableur concernent l'**âge**, la **santé** ou le **handicap** des clients.
- Plusieurs communes rurales de la zone n'ont pas de couverture mobile fiable.
- Mise en service souhaitée en octobre. Budget "à voir", selon le gérant.

---

## D.2 - L'Épi : l'épicerie sociale et solidaire

> **Le service :** permettre à des foyers en difficulté d'acheter des produits à prix très réduit, le temps de réaliser un projet.
> **Commanditaire :** Hélène Roux, présidente de l'association.

### Le contexte

L'Épi est une épicerie sociale et solidaire, tenue par une association. Elle compte une salariée, Fatou, coordinatrice, et vingt-six bénévoles. Elle accompagne environ **190 foyers par an**, dont 110 à un moment donné. Les produits y sont vendus entre 10 et 30 % de leur prix habituel.

On n'entre pas à l'Épi de sa propre initiative : un·e travailleur·se social·e - du centre communal d'action sociale (CCAS), du département, d'une association - remplit une **fiche d'orientation**, et une **commission d'attribution** décide de l'accès. Chaque foyer définit avec Fatou un **projet** : rembourser une dette, financer un permis de conduire, faire face à une période sans revenus.

L'épicerie ouvre le mardi et le vendredi, de 14 h à 17 h.

### Ce qu'on a observé

- Le fichier des bénéficiaires est un **tableur**, recopié sur clé USB entre quatre bénévoles. En mars, on en a trouvé **trois versions différentes**.
- Les dossiers papier et leurs justificatifs sont rangés dans une armoire fermée à clé, mais restent parfois sur le comptoir pendant l'ouverture.
- **60 % des bénéficiaires arrivent dans les quarante-cinq premières minutes**, de peur qu'il ne reste plus de produits frais.
- **35 % des bénéficiaires** n'ont pas de smartphone ou n'ont qu'un forfait très limité ; un sur cinq lit difficilement le français.
- À la caisse, le bénévole ne sait pas ce qu'il reste au foyer sur son plafond du mois. Certains plafonds sont dépassés ; d'autres foyers sont bloqués à tort.
- Fatou passe **trois soirées par an** à préparer les statistiques demandées par les financeurs.

### Pièce jointe 1 - Le courriel du commanditaire

> **De :** Hélène Roux · **Objet :** Notre projet numérique
>
> Bonjour,
>
> Nous aimerions offrir à nos bénéficiaires une carte de fidélité avec un QR code, et une application pour qu'ils puissent commander leurs courses à l'avance et ne plus faire la queue le mardi. Ce serait plus digne pour eux.
>
> Les financeurs nous demandent aussi de plus en plus de statistiques, et Fatou y passe ses soirées. Une fondation nous a accordé 8 000 € pour ce projet.
>
> Bien cordialement,
> Hélène Roux, présidente

### Pièce jointe 2 - Règlement intérieur (extrait)

> **Article 2 - Accès.** L'accès est ouvert aux foyers orientés par un travailleur social au moyen de la fiche d'orientation, et dont le reste à vivre journalier par personne est compris entre 3 € et 12 €. Le reste à vivre journalier est égal aux ressources mensuelles du foyer, diminuées de ses charges fixes mensuelles, divisées par le nombre de personnes du foyer, puis par trente.
>
> **Article 3 - Durée.** L'accès est accordé pour trois mois. Il peut être renouvelé deux fois, sur décision de la commission d'attribution, qui se réunit le premier lundi de chaque mois.
>
> **Article 4 - Plafond d'achats.** Chaque foyer dispose d'un plafond mensuel d'achats de 40 € pour une personne, augmenté de 20 € par personne supplémentaire, dans la limite de 120 €.
>
> **Article 6 - Confidentialité.** Les bénévoles sont tenus à la discrétion. L'identité des bénéficiaires et leur situation ne sont communiquées à personne en dehors de l'association.
>
> **Article 8 - Bilan.** Un bilan d'activité est adressé chaque année aux financeurs.

### Pièce jointe 3 - Extrait du tableur des bénéficiaires

| N° | Nom | Pers. | Ressources | Charges | RAV | Entrée | Fin droits | Plafond | Dépensé mars | Orienté par | Projet | Remarques |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| 112 | Martin S. | 3 | 1 450 | 1 080 | 4,1 | 06/01 | 06/04 | 80 | 62,40 | CCAS | dette loyer | |
| 118 | Haddad K. | 1 | 980 | 690 | 290 | 03/02 | 03/05 | 40 | 41,80 | Dépt | permis B | |
| 121 | Lopez M. | 5 | 1 900 | 1 320 | 3,9 | 03/02 | 05/05 | 140 | 97,00 | Asso Femmes | | violences - ne JAMAIS donner l'adresse |
| 124 | Nguyen T. | 2 | 1 210 | 950 | 4,3 | 03/03 | 03/06 | 60 | 0 | CCAS | | handicap, vient avec sa fille |
| 125 | Petit A. | 4 | 2 300 | 1 250 | 8,8 | 03/03 | | 100 | 12,10 | CAF ? | | renouvellement ? |

### Pièce jointe 4 - La fiche d'orientation, et des verbatims

La fiche d'orientation, en PDF, comporte : l'identité du travailleur social et de son organisme ; la composition du foyer - adultes, enfants et leurs âges ; les ressources par nature - salaires, allocations, pensions - ; les charges fixes - loyer, énergie, assurances, crédits ; la situation - "une phrase sur la situation de la famille" ; la signature du bénéficiaire, qui accepte que ses informations soient transmises.

> **Une bénéficiaire :** "Ma voisine est bénévole. Je ne veux pas qu'elle voie mes papiers."
>
> **Un bénévole à la caisse :** "Je ne sais jamais combien il leur reste. Alors, dans le doute, je laisse passer."
>
> **Une assistante sociale du département :** "J'envoie la fiche par mail, et je ne sais jamais si la famille a été acceptée, ni quand ses droits se terminent."
>
> **Fatou, coordinatrice :** "Les statistiques, c'est trois soirées par an. Et depuis cette année, le département veut des chiffres par commune."

### Les acteurs pressentis

Les foyers bénéficiaires ; les bénévoles, à la caisse et à l'accueil ; la coordinatrice ; la commission d'attribution ; les travailleur·se·s sociaux·ales des organismes prescripteurs ; les financeurs ; la présidente.

### Le système d'information existant

| Système | Ce qu'il sait | Comment on lui parle |
|---|---|---|
| Tableur des bénéficiaires | foyers, ressources, droits, plafonds, dépenses | fichier recopié sur clé USB |
| Caisse enregistreuse | montants des ventes, par ticket | autonome, sans réseau ; aucun lien avec les foyers |
| Messagerie de l'association | fiches d'orientation reçues en PDF | à la main |
| Armoire des dossiers | justificatifs papier | clé détenue par Fatou et la présidente |

### Les contraintes

- Les informations sur les foyers sont **très personnelles** ; certaines - santé, handicap, violences subies - sont **particulièrement sensibles**.
- Une partie du public n'a ni smartphone, ni accès facile à l'écrit.
- Les bénévoles changent souvent, et ne sont présents que quelques heures par semaine.
- Budget : 8 000 €, accordé par une fondation, à utiliser dans l'année.

---

## D.3 - Lycée Marie-Curie : les stages des étudiant·e·s de BTS

> **Le service :** permettre à chaque étudiant·e de réaliser son stage dans les règles, et d'en avoir la preuve pour l'examen.
> **Commanditaire :** Sophie Lambert, directrice déléguée aux formations.

### Le contexte

Le lycée Marie-Curie accueille **310 étudiant·e·s** dans cinq sections de BTS. Chacun·e effectue un stage par année de formation, de six à huit semaines selon la section. Certain·e·s étudiant·e·s de première année sont encore mineur·e·s.

Chaque stage fait l'objet d'une **convention** entre l'étudiant·e, l'organisme d'accueil et le lycée, que signent aussi le ou la tuteur·rice en entreprise et l'enseignant·e référent·e. Un seul secrétaire, Olivier, gère les conventions des cinq sections. À la fin du stage, l'**attestation de stage** signée par l'entreprise doit être versée au dossier d'examen.

Aujourd'hui, la convention est un document Word que l'étudiant·e remplit, que le secrétariat vérifie, puis qui circule par courriel en PDF, est imprimé, signé, scanné, renvoyé.

### Ce qu'on a observé

- L'an dernier, **27 étudiant·e·s ont commencé leur stage sans convention entièrement signée** - ce qui est interdit, et expose le lycée en cas d'accident.
- Il faut en moyenne **19 jours** pour réunir toutes les signatures.
- **41 % des étudiant·e·s** trouvent leur stage moins de trois semaines avant son début.
- En juin, **12 attestations de stage** manquaient au moment de constituer les dossiers d'examen.
- Trois conventions de stages de plus de deux mois ne mentionnaient pas de gratification.
- Les enseignant·e·s référent·e·s suivent leurs stagiaires dans leur propre carnet ; certain·e·s ne savent qui suivre que la veille du début des stages.
- Le lycée reçoit environ **vingt offres de stage** spontanées par an.

### Pièce jointe 1 - Le courriel du commanditaire

> **De :** Sophie Lambert · **Objet :** Plateforme stages
>
> Bonjour,
>
> Nous souhaiterions disposer d'une plateforme de type LinkedIn : les entreprises y déposeraient leurs offres, les étudiants postuleraient en ligne, et nous aurions enfin tout au même endroit. Plusieurs lycées du secteur en ont une, et cela participe à l'attractivité de nos formations.
>
> Il faudrait qu'elle soit opérationnelle à la rentrée de septembre.
>
> Sophie Lambert, directrice déléguée aux formations

### Pièce jointe 2 - Règlement des stages du lycée (extrait)

> **Article 1 - Convention.** Tout stage fait l'objet d'une convention signée, avant le premier jour du stage, par l'étudiant ou, s'il est mineur, par son représentant légal ; par l'organisme d'accueil ; par le tuteur ; par l'enseignant référent ; et par le proviseur.
>
> **Article 2 - Durée.** La durée du ou des stages effectués par un même étudiant dans un même organisme d'accueil ne peut excéder six mois par année d'enseignement (Code de l'éducation, article L124-5).
>
> **Article 3 - Gratification.** Lorsque la durée du stage au sein d'un même organisme d'accueil est supérieure à deux mois, consécutifs ou non, au cours d'une même année d'enseignement, le stage fait l'objet d'une gratification (Code de l'éducation, article L124-6).
>
> **Article 4 - Suivi.** L'enseignant référent prend contact avec le tuteur au moins une fois pendant le stage. Il effectue une visite sur le lieu de stage pour tout stage de plus de quatre semaines.
>
> **Article 5 - Attestation.** L'organisme d'accueil remet à l'étudiant, à la fin du stage, une attestation de stage, qui est versée au dossier d'examen.
>
> **Article 6 - Restriction.** Un étudiant ne peut pas effectuer son stage dans une entreprise dirigée par un membre de sa famille.

### Pièce jointe 3 - Extrait du tableur de suivi

| Étudiant·e | Section | Entreprise | Tuteur·rice | Début | Fin | Conv. envoyée | Sign. étud. | Sign. entr. | Sign. lycée | Référent·e | Visite | Attest. |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| Diallo A. | SIO 1 | Webexpert | M. Roy | 12/05 | 04/07 | 22/04 | 23/04 | 06/05 | 09/05 | Mme Caron | 03/06 | ✓ |
| Fabre L. | MCO 1 | Carrefour City | ? | 12/05 | 04/07 | 07/05 | 07/05 | | | M. Hamel | | |
| Girard T. | SIO 1 | Garage Girard | P. Girard | 12/05 | 04/07 | 28/04 | 29/04 | 30/04 | 02/05 | Mme Caron | | |
| Kone M. | CG 2 | Cabinet Alpha | Mme Bel | 06/01 | 14/03 | 10/12 | 11/12 | 13/12 | 16/12 | M. Petit | tél. | ✓ |
| Leroy E. | NDRC 1 | Orange | J. Sanz | 12/05 | 18/07 | 30/04 | 02/05 (mère) | 15/05 | 16/05 | Mme Diaz | | |

### Pièce jointe 4 - Verbatims

> **Un étudiant :** "J'ai trouvé mon stage, mais l'entreprise a mis trois semaines à signer. J'ai commencé avant, le tuteur m'a dit que ce n'était pas grave."
>
> **Une tutrice en entreprise :** "Je reçois la convention en PDF. Je dois l'imprimer, la signer, la scanner… Je n'ai pas de scanner au magasin."
>
> **Un enseignant référent :** "Je ne sais pas qui sont mes stagiaires avant la veille. Et les visites, je les note dans mon carnet : personne ne me les demande, sauf l'inspection, une fois tous les trois ans."
>
> **Olivier, secrétaire :** "Les offres des entreprises, on en reçoit vingt par an. Le problème, ce n'est pas de trouver des offres : c'est de faire signer les conventions. Et *deux mois*, pour la gratification, ce n'est pas deux mois de calendrier : on m'a dit que c'était quarante-quatre jours de présence."

### Les acteurs pressentis

Les étudiant·e·s, et le représentant légal des mineur·e·s ; les organismes d'accueil, leurs signataires et les tuteur·rice·s ; les enseignant·e·s référent·e·s ; le secrétariat ; le proviseur ; la directrice déléguée aux formations.

### Le système d'information existant

| Système | Ce qu'il sait | Comment on lui parle |
|---|---|---|
| Logiciel de vie scolaire | étudiant·e·s, sections, enseignant·e·s, responsables légaux | export CSV ; aucune écriture possible depuis un autre outil |
| Environnement numérique de travail (ENT) | comptes des étudiant·e·s et des personnels | authentification unique pour les applications raccordées |
| Modèle de convention Word | - | rempli à la main, circule en PDF par courriel |
| Tableur de suivi des stages | conventions, signatures, visites, attestations | saisie à la main par le secrétaire |

### Les contraintes

- Le **Code de l'éducation** encadre les stages : convention signée avant le début, durée maximale, gratification au-delà de deux mois.
- Les tuteur·rice·s et les signataires des entreprises **n'ont pas de compte** à l'ENT du lycée.
- Une partie des étudiant·e·s de première année est mineure.
- Mise en service souhaitée à la rentrée de septembre ; les premiers stages commencent en janvier.

---

## D.4 - Festival des Rives : les bénévoles

> **Le service :** réunir, affecter et accompagner les bénévoles sans qui le festival n'aurait pas lieu.
> **Commanditaire :** Julien Ferrand, coordinateur des bénévoles.

### Le contexte

Le Festival des Rives est un festival de musique associatif : trois jours fin juin, **18 000 festivalier·ère·s**, et **320 bénévoles** répartis sur quatorze postes - accueil, billetterie, bar, caisse, restauration des artistes, navettes, parking, camping, propreté, secours, et d'autres. Chaque poste a un·e chef·fe de poste, bénévole, lui aussi.

Julien est salarié de l'association. Avec une stagiaire, il recrute les bénévoles par un formulaire en ligne, construit le planning à la main dans un tableur pendant trois semaines, puis l'envoie par courriel. Sur place, chaque bénévole reçoit des tickets repas et, s'il y a droit, un pass trois jours.

### Ce qu'on a observé

- Le formulaire a recueilli **600 candidatures** l'an dernier, dont des doublons ; 280 n'ont jamais été utilisées.
- **Un bénévole sur sept** ne s'est pas présenté à au moins un de ses créneaux.
- Le jeudi soir, veille du festival, Julien a reçu **quarante désistements** par SMS, et a refait le planning à la main jusqu'à 2 h du matin.
- Le bar manquait de monde le samedi soir ; le parking en avait trop le vendredi matin.
- Douze bénévoles étaient mineur·e·s ; deux ont été affecté·e·s au bar par erreur.
- **15 % des tickets repas** ont été perdus ou distribués deux fois.
- Les chef·fe·s de poste reçoivent la liste de leurs bénévoles sur papier, la veille.

### Pièce jointe 1 - Le courriel du commanditaire

> **De :** Julien Ferrand · **Objet :** Appli bénévoles !!
>
> Salut,
>
> On voudrait une appli mobile pour les bénévoles, avec un chat, des badges à gagner et un classement des meilleurs bénévoles : ça les motivera. Et qu'ils puissent choisir leurs créneaux en swipant, comme sur Tinder, ce serait trop bien.
>
> Il faudrait que ce soit prêt pour l'ouverture des inscriptions bénévoles, en mars. On a 5 000 € de budget.
>
> Julien

### Pièce jointe 2 - Charte du bénévole (extrait)

> **Article 1 - Âge.** Les bénévoles ont au moins 16 ans au premier jour du festival. Les mineurs fournissent une autorisation parentale.
>
> **Article 2 - Engagement.** Chaque bénévole effectue au moins trois créneaux de quatre heures sur la durée du festival, et pas plus de deux créneaux par jour.
>
> **Article 3 - Contreparties.** Chaque créneau effectué donne droit à un repas. Le pass trois jours est offert aux bénévoles qui ont effectué au moins trois créneaux.
>
> **Article 4 - Postes réservés.** Le bar et la caisse sont réservés aux bénévoles majeurs. Le poste secours est réservé aux titulaires du PSC1 ou d'un diplôme de secourisme supérieur. Les navettes sont réservées aux titulaires du permis B depuis plus de trois ans.
>
> **Article 5 - Binômes.** Un bénévole peut demander à être affecté avec un ou une ami·e.
>
> **Article 6 - Désistement.** Un bénévole qui ne peut assurer un créneau prévient au moins 48 heures à l'avance. Un bénévole absent sans prévenir à deux créneaux perd son pass.

### Pièce jointe 3 - Extrait du tableur des bénévoles

| Nom | Âge | Tél. | Postes souhaités | Disponibilités | Permis | PSC1 | Avec | T-shirt | Remarques |
|---|---|---|---|---|---|---|---|---|---|
| Benoît C. | 17 | 06… | bar, accueil | ven. soir, sam. | non | non | Léo M. | M | |
| Léo M. | 19 | 07… | bar | sam., dim. | oui (2025) | non | Benoît C. | L | |
| Amrani Y. | 34 | 06… | secours | tout | oui (2008) | oui | | XL | infirmier |
| Duval P. | 52 | 06… | navette, parking | ven., sam. | oui (1992) | non | | L | en fauteuil depuis 2024 - poste assis ? |
| Chen L. | 23 | 07… | restauration | dim. | non | non | | S | allergie arachides |
| Morel J. | 28 | 06… | bar | ven. | oui | non | | M | a trop bu au bar en 2024 |

### Pièce jointe 4 - Verbatims

> **Une bénévole :** "Je reçois le planning trois jours avant, et je ne peux plus rien changer. Alors quand j'ai un empêchement, je ne viens pas, c'est tout."
>
> **Le chef du poste bar :** "Il me faut des gens qui savent tirer une bière. Pas des nouveaux à chaque créneau."
>
> **Un bénévole fidèle :** "Un classement des meilleurs bénévoles ? Je viens pour la musique et pour les copains, pas pour être noté."
>
> **La responsable sécurité :** "Je dois savoir, à tout moment, combien de personnes sont en zone backstage, et qui."
>
> **Julien :** "Ce qui me tue, c'est le jeudi soir. Je refais tout le planning à la main."

### Les acteurs pressentis

Les bénévoles, majeur·e·s et mineur·e·s, et les parents des mineur·e·s ; les chef·fe·s de poste ; le coordinateur et la stagiaire ; la responsable sécurité ; le bureau de l'association.

### Le système d'information existant

| Système | Ce qu'il sait | Comment on lui parle |
|---|---|---|
| Formulaire en ligne gratuit | candidatures | export en tableur |
| Tableur des bénévoles et du planning | bénévoles, souhaits, affectations | à la main |
| Billetterie, chez un prestataire | pass et billets | le prestataire génère des pass sur demande, par lot, avec nom et prénom |
| Groupe de messagerie instantanée | - | 320 personnes, des centaines de messages par jour en juin |

### Les contraintes

- Des bénévoles **mineur·e·s**, et des postes interdits aux mineur·e·s.
- Des informations de **santé** dans les remarques : allergies, handicap.
- Sur le site, pendant le festival, le **réseau mobile est saturé** par 18 000 personnes.
- Les bénévoles ne se servent de l'outil que quelques semaines par an ; beaucoup changent d'une année à l'autre.
- Budget : 5 000 €. Ouverture des inscriptions bénévoles en mars.

---

[← Chapitre précédent](C-Glossaire-et-ressources.md) · [Sommaire](Readme.md)
