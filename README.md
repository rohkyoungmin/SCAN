This project is published to SCIE Journal, CMES (Computer Modeling in Engineering and Sciences).

# Publication
- More details are available in the paper "[SCAN: Structural Clustering with Adaptive Thresholds for Intelligent and Robust Android Malware Detection under Concept Drift](https://www.techscience.com/CMES/v146n3/66789)".
- Please consider to cite the paper following this:
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
- The main code of SCAN is contained in the code: ```SCAN_main_code.ipynb```.
- The supplementary experiment of SCAN is contained in the code: ```DREBIN_Additional.ipynb```.

## Datasets
- We mainly used AndroZoo datasets (available at [https://androzoo.uni.lu/](https://androzoo.uni.lu/)) for experiment.
- We used additional datasets from DREBIN (available at [https://drebin.mlsec.org/](https://drebin.mlsec.org/)) to reflect realistic class imbalance.

## System Environment
- The implementation of the SCAN and experiments was conducted on a Microsoft Windows 11 Pro system (Version 24H2, Build 26100.4946) running under WSL2 with Linux Kernel 6.6.
- The hardware configuration included an Intel(R) Xeon(R) W-3235 CPU @ 3.30 GHz (12 cores, 24 Threads), 64GB of DDR4 RAM and an NVIDIA Quadro RTX 4000 GPU.


# Acknowlodgements
## Funding Statement
- This work was supported in part by Basic Science Research Program through the National Research Foundation of Korea (NRF) funded by the Ministry of Science and ICT (No. 2021RA2C2012574).
- This work was supported in party by the IITP (Institute of Information & Communications Technology Planning & Evaluation) - ITRC (Information Technology Research Center) grant funded by the Korea government (Ministry of Science and ICT) (IITP-2025-RS-2023-00259967).

## Developer
- This Machine Learning code is developed by **Kyoungmin Roh** in [Computer Security & Operating Systems (CSOS) Lab](https://securesw.dankook.ac.kr/index.html), Dankook University.
