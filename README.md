# 📚 혼자 공부하는 머신러닝+딥러닝 실습

> 박정현著的 **〈혼자 공부하는 머신러닝+딥러닝(개정판)〉**(한빛미디어, 2025)의 영상 강의를 따라하며 실습하는 프로젝트입니다.

## 🎯 학습 목표

- 머신러닝과 딥러닝의 기본 개념 이해
- Python을 활용한 머신러닝 알고리즘 구현 및 실습
- 케라스(Keras)와 파이토치(PyTorch)를 활용한 딥러닝 모델 학습
- 트랜스포머와 대규모 언어 모델(LLM) 이해

## 🛠️ 학습 환경

- **OS**: macOS (ARM64)
- **IDE**: PyCharm / JupyterLab
- **패키지 관리자**: uv
- **Python**: 3.11+

### 주요 의존성

| 패키지 | 용도 |
|--------|------|
| jupyterlab | 노트북 환경 |
| pandas | 데이터 처리 |
| matplotlib | 시각화 |

## 📖 영상 강의 플레이리스트

[**[머신러닝+딥러닝 기초 강의]**](https://www.youtube.com/watch?v=2a5Xc9S3vm0&list=PLJN246lAkhQihHwcbrZp9uuwgxQen5HS-) (YouTube)

## 📂 프로젝트 구조

```
hg-mdld-practice/
├── README.md          # 이 파일
├── pyproject.toml     # 프로젝트 의존성 관리
├── uv.lock            # uv 잠금 파일
├── .gitignore         # Git 무시 규칙
├── notebooks/         # Jupyter 실습 노트북 (장별 파일명 구분)
├── data/              # 데이터 파일 저장 폴더
└── models/            # 학습된 모델 저장 폴더
```

### 노트북 파일명 규칙

각 장별 실습 노트북은 `notebooks/` 폴더에 저장하며, 아래 규칙으로 이름을 붙입니다.

| 형식 | 예시 |
|------|------|
| `MM_장제목.ipynb` | `01_인공지능과_머신러닝.ipynb` |
| `MM_장제목_하위주제.ipynb` | `03_회귀분석_선형회귀.ipynb` |

한 장에 노트북이 여러 개 생기면 하위주제를 추가하여 구분합니다.

## 📚 장별 학습 내용

| 장 | 주제 | 주요 내용 |
|----|------|-----------|
| 1장 | 인공지능과 머신러닝 | AI, ML, DL의 개념과 역사, Jupyter 사용법 |
| 2장 | Python과 NumPy | Python 기초, NumPy 배열 연산 |
| 3장 | 회귀 분석 | 선형 회귀, 다항 회귀, 과적합과 정규화 |
| 4장 | 분류 분석 | 로지스틱 회귀, SVM, k-NN |
| 5장 | 앙상블 학습 | 결정 트리, 랜덤 포레스트, 그래디언트 부스팅 |
| 6장 | 비지도 학습 | k-평균 클러스터링, PCA, 차원 축소 |
| 7장 | 딥러닝 기초 | 신경망, 역전파, 케라스/파이토치 구현 |
| 8장 | 합성곱 신경망(CNN) | 이미지 분류, 컨볼루션, 풀링 |
| 9장 | 순환 신경망(RNN) | 시계열 분석, LSTM, GRU |
| 10장 | 트랜스포머와 LLM | 어텐션, 트랜스포머, KoBART, EXAONE |

## 🚀 시작하기

### 1. 의존성 설치

```bash
uv sync
```

### 2. JupyterLab 실행

```bash
uv run jupyterlab
```

### 3. 실습 노트북 복사

원본 저장소의 노트북을 참고하여 실습합니다.

```bash
# 원본 저장소 클론 (참고용)
git clone https://github.com/rickiepark/hg-mldl2.git ../hg-mldl2-reference
```

## 📌 참고 자료

- **원본 코드 저장소**: [rickiepark/hg-mldl2](https://github.com/rickiepark/hg-mldl2)
- **도서 정보**: [한빛미디어](https://www.hanbit.co.kr/store/books/look.php?p_code=B9993598694)
- **에러타 및 업데이트**: [텐서플로우 블로그](https://tensorflow.blog/hg-mldl2)
- **Q&A 커뮤니티**: [구글 그룹스](https://groups.google.com/g/mldl-book)

## 📝 학습 노트

학습 중 정리한 내용과 인사이트를 여기에 기록합니다.

---

> 💡 **Tip**: 영상 강의를 따라하면서 각 장별 노트북을 직접 작성하고, 이해가 안 되는 부분은 원본 저장소의 코드를 참고하세요.
