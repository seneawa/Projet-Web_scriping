#  Web Scraping des Horaires et Tarifs Dem Dikk

## Description

Ce projet a pour objectif de **collecter automatiquement** les données publiques disponibles sur le site de la compagnie de transport **Dem Dikk**, notamment :

- Les **horaires** de départ
- Les **tarifs**
- Les **villes desservies**
- Les **informations de contact**

Le scraping est réalisé à partir d’un fichier HTML du site, sans recourir à une API officielle.



## Objectifs

- Extraire proprement les données à partir d’un code HTML brut
- Nettoyer et structurer les informations collectées (horaires, lieux de départ, contacts, etc.)
- Enregistrer les résultats dans un fichier CSV pour une future analyse ou visualisation



## Technologies utilisées

- **Python 3**
- **BeautifulSoup** (analyse HTML)
- **pandas** (nettoyage et sauvegarde des données)
- re (expressions régulières)



##  Méthodologie

1.  Chargement du fichier HTML contenant les informations des lignes Dem Dikk
2.  Parsing avec **BeautifulSoup**
3.  Nettoyage des balises HTML (`<div>`, `<p>`, `<br>`)
4.  Extraction des champs :
   - Ville
   - Lieu de départ
   - Horaires
   - Tarifs
   - Contact
5. Export final dans un fichier CSV (`demdikk_data.csv`)



