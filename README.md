# project-management

“Construisez un outil de mesure de la Qualité de Service (QS)”

🧠 Contexte du projet :

Une entreprise souhaite développer un outil interne pour mesurer, visualiser et piloter la qualité de service (QS) de ses applications et infrastructures.

L’outil devra permettre :
	•	la déclaration d’indicateurs de qualité (SLOs, SLIs, SLA)
	•	le calcul de la QS globale en fonction de critères et pondérations
	•	la visualisation dynamique (graphes, alertes, tableaux de bord)
	•	l’intégration avec des outils de supervision existants (Prometheus, Grafana, etc.)

Le but est d’aider les équipes à maîtriser leur QS, identifier les dérives, piloter les améliorations et documenter les niveaux d’engagement (SLA) auprès des clients internes ou externes.

⸻

📌 Livrables attendus

⚠️ Aucun code n’est attendu — uniquement une préparation technico-fonctionnelle du projet.

1. Cadrage fonctionnel
	•	Qui sont les utilisateurs de l’outil ? (infra, projet, client, manager…)
	•	Quels sont les objectifs métier ?
	•	Définir les fonctionnalités MVP
	•	Création d’un SLO/SLI
	•	Pondération et calcul de QS
	•	Visualisation (graphes, tableaux)
	•	Export de rapports
	•	Décrire 5–10 user stories prioritaires

2. Organisation d’équipe
	•	Répartition des rôles (PM, dev front/back, architecte, QA, etc.)
	•	Choix d’un outil de gestion (Trello, GitLab Board, Notion…)
	•	Quelle méthode agile ? (Scrum, Kanban, hybride ?)

3. Conception technique
	•	Choix de l’architecture (monolithe vs microservices ?)
	•	Technologies pressenties :
	•	Back (Spring Boot, Flask…)
	•	Front (React, Vue, Thymeleaf…)
	•	Base de données (PostgreSQL ?)
	•	API REST ou GraphQL ?
	•	Format des données : JSON, YAML ?
	•	Modèle de données simplifié (SLO, composant, métrique, période)

4. Planification projet
	•	Itérations prévues
	•	Détail du MVP et jalons clés
	•	Gestion de la dette technique
	•	Plan de tests (unitaires, intégration, end-to-end)
	•	Intégration continue (CI), livraison continue (CD)
	•	Gestion des versions

5. CI/CD, déploiement, monitoring, observabilité
	•	Outils CI/CD (GitLab CI, GitHub Actions, Jenkins…)
	•	Pipeline cible (build, tests, quality gate, déploiement auto ?)
	•	Hébergement (local, cloud, conteneurs…)
	•	Stratégie de monitoring des composants de l’outil
	•	Intégration avec outils d’observabilité (logs, métriques, traces)
	•	Politique d’alerting ?

⸻

⏱️ Déroulé

⌛ 15 min — Introduction du cas

Tu expliques le besoin comme si tu étais un client interne. Tu insistes sur le fait que c’est leur outil, à eux de concevoir. Tu précises que tu observeras leur manière de s’organiser.

👥 Travail de groupe

Chaque groupe (6/7 étudiants) travaille sur sa propre version du projet :
	•	discussions, organisation interne, rédaction
	•	création de tableaux de bord (Trello, Miro…), de documents techniques ou fonctionnels

🗣️ 30 min — Pitches des groupes

Chaque groupe présente son projet (10 slides ou équivalent)

⸻

🎯 Objectifs pédagogiques
	•	Favoriser la pensée systémique et l’approche produit
	•	Développer le réflexe de qualité (test, observabilité, dette technique)
	•	Exercer les soft skills : communication, collaboration, priorisation
	•	Introduire la culture DevOps/SRE de manière concrète dès le départ

⸻
