# SIR-Influence
Support pour un projet de mémoire. 
Les opérations d'influence se propagent comme des virus : un vecteur, une population exposée, des individus "immunisés" par le sens critique ou un contre-narratif.

## Prémice
Les opérations d'influence (IO) — désinformation, narratifs adverses, manipulation cognitive — se propagent dans les réseaux sociaux selon des dynamiques qui rappellent fortement celles d'une épidémie : un vecteur initial, une population exposée, des individus "immunisés" (esprit critique, contre-narratif) et une phase d'extinction ou d'endémicité.

Ce projet explore si le modèle SIR (Susceptible → Infected → Recovered), standard en épidémiologie computationnelle, constitue un cadre analytique valide pour modéliser la propagation d'une opération informationnelle dans un espace numérique.

## Hypothèse de départ
H₀ : La dynamique de diffusion d'un narratif d'influence suit une courbe épidémique modélisable, caractérisée par un taux de reproduction de base (R₀) propre au narratif, au vecteur et à la population cible.

Corollaires testables :

Un narratif à fort R₀ (haute virulence + faible immunité) peut saturer un espace informationnel en quelques heures
Une intervention (fact-check, contre-narratif, suppression) agit comme une mesure de santé publique — elle modifie β (taux de transmission) ou augmente γ (taux de "guérison")
Certaines populations présentent une immunité naturelle mesurable (exposition antérieure, littératie médiatique)

## Sources & état de l'art
Vosoughi et al. (2018) — Science : la désinformation se propage plus vite et plus loin que la vérité sur Twitter
Bettencourt et al. (2006) : premier usage explicite du SIR pour modéliser la diffusion d'idées (meme epidemics)
OTAN / doctrine AJP-3.10 : cadre doctrinal des opérations d'influence en contexte militaire
Roozenbeek et al. (2020) — prebunking comme analogue de la vaccination informationnelle
Modèles SEIR appliqués à la désinformation COVID (2020-2022) : infodémie OMS

## Démarche & feuille de route
Phase 1 (actuelle) — Calibration du modèle SIR de base sur des cas documentés (opérations connues : IRA 2016, narratifs Donbass, etc.)
Phase 2 — Extension vers SEIR (ajout d'un compartiment Exposed = audience exposée mais non encore relayeuse)
Phase 3 — Intégration de métriques au-delà des vues : engagement pondéré, polarité émotionnelle, vélocité de reshare, reach estimé
Phase 4 — Validation croisée avec données réelles (via API X/Twitter, CrowdTangle archivé, GDELT)

## Aller plus loin — précision des mesures
Problème actuel : les "vues" sont un proxy grossier — elles ne distinguent pas l'exposition passive du relai actif, ni l'adhésion du rejet.

Métriques candidates pour affiner β et γ :

Reshare Rate — ratio retweets/vues (proxy du taux de transmission β)
Sentiment Score — polarité émotionnelle des commentaires (proxy d'adhésion vs rejet)
Reach effectif — audience estimée pondérée par le nombre d'abonnés des relais
Time-to-peak — délai entre injection du narratif et pic de diffusion
Cross-platform spillover — migration vers d'autres plateformes (Telegram, forums)

