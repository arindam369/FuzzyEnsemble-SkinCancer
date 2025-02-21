# A Fuzzy Rank-based Deep Ensemble Methodology for Multi-Class Skin Cancer Classification
Arindam Halder, Anogh Dalal, Sanghita Gharami, Marcin Wozniak*<sup>[[0000-0002-9073-5347](https://orcid.org/0000-0002-9073-5347)]</sup>, Muhammad Fazal Ijaz*<sup>[[0000-0001-5206-272X](https://orcid.org/0000-0001-5206-272X)]</sup>, Pawan Kumar Singh<sup>[[0000-0002-9598-7981](https://orcid.org/0000-0002-9598-7981)]</sup>

(* Corresponding Authors)

This is the official implementation of the paper, "[A fuzzy rank-based deep ensemble methodology for multi-class skin cancer classification](https://www.nature.com/articles/s41598-025-90423-3)" published in "Scientific Reports (Nature)"

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

## Citation
If you find this work helpful, consider citing our study:
```
@article{Halder2025,
   title={A fuzzy rank-based deep ensemble methodology for multi-class skin cancer classification},
   author={Halder, Arindam and Dalal, Anogh and Gharami, Sanghita and Wozniak, Marcin and Ijaz, Muhammad Fazal and Singh, Pawan Kumar},
   journal={Scientific Reports},
   volume={15},
   number={1},
   pages={6268},
   year={2025},
   month={feb},
   day={20},
   issn={2045-2322},
   doi={10.1038/s41598-025-90423-3},
   url={https://doi.org/10.1038/s41598-025-90423-3}
}
```