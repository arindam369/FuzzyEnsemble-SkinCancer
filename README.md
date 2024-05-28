# A Fuzzy Deep Ensemble Methodology for Classifying Skin Cancer Images
Arindam Halder, Sanghita Gharami, Anogh Dalal, Pawan Kumar Singh<sup>[[0000-0002-9598-7981](https://orcid.org/0000-0002-9598-7981)]</sup>

### Directory Structure


```

+-- gradcam
|   +-- .
|   +-- GradCAM_DermaMNIST.ipynb
|   +-- GradCAM_Ham10000.ipynb
+-- Ham10000_FuzzyEnsembled.ipynb
+-- DermaMNIST_FuzzyEnsembled.ipynb

```

## Running Codes

**Clone the project repository:**

``` git clone https://github.com/arindam369/FuzzyEnsemble-SkinCancer.git ``` &nbsp;  ``` cd FuzzyEnsemble-SkinCancer ```

*Run Ham10000_FuzzyEnsembled.ipynb, DermaMNIST_FuzzyEnsembled.ipynb files to view the result of our fuzzy ensemble model on Ham10000 & DermaMNIST datasets respectively. ``gradcam`` directory contains the codes of visualising GradCAM Analysis on the respective datasets using our proposed model.*



## Datasets
Two datasets are utilized in this study -
- **DermaMNIST** can be found at: [albertvillanova/medmnist-v2](https://huggingface.co/datasets/albertvillanova/medmnist-v2) | [MedMNIST](https://medmnist.com)
- **Ham10000** can be found at: [Kaggle Datasets](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000) | [ISIC 2018 Challenge](https://challenge2018.isic-archive.com) | [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T)