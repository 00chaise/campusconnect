# CampusConnect

> Plateforme permettant aux étudiants de découvrir les événements universitaires et de s'y inscrire.

Projet fil rouge du groupe **CCG3** (B1-BX-CS) : Krys-Edouard Henrion-Lescouzeres, Simon Loubere, Vladimir Plasse, Reski Rowan, Daniel Vincent.

---

## 📌 Présentation et objectifs

Sur le campus, les événements (BDE, associations, services de l'école) sont annoncés par des canaux dispersés : affiches, réseaux sociaux, mails. Les étudiants en ratent et les organisateurs ne savent pas combien de personnes viendront.

CampusConnect vise à :

- permettre aux **étudiants** de consulter et rechercher les événements du campus, puis de s'y inscrire pour réserver leur place ;
- permettre aux **organisateurs** de créer, publier et gérer leurs événements.

## 🚧 État réel du projet

| | |
| --- | --- |
| **Phase** | **Conception.** Aucune fonctionnalité n'est développée. |
| **Sprint en cours** | Sprint 1, du 28/10/2026 au 11/11/2026 |
| **Sprint Goal** | « Un étudiant peut voir les événements publiés et s'y inscrire. » |
| **Contenu du dépôt** | Documentation uniquement (diagrammes UML, notes de Sprint). Pas encore de code source. |

Il n'y a donc **pas encore de procédure d'installation** : elle sera ajoutée quand un premier prototype existera.

## 🗺️ Fonctionnalités envisagées

Toutes ces fonctionnalités sont **prévues, aucune n'est développée**.

| Domaine | Fonctionnalité | User Story | Jira | Priorité | Statut |
| --- | --- | --- | --- | --- | --- |
| Consulter | Consulter la liste des événements à venir | US02 | [SCRUM-9](https://ccgroupsix.atlassian.net/browse/SCRUM-9) | MUST | Sprint 1 |
| Rechercher | Rechercher un événement par mot-clé | US01 | [SCRUM-8](https://ccgroupsix.atlassian.net/browse/SCRUM-8) | SHOULD | Backlog |
| S'inscrire | S'inscrire à un événement | US03 | [SCRUM-10](https://ccgroupsix.atlassian.net/browse/SCRUM-10) | MUST | Sprint 1 |
| S'inscrire | Recevoir une notification (catégorie suivie) | US04 | [SCRUM-11](https://ccgroupsix.atlassian.net/browse/SCRUM-11) | COULD | Backlog |
| Gérer | Créer un événement | US08a | [SCRUM-15](https://ccgroupsix.atlassian.net/browse/SCRUM-15) | MUST | Sprint 1 |
| Gérer | Publier un événement | US08b | [SCRUM-16](https://ccgroupsix.atlassian.net/browse/SCRUM-16) | MUST | Sprint 1 |
| Gérer | Modifier un événement | US07 | [SCRUM-14](https://ccgroupsix.atlassian.net/browse/SCRUM-14) | MUST | Backlog |
| Gérer | Annuler un événement | US06 | [SCRUM-13](https://ccgroupsix.atlassian.net/browse/SCRUM-13) | MUST | Backlog |
| Gérer | Consulter la liste des inscrits | US05 | [SCRUM-12](https://ccgroupsix.atlassian.net/browse/SCRUM-12) | WON'T | Hors périmètre |

« Sprint 1 » veut dire que la story est **planifiée** dans le Sprint en cours, pas qu'elle est terminée.

## 🧰 Outils

| Outil | Usage | Lien |
| --- | --- | --- |
| **Jira** | Product Backlog, Sprints, suivi des tickets (clé `SCRUM`) | [Tableau du Sprint](https://ccgroupsix.atlassian.net/jira/software/projects/SCRUM/boards/1) |
| **Confluence** | Documentation fonctionnelle et technique, guide utilisateur | [Espace Campus Connect](https://ccgroupsix.atlassian.net/wiki/spaces/~712020da25d0d047dd4535a21f8f5f3fe9c358) |
| **GitHub** | Dépôt de la documentation versionnée (UML, notes de Sprint) et plus tard du code | ce dépôt |

## 📐 Diagrammes UML

Réalisés avec PlantUML. Les sources modifiables (`.puml`) et les images (`.png`) sont dans [`docs/uml/`](docs/uml/).

| Diagramme | Image | Source |
| --- | --- | --- |
| Cas d'utilisation | [cas_utilisation.png](docs/uml/cas_utilisation.png) | [cas_utilisation.puml](docs/uml/cas_utilisation.puml) |
| Classes | [classes.png](docs/uml/classes.png) | [classes.puml](docs/uml/classes.puml) |
| Séquence : inscription (US03) | [sequence_inscription.png](docs/uml/sequence_inscription.png) | [sequence_inscription.puml](docs/uml/sequence_inscription.puml) |

Les mêmes diagrammes, avec leurs explications, sont sur la page Confluence [03 — Documentation technique](https://ccgroupsix.atlassian.net/wiki/spaces/~712020da25d0d047dd4535a21f8f5f3fe9c358/pages/10944513).

## 📚 Documentation Confluence

| Page | Contenu |
| --- | --- |
| [01 — Présentation du projet](https://ccgroupsix.atlassian.net/wiki/spaces/~712020da25d0d047dd4535a21f8f5f3fe9c358/pages/10911745) | Contexte, objectifs, acteurs |
| [02 — Documentation fonctionnelle](https://ccgroupsix.atlassian.net/wiki/spaces/~712020da25d0d047dd4535a21f8f5f3fe9c358/pages/10911762) | User Stories, règles métier, critères d'acceptation |
| ↳ [Spécification — US03 S'inscrire à un événement](https://ccgroupsix.atlassian.net/wiki/spaces/~712020da25d0d047dd4535a21f8f5f3fe9c358/pages/11239426) | Spécification détaillée liée à SCRUM-10 |
| [03 — Documentation technique](https://ccgroupsix.atlassian.net/wiki/spaces/~712020da25d0d047dd4535a21f8f5f3fe9c358/pages/10944513) | Diagrammes UML, architecture envisagée |
| [04 — Gestion Agile](https://ccgroupsix.atlassian.net/wiki/spaces/~712020da25d0d047dd4535a21f8f5f3fe9c358/pages/10944530) | Sprint Goal, suivi du Sprint, liens Jira |
| [05 — Guide utilisateur](https://ccgroupsix.atlassian.net/wiki/spaces/~712020da25d0d047dd4535a21f8f5f3fe9c358/pages/10977281) | Parcours prévus et FAQ |

## 🤝 Contribuer

1. **Partir d'un ticket Jira.** Tout travail correspond à un ticket `SCRUM-xx`. S'il n'existe pas, le créer dans le backlog et en parler au Product Owner.
2. **Créer une branche** à partir de `main`, avec la clé Jira dans le nom :
   `type/SCRUM-xx-description-courte` (ex. `docs/SCRUM-10-sprint-notes`).
   Types utilisés : `docs`, `feat`, `fix`.
3. **Commits** : un message court qui commence par la clé Jira.
   Exemple : `SCRUM-10 docs: ajout des notes du Sprint 1`.
4. **Pull Request** vers `main`, avec la clé Jira dans le titre. Au moins **un autre membre** relit et approuve avant la fusion.
5. **Garder la documentation cohérente.** Si une règle métier ou un diagramme change, mettre à jour la page Confluence concernée et ajouter le lien de la PR dans le ticket Jira.
6. **Diagrammes UML** : modifier le fichier `.puml`, régénérer le `.png`, puis remplacer l'image sur Confluence.
7. **Ne jamais présenter comme terminé** ce qui n'est pas développé et validé selon la Definition of Done.
