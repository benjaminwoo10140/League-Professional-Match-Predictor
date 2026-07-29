# League-Professional-Match-Predictor
Analyzed datasets of professional League of Legends matches across all regions and patches to predict the winning team at different points in the game (post-draft, 10, 15, 20, 25 minutes in).

## Data
I take my match data from [Oracle's Elixir](https://oracleselixir.com/tools/downloads), a database of professional League of Legends match statistics. The CSV by itself is not committed to this repo (see `.gitignore`) because of its sheer size — download the current season's file from the link above and place it in the project root (or `data/`) to reproduce the notebooks.
