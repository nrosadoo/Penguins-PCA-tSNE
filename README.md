# PCA & t-SNE — Penguins

Dimensionality reduction and cluster visualization on the Palmer Penguins dataset using PCA, t-SNE, and t-SNE on PCA.

## Files
- `Principal_Component_Analysis_(PCA).ipynb` — main notebook
- `penguins.csv` — dataset (UTF-8)
- `pca_penguins.pkl`, `tsne_penguins.pkl`, `pca_tsne_penguins.pkl`, `cleaned_penguins.pkl` — artifacts

## Run
conda create -n dtsc680 python=3.11 -y
conda activate dtsc680
pip install numpy pandas matplotlib scikit-learn jupyter
jupyter notebook

## Results
![PCA 2D](figures/01_pca.png)
![t-SNE 2D](figures/02_tsne.png)
![t-SNE on PCA](figures/03_tsne_on_pca.png)
