# PROJET_CONTEXTE — L'Atelier Connecté

> Emplacement de ce fichier une fois rempli : racine du projet concerné
> Template source : METHODO/PROJET_CONTEXTE_TEMPLATE.md
>
> ⚠️ INSTRUCTION POUR L'IA (Claude et Cascade)
> Ce fichier est la source de vérité absolue du projet.
> Le lire EN ENTIER avant toute action.
> Toute décision technique qui le contredit est interdite.
> Si une demande sort de ce cadre : poser UNE question avant d'agir.

---

## 1. IDENTITÉ DU PROJET

| Champ | Valeur |
|---|---|
| Nom | L'Atelier Connecté |
| Type | Web |
| Objectif en 1 phrase | Présenter l'offre de services numériques locaux et générer des prises de contact via un formulaire. |
| Statut | ⚠️ À confirmer (En développement / En production) |
| Utilisateurs actuels | ⚠️ À confirmer |
| Dernière mise à jour de ce fichier | 2026-04-14 |

---

## 2. STACK TECHNIQUE

> Tout ce qui n'est pas listé ici ne doit pas être utilisé sans validation.

**Frontend :**
- Framework : Aucun framework (site statique)
- Langage : HTML5, CSS3, JavaScript
- Composants UI : Sections vitrine (Accueil, À propos, Services, Cas concret, Tarifs, Contact)
- Gestion de l'affichage dynamique : JavaScript DOM (menu mobile, scroll smooth, animations IntersectionObserver, gestion formulaire)

**Backend :**
- Framework : Aucun
- Langage : Aucun
- Port local : N/A (prévisualisation via serveur statique IDE)

**Base de données :**
- Technologie : Aucune
- Outil de liaison avec le code : Aucun
- Lancement en local : N/A

**Services externes :**
- Comptes utilisateurs : Aucun
- Stockage fichiers : Fichiers locaux (`assets/`)
- Mise en ligne : GitHub Pages (documenté dans `README.md`)
- Autres : EmailJS (envoi formulaire), Google Fonts, CDN jsDelivr (lib EmailJS)

---

## 3. ARCHITECTURE

> Cette structure ne change pas sans validation écrite dans ce fichier.

```
L-Atelier_connect-/
├── index.html
├── styles.css
├── script.js
├── PROJET_CONTEXTE.md
├── README.md
├── STACK_STANDARD.md
├── _archives/
│   ├── GUIDE-EMAILJS.md
│   ├── PROJET_CONTEXTE_TEMPLATE.md
│   ├── README_METHODE.md
│   └── ressources/
│       ├── BASE DE SPEECH – Porte à porte ...md
│       ├── DESIGN_SYSTEM.md
│       ├── DOCUMENT DE PRÉSENTATION ...md
│       ├── Document de cadrage stratégique perso ...md
│       └── PROMPT_CASCADE_REFONTE.md
├── assets/
│   ├── Logo base.jpeg
│   ├── base 1 .png
│   ├── fond 1.jpg
│   ├── fond 2.jpg
│   ├── instagram.png
│   ├── logo simple.png
│   └── titre clair.png
├── ressources/
├── emailjs-template.html
└── template-reponse-gmail.html
```

**Nombre de services actifs :** 3 / 20 maximum

---

## 4. FONCTIONNALITÉS

### ✅ Stables (ne pas toucher sans raison)
- Navigation responsive avec menu mobile et liens d'ancrage.
- Page vitrine complète avec sections marketing.
- Formulaire de contact connecté à EmailJS.
- Animations d'apparition au scroll.

### 🚧 En cours (mission actuelle uniquement)
- Reprise projet existant : création du contexte projet et alignement documentaire.

### ❌ Bugs connus
- ⚠️ À confirmer (aucun bug formalisé dans la documentation actuelle).

### 🔒 Hors scope (ne jamais implémenter sans décision explicite)
- Ajout d'un backend ou d'une base de données.
- Refonte visuelle majeure du site.
- Ajout de nouvelles dépendances tierces.

---

## 5. RÈGLES STRICTES DU PROJET

- Ne modifier QUE les fichiers concernés par la mission en cours.
- Ne créer aucun nouveau fichier sans le lister ici après création.
- Ne pas ajouter de dépendance sans demande explicite.
- Modifier l'existant avant d'en créer du nouveau.
- Zéro structure vide créée "pour le futur".
- Pendant la reprise P2 : aucune suppression définitive, aucun refactoring, aucune modification de code applicatif.

---

## 6. DÉCISIONS FIGÉES

> Ces décisions ont été prises et validées. Elles ne se remettent pas en question.

| Date | Décision | Raison |
|---|---|---|
| ⚠️ À confirmer | Le site reste une application statique sans backend. | Simplicité de maintenance et coût réduit. |
| ⚠️ À confirmer | Le formulaire de contact utilise EmailJS côté client. | Éviter la mise en place d'un serveur d'envoi. |
| ⚠️ À confirmer | Les visuels sont stockés localement dans `assets/`. | Déploiement simple sur hébergement statique. |

---

## 7. FICHIERS DE DOCUMENTATION AUTORISÉS

> Maximum 6 fichiers .md à la racine

| Fichier | Rôle |
|---|---|
| PROJET_CONTEXTE.md | Source de vérité (ce fichier) |
| CHANGELOG.md | Historique des missions terminées |
| BUGS.md | Bugs connus et leur statut |
| README.md | Présentation du projet |
| STACK_STANDARD.md | Stack de référence |
| CADRAGE_STRATEGIQUE.md | Identité, positionnement et règles de communication de L'Atelier Connecté |

Tout autre fichier `.md` va dans `_archives/`.

---

## 8. SESSION EN COURS

> Remplir EN DÉBUT de session. Compléter EN FIN de session.

### Session précédente (avril 2026 — clôturée rétroactivement le 2026-08-15)

**Objectif de la session :** Nettoyage visuel section cas concret, correction bug JS animation, intégration normes design, suppression fichiers parasites.
**Fichiers concernés :** `index.html`, `styles.css`, `script.js`, `PROJET_CONTEXTE.md`, `_archives/ressources/`.
**Hors scope cette session :** sections `hero`, `apropos`, `services`, `tarifs`, `contact`, `footer`, navigation, EmailJS hors ligne 43, `README.md`, `STACK_STANDARD.md`, `assets/`.
**Résultat de fin de session :** Jamais refermée formellement à l'époque — reprise identifiée lors de l'audit du 2026-08-06 (section 11). Clôturée rétroactivement sans reprise de contenu ; le travail effectif de cette période est reflété par les commits `00b72fa` et `1fc008f` de l'historique git.

### Session du 2026-08-15 — Unification des offres site/outils + IA

**Objectif de la session :** Fusionner l'offre historique (sites/outils sur mesure) et l'offre architecture/automatisation IA en un seul profil cohérent, sur une seule page.
**Décision structurante :** intégration complète dans les sections partagées existantes (`#services`, `#realisations`, `#tarifs`, formulaire de contact), plutôt qu'un système d'aiguillage vers deux blocs séparés (V1 jugée non challengée, offres juxtaposées sans unification). À l'intérieur de `#services`, sous-titres de sous-groupes conservés pour garder une lisibilité entre les deux types de prestations.
**Fichiers concernés :** `index.html`, `styles.css`.
**Hors scope cette session :** le backlog de l'audit de reprise du 2026-08-06 (section 11 — statut du site, utilisateurs actuels, décisions figées section 6, `graphify-out/`, mention obsolète "Cascade" en pied de page) reste en attente, traité dans une session dédiée à part.
**Vérification :** rendu contrôlé visuellement en desktop et mobile (preview locale), aucune anomalie constatée.
**Résultat de fin de session :** ✅ Testé et commité (`5366869`). Push vers `origin/main` en attente — échec 403 (droits d'accès du compte git local insuffisants sur le repo distant, à résoudre par Kinder).

---

## 9. BACKLOG (missions suivantes)

> Ordonné par priorité. Ne jamais commencer la suivante sans que la précédente soit ✅ testée.

1. Valider et compléter les champs marqués `⚠️ À confirmer`.
2. Finaliser la reprise P2 (archivage docs + vérification structure + alignement validé).
3. Formaliser les bugs connus dans `BUGS.md` si nécessaire après test manuel.

---

## 10. NORMES DE DESIGN

### Palette (variables CSS source)

- `--primary-color` : `#7ed957`
- `--primary-dark` : `#5fb83a`
- `--secondary-color` : `#d4a574`
- `--dark-bg` : `#2a2520`
- `--dark-wood` : `#3d3530`
- `--light-bg` : `#f8f7f5`
- `--text-dark` : `#2a2520`
- `--text-light` : `#ffffff`
- `--text-gray` : `#6b6b6b`

### Typographie

- Police unique projet : `Poppins`, sans-serif.
- Tailles repères :
  - Titres section (`h2`) : `2.5rem`
  - Titre hero (`h1`) : `3rem`
  - Sous-titres section : `1.1rem`
  - Texte courant : `1rem` (line-height global `1.6`)
  - Micro-textes/badges/disclaimer : `0.82rem` à `0.95rem`
- Graisses utilisées : `300`, `400`, `500`, `600`, `700`.

### Espacements

- Padding standard des sections : `80px 20px` (mobile `60px 15px`).
- Largeur conteneur : `max-width: 1200px`, padding latéral `20px`.
- Gaps usuels des grilles : `20px`, `24px`, `30px` selon densité du bloc.
- Rayon standard composants : `--border-radius` (`12px`).

### Règles composants

- Cartes : fond défini (`white` ou `var(--light-bg)`), coins arrondis, ombre légère, transition homogène (`--transition`).
- Boutons : `.btn` base commune, variantes `.btn-primary` / `.btn-secondary`, état hover systématique.
- Badges/résultats : texte court, lisible en un coup d'œil, contraste suffisant, usage prioritaire des variables existantes.
- Cas concret : structure `Avant / Après` en grille conservée, disclaimer maintenu si illustration fictive.

### Règles strictes

- Ne jamais créer de nouvelle variable CSS sans validation explicite.
- Ne jamais laisser une section sans fond défini.
- Ne jamais ajouter de placeholder vide.
- Ne jamais casser l'alignement vertical/horizontal des cartes entre desktop et mobile.
- Améliorer l'existant sans refonte globale non demandée.

---

*Template source : METHODO/PROJET_CONTEXTE_TEMPLATE.md*  
*Rempli avec : Cascade (analyse projet existant)*  
*Lu par : Cascade à chaque début de session*

---

## 11. AUDIT DE REPRISE (2026-08-06)

**Constat :** `git status` propre (rien à committer), doc cohérente avec la structure de fichiers réelle. En revanche, plusieurs champs sont restés marqués `⚠️ À confirmer` depuis la création du fichier (14/04/2026) : Statut, Utilisateurs actuels, et les trois décisions figées en section 6 — jamais levés depuis. La section 8 (SESSION EN COURS) affiche encore "Résultat de fin de session : ⚠️ En cours" — la dernière session ouverte n'a jamais été refermée proprement, alors que le dernier commit (`73dbfdd`) date de la réorganisation doc qui a suivi.

**Backlog (reprise, complète le backlog existant en section 9) :**
1. Lever les `⚠️ À confirmer` de la section 1 (Statut réel du site, utilisateurs actuels) — demander directement à Kinder si le site est en ligne / a des vrais utilisateurs.
2. Lever les `⚠️ À confirmer` de la section 6 (décisions figées) — probablement déjà tranché dans les faits (le code applique déjà ces choix), il ne reste qu'à les acter formellement.
3. Refermer proprement la section 8 (SESSION EN COURS) — dernier "Résultat" resté à "⚠️ En cours" depuis avril, aucune trace de clôture malgré des commits ultérieurs.
4. Pas de `graphify-out/` — non initialisé, à faire avant toute mission de fond (le site a dépassé le stade minimal : plusieurs fichiers, EmailJS, `_archives/`).
5. Le pied de page mentionne encore Cascade comme outil pilote — obsolète selon la méthode actuelle (Claude Code), à corriger à la prochaine reprise.
