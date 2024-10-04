# awesome-taiwan-biodiversity-web-api
Public Listing (awesome) Taiwan Biodiversity Web API resources


## Content Curator

## TaiCOL (Catalogue of Life in Taiwan)
https://taicol.tw/zh-hant/api

- 學名 API - name: https://api.taicol.tw/v2/name
- 物種 API - taxon: https://api.taicol.tw/v2/taxon
- 較高階層 API - higherTaxa: https://api.taicol.tw/v2/higherTaxa
- 文獻 API - references: https://api.taicol.tw/v2/references
- 學名比對 API - nameMatch: https://api.taicol.tw/v2/nameMatch
- 物種有效名版本紀錄 API - taxonVersion: https://api.taicol.tw/v2/taxonVersion


## TaiEOL (Taiwan Encyclopedia of Life)
https://data.taieol.tw/

- 物種多媒體 API: 
    - https://data.taieol.tw/api/v2/taieol_object/tid/99628?token=hello_world (TaiEOL(ASCDC)內部使用學名骨幹ID，可與物種頁面(taxon page)直接對應)
    - https://data.taieol.tw/api/v2/taieol_object/taxon_id/t0085379?token=hello_world (TaiCOL(V2) 的學名骨幹ID)
    - https://data.taieol.tw/api/v2/taieol_object/name_code/341781?token=hello_world (舊版taxon_id:TaiCOL的學名代碼(之後將棄用))

## Content Aggregrator


### TaiBIF (Taiwan Biodiversity Information Facility):
https://portal.taibif.tw/zh-hant/taibif-api

- 出現紀錄 Occurrence API: https://portal.taibif.tw/api/v2/occurrence/detail_occ?occurrenceID={occurrecceID}
- 資料集 Datset API: https://portal.taibif.tw/api/v2/dataset/
- 發布單位 Publisher API: https://portal.taibif.tw/api/v2/publisher/

## TBIA (Taiwan Biodiversity Information Alliance)
https://tbiadata.tw/zh-hant/api/doc

- 出現紀錄 API: https://tbiadata.tw/api/v1/occurrence


## TBN (Taiwan Biodiversity Network)
https://www.tbn.org.tw/data/api

- Map API
  - WFS: https://map.tbn.org.tw/geoserver/wfs
  - WMS: https://map.tbn.org.tw/geoserver/wms
- Open API https://www.tbn.org.tw/api/{version}/{type}?{parameters}
  - https://www.tbn.org.tw/api/v25/occurrence?
  - https://www.tbn.org.tw/api/v25/taxon?
  - https://www.tbn.org.tw/api/v25/dataset?
