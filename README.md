# GOGANG

<img width="283" alt="LOGO" src="https://github.com/HUFS-Capstone-23-01/TravelFeelDog-Server/assets/37647483/69cfadd7-c83f-4ee8-8de0-eaaaa6e57df8">

고양이 그리고 강(갱)아지와 하는 가위바위보 게임



## 기능 목록

배팅을 한다. 
사용자가 가위 바위 보 중 입력을 한다.
 [가위 , 바위, 보] 

고양이의 얼굴을 사진을 찍어서 올리고 인식한다 . 

기분의 따라 달라지는 것을 가위,바위,보 로 표현한다.

결과를 출력한다. : 배팅금 차감 또는 2 배 지급


## 개발 단계
-> CNN 원핫 인코딩 , 고양이 강아지 얼굴을 인식
-> 동물 얼굴의 랜드마크 데이터를 넣어 수집+ 데이터 라밸링 작업

공격적 적대 : 주먹
관심 , 흥미 : 가위
무시 , 편안한 상태 : 보

-> 공격적이고 적대는 거의 없으니 가끔씩 편안한 상태에서 가위를 제공하는 로직 추가


# 개발시 pyhon , flask 를 이용하여 빠르게 개발
이후 goLand 이용 
