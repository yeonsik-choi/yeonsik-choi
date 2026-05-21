# 최연식 | 데이터 분석가

> 막연한 감이 아닌, 실제 데이터로 근거를 만들고 유저에게 더 나은 경험을 설계하는 일을 합니다.

Python과 R로 데이터를 분석하고 모델링하며, 유저 로그 기반 실험과 개인화 추천 시스템에 관심이 많습니다.
분석에서 끝나지 않고 백엔드·앱까지 직접 구현하며 데이터가 실제 서비스로 이어지는 과정을 경험하고 있습니다.

<br>

## Education & Activities

| | |
|---|---|
| 🎓 동국대학교 통계학과 / 데이터사이언스 소프트웨어 연계전공 | 2021.03 ~ 2027.02 졸업 예정 |
| 🪖 육군 병장 전역 | 2022.07 ~ 2024.01 |
| 📊 데이터 분석 학회 **B.a.f** 학회원 | 2025.01 ~ |
| 🏛 통계학과 부학생회장 | 2024.12 ~ |
| 🗃 SQL 개발자 (SQLD) 취득 | 2025.09 |

<br>

## Tech Stack

**Languages**
`Python` `R`

**분석 & AI**
`Pandas` `NumPy` `Scikit-learn` `matplotlib` `seaborn` `ggplot2`
`OpenCV` `MediaPipe` `YOLOv8` `LangChain` `OpenAI API`

**백엔드 & 앱**
`FastAPI` `Flutter`

**인프라 & 협업**
`PostgreSQL` `Supabase` `Docker` `AWS` `Vercel` `Git`

<br>

## Projects

### 메이플 썬데이 웹 개발
**[maplessunday.com](https://www.maplessunday.com)** · [GitHub](https://github.com/yeonsik-choi/maplessunday-web)

과거 썬데이 메이플 이벤트 데이터를 수집·분석해 다음 이벤트 등장 확률을 예측하는 웹 서비스입니다. Nexon Open API로 실시간 데이터를 연동하고, API 호출 제한 문제는 자체 캐싱 시스템으로 해결했습니다. 프론트(Vercel)와 백엔드(Docker+Render)를 분리 배포해 유지보수성을 높였습니다.

`HTML/CSS/JS` `FastAPI` `Supabase` `Docker` `Vercel` `Nexon Open API`

---

### 온라인 거래 이상 탐지
[GitHub](https://github.com/DGU-BAF/BAF-25-1-society)

IEEE-CIS & Vesta 거래 데이터로 결제 사기를 탐지하는 머신러닝 모델입니다. 사용자 ID가 없는 데이터에서 `card1`, `addr1`, `emaildomain`을 조합한 UID 파생변수를 제안해 핵심 피처로 활용했습니다. LightGBM + CatBoost를 Stacking 앙상블로 결합해 **ROC-AUC 0.952 (Public) / 0.927 (Private)** 를 달성했습니다.

`Python` `LightGBM` `CatBoost` `Optuna` `Scikit-learn`

---

### 아동·청소년 게임 이용 인식 분석

2020~2024년 한국콘텐츠진흥원 패널 데이터를 활용해 게임 행동 유형이 청소년의 삶에 미치는 영향을 실증 분석했습니다. OLS에서 나아가 고정 효과 패널 회귀(Fixed-Effect)를 적용해 개인 특성을 통제하고 인과성을 추정했습니다. 게임 이용이 대인관계 형성에 긍정적 영향을 미침을 통계적으로 검증했습니다.

`R` `dplyr` `plm` `gtsummary`

---

### 동국대학교 파이썬 강의 챗봇

강의안 데이터를 Key-Value 구조로 직접 구축하고, `difflib.get_close_matches`로 유사도 기반 매칭을 구현했습니다. 외부 API나 모델 파인튜닝 없이 비용 0원으로 강의 특화 챗봇을 만들었고, Gradio로 UI를 제공했습니다.

`Python` `Gradio` `Difflib`

---

### 사용자 위치 기반 운동 추천 챗봇 앱
[GitHub](https://github.com/DGU-BAF/BAF-25-2-sports)

GPS 기반으로 주변 운동 시설을 추천하는 대화형 앱입니다. LangChain + GPT-4o-mini로 환각을 억제하고, Vector DB 유사도 검색에 유클리드 거리 필터를 결합해 물리적으로 가까운 시설을 우선 추천하도록 했습니다. Flutter 앱과 FastAPI 서버를 연동해 풀스택으로 구현했습니다.

`LangChain` `OpenAI API` `FastAPI` `Flutter` `Supabase`

---

### 체형 기반 코디 추천 앱
[GitHub](https://github.com/CSID-DGU/2025-2-DSCDPasitongtong-06)

신체 사진으로 체형을 분류하고 보유 의류를 조합해 맞춤 코디를 제안하는 앱입니다. MediaPipe로 신체 랜드마크를 추출하고 절대 픽셀이 아닌 신체 비율(WHR, SHR)로 체형을 5가지로 분류해 촬영 환경 변화에 강한 모델을 구현했습니다. YOLOv8 + ResNet50/VGG16으로 의류 카테고리와 속성을 자동 태깅했습니다.

`Python` `OpenCV` `MediaPipe` `YOLOv8` `FastAPI` `Flutter` `Supabase`

<br>

## Contact

📧 chldustlr559@naver.com  
🐙 [github.com/yeonsik-choi](https://github.com/yeonsik-choi)
