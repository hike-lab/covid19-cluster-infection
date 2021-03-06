# covid19-cluster-infection
코로나19 집단감염 데이터 

**📌 2022-03-16 공지**
* 정례브리핑 보도자료의 집단감염 보도 형식이 변경된 이후의 **ver2-1** 집단감염 데이터는 'csv_ver2-1'폴더로 이동하여 업로드하였습니다.
* ver2 중 기존 데이터 날짜 오류(ex. 0201-11 => 2021-11, 0202-10 => 2020-10) 수정하여 업로드하였습니다.

---

**📌 2022-03-06 공지**
* caseID 4809: keyword 수정. ('일반 음식점' > '일반음식점')
* caseID 319: keyword 수정. ('마트/시장;쇼핑몰' > '마트/시장;쇼핑센터')
* caseID 1084: keyword 수정. ('보유시설' > '보육시설')
* caseID 1214: keyword 수정. ('기타직장;기타직장동료' > '기타직장')
* caseID 1320: keuword 수정. ('초중고;스포츠;대회;탁구' > '초중고;스포츠;대회;탁구장')
* caseID 246: keyword 수정. ('직장/주거시설' > '직장;주거시설')
* caseID 2053 keyword 수정. ('어린이집/유치원;아동어린이집/유치원;아동' > '어린이집/유치원')
* caseID 141: keyword 수정. ('오피스텔;방문판매업' > '오피스텔;방문;판매업')
* caseID 4724: keyword 수정. ('기타;마을' > '마을')
* caseID 4752: keyword 수정. ('마을;주민;모임' > '마을')
* caseID 3425: keyword 수정. ('병원;의료기곤' > '병원;의료기관')
* caseID 2326: keyword 수정. ('도장업' > '도장업/도금업')
* caseID 140: keyword 수정. ('부동산;모임' > '부동산업;모임')
* caseID 1194: keyword 수정. ('부동산;상담' > '부동산업;상담')
* caseID 1514: keyword 수정. ('유통업;공구' > '유통업')
* caseID 1691: keyword 수정. ('스포츠;운동시설스포츠' > '스포츠;운동시설')
* caseID 73: keyword 수정. ('경찰;경찰서' > '경찰')
* caseID 813: keyword 수정. ('기타직장;협력' > '기타직장')
* caseID 3559: keyword 수정. ('아동;복지센터;돌봄교육시설' > '아동;복지센터;돌봄;교육시설')
* caseID 1381: keyword 수정. ('기타직장;사업장' > '기타직장')
* caseID 1407: keyword 수정. ('기타직장;사업장' > '기타직장')
* caseID 246: keyword 수정. ('직장;주거시설' > '기타직장;주거시설')
* caseID 273: keyword 수정. ('직장;상담' > '기타직장;상담')
* caseID 276: keyword 수정. ('마트/시장;음식점' > '마트/시장;일반음식점')
* caseID 2244: keyword 수정. ('병원;의료센터' > '병원;의료기관')
* caseID 2096: keyword 수정. ('교회;종교시설' > '교회;종교')
* caseID 4468: keyword 수정. ('주거기설;숙박업' > '주거시설;숙박업')
* caseID 1084: keyword 수정. ('보육센터' > '아동;복지센터;돌봄')

> 위 수정내용을 반영하여 'ver2_코로나19_집단감염현황_20220306' 파일로 업로드하였습니다.
---

**📌 2022-03-04 공지**
* caseID 29: accumulated와 date가 누락되어 있어 확인 후 수정하였습니다.
* caseId 2514, 2515: 동일한 케이스인 것을 확인하여 같은 caseID인 2514로 통일하고, accumulated가 누락되어 있는 '운동시설'의 값을 수정하였습니다.
* caseID 4469: classname이 누락되어 있고 keyword에 오류가 있는 것을 확인하여 수정하였습니다.
* caseID 4864, 4863: regionID가 누락되어 있는 것을 확인하여 수정하였습니다.

> 위 수정내용을 반영하여 'ver2_코로나19_집단감염현황_20220304' 파일로 업로드하였습니다.

---

**📌 2022-03-03 공지**
1. 정례브리핑 보도자료의 집단감염 보도 형식이 다음과 같이 수정되었습니다.
    * ~2022-01-31 (예상): 지역별 집단감염 케이스를 일별로 신규, 누적 확진자 수를 줄 글로 기록. 
    * 2022-02-01 ~ 2022-02-19 (예상): 지역별 집단감염 중 <u>'요양병원, 요양시설'</u>과 관련한 케이스만 <u>일별</u>로 신규, 누적 확진자 수를 줄 글로 기록. 
    * 2022-02-20 ~: 지역별 집단감염 중 '요양병원, 요양시설'과 관련한 케이스만 <u>__주별__</u>로 <u>__누적 확진자 수__</u>를 표로 기록.
2. 따라서 2022-03-03 업데이트 부터는 주별로 집단감염 케이스를 기록한 새로운 파일을 업데이트 합니다. 
    * 형식1: 2022-02-22 최종 업데이트 본 (2020-02 ~ 2022-02-19 까지 일별 수집한 데이터)
    * 형식2: 2022-03-03 이후 업데이트 본 (2022-02-20 ~ 주별 수집한 데이터)
3. 컬럼명, 의미가 조금씩 바뀌었습니다. 자세한 내용은 '코로나19-집단감염현황 ver2-1 데이터 설명서' 파일을 확인해주세요.
    * 'date' > 'week' 
    * 'confirmed'의미: 각 집단감염사건의 당일 확진자 수 > 각 집단감염 사건의 주별 신규 확진자 수 (보도자료에는 해당 내용을 보도하지 않으므로 (이번주 누적)-(지난주 누적)을 통해서 계산함.
    * note의 종류가 바뀜.

---

**📌 2022-02-22 공지**
* 정례브리핑 보도자료에 2/19일까지만 집단감염 정보가 기록되어 있어서 2/19일까지만 기록했습니다.
* [2020-02-20 보도자료](https://www.kdca.go.kr/board/board.es?mid=a20501010000&bid=0015&list_no=718745&cg_code=&act=view&nPage=2#)공지 내용: `현재 집단발생 현황은 위중증, 고위험군 중심으로 관리하고 있어 요양시설 집단사례만 취합관리되고 있으므로 향후 주 단위로 정리하여 제공 예정임`

---

**📌 2022-02-21 수정사항 공지**    
* caseID 4041: 대전 중구 date가 12/25인 '초등학교' 케이스의 데이터값 누락 확인 결과 기록 오류인 것으로 확인되며, 12/31 보도자료에 대전 중구 date가 12/28인 '초등학교/어린이집' 케이스가 누락된 것을 확인하여 이전 데이터를 수정하였습니다.    
* caseID 4228: 전남 남원 date가 12/26인 '초등학교/고등학교' 케이스의 데이터값 누락 확인 후 수정하였습니다. 

---

**📌 2022-02-02 수정사항 공지**

* ver2 작업 완료하여 2020-02-18 ~ 2022-02-02 집단감염 데이터를 업데이트 하였습니다. 
* '코로나19-집단감염현황 ver2 데이터 설명서' 파일을 반드시 확인해주세요. 
* 앞으로 매주 수요일마다 ver2가 업데이트 됩니다. 

---

**📌 2022-01-26 수정사항 공지**

* ver2 작업 진행 속도가 더뎌 오늘 예정되었던 ver2 업로드는 불가피하게 연기하게 되었습니다. 죄송합니다.
* 다음주 수요일(2/2)안으로 업데이트 예정입니다. 대신하여 예전처럼 ver1 업데이트를 진행하였습니다.

---

**📌 2021-12-15 수정사항 공지**

1. 2021-12-08 업데이트 본 기준으로 caseID 1278 (하남시 음식점)과 caseID 1748 (하남시 음식점)이 같은 케이스로 확인되어 2021-12-15 업데이트 본 이후 둘을 동일한 케이스 (caseID: 1278)로 구분한다. (1749 부터 -1 해주어 caseID 수정함. 빈 caseID 없음)
2. 2021-12-08 업데이트 본 기준으로 caseID 3665 (함안군 경로당)과 caseID 3753 (함암군 경로당)이 같은 케이스로 확인되어 2021-12-15 업데이트 본 이후 둘을 동일한 케이스 (caseID: 3664. 위에서 -1해주었으므로 3665가 3664가 됨)로 구분한다. (3753 부터 -1 해주어 caseID 수정함. 빈 caseID 없음)
3. 2021-12-08 업데이트 본 기준으로 '경로당'의 classname이 일부는 '가족 및 지인 모임'으로, 일부는 '기타'로 다른 것을 확인하여 2021-12-15 업데이트 본 이후 모든 '경로당'의 classname을 '가족 및 지인 모임'으로 통일한다.
