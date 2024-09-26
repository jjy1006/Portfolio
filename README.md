

### 1. 뱅킹 웹 서비스 (팀 프로젝트) 
2024.04.20 ~ 2024.06.25

**🛠 사용 기술**:  
![Java Badge](https://img.shields.io/badge/Java-%23ED8B00.svg?style=flat-square&logo=openjdk&logoColor=white) 
![Spring Badge](https://img.shields.io/badge/Spring-%236DB33F.svg?style=flat-square&logo=spring&logoColor=white) 
![MyBatis Badge](https://img.shields.io/badge/MyBatis-%23ED8B00.svg?style=flat-square&logo=MyBatis&logoColor=white) 
![JavaScript Badge](https://img.shields.io/badge/JavaScript-%23F7DF1E.svg?style=flat-square&logo=javascript&logoColor=black) 
![JSP Badge](https://img.shields.io/badge/JSP-%230769AD.svg?style=flat-square&logoColor=white) 
![Oracle Badge](https://img.shields.io/badge/OracleDB-%23F80000.svg?style=flat-square&logo=oracle&logoColor=white) 
![HTML5 Badge](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white) 
![CSS3 Badge](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)

**개발인원** : 2명 

**담당 역할**: 요구사항 설계, DB 설계 , 백엔드, 프론트앤드, 디자인 

**GitHub Repository**: [GitHub 링크](https://github.com/Helluoo/bank)



### 프로젝트 설명
회원가입 , 계좌생성, 상품가입, 계좌이체 서비스를 제공하고 이를 위한 관리자 기능을 사용할 수 있는 Spring 프레임워크 기반의 웹서비스입니다. 

### 세부 기능
- MVC 패턴
- 회원가입 및 계좌 개설
- Transaction 처리를 통한  계좌 조회/이체

### 문제

### 해결


---


## 식물인식 판별기(개인)
2024.05.01 ~ 2024.06.14


**🛠 사용 기술**:  
![Python Badge](https://img.shields.io/badge/Python-%2314354C.svg?style=flat-square&logo=python&logoColor=white) 
![Scikit-learn Badge](https://img.shields.io/badge/Scikit--learn-%23F7931E.svg?style=flat-square&logo=scikit-learn&logoColor=white) 
![Random Forest Badge](https://img.shields.io/badge/Random_Forest-%2366CCFF.svg?style=flat-square&logoColor=white) 
![OpenCV Badge](https://img.shields.io/badge/OpenCV-%235C3EE8.svg?style=flat-square&logo=opencv&logoColor=white) 
![Tkinter Badge](https://img.shields.io/badge/Tkinter-%23FF6347.svg?style=flat-square&logo=python&logoColor=white) 


**담당 역할**:  데이터셋 수집, 모델 개발, GUI 구현 

**GitHub Repository**: [GitHub 링크](https://github.com/jjy1006/Basil)



### 프로젝트 설명
이미지 분류 모델을 사용하여 바질과 인삼을 구분하는 애플리케이션을 개발하는 것을 목표로 하였습니다. OpenCV를 활용하여 이미지 데이터를 전처리하고, Random Forest 알고리즘을 적용하여 바질과 인삼을 분류하는 모델을 학습시켰습니다. 사용자는 GUI에서 이미지를 업로드하면 해당 식물(바질 또는 인삼)을 실시간으로 예측할 수 있습니다. Tkinter를 이용해 사용자가 이미지 분류 결과를 쉽게 확인할 수 있도록 직관적인 인터페이스를 제공하였습니다.


### 세부 기능
- 훈련된 모델을 사용해 사용자가 업로드한 이미지를 바질 또는 인삼으로 분류
- GUI를 통해 이미지 업로드 및 결과를 직관적으로 확인 가능
- 이미지 전처리 및 분류 결과를 실시간으로 제공

- 데이터 수집
  - 촬영기종 = iPhone 12 Pro
  - 훈련 데이터셋 : 423장 , 검증 데이터셋 51장


### 문제


### 해결

---

## 수어인식 변역기(개인)
2024.06.01 ~ 2024.06.30


**🛠 사용 기술**:  
![Python Badge](https://img.shields.io/badge/Python-%2314354C.svg?style=flat-square&logo=python&logoColor=white) ![OpenCV Badge](https://img.shields.io/badge/OpenCV-%235C3EE8.svg?style=flat-square&logo=opencv&logoColor=white) ![MediaPipe Badge](https://img.shields.io/badge/MediaPipe-%23FF3D00.svg?style=flat-square&logo=google&logoColor=white) ![NumPy Badge](https://img.shields.io/badge/NumPy-%23013243.svg?style=flat-square&logo=numpy&logoColor=white) ![KNN Badge](https://img.shields.io/badge/KNN-%234C8C4A.svg?style=flat-square&logoColor=white)



**담당 역할**:  데이터 수집, 영상 처리, 제스처 인식, 손가락 감지 및 추적, 결과 출력 

**GitHub Repository**: [GitHub 링크](https://github.com/jjy1006/Basil)



### 프로젝트 설명
실시간으로 기초적인 알파벳 수어 동작을 인식하여 번역해주는  애플리케이션을 개발하는것을 목표로 하였습니다. OpenCV와 MediaPipe를 활용하여 웹캠에서 손의 위치와 동작을 감지하고, KNN 알고리즘을 통해 수어 제스처를 인식 사용자는 손의 제스처를 통해 알파벳을 입력할 수 있으며, 인식된 결과는 화면에 표시됩니다.
### 세부 기능
- 손가락 인식: MediaPipe를 사용하여 손가락의 위치를 실시간으로 추적
- 제스처 인식: KNN 알고리즘을 통해 수어 알파벳 제스처를 인식하고 출력
- 데이터 수집: 손 제스처 각도를 데이터로 저장
- 시각적 피드백: 인식된 제스처를 화면에 텍스트로 표시하여 사용자가 결과를 확인할 수 있도록 함.
- 사용자 인터페이스: 간단한 UI를 통해 직관적으로 사용할 수 있도록 설계.



### 문제


### 해결

---

## 영화추천 웹페이지(개인)
2023.04.15 ~ 2023.04.17


**🛠 사용 기술**:  
![HTML5 Badge](https://img.shields.io/badge/HTML5-%23E34F26.svg?style=flat-square&logo=html5&logoColor=white) 
![CSS3 Badge](https://img.shields.io/badge/CSS3-%231572B6.svg?style=flat-square&logo=css3&logoColor=white)


**담당 역할**:  기획,디자인,프론트엔드 

**GitHub Repository**: [GitHub 링크](https://github.com/jjy1006/netflix)



### 프로젝트 설명
HTML과 CSS를 활용하여 간단한 영화 추천 웹페이지를 제작하였습니다. ,직관적인 디자인과 구조를 통해 사용자에게 장르별로 영화를 추천하는 시스템을 제공합니다. 주요 목표는 넷플릭스 스타일의 영화 추천 인터페이스를 구현하는 것이며, 사용자가 진입 후 다양한 추천 영화 리스트를 확인할 수 있는 페이지로 연결됩니다. 전체적으로 심플하고 사용하기 쉬운 인터페이스를 구성하였습니다.

### 세부 기능
- 장르별로 영화를 추천


### 문제


### 해결





