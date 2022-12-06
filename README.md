# q-gis-dataset

## ✔️ 링크 데이터
ITS 국가교통정보센터 https://www.its.go.kr/nodelink/nodelinkRef </br>
국가교통 DB https://www.ktdb.go.kr/www/addPbldataReqstData.do?key=202&clTy=1 </br>
VWORLD 오픈 API https://www.vworld.kr/dev/v4dv_2ddataguide2_s001.do </br>
국가공간정보포털 오픈마켓 http://data.nsdi.go.kr/dataset?q=%EB%8F%84%EB%A1%9C </br>
국가공간정보포털 오픈마켓 http://data.nsdi.go.kr/dataset/20180927ds0062 </br>

## ✔️ 교통량 데이터
ITS 국가교통정보센터 https://www.its.go.kr/opendata/opendataList?service=traffic </br>
도로교통공사(고속도로만) http://data.ex.co.kr/ </br>
서울시 교통정보 https://topis.seoul.go.kr/refRoom/openRefRoom_1.do </br>
경기도교통정보센터 https://gits.gg.go.kr/gtdb/web/trafficDb/trafficSpeed/alwaysSpeed.do </>

## ✔️ 사용 데이터셋
![image](https://user-images.githubusercontent.com/99319638/204686789-d39d1234-8cdd-4dcf-9404-7d798bb552f1.png) </br>


`전국표준노드링크 2022-11-15` </br>
https://www.its.go.kr/nodelink/nodelinkRef </br>

`행정구역시군구_경계_경기` </br>
http://data.nsdi.go.kr/dataset/15144

`행정구역읍면동_경계_경기` </br>
http://data.nsdi.go.kr/dataset/15145

`행정동경계_전국` </br>
http://data.nsdi.go.kr/dataset/20171206ds00001 </br>
(인구수가 행정동별로 되어 있고 위의 shp 파일은 법정동별로 구분되어 있음..😥) </br>
(구별로 하기에는 범위가 너무 커지는 것 같아서 행정동 shp 파일을 찾아냄!)
 
`교통소통정보_2022-11-28` </br>
https://www.its.go.kr/opendata/opendataList?service=traffic

`경기도 광주시 읍면동별 세대 및 인구 2020` </br>
https://kosis.kr/statHtml/statHtml.do?tblId=DT_63701_B000017&orgId=637&language=kor&conn_path=&vw_cd=&list_id=

`경기도 광주시 주민등록 인구 현황 2022-07` </br>
https://www.gjcity.go.kr/portal/bbs/view.do?bIdx=308572&ptIdx=44&mId=0304040200

`경기도 광주시` </br>
https://www.gjcity.go.kr/portal/contents.do?mId=0102010300

~`경기도 광주시 읍면동 코드 목록 (경기도 광주시 : **416**)`~ </br>
~https://www.data.go.kr/data/15101142/fileData.do?recommendDataYn=Y~

~`전국 법정동 코드 목록`~ </br>
~https://www.code.go.kr/stdcode/regCodeL.do~

`서울시 읍면동별 인구` </br>
https://data.seoul.go.kr/dataList/10584/S/2/datasetView.do

`경기도 읍면동별 인구` </br>
https://kosis.kr/statHtml/statHtml.do?orgId=210&tblId=DT_210J0008&conn_path=I2 </br>
오른쪽 조회설정에서 조회 수정할 수 있음! 😊

|시군구명|코드|
|:---:|:---:|
|성남시 수정구|204|
|성남시 중원구|205|
|성남시 분당구|206|
|구리시|221|
|남양주시|222|
|하남시|227|
|이천시|230|
|광주시|234|
|여주시|237|
|양평군|240|
|용인시 처인구|243|
|용인시 기흥구|244|
|용인시 수지구|245|

하남시 빼먹어서 다시.. 

## ✔️ 문제점
네트워크 분석이 안먹음..
```
링크와 노드가 만나지 않아서 그런가
다른 데이터를 이용해보자
```

`(도로명주소)도로구간` </br>
http://data.nsdi.go.kr/dataset/12902 
http://www.gisdeveloper.co.kr/?p=2310  
`국가교통DB_교통망GIS DB_지역좌표계_도로망` </br>
`국가교통DB_네트워크_도로_수도권` </br>
https://www.ktdb.go.kr/www/addPbldataReqstData.do?key=202&clTy=1

![image](https://user-images.githubusercontent.com/99319638/204744438-f44db586-6326-407e-985c-8f5dd8bdd748.png) </br>

.... </br>
경로가 없으면 패스를 하던가.. </br>
멍첯ㅇ한 컴퓨터 녀석.. </br>

## ✔️ 부가설명
최단 경로를 탐색하는 경우 (망 레이어 단위의) 거리로 추정한 값, `최속 경로`의 경우 (시 단위의) `시간으로 추청한 값`

## ✔️ 해결
..
