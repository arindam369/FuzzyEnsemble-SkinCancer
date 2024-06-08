# A Fuzzy Rank-based Deep Ensemble Methodology for Multi-Class Skin Cancer Classification
Arindam Halder, Anogh Dalal, Sanghita Gharami, Pawan Kumar Singh<sup>[[0000-0002-9598-7981](https://orcid.org/0000-0002-9598-7981)]</sup>

### Directory Structure

```
+-- assets/
+-- DermaMNIST_FuzzyEnsemble.ipynb
+-- GradCAM_DermaMNIST.ipynb
+-- Ham10000_FuzzyEnsemble_GradCAM.ipynb
```

## Running Codes

**Clone the project repository:**

``` git clone https://github.com/arindam369/FuzzyEnsemble-SkinCancer.git ``` &nbsp;  ``` cd FuzzyEnsemble-SkinCancer ```

- Run ``Ham10000_FuzzyEnsemble_GradCAM.ipynb`` file to view the result of our fuzzy ensemble model on Ham10000 dataset.
- Run ``DermaMNIST_FuzzyEnsemble.ipynb`` file to view the result of our fuzzy ensemble model on DermaMNIST dataset.
- To visualise GradCAM analysis on DermaMNIST dataset, run the ``GradCAM_DermaMNIST.ipynb`` file.<br>

``assets`` directory contains all the images of our study including results, architectures etc.



## Datasets
Two datasets are utilized in this study -
- **DermaMNIST** can be found at: [albertvillanova/medmnist-v2](https://huggingface.co/datasets/albertvillanova/medmnist-v2) | [MedMNIST](https://medmnist.com)
- **Ham10000** can be found at: [Kaggle Datasets](https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000) | [ISIC 2018 Challenge](https://challenge2018.isic-archive.com) | [Harvard Dataverse](https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/DBW86T)