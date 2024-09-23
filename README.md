# 태현수
인공지능 개발자 지망 학생

## 🛠️ Skills
**Python**  
- Python을 활용한 컴퓨터 비전 프로젝트 경험 有
- 백준 Online Judge Silver 5 티어

**CNN**
- CNN을 활용한 프로젝트 경험 有
- 신경망을 설계하여 모델을 학습시킬 수 있음
- CNN의 동작 원리와 구성 요소를 이해하고 있음

**Yolov5**
- Yolov5를 활용한 Object Detection, Classification 경험 多

**Opencv**
- Opencv를 통해 카메라 화면에 인공지능을 적용시킬 수 있음


&nbsp;  

## 💻 Project

### S.C.C(Subway Crowd Control AI)
'23.05.30 - '23.06.28, 개발인원 1명

**[프로젝트 개요]**
- 첫번째 인공지능 개발 경험이자 동아리 활동으로 진행한 프로젝트 입니다. 
- 인구 과밀집으로 인한 사고를 예방하기 위해 개발된 시스템입니다.
- Yolov5를 활용한 객체탐지를 통해 사람의 머리를 세어 인원을 파악하고, 임계값 이상의 인원이 인식되면 안내 방송을 통해 통제합니다.
- Intel Global Impact 출품작으로서, 대한민국 대표 3팀에 선정된 프로젝트이기도 합니다.  

**[역할] : AI 개발자**
- 시스템 설계 및 구현 :
병렬 Thread 및 Opencv 이용 실시간 웹캠 시스템 구축, Pygame 이용 안내방송 송출 설계 
- 데이터 수집 및 모델 학습 :
모델 학습을 위한 이미지 수집 및 Yolov5 커스텀 트레이닝

**[주요 라이브러리]**
-Opencv, Yolov5, Pygame, Torch, Thread

**🎥시연영상**
https://youtu.be/7izh1vydHPA?si=bGfsZP107jjBp1-M

**GitHub:**
https://github.com/xohyver/Subway_Crowd_Control_AI-S.C.C-.git


&nbsp;  

### 자동 분류 쓰레기통
'24.07.05 - '24.09.30
개발인원
> |                    Name                    |  Position   |
> | :----------------------------------------: | :---------: |
> | [김동우](https://github.com/kimphysicsman) |   Software  |
> |   [김진수](https://github.com/creamone)    |   Hardware  |


**[프로젝트 개요]**
- 스스로 쓰레기를 분류하는 똑똑한 쓰레기통입니다.
- 아두이노와의 시리얼 통신으로 모터를 동작시킵니다. 
- Pet, Can, Bottle 세 종류의 쓰레기를 분리수거할 수 있습니다.

**[역할] : AI 개발자 및 구조물 제작**
- 모델 학습 :
Yolov5를 활용, 적은 이미지로 99.8%의 val_accuracy를 뽑아냄
- 코드 논리 구성 :
인식된 객체의 클래스에 따라 각 케이스 별로 모터가 동작하도록 함
- 카메라 각도 결정 :
카메라 위치 및 각도 조절을 통해 기존 80%의 정확도를 95%까지 향상시킴
- 연산 최적화
time 이용하여 5초 간격의 프레임 캡쳐 실행하도록 최적화

**[주요 라이브러리]**
-Opencv, Yolov5, Tensorflow, Time, Serial, Numpy

**🎥시연영상**
유튜브 링크달기

**GitHub:**
깃허브 링크


&nbsp;  






