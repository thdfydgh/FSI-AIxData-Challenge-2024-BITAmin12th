# **FSI AIxData Challenge 2024**
![image](https://github.com/user-attachments/assets/b65320be-7b41-4a9f-94fc-503fb7174220)


## 대회개요

- 주최 / 주관 : 금융보안원
- 후원 : 금융위원회, KB국민은행, 하나은행, 미래에셋증권, 생명보험협회
- 운영 : 데이콘
- 기간 : 2024/08/05-2024/10/11
- 주제 : 이상금융거래 데이터셋으로 분류 AI모델을 구현하고, 오픈소스 생성형 AI 모델을 응용/활용하여 분류 AI모델의 성능을 개선
- 대회 설명 :
    1) 클래스 불균형이 심한 데이터셋의 특성을 고려하여 분류 AI모델 개발
    2) 제공하는 데이터셋을 오픈소스 생성형 AI 모델 등 AI 기술에 응용
    3) 이를 분류 AI모델에 활용함으로써 분류 AI모델의 성능을 개선

## 팀/멤버

- 팀 : BITAmin 12기
- 멤버 :
  
<div align="center">

| 김재원                     | 박석우                     | 송용호                          | 황영서                     |
|-----------------------------|-----------------------------|----------------------------------|-----------------------------|
| 고려대학교<br>반도체공학과  | 서울대학교<br>산업공학과    | 서울과학기술대학교<br>산업정보시스템공학과 | 숙명여자대학교<br>IT공학전공 |
| [@eric98040](https://github.com/eric98040) | [@ParkSeokwoo](https://github.com/ParkSeokwoo) | [@thdfydgh](https://github.com/thdfydgh) | [@youngseoh](https://github.com/youngseoh) |

</div>






## 파일 구조
```
.
├── data/
│   ├── train.csv
│   ├── test.csv
│   ├── sample_submission.csv
│   ├── only_ctgan.csv
│   └── others.csv
│
├── final.ipynb
├── saved_models.zip
├── ACTGAN_weight.pth
│ 
└── clf_submission/
    ├── data/
    │   ├── ACTGAN_clf_submission.csv
    │   ├── CTGAN_clf_submission.csv
    │   ├── ForestDiffusion_clf_submission.csv
    │   └── TVAE_clf_submission.csv
    │
    ├── ACTGAN_clf_submission.ipynb
    ├── CTGAN_clf_submission.ipynb
    ├── ForestDiffusion_clf_submission.ipynb
    ├── TVAE_clf_submission.ipynb
    ├── Cocnat_ctgan_actgna_tvae_forestdiffusion.ipynb
    └── CTGAN_1000_clf_submission.ipynb
```

## Requirements
```
sdv==1.16.1
gretel-synthetics==0.18.0
ForestDiffusion==1.0.5
pandas==1.5.3
numpy==1.26.4
lightgbm==4.5.0
xgboost==2.1.1
scikit-learn==1.5.1
torch==2.4.1
```

## Score

- PRIVATE : 0.80137(6/941)
- PUBLIC : 0.80396(10/1037)

