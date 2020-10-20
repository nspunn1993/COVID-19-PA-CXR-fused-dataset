# COVID-19 Posteroanterior Chest X-Ray fused (CPCXR) dataset
The dataset is genrated by the fusion of three publicly available datasets: COVID-19 cxr image [[1]](https://github.com/ieee8023/covid-chestxray-dataset), Radiological Society of North America (RSNA) [[2]](https://www.kaggle.com/c/rsna-pneumonia-detection-challenge), and U.S.  national  library  of  medicine  (USNLM) collected  Montgomery  country - NLM(MC) [[3]](https://lhncbc.nlm.nih.gov/publication/pub9931). The dataset consists of samples of diseases labeled as COVID-19, Tuberculosis, Other pneumonia (SARS, MERS, etc.), and Normal.
The dataset can be utilized to train an evaulate deep learning and machine learning models as binary and multi-class classification problem.
The complete dataset is available [here](https://drive.google.com/file/d/1nwCNWlicaXHABMWMB8icsvCfsuafV-HS/view?usp=sharing).

# Dataset description

| Class | Label | Samples |
| :--- | --- | --- |
| Normal | 0 | 533 |
| COVID-19 | 1 | 108 |
| Other pneumonia | 2 | 515 |
| Tuberculosis | 3 | 58 |

# Citation
```
@article{Punn_2020,
   title={Automated diagnosis of COVID-19 with limited posteroanterior chest X-ray images using fine-tuned deep neural networks},
   ISSN={1573-7497},
   DOI={10.1007/s10489-020-01900-3},
   journal={Applied Intelligence},
   publisher={Springer Science and Business Media LLC},
   author={Punn, Narinder Singh and Agarwal, Sonali},
   year={2020}
}
```
