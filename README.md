# Cotisations TNS

Version de test 1.6

Outil d’aide au calcul des cotisations sociales des travailleurs indépendants, développé par LGC Expertise et partagé entre confrères pour test. Novembre 2026.

## Ce qu’il fait

- Cotisations définitives sur la nouvelle assiette (réforme 2025), arrondies comme l’Urssaf : contrôlé à l’euro près sur une dizaine d’avis 2025.
- Régularisation, charge à payer ou produit à recevoir, écritures de clôture, y compris en exercice décalé.
- Montants à déclarer : cases 1GB, DSEC, DSAA (gérant), résultat fiscal et 5KC (BIC), cases de la 2035 et 5QC (BNC).
- Contrôle avec la comptabilité, fiche imprimable, texte pour le client.
- Échéancier de l’année et projection de l’année suivante.
- Statuts : gérants majoritaires (SSI et professions libérales réglementées), EI ou EIRL à l’IS, EI BIC, EI BNC (SSI et CNAVPL), professions de santé conventionnées.
- Cas particuliers : revenus de remplacement (IJ), dividendes (part au-delà de 10 %), intéressement et participation, chèques-vacances, frais réels du gérant, impayés, cessation, estimations en cours d’année, exercice décalé.

## Installation

1. En ligne, sans rien télécharger : ouvrir le lien GitHub Pages du dépôt dans Chrome ou Edge.
2. Ou en local : télécharger `index.html` (bouton « Code », puis « Download ZIP », ou depuis la dernière release), le placer sur le poste ou sur le serveur de fichiers du cabinet et l’ouvrir avec Chrome ou Edge.
3. Dans les deux cas, la première fois, cliquer sur « Première installation du cabinet » : cela crée le fichier de données JSON, une seule fois pour tout le cabinet. Sur les autres postes, cliquer sur « Ouvrir le fichier de données ».

Les données restent dans ce fichier JSON. Aucune donnée n’est transmise à LGC Expertise ni à un tiers. La recherche par SIREN, en version locale, interroge l’Annuaire des entreprises avec le seul SIREN.

Le mode d’emploi complet, pas à pas, est dans l’onglet « Mode d’emploi ».

Icône : `icone.ico` (raccourci Windows : clic droit sur le raccourci, « Propriétés », « Changer d’icône »), `icone.png` pour les autres usages.

## Protocole de test proposé

1. Choisir deux ou trois dossiers par statut, déjà traités dans votre logiciel habituel.
2. Les saisir dans l’outil et comparer cinq points : assiette de l’avis N-1, cotisations définitives ligne par ligne, charge à payer, montants à déclarer, contrôle avec la comptabilité.
3. Tolérance : 5 € (arrondis).
4. Pour tout écart, ouvrir une « Issue » sur ce dépôt : statut, année, étape, les deux montants, et l’avis Urssaf anonymisé (jamais de nom, de numéro de sécurité sociale ni d’IBAN).

## Non inclus dans cette version

- La récupération automatique des données Urssaf (extension Chrome), en cours de mise au point.
- Micro-entrepreneurs, début d’activité, ACRE, prorata d’année incomplète, associés de sociétés à l’IR.
- Classes des caisses libérales autres que la CIPAV (montants à saisir), plafonds Madelin et PER (calculés, hors abondements d’entreprise).

## Mise à jour annuelle

Onglet Paramètres : « Ajouter l’année suivante », puis mettre à jour le PASS, l’assiette minimale de retraite et les taux.

## Avertissement

Outil d’aide au calcul, fourni gratuitement et sans garantie. Les résultats doivent être contrôlés sur les avis de l’Urssaf et des caisses. Leur utilisation relève de la responsabilité de l’utilisateur.

## Licence

MIT : utilisation, modification et diffusion libres, en conservant la mention d’origine (voir LICENSE).
