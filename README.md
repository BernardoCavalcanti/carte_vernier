
# Vernier Interactive Map

This project generates an interactive HTML map displaying:

- 🏫 Schools (blue pins)
- 🏡 Maisons de quartier (green pins)
- 🔵 Sub-sector bubbles sized by number of children

## How to Use

1. Place the following files in the same directory:
   - `Coordonées_écoles_mqs_addresses.xlsx` (with sheets `écoles` and `MQs`)
   - `final_subsector_data.csv` (with columns: Sous-secteur, Latitude, Longitude, Nombre_enfants)

2. Run the script:

```bash
python generate_vernier_map.py
```

3. Open `vernier_map.html` in a browser or publish it on GitHub Pages.

## Hosting

To publish the map:
- Push the HTML file to your GitHub repo
- Enable GitHub Pages in repo settings
- Access your map at: `https://your-username.github.io/your-repo-name/`
