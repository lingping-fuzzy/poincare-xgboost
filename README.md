# Poincare-XGBoost

This repository contains the implementation of the PXGBoost method, as described in the paper *"Euclidean and Poincare Space Ensemble XGBoost"*.
[Read the paper here.](https://www.sciencedirect.com/science/article/pii/S1566253524005244?dgcid=coauthor)

## Running the Code

### Datasets
Place the `datasets` folder inside the `hyperXGB` folder.

### Download the Data
Download the UCI datasets from [this link](https://github.com/lingping-fuzzy/UCI-data-correct-split) and create a folder named `data` under `hyperXGB` to store them.

## hyperbolic Data

The network embeddings can be downloaded from [this repository](https://github.com/hhcho/hyplinear). We copy the WordNet embeddings and labels for our experiments [here](https://drive.google.com/drive/folders/14Mmp_jGmLu5jkKpvv_vIR7K-e0Pdl8BV?usp=sharing) from code [link](https://github.com/LarsDoorenbos/HoroRF/tree/main)

> **Note**: The upload process is not yet complete. Additional data will be available soon.

# Compared Algorithms in `hororf/hsvm`

This folder (`hororf/hsvm`) contains the implementation code of various algorithms used for comparison in our experiments.

We sincerely thank the original authors for publicly sharing their code, which made our comparative analysis possible.

## Referenced Repositories and Papers

- [Hyplinear (hhcho/hyplinear)](https://github.com/hhcho/hyplinear)  
  Hyperbolic SVM with a linear decision boundary in hyperbolic space.

- [Hyperbolic Learning (drewwilimitis/hyperbolic-learning)](https://github.com/drewwilimitis/hyperbolic-learning)  
  Learning with hyperbolic embeddings and classifiers.

- [HoroRF (LarsDoorenbos/HoroRF)](https://github.com/LarsDoorenbos/HoroRF/tree/main)  
  Hyperbolic Random Forests for classification in hyperbolic space.

- [NeurIPS 2023 Paper on Hyperbolic Learning](https://proceedings.neurips.cc/paper_files/paper/2023/hash/24cb8b08f3cb2f59671e33faac4790e6-Abstract-Conference.html)  
  A recent contribution on hyperbolic machine learning methods presented at NeurIPS 2023.

---

Please refer to each repository for specific usage, citation, and license details.

# Fast implementation

please find this repository for speed-up implementation [Lukus](https://github.com/lowoncuties/HyperbolicML)


# contact
if you have any questions, please contact
lingping.kong@vsb.cz
