# cross-dataset-generalisation
Cross Dataset evaluation of ML intrusion detection: supervised (RF, XGBoost, CatBoost) and unsupervised (Isolation Forest, One-Class SVM, Autoencoder, VAE, Deep SVDD) models trained on CSE-CIC-IDS2017 and tested on CSE-CIC-IDS2018 and NF-UNSW-NB15 without retraining. MSc dissertation.
## Data availability
The datasets are large (~2 GB / 6.4 GB / 600 MB) and are NOT stored in this repo.
Download from the official sources, or from the shared Drive links below, and set
the paths at the top of the notebook (Part 0 / Part 1).

| Dataset | Official source | Drive link |
|---|---|---|
| CSE-CIC-IDS2017 | https://www.unb.ca/cic/datasets/ids-2017.html | •	Drive link: 2017: https://drive.google.com/drive/folders/1xaRG4WQSiIj wWBv7_CvCrij8qbsSJRh?usp=sharing	|
| CSE-CIC-IDS2018 | https://www.unb.ca/cic/datasets/ids-2018.html | Drive link: 2018: https://drive.google.com/drive/folders/1xyWzI8y_fhzT45 tBzf1kfHtLtPKLXlB?usp=sharing |
| NF-UNSW-NB15-v3 | https://rdm.uq.edu.au/  | Drive link: NF UNSW: https://drive.google.com/file/d/1oG_FVsJcgUYxYHKX6weAcrkeBXQx19cp/view?usp=drive_link |

Expected layout in Google Drive:
/MyDrive/CICIDS2017/*.csv
/MyDrive/CICIDS_2018/*.csv
/MyDrive/NIDS/NF-UNSW-NB15-v3.csv
