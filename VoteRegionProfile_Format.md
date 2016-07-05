# VoteRegionProfile.csv 欄位格式說明

VoteRegionProfile.csv 檔案是由各次選舉 RawData 中 (elbase, elprof) 等兩項資料內容彙整而成，主要呈現各地區縣市、鄉鎮市區、村里、選區、投開票所等地區的選舉概況。主要包括以下 16 項欄位:


## 相關選舉概況資料內容格式

|欄位名稱               |欄位代表                       |說明                                           |
|-----------------------|-------------------------------|-----------------------------------------------|
|CountyCityName         |縣市名                         |縣市以上層級彙總時，該縣市別為空值             |
|TownshipName           |鄉鎮市區                       |鄉鎮市區以上層級彙總時，該鄉鎮市區為空值       |
|VillageName            |村里名                         |村里以上層級彙總時，該村里別為空值             |
|PollStationNo          |投開票所                       |投開票所以上層級彙總時，該投開票所別為0        |
|DistrictName           |選區                           |選區以上層級彙總時，該選區為0                  |
|BallotsAccepted        |有效票                         |                                               |
|BallotsRejected        |無效票                         |                                               |
|BallotsCast            |投票數                         |                                               |
|Voters                 |選舉人數                       |                                               |
|CandidateCounts        |候選人數                       |                                               |
|ElectedCounts          |當選人數                       |                                               |
|CandidateMaleCounts    |候選人數-男                    |                                               |
|CandidateFemaleCounts  |候選人數-女                    |                                               |
|ElectedMaleCounts      |當選人數-男                    |                                               |
|ElectedFemaleCounts    |當選人數-女                    |                                               |
|BallotsRate            |投票數對選舉人數(投票率)       |                                               |


## 相關選舉概況統整資料內容格式

而 ALL_VoteRegionProfile.csv 則為跨年度合併資料，可方便由此整合檔案進行跨年度查詢與比較的呈現。除以上各次選舉的 16 欄位外另外新增兩欄位ElectionyYear(選舉年),ElectionName(選舉定義名稱):

|欄位名稱               |欄位代表                       |說明                                           |
|-----------------------|-------------------------------|-----------------------------------------------|
|CountyCityName         |縣市名                         |縣市以上層級彙總時，該縣市別為空值             |
|TownshipName           |鄉鎮市區                       |鄉鎮市區以上層級彙總時，該鄉鎮市區為空值       |
|VillageName            |村里名                         |村里以上層級彙總時，該村里別為空值             |
|PollStationNo          |投開票所                       |投開票所以上層級彙總時，該投開票所別為0        |
|DistrictName           |選區                           |選區以上層級彙總時，該選區為0                  |
|BallotsAccepted        |有效票                         |                                               |
|BallotsRejected        |無效票                         |                                               |
|BallotsCast            |投票數                         |                                               |
|Voters                 |選舉人數                       |                                               |
|CandidateCounts        |候選人數                       |                                               |
|ElectedCounts          |當選人數                       |                                               |
|CandidateMaleCounts    |候選人數-男                    |                                               |
|CandidateFemaleCounts  |候選人數-女                    |                                               |
|ElectedMaleCounts      |當選人數-男                    |                                               |
|ElectedFemaleCounts    |當選人數-女                    |                                               |
|BallotsRate            |投票數對選舉人數(投票率)       |                                               |
|ElectionyYear          |選舉年                         |                                               |
|ElectionName           |選舉定義名稱                   |                                               |


# 資料整合聲明

高雄大學資訊管理學系
2016.7
