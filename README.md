# Fundus-Image-Vascular-Analysis
● Developed a computer-vision solution to automatically trace blood-vessel structures in retinal fundus images, using a pretrained ResNet-34 as the core feature extractor.

● Built the training workflow around dataset-specific preprocessing, synthetic image variations, and model fine-tuning to improve performance on previously unseen retinal scans.

● Integrated a post-processing stage to clean and refine predicted vessel maps, obtaining Dice scores of 0.88 (CHASE_DB1), 0.84 (STARE), 0.83 (DRIVE), and 0.81 (HRF) across four publicly available datasets.


# Datasets:
DRIVE: [https://www.kaggle.com/datasets/andrewmvd/drive-digital-retinal-images-for-vessel-extraction](https://www.kaggle.com/datasets/andrewmvd/drive-digital-retinal-images-for-vessel-extraction)
Chase-DB1: [https://www.kaggle.com/datasets/rashasarhanalharthi/chase-db1](https://www.kaggle.com/datasets/rashasarhanalharthi/chase-db1)
STARE: [https://www.kaggle.com/datasets/akriti187/dataset-stare](https://www.kaggle.com/datasets/akriti187/dataset-stare)
HRF: [https://www.kaggle.com/datasets/akriti187/hrf-dataset](https://www.kaggle.com/datasets/akriti187/hrf-dataset)
