# The Worst Roommate

Un survival psychologique urbain. Chaque soir, vous rentrez au studio. Les tâches ménagères deviennent un rituel où l’angoisse monte. Vos choix sculptent une semaine complète d’événements dynamiques, avec fins multiples et comportements imprévisibles du colocataire.

- Genre: Survival psychologique, narratif
- Contexte: Appartement urbain, quotidien qui déraille
- Boucle de jeu: 7 jours (retour, gestion, surveillance, repos)
- Moteur: Unreal Engine 5
- Plateforme: PC
- Style visuel: PS1 maîtrisé

Lien officiel: https://lburdier.fr/projects/the-worst-roommate.html

## Axes de conception

- Immersion par les sons domestiques, espaces exigus, lumières faibles
- Lecture environnementale: objets déplacés, déchets, odeurs suggérées par le design sonore
- Tension progressive; jumpscares maîtrisés et justifiés par la narration
- Appartement semi-procédural (agencement, saleté, points d’intérêt) pour varier chaque run

Voir: https://lburdier.fr/projects/the-worst-roommate.html#about

## Mécaniques principales

- Routines et tâches: checklist dynamique (vaisselle, poubelle, tri, serpillière) impactant odeur, infestation, patience; pièces propres = stress réduit
- Système de suspicion: jauge invisible; fouiller/déplacer/photographier ↑; collaborer/notes/compromis ↓; réactions: silences, regards, portes claquées, messages
- Sanité & hallucinations: stress ⇒ vision tunnel, grain, aberrations, faux sons; se stabiliser via douche chaude, musique, appel ami, lumière chaude
- IA du colocataire: horaires semi-procéduraux, zones de confort, déclencheurs d’humeur; comportements: évitement, passif-agressif, sabotage, confrontation
- Événements contextuels: coupure de courant, fuite d’eau, odeur de brûlé, bruits nocturnes, colis, visiteurs; multiples résolutions; carnet d’indices intégré
- Stealth domestique: marcher sans grincer, obscurité partielle, diversion (radio, micro-ondes, robinet); pas d’armes, sang-froid et méthode
- Preuves & narration: photos, factures, historiques, notes manuscrites; servent à négocier, alerter, ou déclencher une fin; manques = biais d’interprétation
- Économie du temps: soirées courtes; arbitrer entre ranger, enquêter, dormir; manque de sommeil ⇒ paranoïa

Voir: https://lburdier.fr/projects/the-worst-roommate.html#mechanics

## Fonctionnalités clefs et systèmes

- Fins multiples: au moins 7 fins selon l’ordre, les preuves et l’escalade des conflits
- QTE ponctuels, courts et lisibles (pas de punition gratuite)
- IA: humeur, routines, zones et réactions contextuelles
- Cycle Jour/Nuit: 7 jours, événements et tensions évolutives
- Relations: messages, notes, dialogues brefs, seuils de confiance
- PC & Téléphone diégétiques: journal, photos-preuves, tâches, messagerie
- Conséquences persistantes: scènes, IA, fins
- Génération: layout, encombrement, pannes et points d’intérêt semi-procéduraux
- Cinématiques brèves aux moments clés (cam fixe/épaulé)
- Hallucinations pilotées par la barre de stress

Voir: https://lburdier.fr/projects/the-worst-roommate.html#mechanics

## Chara Design & Direction artistique

### Intention et style PS1
- Limiter la fidélité pour stimuler l’imaginaire; lisibilité des silhouettes; focus son/lumière/timing
- Recettes: textures basse résolution, palette réduite, filtrage point, dithering subtil, légère instabilité sub-pixel pour l’écho vintage
- UI diégétique: menu minimal façon carte de transport; journal sur téléphone; sauvegardes par points de routine

Voir: https://lburdier.fr/projects/the-worst-roommate.html#style

### Personnages
- Protagoniste: silhouette fine, vêtements quotidiens, expressions sobres; nervosité contenue; poses au bord du lit; palette froide, touches chaudes; smartphone carnet; animations courtes, respirations audibles
- Le colocataire: posture instable, cheveux en désordre, lunettes abîmées; états: neutre/irritable/absent/menaçant; yeux hors lumière; silhouette reconnaissable; gestuelle saccadée, micro-tremblements; voix feutrée, souffle en micro distant

Voir: https://lburdier.fr/projects/the-worst-roommate.html#characters

### Environnements UE5 & pipeline visuel
- Modélisation low-poly pour silhouettes lisibles
- Génération procédurale d’appartements (layout, encombrement, éclairage)
- Textures 256–512 px, atlas partagés, UV packs sobres
- Lighting stationnaire, baked GI, downsample ciblé
- Post-process: grain, vignette légère, légère aberration chromatique
- Audio: foley domestique multicanal, réverb légère par pièce

Voir: https://lburdier.fr/projects/the-worst-roommate.html#environments

## Équipe

The Worst Roommate est un projet collaboratif.

- Lucas Burdier — Chef de projet, Game Designer & Développeur
  - Supervision du concept, développement du prototype, direction artistique et ton narratif
- Léo Daurelle — 3D Artist, RDI & Level Designer
  - Environnements low-poly, scènes d’appartement, intégration lumières UE5
- Léo Chérubin — Modeleur 3D & RDI
  - Conception de modèles 3D low-poly
- Emma Escudero — Chara Designer, RDI & Illustratrice
  - Recherche visuelle des personnages, variations d’états émotionnels, silhouettes style PS1

Voir: https://lburdier.fr/projects/the-worst-roommate.html#team

## Communauté & Discord

Un serveur Discord officiel ouvrira prochainement (actuellement indisponible). Il permettra de discuter des avancées, d’être informé des annonces, playtests et recrutements, de partager des créations et de rejoindre la communauté.

- Annonce et notifications: https://lburdier.fr/projects/the-worst-roommate.html#announcement
- Section communauté: https://lburdier.fr/projects/the-worst-roommate.html#team

## Outils & pipeline de production

- 3D & Animation: Blender, Maya, Substance 3D Painter, Leonardo AI
- Moteur de jeu: Unreal Engine 5 (lighting, Blueprints, IA comportementale); gestion procédurale de l’appartement et scripts d’événements quotidiens
- Audio & Narration: DaVinci Resolve/Fairlight, FL Studio, ElevenLabs AI (voix in-game pour tests)
- Organisation & Collaboration: Miro, Discord
- Versioning & Suivi: GitHub (branches par module; organisation par jours de jeu; validations via PR)
- Rendu & Optimisation: pipeline simplifié, compatibilité PSX-style, intégration UE5 optimisée avec Nanite low-poly

Voir: https://lburdier.fr/projects/the-worst-roommate.html#production

## Roadmap & avancement

- Pré-production GDD v1 — En cours: écriture du GDD, mécaniques clés, moodboard, pipeline, planification du prototype
- Prototype vertical slice — À venir: boucle d’une soirée, IA coloc basique, 2 événements contextuels
- Art pass — À venir: pack textures PS1, lighting cohérent, premiers SFX
- Playtests fermés — À venir: itérations UX, options confort, équilibrage sanité/suspicion
- Démo publique — À venir: une soirée complète, embranchements, 2 fins

Voir: https://lburdier.fr/projects/the-worst-roommate.html#roadmap

## FAQ

- Le projet est-il rémunéré ? — Pour l’instant, participations bénévoles (pré-production et prototypage). Crédits et références seront mentionnés sur les supports officiels.
- Comment rejoindre l’équipe ? — Via le formulaire de contact en bas de la page; préciser compétences et lien vers portfolio/travaux.
- Quand pourra-t-on jouer à la démo ? — Après la finalisation du prototype; une masterclass présentera les premières scènes et mécaniques.
- Quelle est la durée prévue du développement ? — Plusieurs mois, rythme progressif selon disponibilités; roadmap publique mise à jour.
- Dans quel esprit s’inscrit The Worst Roommate ? — Tension du quotidien, isolement, perception, paranoïa. Inspiré par des faits réels et expériences de colocation.

Liens: https://lburdier.fr/projects/the-worst-roommate.html#faq | https://lburdier.fr/projects/the-worst-roommate.html#contact | https://lburdier.fr/projects/the-worst-roommate.html#announcement

---

© 2025 The Worst Roommate — Projet narratif et psychologique en développement. Site: https://lburdier.fr/projects/the-worst-roommate.html
