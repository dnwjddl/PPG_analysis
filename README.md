# PPG_analysis 
PPG_analysis by emotion / 생체신호 기반 감정에 따른 영상평가지표 설계
## 주제
PPG(Photoplethysmography)기반 생체신호를 이용한 영상평가지표 설계

## 측정 방법 및 하드웨어
![image](https://user-images.githubusercontent.com/72767245/97099017-f97d3480-16c6-11eb-9ee4-f6572329b609.png) ![image](https://user-images.githubusercontent.com/72767245/97099026-10bc2200-16c7-11eb-8041-d2b436b58b88.png)

Idaq 400으로 측정

## 분석 알고리즘
1. 피험자 dataset 불러오기
2. 전처리
3. peak 값 검출
4. Amplitude PPI 계산
5. Reference 기반 변화율 계산
6. 피험자의 각 영상별 변화율 csv로 출력

## 새로운 사용자의 감성 분석 알고리즘
1. 사용자의 한 영상 Dataset 불러오기
2. 전처리
3. peak 값 검출
4. Amplitude PPI 계산
5. Reference 기반 변화율 계산
6. 해당 변화율의 지표값 기준 거리 계산
7. 최소 거리의 해당 지표값으로 감성 채택

## 결과값
![image](https://user-images.githubusercontent.com/72767245/97099053-8b853d00-16c7-11eb-881e-a7b3c3031d9e.png)
![image](https://user-images.githubusercontent.com/72767245/97099074-c0918f80-16c7-11eb-9c1b-079f724d5ae1.png)
