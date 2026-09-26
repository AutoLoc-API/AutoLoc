# AutoLoc

## 1. Acteurs du système

Dans le cadre de la Séance 1, les principaux acteurs identifiés pour l'application **AutoLoc** sont :

| Acteur                   | Description                                                                            |
| ------------------------ | -------------------------------------------------------------------------------------- |
| **Client**               | Utilisateur qui souhaite consulter, réserver et gérer la location d'un véhicule.       |
| **Agent d'agence**       | Employé chargé de gérer les locations, les réservations et les véhicules d'une agence. |
| **Responsable d'agence** | Responsable de la gestion et du suivi de l'activité d'une agence.                      |
| **Administrateur**       | Responsable de l'administration globale de la plateforme AutoLoc.                      |

---

## 2. Cas d'utilisation

### 2.1 Client

Le **Client** peut :

* S'inscrire sur la plateforme.
* Se connecter et se déconnecter.
* Gérer son profil.
* Consulter les véhicules disponibles.
* Rechercher un véhicule selon différents critères.
* Consulter les détails d'un véhicule.
* Effectuer une réservation.
* Modifier ou annuler une réservation.
* Consulter l'historique de ses réservations.
* Consulter les informations de son agence de location.
* Effectuer un paiement.
* Consulter ses factures.
* Donner une note ou un avis après une location.

### 2.2 Agent d'agence

L'**Agent d'agence** peut :

* Se connecter à son espace professionnel.
* Consulter les réservations de son agence.
* Ajouter une réservation pour un client.
* Modifier ou annuler une réservation.
* Confirmer ou refuser une réservation.
* Gérer les véhicules de son agence.
* Ajouter un véhicule.
* Modifier les informations d'un véhicule.
* Modifier la disponibilité d'un véhicule.
* Enregistrer la remise d'un véhicule au client.
* Enregistrer le retour d'un véhicule.
* Consulter les informations des clients.
* Consulter l'historique des locations.

### 2.3 Responsable d'agence

Le **Responsable d'agence** peut :

* Se connecter à son espace.
* Gérer les agents de son agence.
* Consulter et superviser les réservations.
* Suivre les locations en cours et terminées.
* Gérer le parc automobile de l'agence.
* Consulter les statistiques de l'agence.
* Consulter les revenus et les performances de l'agence.
* Consulter les avis et évaluations des clients.
* Générer des rapports d'activité.

### 2.4 Administrateur

L'**Administrateur** peut :

* Se connecter à l'espace d'administration.
* Gérer les comptes utilisateurs.
* Gérer les clients.
* Gérer les agences.
* Ajouter, modifier ou supprimer une agence.
* Gérer les responsables et les agents d'agence.
* Gérer les véhicules de la plateforme.
* Consulter toutes les réservations.
* Superviser les activités des agences.
* Consulter les statistiques globales de la plateforme.
* Gérer les paramètres généraux de l'application.

---

## 3. Synthèse des acteurs et cas d'utilisation

| Acteur                   | Principaux cas d'utilisation                                                                                                  |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------- |
| **Client**               | Inscription, authentification, gestion du profil, recherche de véhicules, réservation, paiement, annulation, historique, avis |
| **Agent d'agence**       | Gestion des réservations, gestion des véhicules, gestion des locations, gestion des clients                                   |
| **Responsable d'agence** | Supervision de l'agence, gestion des agents, gestion du parc automobile, statistiques, rapports                               |
| **Administrateur**       | Gestion des utilisateurs, agences et véhicules, supervision globale, statistiques, configuration                              |

> **Remarque :** Cette première liste pourra être complétée et affinée au cours des prochaines séances, notamment lors de la réalisation du diagramme de cas d'utilisation UML.
