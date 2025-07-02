# 📊 03_ExcessWord_Analysis

이 폴더에는 KCI 초록 데이터에서 과잉어휘(excess vocabulary)를 분석한 코드 및 결과가 포함되어 있습니다.  

## 포함 파일

- `excess_words_by_year.ipynb` :  
연도별 초록 데이터를 기반으로 과잉어휘 후보를 도출하는 분석 노트북

## 분석 개요

- KCI 초록 데이터를 연도별로 분리해 주요 단어 빈도 계산
- 이전 연도 대비 비정상적으로 증가한 단어를 **과잉어휘 후보**로 간주
- 분석 방식은 Kobak et al. (2025)의  
  _"Delving into LLM-assisted writing through excess vocabulary"_ 논문을 참고하여 변형 적용함
