# 🏆 Plateforme de Challenges public for attendees

Une plateforme permettant aux participants (attendees) de consulter les challenges d’un événement.

# 🏗 1. Planification & Conception

## Définir les fonctionnalités principales

Affichage de la liste des challenges
Recherche et filtrage des challenges
Affichage des détails d’un challenge
Ouvrir les détails d’un challenge par un secret code

## Choisir la stack technologique

## Concevoir l’architecture du projet

## Définir les modèles de données

- [ ] Schéma de la base de données

- [ ] Définir les routes API

# 🖥 2. Mise en place du projet

- [ ] Initialiser le projet

- [ ] Configurer la base de données

# 🏁 3. Gestion des Challenges

## Récupérer les informations nécessaires :

model Challenge {
id Int @id @default(autoincrement())
name String
number Int
points Int
description String
key String?
hint String?

tech Tech?
challengesByTeam ChallengesByTeam[] @relation("TeamChallenges")

domaineId Int?
domaine Domaine? @relation(fields: [domaineId], references: [id])
}

- [ ] Créer une API pour les challenges

- [ ] Route GET /challenges : Récupérer la liste des challenges

- [ ] Route GET /challenges/:id : Récupérer les détails d’un challenge

- [ ] Créer une interface pour afficher les challenges

# 🔍 5. Recherche et Filtrage

- [ ] Ajout d’un champ de recherche

- [ ] Filtrer par difficulté, catégorie, date de début et de fin

# 📢 6. Notifications

🖥 7. Interface utilisateur

- [ ] Page d’accueil avec la liste des challenges
- [ ] Page de détails d’un challenge

# 🛠 8. Tests et validation

# 🚀 9. Déploiement

- [ ] Déployer le back-end
- [ ] Déployer le front-end sur Vercel / Netlify
- [ ] Configurer un domaine

# 💡 10. Documentation nécessaires

- [ ] API des challenges
- [ ] Utilisation de React Query

# ✅ Bonus (Améliorations possibles)

Ajouter un système de badges pour les challenges complétés
