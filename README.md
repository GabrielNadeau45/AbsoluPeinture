# AbsoluPeinture
Application de gestion de contrats de peinture. Les peintres peuvent consulter les contrats disponibles, voir les photos et les détails,
puis accepter les contrats. L’administrateur peut créer, gérer et assigner des contrats facilement. Pensée pour évoluer en PWA.

 1. Authentification (page de connexion)  
  - Page de connexion (email + mot de passe)
  - Page d'inscription pour peintres
  - Mot de passe oublié (optionnel)
  - Middleware de protection pour pages privées


 2. Page d’accueil (type Marketplace)
  Chaque contrat aura :
  - Photos (minimum 3 par pièce)
  - Dimensions des pièces
  - Date prévue des travaux
  - Prix proposé
  - Type de peinture (couleur + marque)
  - Bouton “Postuler”
  - Filtres par région, date, type de pièce, prix


 3. Système de postulation
 Lorsqu’un peintre clique sur “Postuler” :
  - Une alerte est envoyée à l’administrateur
  - L’admin peut accepter/refuser
    
    Si accepté, le peintre peut voir :
     - Adresse
     - Téléphone du client


 4. Page profil du peintre
  Contient :
  - Nom
  - Courriel
  - Numéro de téléphone
  - Années d'expérience
  - Endroits où il/elle peut travailler (régions)
  - Contrat deja terminer


 5. Notifications (admin seulement)
  - Voir les nouvelles postulations
  - Accepter/refuser manuellement
  - Historique des contrats attribués


 6. Base de données (tables principales)
  - Utilisateurs (peintres pour l’instant)
  - Contrats
  - Photos liées à un contrat
  - Postulations
  - Notifications


 Partie 2 (à venir) - pour les clients :
  - Formulaire de création de contrat (photos, dimensions, pièces)
  - Prix souhaité par le client
  - Alerte automatique si le prix est trop bas
  - Mise en ligne d’un contrat validé par l’admin
  - Intégration avec Marketplace des peintres


 À prévoir :
 Système de messagerie intégrée entre peintre et client
