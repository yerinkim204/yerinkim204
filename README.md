# Yerin Kim 
> **[한 줄 요약: 데이터 분석을 통한 항공권 가격 변동 요인 파악 및 스태킹 앙상블 예측 모델 구축]**

---

### 🛠 Tech Stack
<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white">
  <img src="https://img.shields.io/badge/Scikit--Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white">
  <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white">
</p>

---

### 📌 Project Overview
* **목적**: [항공권 가격에 영향을 미치는 주요 요인을 분석하고 실시간 가격 예측 서비스의 기반 마련]
* **주요 역할**: [데이터 전처리, SHAP을 활용한 변수 중요도 산출, 스태킹 앙상블 모델 구축]
* **성과**: [기존 단일 모델 대비 RMSE 15% 감소 달성]

---

### 📊 Data Analysis & Visualization
분석 과정에서 얻은 핵심 인사이트를 시각화 자료와 함께 설명합니다.

| EDA 결과 | 모델 성능 (SHAP) |
| :---: | :---: |
| ![그래프1](https://via.placeholder.com/400x250) | ![그래프2](https://via.placeholder.com/400x250) |
| [설명: 시간대별 가격 변동 추이] | [설명: 모델 예측에 기여도가 높은 변수 분석] |

---

### 🏗 Directory Structure
```text
├── data/               # Raw & Processed Data
├── notebooks/          # EDA & Model Experiments (Jupyter Notebooks)
├── src/                # Final Model & Scripts
│   ├── preprocessing.py
│   └── train_model.py
└── README.md
