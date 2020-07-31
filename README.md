# PostCorona
# 시작하기 전에

- <b>대회 주제</b>
    - 포스트 코로나 시대 유명 품목 및 산업 발굴
    - 코로나로 인한 국민의 생활, 소비의 변화 파악     
<br><br>
- COVID19가 세계적으로 대유행하면서, 쉽게 변하지 않을 것 같던 우리의 생활 및 소비패턴을 바꿔놓았습니다. 감기에 걸리면 썼던 마스크는 이제 필수 아이템이 되었고, 언택트에 대한 중요성이 강조되며 비대면 관련 산업들이 크게 성장하였습니다. 코로나가 기존의 전염병과 다른 점은, 전염병 예방을 위한 사회의 움직임이 일시적인 현상이 아니라 지속적이며, 코로나가 종식된 후에도 우리의 생활 전반에 대한 패러다임을 바꿀 것이라는 점입니다. 사람들은 적응하게 될 것이며, 기업들은 그러한 패러다임에 적합한 서비스와 제품들을 만들어 낼 것입니다.     
<br><br>

### 과정    
<br><br>
- 데이터셋 자체에 대한 이해를 하고 있는 상황이 아니었기 때문에, 어떠한 주제와 결과를 설정하고 접근하는 하향식 방식이 아닌 탐색적 분석부터 시작하는 상향식 방식으로 접근하였습니다. <b> 때문에 서론에서 분석 목표에 대한 설정은 하지 않았습니다. 여러분들께서 이 게시물을 읽어가시면서, 저희 팀이 <b>어떻게 탐색적 분석을 하였고 어떤 인사이트를 도출하였는지에 대해 순차적으로 확인하실 수 있을 것입니다.</b>


# <center>목차</center>

----
## <center>1. 탐색적 분석</center>

<center> - 탐색적 분석을 통해 인사이트 발굴 및 시각화</center>

## <center> 2. 가설 설정 </center>

<center> - 가설 설정 </center>
<center> - 설정된 가설을 바탕으로 소비패턴 분석 및 시각화 </center>

## <center> 3. 가설 확인 </center>


## <center> 4. 결론 </center>

<center> - 분석 결과 갈무리 </center>
<center> - 포스트 코로나 시대에 대한 전망 </center>

>### 환경 및 사용 Library
>|||
>|------|:---|
>|Environment|python (version : 3.7.7 in anaconda)|
>|Preprocessing Tool|pandas (version 0.23.4)|
>|Preprocessing Tool|numpy (version 1.18.5)|
>|Visualization Tool|plotly (version 4.5.2)|
>|Visualization Tool|plotly-express (version 0.4.1)|
>|Visualization Tool|matplotlib (version 3.2.2)|
>|Visualization Tool|seaborn (version 0.9.0)|
>|Visualization Tool|chart_studio (version 1.1.0)|
>|Visualization Tool|cufflinks (version 0.17.3)|
>|Visualization Tool|wordcloud(1.7.0)|
>|Crawling Tool|beautifulsoup4 (version : 4.6.0)|
>|Crawling Tool|urllib3 (version : 1.25.9)|
>|Crawling Tool|requests (version : 2.24.0)|
>|Natural Language Processing|nltk(version : 3.5)|
>|Natural Language Processing|konlpy(version : 0.5.2)|
>|Natural Language Processing|Jpype1(version : 1.0.1)|
>---
<br>

>### 사용한 데이터 셋
>
>|||
>|------|:---|
>|card.csv|업종 별 결제금액 데이터|
>|fpopl.csv|행정동별 유동인구 데이터|
>|Time.csv|한국 코로나 바이러스에 대한 시계열 데이터|
>|Policy_edit.csv|policy정책 데이터 + 코로나 주요일지 일정|
>|key_com.xlsx| 검색어 평균 클릭수(1~6월) |
>|keyword.xlsx| 연관검색어 데이터(2018년~2020년) |
>|Camp_Keyword.csv| 특정 키워드 뉴스 타이틀 연관 검색어(2020년) |
>|CampLastYear_Keyword.csv|특정 키워드 뉴스 타이틀 연관 검색어>(2019년) |
>|camp_score.csv|특정 키워드 뉴스 타이틀 감성분석 데이터셋 |

---
<br>

>### 데이터 출처
>||||
>|------|:---|:---|
>|key_com.xlsx| Naver 광고 | https://manage.searchad.naver.com/ |
>|keyword.xlsx| Naver DataLab | https://datalab.naver.com/ |
>|Camp_Keyword.csv| 네이버 뉴스(Crawling) | |
>|CampLastYear_Keyword.csv| 네이버 뉴스(Crawling) | | 
>|camp_score.csv| Camp_Keyword.csv를 이용하여 KNU감성어사전 참조 | |
>|KNU 감성어사전| Camp_Keyword.csv를 이용하여 KNU감성어사전 참조 | https://github.com/park1200656/KnuSentiLex |

