# 📚 혼자 공부하는 머신러닝+딥러닝 실습

> 박해선 저 **〈혼자 공부하는 머신러닝+딥러닝(개정판)〉**(한빛미디어, 2025)의 영상 강의를 따라하며 실습하는 프로젝트입니다.

## 🎯 학습 목표

- 머신러닝과 딥러닝의 기본 개념 이해
- Python을 활용한 머신러닝 알고리즘 구현 및 실습
- 케라스(Keras)와 파이토치(PyTorch)를 활용한 딥러닝 모델 학습
- 트랜스포머와 대규모 언어 모델(LLM) 이해

## 🛠️ 학습 환경

- **실행 환경**: [Google Colab](https://colab.research.google.com/) (로컬 런타임은 사용하지 않음)
- **노트북 저장소**: 이 GitHub 저장소 (`notebooks/`)
- **GPU**: 7장 이후 딥러닝 실습은 Colab의 `런타임 > 런타임 유형 변경`에서 GPU를 선택

## 📖 영상 강의 플레이리스트

[**[머신러닝+딥러닝 기초 강의]**](https://www.youtube.com/watch?v=2a5Xc9S3vm0&list=PLJN246lAkhQihHwcbrZp9uuwgxQen5HS-) (YouTube)

## 📂 프로젝트 구조

```
hg-mldl-practice/
├── README.md          # 이 파일
├── pyproject.toml     # 로컬 의존성 정의 (Colab 실습에는 사용하지 않음)
├── uv.lock            # uv 잠금 파일
├── .gitignore         # Git 무시 규칙
└── notebooks/         # 실습 노트북 (장-절별 파일명 구분)
```

### 노트북 파일명 규칙

원본 저장소와 같은 `장-절` 형식으로 이름을 붙여, 원본 노트북과 1:1로 비교할 수 있게 합니다.

| 형식 | 예시 |
|------|------|
| `CC-S.ipynb` | `01-3.ipynb` (1장 3절) |
| `CC-S.pytorch.ipynb` | `07-2.pytorch.ipynb` (파이토치 버전) |

## 📚 장별 학습 내용

| 장 | 주제 | 주요 내용 |
|----|------|-----------|
| 1장 | 나의 첫 머신러닝 | 인공지능·머신러닝·딥러닝, 코랩과 주피터 노트북, k-최근접 이웃 |
| 2장 | 데이터 다루기 | 훈련 세트와 테스트 세트, 데이터 전처리 |
| 3장 | 회귀 알고리즘과 모델 규제 | k-최근접 이웃 회귀, 선형 회귀, 특성 공학과 규제 |
| 4장 | 다양한 분류 알고리즘 | 로지스틱 회귀, 확률적 경사 하강법 |
| 5장 | 트리 알고리즘 | 결정 트리, 교차 검증과 그리드 서치, 트리의 앙상블 |
| 6장 | 비지도 학습 | 군집 알고리즘, k-평균, 주성분 분석 |
| 7장 | 딥러닝을 시작합니다 | 인공 신경망, 심층 신경망, 신경망 모델 훈련 (케라스/파이토치) |
| 8장 | 이미지를 위한 인공 신경망 | 합성곱 신경망, 이미지 분류, 시각화 |
| 9장 | 텍스트를 위한 인공 신경망 | 순환 신경망, IMDB 리뷰 분류, LSTM과 GRU |
| 10장 | 트랜스포머와 대규모 언어 모델 | 어텐션, 트랜스포머, KoBART, EXAONE, OpenAI API |

## 🚀 Colab에서 실습하기

### 1. 노트북 열기

Colab에서 `파일 > 노트북 열기 > GitHub` 탭을 선택하고 `calmbino/hg-mldl-practice`를 검색하거나, 아래 형식의 URL로 바로 엽니다.

```
https://colab.research.google.com/github/calmbino/hg-mldl-practice/blob/main/notebooks/01-3.ipynb
```

### 2. GitHub에 저장하기

`파일 > GitHub에 사본 저장`을 선택하고 저장소 `calmbino/hg-mldl-practice`, 브랜치 `main`, 경로 `notebooks/<파일명>.ipynb`를 지정합니다.

> ⚠️ Colab에서 저장하면 GitHub에 바로 커밋되므로, 로컬 저장소에서 작업하기 전에 `git pull`로 먼저 동기화하세요.

### 3. 원본 노트북 참고

원본 저장소의 노트북은 Colab에서 바로 열어 볼 수 있습니다.

```
https://colab.research.google.com/github/rickiepark/hg-mldl2/blob/main/01-3.ipynb
```

## 📌 참고 자료

- **원본 코드 저장소**: [rickiepark/hg-mldl2](https://github.com/rickiepark/hg-mldl2)
- **도서 정보**: [한빛미디어](https://hanbit.co.kr/store/books/look.php?p_code=B7077594897)
- **에러타 및 업데이트**: [텐서플로우 블로그](https://tensorflow.blog/hg-mldl2)
- **Q&A 커뮤니티**: [구글 그룹스](https://groups.google.com/g/mldl-book)

## 📝 학습 노트

학습 중 정리한 내용과 인사이트를 여기에 기록합니다.

---

> 💡 **Tip**: 영상 강의를 따라하면서 각 장별 노트북을 직접 작성하고, 이해가 안 되는 부분은 원본 저장소의 코드를 참고하세요.
