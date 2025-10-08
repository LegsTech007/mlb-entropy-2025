# MLB 2025 Outcome Entropy

This project computes and publishes **plate appearance outcome entropy** for all MLB players (2025 season).  
Entropy measures the diversity of outcomes (HR, K, BB, 1B, etc.) — higher entropy = more unpredictable, lower = more predictable.

## Contents
- `index.html` – Web page that loads CSVs and displays interactive tables
- `entropy_players.csv` – Entropy results by player
- `entropy_teams.csv` – Entropy results by team (if generated)

## View the site
Hosted on **GitHub Pages**:  
👉 [https://<your-username>.github.io/<your-repo>/](https://<your-username>.github.io/<your-repo>/)

## How to update data
1. Run your `compute_entropy.py` script locally to regenerate:
   - `entropy_players.csv`
   - `entropy_teams.csv`
2. Replace the old CSVs in the repo with the new ones.
3. Commit and push changes:
   ```bash
   git add entropy_players.csv entropy_teams.csv
   git commit -m "Update entropy results"
   git push
