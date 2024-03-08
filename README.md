### 가스공급량 수요예측 모델개발

- 한국가스공사의 시간단위 공급량 내부 데이터를 활용하여 일간 공급량을 예측하는 인공지능 모델 개발
- 데이터
    - 공공데이터 - 한국가스공사_시간별 공급량_20181231.csv
    
    [한국가스공사_시간별 공급량_20181231](https://www.data.go.kr/data/15091497/fileData.do)
    
    - 2013년부터 2018년까지의 시간별 공급량
    - 연/월/일/시간 단위로 구분
    - 구분: 영업비밀(A,B,C.. 로 나타냄)
        - 용도별 구분 혹은 지역별 공급사(지역) 이라고 가정
        - 용도별 구분
            - 민수용 : 주택용, 업무난방용, 일반용, 냉난방공조용, 열병합용, 연료전지용, 열전용설비용
            - 산업용 : 산업용, 수송용
        - 지역별 공급사
            - 구분→지역단위(서울, 경기, 강원, 전라, 등 )
