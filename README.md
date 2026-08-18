# skala-dataAnalyzing

SKALA 데이터 분석 개요 및 기초통계 실습. 표본 분포 이론과 선형회귀 두 축으로 진행했습니다.

## 노트북

### `실습_SamplingTheory.ipynb`
표본과 분포를 시뮬레이션으로 확인합니다. 대수의 법칙, 제곱근의 법칙 등을 각각 **Question → Expectation → Code Run → Result → Interpretation → AI Application** 순서로 다룹니다. 결과를 먼저 예상하고 코드로 검증한 뒤, 그 원리가 AI에서 어디에 쓰이는지 연결하는 구성입니다.

### `실습_LinearRegression.ipynb`
회귀분석 실습.

- Data Load · EDA · Baseline 모델
- 잔차진단 (Residual Diagnostics)
- Task 1 — Baseline 회귀 결과 해석
- Task 2 — 모델 개선
- Task 3 — 유의하지 않은 변수 제거

비선형성 확인 파트가 별도로 포함되어 있습니다.

## 결과물

- `광주_1반_서혁인_Day2회귀분석.html` — Day2 회귀분석 결과 리포트
- `광주_1반_서혁인_Day2회귀분석_1p.html` — 1페이지 요약본
- `SKALA_4기_1반_데이터분석개요및기초통계_서혁인.pdf` — 제출 리포트

## 실행

```bash
pip install pandas numpy scipy statsmodels scikit-learn matplotlib seaborn
jupyter notebook
```
