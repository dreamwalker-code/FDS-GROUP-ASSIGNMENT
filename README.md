# 🛡️ Foundations of Data Science-GROUP 2-ASSIGNMENT

# 🔐 CSE-CIC-IDS2018 Intrusion Detection System

> A Machine Learning based Network Intrusion Detection System (IDS) for detecting Brute Force Attacks (FTP & SSH)

---

## 📌 Project Overview

This project implements a **Network Intrusion Detection System (IDS)** using the CSE-CIC-IDS2018 dataset from the Canadian Institute for Cybersecurity. The system uses **Random Forest Classifier** to distinguish between benign network traffic and various cyber attacks, specifically:

- ✅ **FTP-BruteForce** attacks
- ✅ **SSH-Bruteforce** attacks

### 🎯 Key Achievement

| Metric | Score |
|--------|-------|
| **Accuracy** | 99.99% |
| **Precision** | 99.99% |
| **Recall** | 99.99% |
| **F1-Score** | 99.99% |

---

## 👥 Group 2 - Team Information

### Team Members

| S.No | Roll Number | Name | Contribution |
|:----:|-------------|------|--------------|
| 1 | 23BCE10121 | **TANISHA** | Data Preprocessing, Model Training |
| 2 | 23BCE10139 | **R ADHITHYAN** | Code Implementation, Documentation |
| 3 | 23BCE10181 | **RUDRA TRIVEDI** | Data Analysis, Visualization |
| 4 | 23BCE10184 | **PRIYANSH CHAUDHARY** | Model Evaluation, Testing |
| 5 | 23BCE10193 | **JITENDRA BHASKAR** | Report Writing, Research |
| 6 | 23BCE10239 | **ALISHA BASA** | GitHub Management, Presentation |

### Course Details

| Field | Information |
|-------|-------------|
| **Course** |Foundations of Data Science |
| **Group Number** | **Group 2** |
| **Instructor** | Dr. Ashfaq Ahmad Najar |
| **Assignment** | Group Project - Intrusion Detection System |
| **Submission Date** | April 11, 2026 |

---

## 📊 Dataset Information

### CSE-CIC-IDS2018

| Property | Details |
|----------|---------|
| **Full Name** | Communications Security Establishment - Canadian Institute for Cybersecurity IDS 2018 |
| **Created By** | Canadian Institute for Cybersecurity (CIC) & Communications Security Establishment (CSE) |
| **Official Website** | 🔗 https://www.unb.ca/cic/datasets/ids-2018.html |
| **Download Source** | **Kaggle** (used for this project) |
| **Kaggle Link** | 🔗 https://www.kaggle.com/datasets/solarmainframe/ids-intrusion-csv |
| **AWS S3 Path** | `s3://cse-cic-ids2018/` |
| **Total Size** | ~50GB (CSV + PCAP files) |
| **Attack Scenarios** | 7 types |

> **Note:** For this project, we downloaded the CSV file from **Kaggle** as it provided faster and easier access compared to AWS CLI. The Kaggle dataset contains the exact same CSV files as the official source.

### Data Used in This Project

| Parameter | Value |
|-----------|-------|
| **File Name** | `02-14-2018.csv` |
| **Downloaded From** | Kaggle |
| **Date** | Wednesday, February 14, 2018 |
| **Attack Types** | FTP-BruteForce, SSH-Bruteforce |
| **Total Samples** | 1,048,575 network flows |
| **Features** | 80+ network flow features |
| **Benign Traffic** | 667,626 (63.7%) |
| **FTP-BruteForce** | 193,360 (18.4%) |
| **SSH-Bruteforce** | 187,589 (17.9%) |

### Attack Types in Full Dataset

| Attack | Tools Used | Duration |
|--------|------------|----------|
| Brute-force | FTP-Patator, SSH-Patator | 1 day |
| DoS | Hulk, GoldenEye, Slowloris, Slowhttptest | 1 day |
| Heartbleed | Heartleech | 1 day |
| Web Attack | DVWA, Selenium (XSS, Brute-force) | 2 days |
| Infiltration | Dropbox, Nmap, Portscan | 2 days |
| Botnet | Ares, Zeus | 1 day |
| DDoS+PortScan | LOIC (UDP, TCP, HTTP) | 2 days |

### Dataset Citation

> Iman Sharafaldin, Arash Habibi Lashkari, and Ali A. Ghorbani, *"Toward Generating a New Intrusion Detection Dataset and Intrusion Traffic Characterization"*, 4th International Conference on Information Systems Security and Privacy (ICISSP), Portugal, January 2018

---

## 🔗 Dataset Access Links

| Source | Link | Status |
|--------|------|--------|
| **Official CIC Website** | https://www.unb.ca/cic/datasets/ids-2018.html | Reference |
| **Kaggle (Used)** | https://www.kaggle.com/datasets/solarmainframe/ids-intrusion-csv | ✅ Working |
| **AWS S3** | s3://cse-cic-ids2018/ | Official source |
| **Google Drive Mirror** | https://drive.google.com/file/d/1EMe83pWkccHg3mD5LLuCaHURjYjx7fjo/view | Alternative |

---

## 🛠️ Technologies Used

| Category | Technologies |
|----------|--------------|
| **Language** | Python 3.11+ |
| **Environment** | Google Colab / Jupyter Notebook |
| **Libraries** | pandas, numpy, scikit-learn, matplotlib, seaborn |
| **Model** | Random Forest Classifier |
| **Version Control** | Git & GitHub |

---

## 📦 Installation & Setup

### Option 1: Run in Google Colab (Recommended)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1rSC2BGttJGzS3eDuOaihkxKCsqH4mfFa?usp=sharing)

> **Direct Colab Link:** https://colab.research.google.com/drive/1rSC2BGttJGzS3eDuOaihkxKCsqH4mfFa?usp=sharing

Click the badge above or the direct link to open the notebook in Google Colab.

### Option 2: Run Locally

1. **Clone the repository**
   ```bash
   git clone https://github.com/dreamwalker-code/FDS-GROUP-ASSIGNMENT.git
   cd FDS-GROUP-ASSIGNMENT
