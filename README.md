# bundleweb

**Développeur indépendant à Paris.** Je conçois et je livre des produits complets, seul :
de l'idée à l'application publiée sur le store, en passant par le design, le backend,
l'infrastructure et le déploiement.

[bundleweb.app](https://bundleweb.app) · [gitlab.com/kazarime](https://gitlab.com/kazarime) · contact@bundleweb.app

---

### En production

Deux applications mobiles publiées sur les stores, les backends et les API qui les
servent, et une suite de soixante et un outils en ligne générée par un template Python.
L'ensemble tourne sur une infrastructure que j'administre : conteneurs, déploiement
continu sur push, domaines, certificats, SMTP authentifié.

**L'API Claude tourne en production**, pas en démonstration : analyse d'image, extraction
de données structurées, génération de texte — avec ce que ça suppose de maîtrise du coût
par appel, de la latence et des cas d'échec.

Le code est sous contrat ou commercialement sensible, donc privé. Accès en lecture
possible sur demande, dans le cadre d'un recrutement ou d'une mission.

### Je développe avec des agents, et j'outille ce travail

Coder avec des agents à l'échelle de plusieurs projets simultanés pose des problèmes que
les outils du marché ne traitent pas. J'ai écrit les miens.

**TermPilot** — piloter plusieurs sessions de terminal sous Linux : l'état de chacune, une
notification quand l'une a fini, des noms mémorisés par projet. Quatre formats commutables
au clavier, et un greffon Terminator qui rend chaque split adressable — ce qu'aucun outil
externe ne peut faire, X11 ne voyant qu'une fenêtre par split. Python/GTK3, DBus, service
systemd utilisateur.

**Vigie** — un tableau de bord local de tous mes projets : ouvrir une session dans l'un
d'eux, démarrer son serveur de développement sur un port libre, voir ce qui reste à
committer. Python, bibliothèque standard seule, aucune dépendance.

### Stack

**Mobile** React Native · Expo
**Back** Python · Node.js · PostgreSQL · Supabase · Firebase
**IA** API Claude en production — vision, extraction structurée, agents de code
**Infra** Docker · Coolify · Cloudflare · CI/CD sur push
**Paiement** RevenueCat · Stripe · publication Google Play automatisée

---

Disponible pour missions freelance et pour discuter d'un poste.
