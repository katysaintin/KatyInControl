Contexte : site KatyInControl (katysaintin.github.io/KatyInControl), architecture
data-driven en JSON (site.json, contributors.json, episodes.json, cv.json), vanilla JS,
GitHub Pages.

Deux chantiers à traiter ensemble :

CHANTIER A — Uniformisation de la charte graphique
1. Ajouter dans site.json un bloc "theme" avec les tokens CSS centralisés :
   - couleur primaire = bleu marine de la page d'accueil (référence unique, à extraire
     du CSS actuel de index.html)
   - --color-youtube: #FF0000 / --color-youtube-text: #FFFFFF pour tous les boutons YouTube
   - couleurs secondaires/accent existantes, à documenter dans ce même bloc
2. Ajouter un bloc "analytics" (ID de mesure Google Analytics) et un bloc "favicon"
   (chemin du fichier) dans site.json.
3. Créer un script JS partagé (ex: applyTheme.js) chargé sur CHAQUE page, qui :
   - lit site.json
   - injecte les variables CSS en :root
   - pose le favicon dynamiquement
   - charge le tag Google Analytics
4. Supprimer tout CSS/script GA dupliqué en dur sur les pages individuelles au profit
   de ce script partagé.
5. Vérifier visuellement que toutes les pages (Home, Episodes, Contributors, Stargate,
   About, CV) utilisent bien le même bleu marine après la migration.

CHANTIER B — Intégration de la trilogie "The Genesis" (3 épisodes spéciaux)
1. Page Home : ajouter une carte/badge "Start here — The Genesis" mise en avant tant
   que le cluster est récent (pas un hero permanent figé sur plusieurs mois).
2. Page Episodes : traiter les 3 parties comme un cluster à part, visuellement distinct
   de la numérotation standard S1E01/E02/E03 — PAS "S1E03" pour ne pas casser la
   continuité de la saison normale. Suggestion : carte groupée "Special: The Genesis
   (3 parts)" en haut de page, avant la liste des épisodes numérotés.
3. Page About : ajouter un encart renvoyant vers la version vidéo enrichie de la Genesis.
4. Dans les notes de chaque épisode Genesis (si des pages HTML dédiées existent ou sont
   prévues) : lien retour vers about.html pour le texte/CV complet.

Merci de proposer une implémentation qui respecte le principe JSON = source unique de
vérité, et de minimiser le code dupliqué entre pages.
