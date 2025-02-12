# 🏗 1. Planification & Conception

### Définir les fonctionnalités principales

- [ ] Création d’un événement et ses détails
- [ ] Inscription des participants
- [ ] Envoi d’e-mails de confirmation
- [ ] Consulter les registrations
- [ ] Affichage des participants
- [ ] rechercher / filtrer par participants ou registration

### Choisir la stack technologique

Front-end : React / Material UI ....
Back-end : Node.js / Nestjs
Base de données : Mysql
Gestion d’état : ReactQuery

### Concevoir l’architecture du projet

- [ ] Définir les modèles de données
- [ ] Schéma de la base de données
- [ ] Définir les routes API

# 🖥 2. Mise en place du projet

- [ ] Initialiser le projet
- [ ] Configurer la base de données

# 🎟 3. Gestion de l'événement :

- [ ] récupèrer les informations nécessaires :
      name: The maze 2.0
      description:
      themes :
      workshops :
      Challenges :
      date : 21-20/04
      lieux :
      capacity :
      availableSeats :

- [ ] Créer une API pour les événements

  - [ ] Route GET /events : Récupérer tous les infos relatives à l'événement

  - [ ] Créer une interface pour afficher l'événements

# 👥 4. Gestion de l'authentification :

- [ ] Implémenter l’authentification avec JWT
- [ ] Route get /auth : recupèrer un token
- [ ] Route POST /auth/login : Connexion
- [ ] composant de protection des routes
- [ ] composant de loading

# 📋 5. Gestion des Registrations

- [ ] Créer un modèle Registration
      export type Registration = {
      id: string;
      name: string;
      email: string;
      phone: string;
      studyLevel: string;
      specialization: string;
      team: {
      id: string;
      name: string;
      };
      fac: {
      id: string;
      name: string;
      };
      ticket: {
      ticketNo: string;
      done: boolean;
      workshops: Workshop[];
      };
      };

- [ ] Créer une API pour les Registrations

  - [ ] Route GET /registrations/get-form : Initialiser form

  - [ ] Route POST /registrations : Inscrire un utilisateur à un événement

  - [ ] Route GET /registrations: Consulter les registrations

  - [ ] Route Patch /registrations/id : éditer les registrations

  - [ ] Ajouter un dashboard de statistique
  - [ ] changer template de la ticket

# 📧 6. Notifications et confirmations

- [ ] Configuration de la fonctionnalité d'envoie d'un email apres registration
- [ ] Configuration de la gestion du paiement
- [ ] Envoyer un e-mail de rappel avant l’événement

# 🖥 7. Interface utilisateur

- [ ] Page d’accueil avec l'événements disponible
- [ ] Page d’inscription avec un formulaire
- [ ] Dashboard admin pour gérer l'événement et participants

# 🛠 8. Tests et validation

- [ ] à définir aprés deploiment

# 🚀 9. Déploiement

- [ ] Déployer le back-end
- [ ] Déployer le front-end sur Vercel / Netlify
- [ ] Configurer un domaine

# 💡 10. Documentation nécessaires :

- [ ] useRoutes
- [ ] createContext
- [ ] use QueryClient
- [ ] useMutation
- [ ] useQuery
- [ ] NodeMailer

# ✅ Bonus (Améliorations possibles)

Ali 3andou fikera inajam izideha w ne5idemou a3liha ma3a ba3athena

- [ ] Exporter la liste des participants en PDF
