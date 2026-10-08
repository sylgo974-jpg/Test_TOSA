Simulateur de parcours Tosa

Mini application web pour les stagiaires des formations bureautiques certifiantes Tosa (Excel, Word, PowerPoint).

Le stagiaire saisit son score au test de positionnement et son objectif. L'application affiche les modules à suivre et le nombre de jours de formation.

Fonctionnement
Étape	Action
1	Cliquer sur le bouton du logiciel (Excel, Word ou PowerPoint) et passer le test de positionnement gratuit
2	Noter le score précis (1 à 1 000)
3	Remplir le cadre orange : logiciel, score, objectif
4	Cliquer sur « Voir mon parcours »
5	Imprimer ou montrer le résultat au formateur

Aucune donnée n'est enregistrée ni envoyée. Tout se calcule dans le navigateur.

Grille utilisée
Score d'entrée	Objectif N3 (551)	Objectif N4 (726)	Objectif N5 (876)
1 – 199	4 j · J0 + M1 + M2a	8 j · + M2b + M3	10 j · + N5
200 – 450	3 j · M1 + M2a	7 j	9 j
451 – 550	2 j · M1 (jour 2) + M2a	6 j	8 j
551 – 650	Atteint · M2a conseillé	5 j · M2a + M2b + M3	7 j
651 – 725	Atteint	2 à 4 j · M2b (+ M3 conseillé)	6 j
726 – 800	—	Atteint · M3 conseillé	4 j · M3 + N5
801 – 875	—	Atteint	2 j · N5
876 – 1 000	—	—	Atteint

Pour modifier les liens des tests : chercher le commentaire LIENS DES TESTS ISOGRAD dans index.html et remplacer l'adresse (href) de chaque bouton.

Pour modifier la grille : éditer les tableaux MOD et GRILLE dans le bloc <script id="logique"> de index.html.

Publier sur GitHub Pages
Créer un dépôt public sur GitHub (ex. simulateur-tosa).
Déposer index.html et README.md à la racine (bouton Add file → Upload files).
Aller dans Settings → Pages.
Source : Deploy from a branch, branche main, dossier / (root). Enregistrer.
Après 1 à 2 minutes, l'appli est en ligne à l'adresse https://<votre-compte>.github.io/simulateur-tosa/.
Technique

Un seul fichier HTML, sans dépendance (police Google Fonts optionnelle). Compatible ordinateur et mobile. Impression optimisée.
