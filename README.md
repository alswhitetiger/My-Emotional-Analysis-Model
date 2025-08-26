# 🎬 Naver 영화 리뷰 감성 분석 딥러닝 모델 
  
### 이 프로젝트는 **Naver 영화 리뷰 데이터셋(NSMC)**을 사용하여 사용자가 입력한 한국어 문장의 긍정과 부정을 예측하는 딥러닝 모델입니다. **TensorFlow(Keras)**와 Konlpy를 활용하여 자연어 처리의 기본적인 흐름을 학습하고 구현하는 것을 목표로 합니다.

---

# ✨ 주요 기능 

### 실시간 감성 분석: 사용자가 입력하는 리뷰 텍스트의 긍정/부정 확률을 실시간으로 예측합니다.

### 한국어 전처리: Konlpy(Okt)를 이용한 형태소 분석, 불용어 제거 등 한국어 텍스트에 최적화된 전처리 파이프라인을 포함합니다.

### LSTM 모델 활용: 문장의 순차적인 맥락을 잘 학습하는 LSTM(Long Short-Term Memory) 신경망을 기반으로 모델을 구축했습니다.

---

# 🚀 사용 방법 
  
### 저장소 복제(Clone)

```bash
git clone https://github.com/your-username/your-repository-name.git
cd your-repository-name
```
필요한 라이브러리 설치

Bash

pip install pandas scikit-learn tensorflow konlpy
Jupyter Notebook 실행
practice.ipynb 파일을 열고 전체 셀을 순서대로 실행하면 모델 학습부터 실시간 추론까지 직접 테스트해볼 수 있습니다.

---

<h1> 🛠️ 사용된 기술 및 라이브러리 <h1>

Python: 프로젝트의 기본 프로그래밍 언어

TensorFlow (Keras): 딥러닝 모델의 설계, 학습 및 추론

Pandas: 데이터 로드 및 기본 처리

Scikit-learn: 데이터 분할

Konlpy (Okt): 한국어 형태소 분석 및 토큰화

Numpy: 데이터 배열 처리

Jupyter Notebook: 프로젝트 개발 환경

---

<h1> 📊 데이터셋 <h1>

Naver Sentiment Movie Corpus (NSMC)

설명: 네이버 영화 리뷰에서 수집된 20만 개의 문장으로 구성된 데이터셋입니다.

구성: 긍정(1) 또는 부정(0) 라벨이 달려있으며, 훈련용 데이터 15만 개, 테스트용 데이터 5만 개로 이루어져 있습니다.

출처: e9t/nsmc GitHub Repository
