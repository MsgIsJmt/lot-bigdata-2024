# Iot-bigdata-2024
2024년 IoT 개발자과정 빅데이터 분석 및 인공지능 학습 리포지토리

## 1일차 (2024-08-01)

### 빅데이터 분석 및 AI
- 빅데이터를 사용하여 사회 전반적인 문제, 현상, 원인, 해결점 등을 찾아가는 방법
- 사회 전반에 모든 곳에서 활용
- Ex. 쿠팡에서 20대 중반 여자들이 선호하는(트렌드) 화장품
    1. 쿠팡에서 20대 중반 여자 : 회원정보를 검색
    2. 회원들이 검색한 내용 중 화장품을 조회
    3. 그 중에서 가장 많이 검색된 화장품 통계
    4. 20대 중반 여자 회원이 로그인
    5. 첫 화면에 검색된 화장품 1위 ~ 3위를 디스플레이한다.

- 빅데이터?
    - Big Data : 디지털 환경에서 발생하는 대규모 정형 혹은 비정형 데이터
    - 3V : Volume (크기, 규모), Variety(다양성), Velocity(속도)
    - 5V - 3V : Veracity(진실성), Value(가치)
    - 7V - 5V : Validity(정확성), Volatility(휘발성 : 데이텉가 얼마나 오래 저장, 사용되는가)

- 데이터인가?
    - 정보를 수집자료 자체, 값, 총계 + Value -> 정보(Information)

- 빅데이터 분석 순서 : 생성 -> 수집 -> 저장 -> 분석 -> 표현
    1. 생성 - IoT 센싱값, (쇼핑몰, 포털) 빅데이터 플랫폼을 통해서 생성
    2. 수집 - MQTT로 DB에 전달, 빅데이터 플랫폼(하둡, 카프카... )에서 수집. 크롤링, 네트워크까지 포함
    3. 저장 - 수집과 거의 동일, DB에 저장 (카프카, 데이터 마이닝, NoSQL... )
    4. 분석 - 통계적 분석, 탐색적 분석(EDA), 머신러닝, 딥러닝, 자연어처리, 패턴인식, 이미지 프로세싱 분석툴(Spark, Tableau, MS PowerBI) 사용
    5. 표현 - 인사이트 도출 (시각화, 그리드)

- 데이터 분석 기초
    - 파이썬 - 파이썬 외에도 R, 자바, C# 등 다른 언어로도 분석 가능, 단 파이썬이 가장 쉽기때문에 많이 사용
    - 데이터 분석에 들어가는 라이브러리(모듈) 부터 학습
        1. 데이터 처리 - Numpy(수치해석, 계산), Pandas(데이터 처리), Scipy(과학 계산) ...
        2. 시각화 - Folium(지도), Matplotlib(차트), Seaborn(Matplotlib 고급화) ...
        3. 엑셀 - openpysl(엑셀 처리)
        4. 크롤링 - Selenium(웹크롤링 자동화), BeautifulSoup(웹페이지 정제)
        5. 머신러닝/딥러닝 - Scikit-Learn(가장 간단한 머신러닝), MS CNTK, Theano, Keras(최초의 딥러닝), TensorFlow(제일 유명, Keras포함), PyTorch(페이스북)

- 빅데이터 학습
    - 실습자료, 파이썬 기본(패스), 빅데이터 분석 기초학습
    - [넘파이](https://github.com/MsgIsJmt/lot-bigdata-2024/blob/main/day01/bda01_numpy_basic.ipynb)
    - [판다스](https://github.com/MsgIsJmt/lot-bigdata-2024/blob/main/day01/bda02_pandas_basic.ipynb)
    - [맷플롭립](https://github.com/MsgIsJmt/lot-bigdata-2024/blob/main/day01/bda03_matplotlib_basic.ipynb)

## 2일차
- 빅데이터 학습
    - 기초학습, 크롤링 관련
    - [뷰티플수프]()
    - [셀레니움] ()

## 3일차

## 4일차

## 5일차

## 6일차

## 7일차

## 8일차

## 9일차