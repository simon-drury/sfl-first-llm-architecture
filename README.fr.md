---

**Langue / Language / Idioma / Lingua / Idioma :**
[EN](README.md) | [FR](README.fr.md) | [ES](README.es.md) | [IT](README.it.md) | [PT](README.pt.md)

> *Versions multilingues produites avec [sfl-translation-agent](https://github.com/simon-drury/sfl-translation-agent) — pipeline de traduction SFL-first du même auteur.*

---

# sfl-première-architecture-llm

**© 2026 Simon Drury (sjd_datascapes)**

---

## Ce que c'est

Une spécification publique et horodatée d'une architecture LLM axée sur la linguistique fonctionnelle systémique (LFS).

L'affirmation centrale : la linguistique fonctionnelle systémique — et en particulier les métafonctions idéationnelle, interpersonnelle et textuelle — constitue le cadre correct pour la conception des LLM, l'ingénierie des prompts et l'orchestration des agents. Il ne s'agit pas d'appliquer la LFS *par-dessus* un LLM. Il s'agit de la LFS comme *système d'exploitation* du LLM.

---

## Le problème avec la conception actuelle des LLM

Les LLM actuels et leurs prompts système sont :

- idéationnellement sous-spécifiés (pas d'architecture de domaine/champ principiée)
- interpersonnellement incohérents (pas de modélisation principiée du rôle, de la posture ou du tenor)
- textuellement ad hoc (pas de structure principiée de genre, de registre ou de flux d'information)

Résultat : les utilisateurs consacrent un temps considérable à corriger des défaillances de niveau système qui n'auraient jamais dû être intégrées.

---

## L'architecture LFS-first

### 1. Le registre comme paramètre de conception primaire

Toute interaction avec un LLM est régie par un contexte de situation. Les trois variables de registre — champ, tenor, mode — doivent être explicitement codées comme paramètres de niveau système, et non inférées de manière stochastique.

- **Champ** : Quel domaine d'activité est en jeu ? Quelle structure de connaissance le régit ?
- **Tenor** : Quelle est la relation de rôle ? Quelles structures d'obligation et d'affect s'appliquent ?
- **Mode** : Quel est le canal rhétorique ? Quelle densité et quel flux d'information sont attendus ?

### 2. Les métafonctions comme système de typage des agents

Les trois métafonctions ne sont pas de simples catégories analytiques. Dans une architecture LFS-first, elles deviennent des rôles fonctionnels pour les agents et les sous-processus :

- **Agent idéationnel** : gère les connaissances du domaine, la construalisation expérientielle, les relations logiques
- **Agent interpersonnel** : gère la posture, l'évaluation, l'obligation, la modalité, les relations de rôle
- **Agent textuel** : gère la cohésion, la structure informationnelle, le séquencement des genres, la progression thématique

### 3. Le genre comme spécification de sortie

La sortie n'est pas « une réponse ». C'est une instance de genre — un processus social stadié et orienté vers un objectif. Le genre doit être explicitement spécifié avant la génération, et non inféré des caractéristiques de surface du prompt.

### 4. Ingénierie des prompts LFS-first

Les prompts ne sont pas des instructions en langage naturel. Ce sont des opérateurs méta-textuels sur un espace fonctionnel systémique. Un prompt LFS-first bien formé spécifie :

- le registre du texte cible
- la structure de genre attendue
- la pondération métafonctionnelle requise
- les paramètres d'évaluation et de modalité

---

## Implémentations

Les dépôts suivants implémentent des aspects de cette architecture :

- [systemic_func_context-wrapper](https://github.com/simon-drury/systemic_func_context-wrapper) — enveloppe d'instruction LFS pour les prompts
- [sfl-translation-agent](https://github.com/simon-drury/sfl-translation-agent) — agent de traduction multilingue ancré dans la LFS
- [browser_bridge_-sfl-playground-extension_sjd_datascapes](https://github.com/simon-drury/browser_bridge_-sfl-playground-extension_sjd_datascapes) — analyse LLM multi-modèle LFS-first
- [numerai-sfl-pipeline](https://github.com/simon-drury/numerai-sfl-pipeline) — pipeline multi-agents informé par la LFS

---

## Licence

Cette spécification est libre d'utilisation personnelle, académique et open source non commerciale.
Toute utilisation commerciale (générant des revenus directs ou indirects) nécessite une licence séparée de l'auteur.

Merci de prendre contact si une utilisation commerciale est envisagée. Les conditions de licence sont ouvertes à discussion.

**Contact** : simondrury2010@gmail.com | [LinkedIn](https://www.linkedin.com/in/simon-drury-60b881293)

---

*Première publication : mars 2026. Horodaté sur GitHub en tant qu'antériorité.*
