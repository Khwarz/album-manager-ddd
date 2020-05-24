# Description du projet
Il s'agit d'un projet de gestion d'albums réalisé en utilisant Spring Boot.

# Conception
## Cas d'utilisation

- Authentification
	- Connexion d'un utilisateur
	- Enregistrement d'un nouvel utilisateur sur la plateforme
	- Déconnexion d'un utilisateur
- Gestion des albums (Créer, Mettre à jour, Supprimer, Récupérer, Filtrer)
- Gestion des artistes (Créer, Mettre à jour, Supprimer, Récupérer, Filtrer)
- Gestion des morceaux (Créer, Mettre à jour, Supprimer, Récupérer, Filtrer)
- Gestion des genres (Créer, Mettre à jour, Supprimer, Récupérer, Filtrer)

## Entités

- Account (email, password, name, role)
- Album (title, distinctions, year, genre, artist)
- Genre (name)
- Track (title, duration, album)
- Artist (name)

## Aggrégats

- Album, Track, Genre, Artist
- Genre
- Artist
