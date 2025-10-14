# Bénévol’Local

Plateforme web qui met en relation des **bénévoles** et des **organisations** pour des **missions communautaires proches de chez eux**.

## 🎯 Objectif
Faciliter l’engagement citoyen local en rendant la recherche, l’inscription et le suivi des missions de bénévolat **simples, rapides et transparentes**.

## ✨ Fonctionnalités clés
- Comptes bénévoles (profil, centres d’intérêt, localisation approximative).
- Catalogue de missions filtrable (catégorie, date, ville/proximité, mots-clés).
- Page mission (description, lieu, créneaux, places, organisateur).
- Candidature / confirmation / désistement.
- Commentaires et actualités pour coordonner la mission.
- Espace organisateur pour créer, modifier et clôturer des missions.
- Signalement/modération de contenu.

## 👥 Public cible
- **Bénévoles** souhaitant agir près de chez eux.  
- **Associations / ONG / collectivités** ayant besoin de volontaires.  
- **Entreprises** pour des actions de volontariat corporate (RSE).

## 🧱 Stack technique
- **Back-end** : PHP  
- **Base de données** : MySQL  
- **Front** : HTML/CSS (avec un peu de JS au besoin)

## 🚀 Mise en route (vue d’ensemble)
1. Configurer la base de données MySQL.  
2. Renseigner les paramètres d’application (URL, DB, répertoires d’upload).  
3. Lancer l’application sur votre serveur web (Apache/Nginx + PHP).  
4. Créer un premier compte organisateur et publier une mission.  

## 🔐 Sécurité & confidentialité (principes)
- Mots de passe hachés, sessions sécurisées, validation des entrées.  
- Protection des formulaires (CSRF), limitation de taux sur les actions sensibles.  
- Modération basique (signalement, suppression de contenus inappropriés).  
- Respect de la vie privée (localisation volontaire et approximative, minimisation des données).

## 📈 Scalabilité & fiabilité (approche)
- Front stateless derrière un serveur web, prêt pour la répartition de charge.  
- Indexation DB et possibilité de réplicas en lecture.  
- Stockage d’images sur disque ou service objet (type S3) selon l’environnement.  
- Journalisation et suivi des erreurs pour une maintenance facilitée.

## 🗺️ Feuille de route (idées)
- Carte interactive et recherche par distance.  
- Notifications e-mail (rappels, confirmations).  
- Export CSV des participants.  
- Badges/attestations pour les bénévoles.  
- Internationalisation (i18n).


