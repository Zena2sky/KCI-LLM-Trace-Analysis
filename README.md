# KCI-LLM-Trace-Analysis

이 리포지터리는 생성형 인공지능(LLM, Large Language Models)의 사용이 한국 학술 글쓰기에 미친 영향을 KCI 초록 데이터를 기반으로 탐색하는 분석 프로젝트입니다.

---

## 🎯 리포지터리 목적

본 프로젝트는 KCI(한국학술지인용색인) 등재 논문 초록(2004~2024)을 대상으로, LLM의 간접 사용 흔적(stylistic trace)이 언어 스타일에 미치는 영향을 정량적으로 분석하고 시각화하는 것을 목표로 합니다.

---

## 🧾 주요 내용

- KCI 초록 텍스트 전처리 및 정규화
- 연도별 과잉어휘(excess vocabulary) 변화 분석
- 시각화를 통한 문체 변화 탐지

---

## 🔍 데이터 설명

- **데이터 출처**: KCI (한국학술지인용색인)
- **분야**: 인문학 및 사회과학
- **기간**: 2019년 ~ 2024년
- **표본 수**: 약 3,000건의 초록

> 데이터는 연구용으로만 활용되며, KCI 공식 정보이용 신청서를 통해 적법하게 수집되었습니다.  
> 👉 [KCI_data_agreement.pdf](./05_Appendix_Resources/KCI_data_agreement.pdf)

---

## 📁 디렉토리 구성

```plaintext
KCI-LLM-Trace-Analysis/
├── 01_Data/                     # 원본 KCI 초록 샘플 및 스키마 설명
├── 02_Preprocessing/           # 텍스트 클리닝 및 정규표현식 기반 전처리
├── 03_ExcessWord_Analysis/     # 연도별 과잉어휘 분석 노트북
├── 04_Visualizations/          # Word shift 등 시각화 결과물
├── 05_Appendix_Resources/      # 부속 문서 및 공식 PDF 자료 (정보이용 신청서 등)
└── README.md                   # 리포지터리 설명 파일 (바로 이 파일)
```

---

## ✍️ 작성자

- **Maintainer**: [Zena2sky](https://github.com/Zena2sky)
- **Contact**: [GitHub Issues](https://github.com/Zena2sky/KCI-LLM-Trace-Analysis/issues)

> 본 리포지터리는 한국 학술 환경 내 LLM의 영향력 분석을 위한 기초 작업으로,  
> 후속 연구와 비교 분석, 도구화 작업으로 확장될 예정입니다.
