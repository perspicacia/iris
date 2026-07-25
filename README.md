# Iris Data Analysis & Prediction App

붓꽃(Iris) 데이터셋의 형태적 특징을 분석하여  
**품종별 차이를 탐색**하고,  
사용자가 입력한 값을 바탕으로 **품종을 예측할 수 있는 웹 애플리케이션**으로 구현한 데이터 분석 프로젝트입니다.

## Live Demo
- Demo: [Iris App](https://perspicacia.github.io/iris/)
- Repository: [GitHub Repository](https://github.com/perspicacia/titanic)

## Project Overview

이 프로젝트는 붓꽃 데이터의 4가지 주요 특성을 바탕으로  
품종 간 차이를 분석하고 예측 가능한 구조로 연결하는 것을 목표로 했습니다.

다음과 같은 질문에 답하는 것을 중심으로 진행했습니다.

- 어떤 feature가 품종 구분에 중요한 역할을 하는가
- 품종별 데이터 분포는 어떻게 다른가
- 사용자가 입력한 수치를 바탕으로 실시간 예측이 가능한가

단순히 분류 결과를 보여주는 데서 끝나는 것이 아니라,  
분석 결과를 시각적으로 이해하고 직접 실험해볼 수 있도록 앱 형태로 구현했습니다.

## Dataset

- Dataset: Iris dataset
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Target:
  - Setosa
  - Versicolor
  - Virginica

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- HTML / CSS / JavaScript

## Analysis Process

1. 데이터 구조와 feature 구성 확인
2. 품종별 기초 통계 및 분포 확인
3. feature 간 상관관계 분석
4. 시각화를 통한 품종별 패턴 비교
5. 분류 모델 적용
6. 예측 기능을 웹 애플리케이션으로 구현

## Key Insights

- **Petal Length**와 **Petal Width**는 품종을 구분하는 데 특히 중요한 변수로 나타났습니다.
- Setosa는 다른 품종과 비교했을 때 상대적으로 뚜렷하게 구분되는 패턴을 보였습니다.
- 일부 feature는 단독으로 볼 때보다 조합해서 볼 때 더 높은 설명력을 보였습니다.
- 분석 결과를 시각화와 예측 기능으로 연결하면 사용자가 데이터 차이를 더 직관적으로 이해할 수 있습니다.

## Model

이 프로젝트에서는 붓꽃의 형태 정보를 바탕으로  
품종을 예측하는 **Decision Tree 분류 모델**을 적용했습니다.

모델은 사용자가 입력한 feature 값을 기반으로  
Setosa, Versicolor, Virginica 중 하나를 예측하도록 구성했습니다.


## App Features

- feature 값 직접 입력
- 입력값에 따른 품종 예측
- 품종별 특징 비교
- 주요 시각화 확인
- 데이터 기반 해석 지원

## Why This Project Matters

이 프로젝트는 단순한 분류 실습을 넘어서,  
**데이터를 해석하고 설명 가능한 결과로 연결하는 과정**에 초점을 두었습니다.

특히 사용자가 직접 값을 입력하고 결과를 확인할 수 있도록 구성함으로써,  
데이터 분석 결과를 보다 직관적이고 인터랙티브한 형태로 전달할 수 있도록 했습니다.

## Folder Structure

```bash
.
├── data
├── notebooks
├── src
├── app
└── README.md
