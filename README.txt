AS VILLEROY - Suivi Match PWA v4

CORRECTION PRINCIPALE
- Le choix du buteur et du passeur ne disparaît plus pendant que le chrono tourne.
- Cause corrigée : les listes de sélection étaient recréées chaque seconde par le rafraîchissement du chrono.
- Les listes sont maintenant rafraîchies uniquement à l'ouverture d'une action ou après un changement de joueurs.
- Message d'erreur visible si aucun buteur n'est choisi.

Fonctions conservées
- préparation du match
- 7 titulaires, remplaçants et postes modifiables
- score + chrono 2x40
- 40+1, 40+2...
- reprise seconde mi-temps à 40:00
- buts, passeurs, CSC
- changements et permutations
- sauvegarde à chaque action
- sauvegarde automatique toutes les 5 minutes
- sauvegarde lors du passage en arrière-plan
- export JSON
- fonctionnement hors ligne après installation

MISE À JOUR
1. Remplacer les fichiers du dépôt GitHub par ceux de ce ZIP.
2. Commit changes.
3. Attendre le redéploiement GitHub Pages.
4. Ouvrir le site dans Safari.
5. Vérifier que "Version 4.0" s'affiche.
6. Si l'ancienne version persiste, supprimer l'icône de l'écran d'accueil puis la recréer après rechargement dans Safari.
