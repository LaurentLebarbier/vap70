# eVaps E-commerce

**eVaps** est un site de commerce en ligne basé sur WordPress et WooCommerce, conçu pour vendre des produits de vapotage, notamment des e-liquides, des cigarettes électroniques, et des accessoires. Ce projet fournit une interface simple pour gérer un inventaire de produits, des commandes et des paiements tout en offrant une expérience utilisateur optimisée.

## Table des matières

- [Technologies](#technologies)
- [Prérequis](#prérequis)
- [Installation](#installation)
- [Configuration](#configuration)
- [Fonctionnalités](#fonctionnalités)
- [Contributions](#contributions)
- [Licence](#licence)

## Technologies

- **WordPress** - Système de gestion de contenu (CMS)
- **WooCommerce** - Plugin WordPress pour la gestion d'un e-commerce
- **PHP** - Langage de développement côté serveur
- **MySQL** - Base de données pour le stockage des produits, commandes, clients
- **HTML/CSS/JavaScript** - Technologies front-end pour l'interface utilisateur
- **Plugins tiers** - Intégrations pour SEO, sécurité, marketing par email, etc.

## Prérequis

- Un serveur avec PHP >= 7.4 et MySQL >= 5.7 (recommandé : PHP 8.x et MySQL 8)
- Un nom de domaine et certificat SSL pour la sécurité HTTPS

## Installation

1. **Cloner le projet** :
   ```bash
   git clone https://github.com/LaurentLebarbier/vap70
   cd vap70

    Installer WordPress :
        Télécharger et installer WordPress sur le serveur, puis configurer wp-config.php.

    Configurer WooCommerce :
        Accéder à l'administration WordPress, installer et activer WooCommerce via le menu Plugins.
        Suivre l'assistant de configuration WooCommerce pour définir les paramètres de boutique, devises, méthodes de paiement et de livraison.


    Importer les données de démonstration (optionnel) :
        Utiliser l'outil d'import WooCommerce pour importer des exemples de produits.

Configuration

    Personnaliser les paramètres WooCommerce :
        Catégories de produits : Configurer les catégories pour e-liquides, cigarettes électroniques, accessoires, etc.
        Méthodes de paiement : Intégrer des options comme Stripe, PayPal, ou des passerelles bancaires.
        Livraison : Configurer les options de livraison en fonction de la zone géographique.

    Configurer les Plugins supplémentaires :
        Sécurité : Utiliser un plugin de sécurité comme Wordfence ou iThemes Security.
        SEO : Activer un plugin comme Yoast SEO pour optimiser le référencement.
        Marketing : Utiliser des plugins de marketing pour les campagnes d'emailing ou la gestion des remises.

Fonctionnalités

    Gestion des produits : Ajouter, éditer et organiser les produits par catégorie et marque.
    Panier et commande : Système intuitif de gestion de panier et de commande pour les utilisateurs.
    Paiement sécurisé : Intégration de plusieurs passerelles de paiement sécurisé.
    Livraison et suivi : Options de livraison personnalisées et suivis de commande.
    Compte client : Espace client pour gérer les informations personnelles, commandes, et adresses.
    Optimisation SEO : Meilleure visibilité sur les moteurs de recherche via un plugin SEO.
    Statistiques et rapports : Vue complète des ventes, clients, et statistiques du magasin.

Contributions

Les contributions sont les bienvenues ! Pour toute proposition de modification :

    Créez un fork de ce dépôt.
    Créez une branche (git checkout -b feature/FeatureName).
    Committez vos modifications (git commit -m 'Ajouter FeatureName').
    Poussez vers la branche (git push origin feature/FeatureName).
    Créez une Pull Request.

Licence

Ce projet est sous licence MIT - voir le fichier LICENSE pour plus de détails.
