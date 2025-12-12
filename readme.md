# 📚 Minseok's Portfolio – Computer Vision & AI Projects

이 레포지토리는 제가 개발한 주요 프로젝트들을 정리한 **포트폴리오 저장소**입니다.  
컴퓨터비전(CV), 딥러닝(AI), 네트워크/백엔드 개발 등 다양한 기술을 사용한 프로젝트들을 포함하고 있습니다.

---

# 📌 Projects Overview

## 1️⃣ GooseTalk – 실시간 멀티 채팅 애플리케이션 (Java)
**기간:** 2024.09 ~ 2024.12  
**기술:** Java, TCP Socket, Multi-threading, JSON Protocol, Git

실시간 소켓 통신 기반으로 만든 채팅 애플리케이션입니다.  
친구관리, 공지, DM, 투표, 출석, 이모티콘 등 다양한 기능을 갖춘 확장형 구조입니다.

### 🔧 주요 기능
- 친구 추가/삭제 및 프로필 정보 동기화  
- 실시간 메시지 및 DM  
- 공지 고정 및 해제  
- 투표 생성·참여·마감  
- 출석부 기능  
- 멀티 스레드 기반 고성능 서버 구조

### 📐 서버 구조 (요약)

GooseTalk/
├── GooseTalk_Client/
│   ├── .classpath
│   ├── .project
│   ├── .settings/
│   ├── src/
│   │   └── com/goosetalk/client/
│   │       ├── app/
│   │       ├── controller/
│   │       ├── model/
│   │       └── view/
│   ├── lib/
│   ├── bin/
│   ├── resources/
│   ├── data/
│   ├── .gitignore
│   └── README.md
│
├── GooseTalk_Server/
│   ├── .classpath
│   ├── .project
│   ├── .settings/
│   ├── src/
│   │   └── com/goosetalk/server/
│   │       ├── app/
│   │       ├── controller/
│   │       ├── model/
│   │       └── service/
│   ├── lib/
│   ├── bin/
│   ├── resources/
│   ├── data/
│   ├── .gitignore
│   └── README.md

---
## 2️⃣ Stanford Dogs 120종 분류 CNN (Deep Learning)
**기간:** 2024.11  
**기술:** TensorFlow, Keras, DenseNet121, Python, OpenCV

120종의 견종을 분류하는 딥러닝 모델을 학습했습니다.  
ImageNet pretrained DenseNet121을 기반으로 Fine-tuning 하여 만든 모델입니다.

### 🔧 주요 기능
- CNN 모델 구성 및 학습  
- Softmax 확률 기반 견종 예측  
- dog_3.jpg 테스트 이미지 분류  
- GUI(PyQt5) 연동하여 실사용 프로그램 제작

### 📊 모델 구조
- DenseNet121 Backbone  
- GlobalAveragePooling → Dense(120 Softmax)  
- Epochs: 60  

---

## 3️⃣ Panorama Stitching – OpenCV 특징점 기반 이미지 합성
**기간:** 2024.10  
**기술:** Python, OpenCV(SIFT, FLANN, Homography), NumPy

3장의 이미지를 SIFT 특징점을 매칭하여 하나의 파노라마 이미지로 합성했습니다.

### 🔧 주요 기능
- SIFT 특징점 추출  
- FLANN 기반 매칭  
- Lowe's Ratio Test 적용  
- Homography 계산 및 warpPerspective  
- 결과 파노라마 생성 및 저장

---

## 4️⃣ Soccer Ball Detection – 객체 인식 (SIFT/FLANN)
**기간:** 2024.11  
**기술:** Python, OpenCV, SIFT, FLANN, NumPy

축구장 장면에서 모델 축구공 이미지를 기반으로 객체를 탐지하고  
중심 + 반지름을 계산하여 원을 그리는 기능을 구현했습니다.

### 🔧 주요 기능
- 모델 이미지 vs 장면 이미지 특징점 매칭  
- Homography 기반 위치 추정  
- 사각형 중심 계산  
- 내접 원의 반지름 계산 후 원 그리기  
- Resize하여 대형 이미지에서도 안정적인 검출

---

# 🛠 Tech Stack Summary
- **Languages:** Java, Python, C++, JavaScript  
- **Backend:** Socket Programming, Multi-threading  
- **AI/CV:** OpenCV, TensorFlow, Keras, SIFT, FLANN  
- **Cloud:** AWS Lambda, IoT Core, SAM CLI  
- **Tools:** Git, IntelliJ, VSCode, Spyder, Docker  

---

# 📎 Contact
- **Email:** (본인 이메일 입력)  
- **GitHub:** https://github.com/Duckrjdnl  

---

감사합니다!  
프로젝트별 코드는 추후 각 레포지토리에 업데이트할 예정입니다.
