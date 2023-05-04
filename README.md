[![Video Label](이미지)](비디오링크)

## 프로젝트 설명
서울특별시 광진구에서 주최한 데이터분석 공모전으로 거주민들의 주차난, 도로위 불법주정차, 골목 주차 해소를 위한</br>
**광진구의 주차 공간이 필요한 후보지 선정을 위한 분석** 입니다.

## 프로젝트 개요
`문제제기`:  광진구의 골목길 불법 주차로 인한 교통 체증 및 주차 공간 부족 발생으로 주민들, 방문객들 또한 주차 문제부담 발생<br>
`데이터수집`:  Open API, Crawling, Open Flatform을 통한 다양한 데이터 수집<br>
`데이터전처리`:  이상치 제거, 결측치 제거, 상관관계 분석, 히스토그램 분석 등을 통한 EDA의 탐색적 분석으로 변수 선택 및 로그 변환 및 데이터 스케일링 진행<br>
`모델링`:  비선형 차원 축소 알고리즘인 **UMAP** 을 이용한 차원축소 후 밀도 기반 클러스터링 알고리즘인 **Hdbscan** 으로 군집 추출   추출한 군집들을 분석을 통한 점수 추출   
`결과 해석 및 인사이트 도출`:  클러스터링 평가 지표인 세가지 지수를 통한 모델로 결과 해석 및 최종 선정 군집으로 인사이트 도출<br>

## 멤버
`김기훈`-- <br>
`황도희`-- <br>
`이정은`-- <br>

## Tools
<img src="https://geopy.readthedocs.io/en/stable/_images/logo-wide.png" width="80" height="40"/> <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/31/NumPy_logo_2020.svg/1200px-NumPy_logo_2020.svg.png" width="80" height="40"/>
<img src="https://blog.kakaocdn.net/dn/IbIVD/btqxuUnkMTz/H7jGw2dJwWotFD7xaVwIMk/img.png" width="80" height="40"/>
<img src="https://www.hanbit.co.kr/data/editor/20210202173444_cacgwlbd.jpg" width="80" height="40"/>
<img src="https://velog.velcdn.com/images/jane15/post/1e40516e-521f-4bf7-a9c5-29ab21648dc8/image.png" width="80" height="40"/>
<img src="https://www.fullstackpython.com/img/logos/scipy.png" width="80" height="40"/>
<img src="https://blog.kakaocdn.net/dn/kDIxI/btqOdMUNeYm/cR1sLFgOLBzTI9kK0IZRb1/img.png" width="80" height="40"/>  
<img src="https://images.velog.io/images/hyungjin1124/post/4eea0774-27d4-4cd6-8da6-a80d34f05102/BeautifulSoup.png" width="80" height="40"/>
<img src="https://blog.kakaocdn.net/dn/dd2wjZ/btrE1t2QStJ/75rMsFSkoI2udiTFm7qEOk/img.png" width="80" height="40"/>
<img src="https://developers.google.com/static/maps/images/google-maps-platform-1200x675.png?hl=ko" width="80" height="40"/>
<img src="https://umap-learn.readthedocs.io/en/latest/_images/logo_large.png" width="80" height="40"/>
<img src="https://pythonfix.com/pkg/h/hdbscan/hdbscan-banner.webp" width="80" height="40"/>
<img src="https://blog.kakaocdn.net/dn/bTkfpq/btq7FiGInAo/jMtmvrEsdsKBzf87z0mdK1/img.png" width="80" height="40"/>

## Branch

main-d: `황도희`의 branch  
main-g: `김기훈`의 branch  
main-j: `이정은`의 branch

## 파일 설명
`Clustering.ipynb`-- 전처리가 완료된 데이터를 불러와 과정에 맞춰 클러스터링을 진행했던 파일입니다. 
`Preprocessing.ipynb`-- 우리가 목표하고자 했던 모델에 맞춰 전처리를 진행했던 파일입니다.
`label.ipynb`-- 추출한 군집을 바탕으로 분석 및 인사이트를 도출을 진행했던 파일입니다.
`parking-demand.ipynb`-- 주차수요지수 데이터를 추출했던 파일입니다.
