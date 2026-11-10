# NIMR SAV V24 — Recette frontend 2026

Pages publiques indépendantes, réservées à la présentation de V24 :

- [Accueil V24](https://irondrass.github.io/NIMR-SAV-V24-2026/)
- [**Démonstration interactive**](https://irondrass.github.io/NIMR-SAV-V24-2026/demo/) : trois dossiers fictifs, recherche, états, planning, paramètres et création d'un dossier d'exemple. Tout reste en mémoire de la page et disparaît au rechargement.
- [Interface technique non connectée](https://irondrass.github.io/NIMR-SAV-V24-2026/app/) : compilation directe de l'interface React V24, écran d'activation sans backend.

**Ce dépôt est réservé aux démonstrations et recettes, pas à la production.** Les données de démonstration sont fictives. Aucun code appareil réel, VIN réel, numéro de téléphone ou donnée client ne doit être saisi.

Le mode démonstration est compilé depuis une copie locale isolée, avec un service de données fictives et sans appel à Supabase. Ce dépôt ne contient aucun code serveur, migration SQL, clé secrète ou fichier source TypeScript.

Les projets de production V23, source privée NIMR-SAV et ancienne recette V24 ne sont pas modifiés.

- [Recette connectée à Supabase](https://irondrass.github.io/NIMR-SAV-V24-2026/recette/) : accès par appareil autorisé, données strictement fictives, backend V24 séparé de V23. Aucune activation publique et aucun vrai dossier client.

**Sécurité recette (10/11/2026) :** le jeton appareil est conservé seulement en mémoire pendant l’onglet actif. Actualiser la page oblige une nouvelle activation. La recette sur le domaine GitHub Pages partagé reste limitée aux données fictives. Un domaine dédié est nécessaire avant toute donnée client ou activation réelle.
