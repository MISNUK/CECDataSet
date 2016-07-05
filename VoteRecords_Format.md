# VoteRecords.csv 欄位格式說明

VoteRecords 檔是由各次選舉 RawData 中(elbase, elcand, elpaty, elctks)等四項資料內容依各地區縣市、鄉鎮市區、村里、選區、投開票所等地區資料與候選人、推薦政黨與各得票數彙整，以提供較為方便的查詢資料格式。
可於各次選舉目錄下 VoteRecords.csv 找到當次選舉的


## 相關選舉票數資料內容格式 

|欄位名稱               |欄位代表        |說明                                          |
|-----------------------|----------------|----------------------------------------------|
|CountyCityName         |縣市名          |縣市以上層級彙總時，該縣市別為空值            |
|TownshipName           |鄉鎮市區        |鄉鎮市區以上層級彙總時，該鄉鎮市區為空值      |
|VillageName            |村里名          |村里以上層級彙總時，該村里別為空值            |
|PollStationNo          |投開票所        |投開票所以上層級彙總時，該投開票所別為0       |
|DistrictName           |選區            |選區以上層級彙總時，該選區為0                 |
|DrawNo                 |候選人號次      |                                              |
|VoteCounts             |得票數          |                                              |
|VoteRate               |得票率          |                                              |
|CandIdateName          |候選人姓名      |                                              |
|EndorsementPartyName   |推薦政黨名稱    |                                              |
|Gender                 |性別            |1:男，2:女                                    |
|IsIncumbent            |是否現任        |Y:現任，N:非現任                              |
|Elected                |當選註記        |T:當選，空值:未當選，TF:婦女保障              |


## 相關選舉票數統整資料內容格式

而 ALL_VoteRecords.csv 則為跨年度合併資料，可方便由此整合檔案進行跨年度查詢與比較的呈現。除了上述各次選舉的 13 欄位外另外新增兩欄位，ElectionyYear(選舉年),ElectionName(選舉定義名稱)

|欄位名稱               |欄位代表        |說明                                          |
|-----------------------|----------------|----------------------------------------------|
|CountyCityName         |縣市名          |縣市以上層級彙總時，該縣市別為空值            |
|TownshipName           |鄉鎮市區        |鄉鎮市區以上層級彙總時，該鄉鎮市區為空值      |
|VillageName            |村里名          |村里以上層級彙總時，該村里別為空值            |
|PollStationNo          |投開票所        |投開票所以上層級彙總時，該投開票所別為0       |
|DistrictName           |選區            |選區以上層級彙總時，該選區為0                 |
|DrawNo                 |候選人號次      |                                              |
|VoteCounts             |得票數          |                                              |
|VoteRate               |得票率          |                                              |
|CandIdateName          |候選人姓名      |                                              |
|EndorsementPartyName   |推薦政黨名稱    |                                              |
|Gender                 |性別            |1:男，2:女                                    |
|IsIncumbent            |是否現任        |Y:現任，N:非現任                              |
|Elected                |當選註記        |T:當選，空值:未當選，TF:婦女保障              |
|ElectionyYear          |選舉年          |                                              |
|ElectionName           |選舉定義名稱    |                                              |


# 資料整合聲明

高雄大學資訊管理學系
2016.7
