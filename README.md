# Data-labeling 교육
![image](https://user-images.githubusercontent.com/54635552/177774200-b31e9d44-18f2-4b4d-9bc4-a46f2515332c.png)


## 인공지능 윤리와 법
### AI 편향성
- AI가 올바르게 학습하도록 교육자가 윤리성을 부여시켜야함
### 데이터 편향성
- AI가 편향된 데이터를 학습하지않도록 데이터관리를 잘해야함
### 인공지능의 윤리적 딜레마
- 특정 상황에서 어떤 선택을 할지 윤리적 문제가발생
### AI 윤리적 문제
- 기술 오남용 ex) 딥페이크
- 데이터 편향성 ex) 추천시스템에서 특정 사람에게 편향된 추천알고리즘 제공
- 알고리즘 차별 ex) 특정인종에 대해 다른 결과값 제공
- 프라이버시 침해 ex) 동의하지않은 개인정보 수집

### AI 저작권과 초상권 지적재산권
- 학습 데이터 무단 수집(크롤링) 
사용자 동의 없이 무단 데이터 수집
- CCTV 얼굴 정보 수집
- 인공지능 지식재산권 ex) 인공지능이 만든 예술작품은 누구의것인가?

### 데이터 라벨링의 중요성
- AI 딥러닝 분야를 공부해보고 여러모델을 경험하고 hyper parameter tuning하고 여러가지 experiment를 해본결과 DL model의 성능도 중요하지만 결국 근본적으로 DataSet이 잘못된다면 Train 자체가 제대로 되지않은 문제가 발생, 그러한의미에서 High Quality의 DataSet 구축의 중요성이 높아짐
- 실제 AI HUB 데이터중에서 간판데이터셋을 사용할 당시 일부 Data에서 Annotation이 제대로 되어있지않은 몇개의 데이터가 존재하여 Text Detection Model을 Train할 당시에 오류가 발생한 경험이존재함.

## 텍스트

### 텍스트/음성 입문(수강 완료)
- 전사 : 음성 데이터를 문자로 옮겨적는 작업
- 음성 싱크 작업 : 음성 데이터 구간과 문자의 데이터를 일치 시키는 작업
- 비식별화 작업 : 개인정보가 포함된 데이터를 전사 단계 에서 해당 부분을 특정 기호로 대신 표기하는 방법
- 이중전사 : 비표준어(ex 방언) 이 음성 데이터에 나타날경우 표준어와 함께 표기

#### 데이터 수집과정
- 수집 -> 정제 -> 검사 -> 전사 -> 검사 -> 최종검수 -> AI학습
- 수집되는 음성데이터에도 저작권이 존재하므로, 미리 수집되는 데이터에 대한 동의를 요구하고, 주의사항을 알려준뒤 데이터 수집진행
- 원시데이터(처음 녹음된 음성 데이터) -> 원천데이터(원시데이터를 기반으로 정제한 데이터, 하는이유 : 데이터의 품질을 향상시키기 위해, 잡음삭제 or 비식별화)

#### 전사 방법
- 일반 전사 : 사람이 말한 그대로 문자화해서 전사하는 방법
- 이중 전사 : 한글 맞춤법 표기에 따른 발음이 차이가 있는경우 (발음 전사)/(철자 전사) 병행하여 표기
- 화자 전사 : 음성에서 화자가 여러명일 경우, 화자를 구분하는 작업, 발화 내용정리하지않고, 발화하는 사람이 누구인지 정리함
- 배경음 및 화자 감정 태깅 : 특정 구간에서 감성섞인 음성부분을 감정을 태깅하는 작업
- 방송 영상 자막 사전 제작 : 방송이나 영화 같은 프로그램에서 자막을 만들기위해 하는 작업


### 텍스트 기본(수강완료)

### 텍스트 심화

## 이미지

### 이미지 입문(수강완료)

### 이미지 기본

### 이미지 심화



## 라이다 센서 전문가 

## 품질관리 전문가 

## 품질관리 심화

## 관리자 PM

## 자율주행 융합센서 전문가

## 특화 인공지능 과 보안

## 특화 데이터 기획
