# 🏆L.POINT 제 6회 Big Data Competition - *Audience Targeting*
* 본 저장소는 [(주)롯데멤버스](https://www.lpoint.com/)에서 주최한 [제 6회 빅데이터 컴피티션](https://competition.lpoint.com/index.tran)에서 최우수상을 수상한 프로젝트를 기록하기 위한 공간입니다.
* 코드에 대한 저작권은 고지형, 이형선, 채운슬에게 있습니다.
* 원본 데이터의 소유권은 [(주)롯데멤버스](https://www.lpoint.com/)에 있으니, 코드 재현을 위해서는 주최 측에 문의하셔야 합니다.  
* This project won the 2nd place in [the 6th Bigdata Competition](https://competition.lpoint.com/index.tran) of the company [Lotte Members](https://www.lpoint.com/app/global/LHGA100100.do?globalFlag=ENG). 
* The team 'CHAE-KO-SUN'(Jihyeong Ko, Hyeongson Lee, Unseul Chae) has the license of these codes.
* If you want to use these datasets, you have to contact the company [Lotte Members](https://www.lpoint.com/app/global/LHGA100100.do?globalFlag=ENG) which owns the license.

## 🏃‍♂️프로젝트 기간
* 2019.11~2020.01

## 😎프로젝트 결과
- `결과보고서_채고선.pdf`: [최종 발표 자료](https://github.com/iloveslowfood/6thLPOINTBigdataCompetition/blob/master/%EA%B2%B0%EA%B3%BC%EB%B3%B4%EA%B3%A0%EC%84%9C_%EC%B1%84%EA%B3%A0%EC%84%A0.pdf)입니다.  
![](https://github.com/iloveslowfood/6thLPOINTBigdataCompetition/blob/master/image/01.%20%EB%B9%84%ED%9A%8C%EC%9B%90%20%EC%8B%9D%EB%B3%84%20%EB%AA%A8%EB%8D%B8.png?raw=true)
![](https://github.com/iloveslowfood/6thLPOINTBigdataCompetition/blob/master/image/03.%20%EC%83%81%ED%92%88%20%EC%B6%94%EC%B2%9C%20%EB%AA%A8%EB%8D%B8.png?raw=true)
![](https://github.com/iloveslowfood/6thLPOINTBigdataCompetition/blob/master/image/05.%20%EB%B9%84%EC%A6%88%EB%8B%88%EC%8A%A4%20%ED%99%9C%EC%9A%A9%20%EB%B0%A9%EC%95%88.png?raw=true)

## 👩‍👧‍👧프로젝트 참여 인원
고지형(본인), 이형선, 채운슬

## 👀 디렉토리 구조
- `DATA`: 원본 데이터, 정제된 데이터가 저장되는 폴더입니다.
- `image`: EDA 이미지가 저장되는 폴더입니다.
- `tracker`: 첫 번째 모델(Tracker) 설계 과정에서 반환된 데이터가 저장되는 폴더입니다.
- `navigator`: 두 번째 모델(Navigator) 설계 과정에서 반환된 데이터가 저장되는 폴더입니다.

## 🎁분석 및 모델링 과정
- `01_이형선_데이터_전처리.ipynb`: 데이터를 불러오고, 결측치와 이상치를 처리합니다.
- `02_이형선_고객행동패턴_분석.ipynb`: 시각화를 통해 유의미한 변수를 발견하고 모델의 방향성을 수립합니다.
- `03_이형선_트래커_모델링.ipynb`: 고객행동패턴을 변수로 하여 고객의 성별과 연령대를 추정하는 모델을 설계합니다.
- `04_고지형_연관성_분석.ipynb`: 상품 판매 경향으로부터 상품 간 연관성을 파악합니다.
- `05_고지형_네비게이터_모델_비회원고객_학습데이터_구성.ipynb`: 맞춤 상품 추천에 활용할 비회원 고객 학습데이터를 구성합니다.
- `06_고지형_네비게이터_모델_상품추천.ipynb`: 구축한 모델을 통해 고객에게 맞춤 상품을 추천합니다.

