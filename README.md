# Skeletal Variation

Explore how skeletal anatomy varies across humans, birds, and mammals using a Jupyter notebook and accompanying CSV datasets.

## Project contents

- `skeletal-variation.ipynb` — guided, hands-on analysis of the datasets.
- `adult-human-skeleton.csv` — 206 adult human bones, with anatomical region, subregion, side, and fusion information.
- `bird-neck-bones.csv` — bird species and reported cervical vertebra counts.
- `mammal-neck-bones.csv` — mammal species and reported neck vertebra counts.
- `README.txt` — source details, including the bird species-to-paper DOI mapping.

## Get started

Use Python 3 with Jupyter Notebook or JupyterLab installed. Install pandas if it is not already available:

```bash
python -m pip install pandas jupyter
```

Clone the repository, move into the project directory, then launch Jupyter:

```bash
git clone https://github.com/zakaria-beny/skeletal-variation-project.git
cd skeletal-variation-project
jupyter notebook
```

Open `skeletal-variation.ipynb` and run its cells in order. The notebook reads the CSV files from the project directory, so keep them alongside the notebook. If you use Google Colab, upload all three CSV files when prompted by the notebook instructions.

## Data fields

The human skeleton dataset records each bone's `name`, `region`, `subregion`, `side`, and `fused_from` count. The bird and mammal datasets each contain a `species` name and a `neck_vertebrae` count. Counts and classifications reflect the cited source material; species coverage and terminology may differ between studies.

## Sources

- Human skeleton and bird dataset source mappings are documented in [`README.txt`](README.txt).
- Mammal neck vertebrae: Williams, Scott A., et al. “Increased variation in numbers of presacral vertebrae in suspensory mammals.” *Nature Ecology & Evolution* 3 (2019): 949–956.

