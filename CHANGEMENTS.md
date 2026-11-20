# Verre bleu natif : historique des versions




## 0.5.1 (20/11/2026)
- Vie de famille : carte réduite à une ligne = les messages seuls ; en touchant un message, l’appli demande sur quelles enceintes l’annoncer
- Écrire une annonce : « Annonce de la maison », le message, puis les enceintes avec leur dessin (Nest Mini, Google Home, écran de la cuisine)
- Boutons rapides : l’ampoule n’est plus jaune quand c’est éteint ; le bouton rebondit au toucher, éclat lumineux à l’allumage
- Poubelle : le bac se dandine le jour où il faut le sortir
- Météo animée : soleil, lune et étoiles, nuages, pluie, neige, orage, brouillard, vent (carte Météo et en-tête)
- Paramètres → Défilement de l’Accueil : Vertical ou Horizontal (pages côte à côte) ; Fixe arrive avec le moteur de rendu
- Paramètres → Espace entre les cartes : Normal ou Réduit
- Toutes ces animations suivent l’interrupteur « Accueil » de Paramètres → Animations

## 0.5.0 (20/11/2026)
- Flux d’énergie : les pointillés avancent dans le sens du courant (soleil → maison, réseau → maison ou maison → réseau, batterie qui charge ou se décharge)
- Portail, porte de garage, volets : le dessin s’ouvre ou se ferme quand l’état change (page Pièces, Entrée & extérieur)
- Accueil : dessins du portail et des volets dans la carte Sécurité et la carte Volets
- Boutons rapides : pictogramme lampe / volet
- Vie de famille : les pièces (enceintes) sont en bas de la carte
- Poubelle : le bac concerné affiché dans la place libre à droite
- Paramètres → Animations : interrupteur ajouté pour l’Accueil

## 0.4.9 (20/11/2026)
- Après une longue veille, la liaison avec Home Assistant se rétablit toute seule (avant, elle pouvait rester bloquée sur « Home Assistant injoignable »)
- Une tentative de connexion bloquée est abandonnée au bout de 12 s, puis l’appli réessaie (1 s, 3 s, puis toutes les 8 s)
- Toutes les 5 s, l’appli vérifie qu’un nouvel essai est bien prévu ; sinon elle le relance
- Au rallumage de l’écran : liaison vérifiée tout de suite ; une liaison morte est détectée et refaite

## 0.4.8 (20/11/2026)
- Énergie, Chauffage, Pièces : les dessins des appareils de tablette pixar (panneaux solaires, compteur, batterie, chaudière, lampes, volets, prises, portail…), animés
- Paramètres → carte « Animations » : un interrupteur par page (coupé = dessins fixes)
- Énergie : quand une carte est agrandie ou réduite, le texte, les chiffres et la mise en page s’adaptent à la place (plus grande police possible, sans rien couper)
- Flux d’énergie : le schéma s’étire en largeur ou en hauteur selon la carte ; carte très petite = les 4 valeurs avec leur dessin
- Production prévue et Bilan du jour : plusieurs mises en page, l’appli choisit celle qui donne les textes les plus grands
- Chiffres et unités jamais coupés (« 9,3 kWh » toujours sur une ligne)

## 0.4.7 (20/11/2026)
- Toutes les pages (Pièces, Énergie, Chauffage, Volets, Sécurité, Caméras, Pronote, Automatismes, Paramètres) : appui long sur la page → déplacer et redimensionner chaque carte, comme sur l’Accueil. Sans modification, la page reste comme à l’origine
- Une carte agrandie garde son contenu entier et le fait grandir ; réduite, le contenu se réduit sans déborder
- Poignées jaunes et flèches : toute la surface du bouton répond (avant, les bouts et les coins ne faisaient rien)
- Le message rouge / vert en bas de l’écran ne bloque plus les touchers pendant 3 s
- Accueil : toucher une carte ouvre sa page (Sécurité, Pièces, Caméras, Volets, Énergie, Chauffage) ; toucher une pièce ouvre la page Pièces sur cette pièce
- Scénarios de nouveau sur une rangée de 4, comme sur tablette pixar

## 0.4.6 (19/11/2026)
- Mode Taille : dans le panneau de gauche, deux gros boutons par côté (Haut, Bas, Gauche, Droite) : Agrandir en jaune, Réduire en sombre, toujours au même endroit
- Les poignées jaunes sur la carte restent pour glisser ; un toucher qui bouge un peu compte encore comme un toucher
- En mode Taille, Retirer et Galerie laissent la place au pavé (ils restent en mode Déplacer)

## 0.4.5 (19/11/2026)
- Toutes les cartes de l’Accueil se réorganisent selon la taille qu’on leur donne : Météo, Sécurité, Scénarios, Pièces, Caméras, Vie de famille, Volets, Énergie, Chauffage, Boutons rapides, Poubelle
- Carte étroite et haute : contenu en colonne (pièces, scénarios et boutons les uns sous les autres, RDC au-dessus de l’Étage, portail au-dessus des volets, bacs empilés, anneau d’énergie au-dessus des chiffres)
- Carte large et basse : contenu sur une ligne (Poubelle : bac à gauche, boutons à droite ; Sécurité : état à gauche, tuiles à droite ; Scénarios : pictogramme à côté du nom)
- Les cartes peuvent donc être beaucoup plus petites ; une carte haute peut être plus étroite. Les tailles de texte ne changent pas
- Mode Déplacer : poser le doigt sur la carte et la faire glisser, elle suit le doigt
- Poignées de taille toujours entières, même quand la carte touche le haut ou un bord de la grille

## 0.4.4 (19/11/2026)
- Flèches : si une carte gêne, les deux échangent leur place (quelle que soit leur taille) ; si plusieurs gênent, elles descendent. Plus de refus, sauf au bord
- Taille : élargir réduit d’abord la voisine (tant que son contenu tient), puis ce qui chevauche descend ; agrandir vers le haut est permis
- Poignées de taille beaucoup plus grandes (58 × 128) ; la croix rouge n’apparaît plus en mode Taille (elle gênait), « Retirer » reste dans le panneau

## 0.4.3 (19/11/2026)
- Taille de police d’Android ignorée : plus de « 11° / C », « 11,0 / kWh », « 20,6° / C » sur la Samsung
- Retoucher la carte choisie la lâche ; flèches à droite de la carte ; poignées jaunes à cheval sur les bords
- Élargir réduit d’abord la voisine (jusqu’à sa taille minimale), sinon elle passe dessous ; agrandir vers le bas pousse vers le bas
- Flèche bloquée par une carte de taille différente : la carte s’insère et l’autre est poussée
- Une carte agrandie grandit avec son contenu (jusqu’à ×1,6), sans jamais rapetisser
- Mots coupés réparés : consignes du chauffage (tailles A/B/C), Pièces et Pronote (Grandes cartes), tuiles Pièces du téléphone, fenêtre « Nouvel appareil » du téléphone

## 0.4.2 (19/11/2026)
- Accueil : appui long de 0,8 s sur une carte → mode modification (grille, carte choisie en jaune)
- Déplacer : flèches ou glisser la carte ; une carte de même taille qui gêne est échangée, sinon message
- Taille : poignées jaunes sur les 4 bords (toucher ou glisser) ; les cartes voisines sont repoussées ; une carte ne descend jamais sous la taille où son contenu tient
- Retirer une carte (croix rouge) et la remettre depuis la Galerie ; Définir défaut / Réinitialiser
- Téléphone : Monter / Descendre / Retirer, Galerie
- Paramètres → Appareil : ligne « Mise à jour de l’appli » directement (Installer / Rechercher) ; connexion sur une ligne à part
- Roue Paramètres : toute la zone répond au toucher

## 0.4.1 (19/11/2026)
- Chauffage : les consignes (« 20,0°C ») restent sur une ligne.
- Sécurité : pastilles des ouvertures de même largeur, texte centré ; bilan de la semaine mis en forme (période, une ligne par point, « À voir » en liste) ; bouton « Scénario Absence » qui ne déborde plus.
- Pronote : onglets tous de la même hauteur.
- Dock : bulle plus grande qui glisse d’une page à l’autre ; en faisant glisser le doigt sur le dock, la bulle suit et la page s’ouvre au lâcher (tablette et téléphone).

## 0.4.0 (19/11/2026)
- Paramètres → Taille de l’affichage (tablettes) : Standard, Tout agrandir, Grandes cartes, Gros textes, comme la version web. Réglage propre à chaque appareil.
- En taille agrandie : écran agrandi, Accueil sur 3 colonnes (2 en « Grandes cartes »), en-tête sans la météo avec la présence résumée sous les avatars (toucher = détail).
- Paramètres → « Rouvrir l’appli après une mise à jour » : une autorisation Android à donner une fois, ensuite l’appli se relance seule après chaque mise à jour.
- Paramètres : la ligne « Annonces : pièces concernées » est retirée (doublon de la carte Vie de famille).
- Page Chauffage : les 4 cases de la chaudière ne coupent plus leur texte.

## 0.3.9 (19/11/2026)
- Plus aucun texte coupé par « … » sur les écrans 1280×800 et téléphone : pastille d’alerte de l’en-tête sur 2 lignes, état de la chaudière (carte Chauffage), noms de la page Sécurité, volets, pièces.
- Dock : le bouton Paramètres est retiré (la roue à côté de l’heure suffit).
- Paramètres : « Écrire une annonce » retiré (le choix des pièces reste).

## 0.3.8 (19/11/2026)
- La roue ouvre maintenant la page Paramètres (comme la version web) ; « Connexion et mise à jour » s’y trouve dans la carte Appareil.
- Code 0000 demandé avant d’éteindre la prise TV ou la prise NAS (réglable dans Paramètres).
- Journal de démarrage de Home Assistant : intégrations Ok / en cours / en erreur, erreurs depuis le démarrage, mis à jour toutes les 3 s.
- Annonces : choix des pièces (gardé sur l’appareil) et « Écrire une annonce ».
- Ajouter un appareil : recherche des appareils récents et fenêtre « Nouvel appareil détecté » (type, nom, pièce).

## 0.3.7 (19/11/2026)
- Page Sécurité (résumé, bilan de la semaine, Maintenance, État des capteurs avec Ignorer partagé, Ouvertures, Portail, garage, Raccourcis).
- Page Automatismes (automatismes de la maison, Mes automatismes, éditeur complet, aide IA).
- Page Pronote (téléphone : 5 cartes ; tablette : récapitulatif + onglets).
- Boutons choisis en blanc comme dans la version web.
## 0.3.6 (19/11/2026)
- Chaudière : durée « depuis » lue dans l’historique (comme la version web).
- Dessins de la version web (chaudière, dock, météo, scénarios, portail, volets, caméras, anneau Énergie, bacs).
- Vie de famille identique à la version web ; 2 rangées sur téléphone étroit plutôt que des textes coupés.
- Chauffage : boutons de mode en grand, « Mode actuel », température 38 px.
- Bilan du jour : anneaux au-dessus de la légende sur téléphone.
## 0.3.5 (19/11/2026)
- Téléphone : message d’alerte de l’en-tête en entier, sous le titre.
- Téléphone : boutons de Vie de famille à leur largeur (textes entiers).
- Tablette : annonces de Vie de famille entières (crayon seul dès 3 annonces).
- Textes des boutons étroits (Rez-de-chaussée, Mi-ombre, Confort) plus rapetissés.
- Mode debug : changement de page et défilement commandés depuis Home Assistant.
## 0.3.4 (18/11/2026)
- Nouvelle page Énergie : flux en direct (solaire, réseau, maison, batterie), production prévue (Solcast), courbe de la journée avec la prévision, bilan du jour.
- Nouvelle page Caméras : les trois caméras en photo ; toucher une photo pour l'agrandir, zoom à deux doigts, double toucher pour zoomer.
- Accueil, carte Caméras : la pastille verte ne s'allume plus que lorsque la photo est vraiment reçue (avant, elle restait verte même sans photo).

## 0.3.3 (18/11/2026)
- Test de la connexion : si l'adresse en http:// ne répond pas, l'appli essaie la même en https:// et affiche le conseil « Essaie plutôt https://… ».

## 0.3.2 (18/11/2026)
- Réglages : bouton « Tester la connexion » qui vérifie, étape par étape, l'adresse, que Home Assistant répond, que le jeton est accepté et que la liaison en direct s'établit ; en cas d'échec, la raison est écrite en clair.
- « Enregistrer et lancer » fait ce test d'abord et refuse une adresse ou un jeton qui ne marchent pas.
- La bannière de reconnexion affiche la vraie raison (nom introuvable, délai dépassé, certificat refusé…) au lieu de « Connexion perdue ».
- Téléphone : les boutons des réglages ne débordent plus de l'écran.

## 0.3.1 (18/11/2026)
- Mode debug dans les réglages (éteint par défaut). Allumé : le journal de l'appli (liaison, erreurs, actions, lenteurs d'affichage) est écrit dans le journal de Home Assistant ; un bouton rouge en bas à droite envoie une capture de l'écran dans le dossier Média de Home Assistant. Rien ne part ailleurs que vers ton Home Assistant.
- Mises à jour plus sûres : l'appli n'accepte un téléchargement que depuis ce dépôt (https), vérifie l'empreinte SHA-256 du fichier avant de proposer l'installation et refuse un fichier abîmé ou modifié. Android refuse de toute façon une version qui n'est pas signée par la même clé.
- Les nouveautés de chaque version sont détaillées dans les réglages avant d'installer.

## 0.3.0 (18/11/2026)
- Pages Pièces, Volets et Chauffage (tablette et téléphone).
- Version de l'appli affichée dans les réglages.

## 0.2.2 (18/11/2026)
- Mise à jour de l'appli depuis les réglages (pastille jaune « Mise à jour » quand une version est disponible).

## 0.2.1 (18/11/2026)
- Disposition téléphone : en-tête, cartes en une colonne, barre de pages en bas.

## 0.2.0 (18/11/2026)
- Première version : connexion à Home Assistant (adresse + jeton), page Accueil de la tablette.
