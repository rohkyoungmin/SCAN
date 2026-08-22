This project was published in CMES (Computer Modeling in Engineering and Sciences), an SCIE journal.

# Publication
- More details are available in the paper "[SCAN: Structural Clustering with Adaptive Thresholds for Intelligent and Robust Android Malware Detection under Concept Drift](https://www.sciencedirect.com/science/article/pii/S1526149226001244)".
- Please consider citing the paper as follows:

```
@article{ROH2026,
    title = {SCAN: Structural Clustering with Adaptive Thresholds for Intelligent and Robust Android Malware Detection under Concept Drift},
    journal = {CMES - Computer Modeling in Engineering and Sciences},
    volume = {146},
    number = {3},
    year = {2026},
    issn = {1526-1492},
    doi = {https://doi.org/10.32604/cmes.2026.074936},
    url = {https://www.sciencedirect.com/science/article/pii/S1526149226001244},
    author = {Kyoungmin Roh and Seungmin Lee and Seong-je Cho and Youngsup Hwang and Dongjae Kim},
    keywords = {Android malware detection, concept drift, intelligent hybrid framework, gaussian mixture model (GMM), class imbalance, adaptive thresholding}
}
```

# SCAN

<img width="7209" height="4420" alt="fig3-1" src="https://github.com/user-attachments/assets/80b501f5-d77c-46cd-bc2b-c8d4dceb4aba" />

## Code
- The main code for SCAN is available in `SCAN_main_code.ipynb`.
- The supplementary experiment code is available in `DREBIN_Additional.ipynb`.

## Datasets
- We mainly used the AndroZoo dataset (available at https://androzoo.uni.lu/) for our experiments.
- We used additional datasets from DREBIN (available at https://drebin.mlsec.org/) to reflect realistic class imbalance.
- The feature data that supports the findings of this study are available from the Corresponding Author, [Seong-je Cho](https://securesw.dankook.ac.kr/Members/Professor.html), upon reasonable request.

## System Environment
- The implementation of SCAN and the experiments were conducted on a Microsoft Windows 11 Pro system (Version 24H2, Build 26100.4946) running under WSL2 with Linux kernel 6.6.
- The hardware configuration included an Intel(R) Xeon(R) W-3235 CPU @ 3.30 GHz (12 cores, 24 threads), 64 GB of DDR4 RAM, and an NVIDIA Quadro RTX 4000 GPU.

# Acknowledgements
## Funding Statement
- This work was supported in part by the Basic Science Research Program through the National Research Foundation of Korea (NRF) funded by the Ministry of Science and ICT (No. 2021RA2C2012574).
- This work was supported in part by the IITP (Institute of Information & Communications Technology Planning & Evaluation) - ITRC (Information Technology Research Center) grant funded by the Korea government (Ministry of Science and ICT) (IITP-2025-RS-2023-00259967).

## Developer
- The machine learning code was developed by **Kyoungmin Roh** in the [Computer Security & Operating Systems (CSOS) Lab](https://securesw.dankook.ac.kr/index.html), Dankook University.
