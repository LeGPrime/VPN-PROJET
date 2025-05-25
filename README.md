Projet VPN WireGuard - Architecture Client-Serveur
Informations du projet
Formation : Ynov Informatique - Bachelor 2
Module : Infrastructure & Système d'Information
Sujet : Projet VPN (Sujet 2)
Période : Mai 2025
Présentation
Ce projet consiste en la mise en place d'une solution VPN basée sur WireGuard permettant un accès distant sécurisé à des ressources internes. L'objectif principal est de déployer une infrastructure VPN fonctionnelle avec une documentation technique complète et des procédures d'exploitation détaillées.
Architecture technique
Environnement de déploiement

Plateforme : MacBook M1 (macOS 14.4.1)
Adresse serveur : 192.168.1.75
Réseau local : 192.168.1.0/24
Réseau VPN : 10.13.13.0/24
Endpoint public : 37.66.226.231:51820

Technologies utilisées

Protocole VPN : WireGuard
Containerisation : Docker avec linuxserver/wireguard
Serveur web de test : Nginx
Chiffrement : ChaCha20-Poly1305

Fonctionnalités implémentées
La solution déployée inclut les éléments suivants :

Serveur VPN WireGuard opérationnel avec interface wg0
Configuration automatique pour 3 clients simultanés
Authentification par clés publiques/privées avec PSK
Routage NAT pour l'accès Internet via le tunnel
Serveur web interne accessible uniquement via VPN
Scripts d'automatisation pour le déploiement et la maintenance
Documentation technique et d'exploitation complète
