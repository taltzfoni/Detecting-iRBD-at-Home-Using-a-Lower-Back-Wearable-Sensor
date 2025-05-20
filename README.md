# Detecting-iRBD-at-Home-Using-a-Lower-Back-Wearable-Sensor

Welcome to the official code repository for the paper (Under Review):

**"Detecting Isolated REM Sleep Behavior Disorder at Home Using a Lower-Back Wearable Sensor"**  
by Tal Tzfoni(1,2), Riva Tauman(3,4,5), Jeffrey M Hausdorff (1,3,4,6), Yael Hanein(2,3,7) and Anat Mirelman(1,3,4)

1-Laboratory for Early Markers of Neurodegeneration, Center for the Study of Movement, Cognition, and Mobility, Neurological Institute, Tel Aviv Sourasky Medical Center, Tel Aviv, Israel
2-School of Electrical Engineering, Tel Aviv University, Tel Aviv, Israel
3-Sagol School of Neuroscience, Tel Aviv University, Tel Aviv, Israel
4-Faculty of Medicine and Health Sciences, Tel Aviv University, Tel Aviv, Israel
5-Sieratzki Sagol Institute of Sleep Medicine, Tel Aviv Sourasky Medical Center, Tel Aviv, Israel
6-Rush Alzheimer’s Disease Center, Rush University Medical Center
7-X-trodes Ltd., Herzliya, Israel

This repository contains the main script used for preprocessing, analysis, and modeling in the study. 
Our aim is to provide a transparent, reproducible pipeline for the researchers interested in depper understanding of the analysis done in the study.

---

## Repository Structure

```
iRBD-Detection/
├── data                           # (TBD) Synthetic data
├── iRBD_detection_analysis        # Scripts for data cleaning, models used, statistical analysis and evaluation
├── LICENSE                        # MIT License 
└── README.md                      # This file
```

---

## Problem Statement

iRBD is a parasomnia characterized by abnormal REM sleep behavior. 
Early detection is important for identifying risk of neurodegenerative diseases. 
This project focuses on detecting iRBD using wearable data and machine learning methods.

---


## Prerequisites

- Python ≥ 3.9  
- Install dependencies using `pip` or `conda`. 


## Data Access

Due to privacy concerns, we do not release raw patient data. 
Please refer to the `data/README.md` for synthetic samples or information on how to request access to the original dataset (if applicable).

---

## How to Run

Run the full pipeline from preprocessing to model training:

TBD

---

## Results

Key findings and evaluation metrics can be found in the `results/` directory. The final model achieves:

- Sensitivity: 100%
- Specificity: 75.86%
- Accuracy: 80.82% 

Please refer to the paper for full experimental details.

---

## Citation

If you find this code useful, please consider citing our paper:

TBD

---

## Contributing

Contributions, suggestions, and improvements are welcome! Please open an issue or submit a pull request.

---

## License

This project is licensed under the MIT License – see the 'LICENSE.txt' file for details.

---

## Contact

For questions or collaborations, reach out at talitzfoni16@gmail.com.
