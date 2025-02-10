# DoctoMap - Backend

Ce dépôt contient le backend de l'application **DoctoMap**, une plateforme de gestion des médecins inspirée de Doctolib.  
Il est développé avec **PHP, Symfony, API Platform et MySQL**.

## Frontend

Le frontend du projet est disponible à l'adresse suivante :  
🔗 [DoctoMap - Frontend](https://github.com/MarvinDlls/doctomap_tp_js)

## Fonctionnalités principales

- Affichage des médecins enregistrés via l'API
- Ajout, suppression et mise à jour des informations des médecins
- API RESTful avec API Platform

## Technologies utilisées

- PHP / Symfony
- API Platform
- MySQL
- Tailwind CSS

## Installation et utilisation

1. Clonez ce dépôt :  
   ```sh
   git clone https://github.com/MarvinDlls/doctomap_TP_SF.git
   composer install
   symfony console doctrine:migrations:migrate
   symfony server:start
