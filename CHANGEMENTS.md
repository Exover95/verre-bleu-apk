# Verre bleu natif : historique des versions

## 0.6.7 (27/11/2026)
- Page Chauffage refaite d'après les maquettes : température et consigne en cours (−/+), mode (Auto / Confort / Éco / Arrêt), autre zone, programmation de la semaine (barres lune / soleil, interrupteur Activée), réglages rapides (Confort, Éco nuit, Vacances), plages d'aujourd'hui, chaudière, « Tout est au vert » (ou ce qui ne va pas).
- Modifier la programmation : jours en pastilles, heures au choix par quart d'heure, « Aussi pour », confirmation avant tout envoi.
- Page Musique (Music Assistant) : bibliothèque, lecture, enceintes groupées, barre de lecture sur l'Accueil.
- Écran de veille : luminosité baissée au bout de 10 min (20 % le jour, 5 % la nuit), jamais au noir ; les 3 caméras en bas ; réveil par le capteur de proximité, la caméra ou le son selon la tablette (réglages dans Paramètres).

## 0.6.4 (27/11/2026)
- Plus fluide : seules les zones animées (dessins, météo, horloges, compte à rebours des caméras) sont redessinées, au lieu de tout l'écran à chaque image.

## 0.6.3 (27/11/2026)
- Gel corrigé : après le réveil de l'écran de veille par un toucher, l'appli ne répondait plus à aucun toucher (il fallait la fermer).
- Correction d'une erreur du choix de mise en page des cartes.

## 0.6.2 (27/11/2026)
- Réveil par la caméra (tablettes Android) : pendant l'écran de veille, la caméra avant voit quelqu'un passer et rallume l'écran ; Paramètres → Réveil par la caméra (Non / Faible / Moyenne / Forte). Aucune image gardée ni envoyée
- Écran fixe : Paramètres → Défilement de l'Accueil → Fixe ; toutes les cartes sur un écran (si elles tiennent, sinon la page défile)
- Boutons rapides : le nom n'est plus coupé dans les petites cases
- Mode debug : liste des capteurs de l'appareil envoyée au journal

## 0.6.0 (27/11/2026)
- Accueil : quand une carte est agrandie, son dessin grandit et remplit la place (dessin en haut et texte dessous si la carte est haute, dessin à gauche si elle est large)
- Scénarios, Volets, Sécurité (Portail / Volets), Météo, Énergie, Chauffage (flamme par zone), Poubelle (bac en grand), Boutons rapides, Vie de famille (grandes tuiles d'annonce)
- Police par paliers (×1, ×1,15, ×1,3, ×1,5) : chaque carte prend le plus grand qui tient, sans jamais couper un texte
- Disposition d'origine inchangée sur la Hikvision

## 0.5.20 (27/11/2026)
- Annonce de la maison : les enceintes ne sont plus coupées quand le clavier apparaît (petit dessin à côté du nom)
- Dessins des enceintes plus petits quand le clavier est fermé
- Au téléphone, deux enceintes par ligne

## 0.5.19 (26/11/2026)
- Page Chauffage : nouvelle carte « Programme de la semaine » (RDC / Étage), une ligne par jour
- Toucher un jour : jusqu'à 3 plages, réglage par 15 min ou 1 h, copie vers d'autres jours (Lun → Ven, Tous)
- Après l'envoi, la chaudière est relue : « Enregistré » ou « pas confirmé » avec Réessayer

## 0.5.18 (26/11/2026)
- Écran de veille : grande heure, météo animée et prévision, famille, cases utiles (bac, soleil, batterie, chauffage, maison, devoirs), fond selon l'heure
- iPad mini et petites tablettes : Accueil en 3 colonnes sous 1150 px de large
- Tablette en portrait : disposition téléphone
- Présence résumée sous les avatars et consignes du chauffage lisibles sur les écrans moins larges

## 0.5.17 (26/11/2026)
- Horloge de veille (tablettes) : après 3 min sans toucher, heure, date, températures, bac du soir, cours d’Iliana, alertes ; écran au minimum ; le 1er toucher réveille seulement
- Fenêtres automatiques comme sur le web : rappel poubelles, portail resté ouvert, photo « Le portail s’ouvre », interphone (photo, ouvrir le portail, direct)
- Toucher l’alerte de l’en-tête ouvre « Messages et alertes » ; « Voir » mène à la page Sécurité

## 0.5.16 (26/11/2026)
- Réseau : nouvelle présentation (Internet, la Bbox dessous, puis une branche par port 1 à 4 et par Wi-Fi de la box) ; gros textes ; sur tablette on glisse de côté
- Réseau : sous le routeur, « Port du routeur » et « Wi-Fi du routeur » ; un téléphone ou une enceinte n’est jamais mis en câble
- Réseau : lecture directe du routeur Netgear R7000 (mot de passe dans « Accès box et routeur ») : câble ou Wi-Fi 2,4 / 5 GHz, vitesse, signal, et état de ses ports
- Énergie : le bouton « Bilan financier » apparaît aussi quand la page a été réorganisée

## 0.5.15 (26/11/2026)
- Page Volets : même dessin animé que l’Accueil (le volet s’ouvre / se ferme quand il bouge) ; interrupteur « Volets » dans Paramètres → Animations
- Réseau : schéma en arbre (Home Assistant sous le NAS, Shield sous le CPL, Wi-Fi du R7000 déduit), pièce de chaque appareil, choix « Pièce » et « Relié à » dans la fiche
- Énergie : Bilan financier (années, mois, jours, détail horaire), chaque mois lu est gardé dans l’appareil

## 0.5.14 (25/11/2026)
- Accueil, carte Sécurité : grande jauge à gauche, Portail et Volets l’un sous l’autre à droite (comme ta maquette)
- Paramètres : case « Dock escamotable », valable pour tous les styles de dock et aussi sur le téléphone (remplace le style « Escamotable »)
- Volets : le dessin s’ouvre / se ferme quand un volet bouge (carte Volets de l’Accueil, tuile Volets de Sécurité)
- Pièces → Adoucisseur : sel et date d’épuisement, eau adoucie du jour et moyenne, eau disponible, dernière régénération, calcaire retiré (kg), débit (L/min) ; sur téléphone, toucher la tuile
- Réseau : ports Ethernet au bon numéro (1, 3, 4), port 2 « libre », appareils non connectés repliés sous un bouton

## 0.5.13 (25/11/2026)
- Réseau : l’état d’Internet est lu correctement (il affichait « coupé » à tort) ; rond rouge s’il est vraiment coupé
- Réseau : le journal montre aussi le branchement brut de chaque appareil donné par la box (pour corriger les numéros de port)

## 0.5.11 (25/11/2026)
- Réseau de la maison : la lecture suit maintenant les renvois de la box (erreur « code 302 »)
- Réseau : bouton « Journal » (chaque échange avec la box, sans le mot de passe), avec « Copier » ; il s’ouvre tout seul en cas d’échec

## 0.5.9 (25/11/2026)
- Paramètres → nouvelle carte « Technique » → « Réseau de la maison » : tous les appareils connectés à la box (IP, port Ethernet ou Wi-Fi, connecté ou non), schéma Internet → Bbox → ports ; « Nouveau » sur un appareil jamais vu ; bouton « Chercher de nouveaux appareils » ; toucher un appareil = fiche + renommer
- Le mot de passe de la box (et l’adresse d’accès à distance) se saisissent une fois, gardés chiffrés sur l’appareil seulement
- Page Chauffage : case « Retour eau » ; cases rangées selon la place (aucun mot coupé)
- Dessin de la chaudière : température de l’eau sur son écran
- Carte Sécurité : cercle « Maison sécurisée » plus grand

## 0.5.7 (25/11/2026)
- Paramètres → Style du dock : trois styles en plus (tablettes) : « Icônes seules » (dock étroit, nom de la page ouverte seulement), « Barre en bas » (dock sous les cartes, sur toute la largeur), « Escamotable » (le dock se cache après 5 s ; toucher ou glisser depuis le bord gauche pour le faire revenir)
- Téléphone : la barre du bas reprend le bleu de Verre bleu




## 0.5.6 (25/11/2026)
- Dock : retour au bleu de Verre bleu (la forme courbe est gardée) ; aucun nom ne dépasse plus du panneau : « Automatismes » devient « Routines » dans le dock, et chaque nom est limité à la largeur de la courbe à sa hauteur
- Carte Sécurité : Portail en haut et Volets en bas, en deux grandes tuiles tactiles sur toute la hauteur de la carte ; la jauge prend toute la place restante

## 0.5.5 (25/11/2026)
- Dock : le bord droit du panneau est maintenant en courbe, comme ta photo de référence (plus étroit en haut et en bas) ; la page choisie va jusqu’au bord et le trait cyan suit la courbe
- Carte Sécurité : Portail / Volets plus grands, la jauge laisse plus de place au texte

## 0.5.4 (25/11/2026)
- Dock refait d’après ta photo de référence : panneau ardoise, pictogrammes en relief, page choisie en cyan avec une tuile collée au bord et un trait lumineux sur le bord du panneau
- Carte Sécurité : « Maison Sécurisée » n’est plus jamais coupé ; la jauge et Portail / Volets prennent toute la place de la carte, en grand
- Le style Classique du dock reste au choix dans Paramètres

## 0.5.3 (25/11/2026)
- Carte Sécurité : les dessins animés du portail et des volets sont revenus, à côté de Portail et Volets
- Portail : plus de double appui ; une fenêtre demande « Ouvrir le portail ? » (ou « Fermer ») avec Annuler / Ouvrir (Accueil et page Sécurité)
- Paramètres → Style du dock : Verre (nouveau) ou Classique (dock d’avant)

## 0.5.2 (25/11/2026)
- Dock : panneau de verre flottant aux coins arrondis ; la page choisie s’éclaire, avec un trait lumineux sur le bord (aussi sur le téléphone)
- Carte Sécurité : jauge circulaire lumineuse « Maison Sécurisée » (rouge avec le nombre d’alertes s’il y en a), Portail et Volets à droite avec un trait d’état vert / ambre, cadenas en haut à droite
- Sécurité : toucher la jauge ouvre la page Sécurité, toucher Volets ouvre la page Volets, le portail garde le double appui

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
