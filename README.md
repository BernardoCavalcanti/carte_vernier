
# Carte interactive de Vernier

Ce projet génère une carte HTML interactive affichant:

- 🏫 Ecoles (épingles blue)
- 🏡 Maisons de quartier (épingles vertes)
- 🔵 Bulles sous-sectorielles dimensionnées par nombre d'enfants

## Mode d'emploi

1. Placez les fichiers suivants dans le même répertoire :
- `Coordonées_écoles_mqs_addresses.xlsx` (avec les feuilles `écoles` et `centres`)
- `final_subsector_data.csv` (avec les colonnes : Sous-secteur, Latitude, Longitude, Nombre_enfants)

2. Exécutez le script :

```bash
python generate_vernier_map.py
```

3. Ouvrez `carte_vernier.html` dans un navigateur ou publiez-le sur GitHub Pages.

## Hébergement

Pour publier la carte :
- Envoyez le fichier HTML vers votre dépôt GitHub
- Activez les pages GitHub dans les paramètres du dépôt
- Accédez à votre carte à l'adresse : `https://bernardocavalcanti.github.io/carte_vernier/`
