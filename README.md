# jmacsv
気象庁防災情報XMLフォーマットの個別コード表をCSVに変換したもの。

気象庁の配布物は以下のURLよりダウンロードできます。

http://xml.kishou.go.jp/tec_material.html

## ファイルの説明

気象庁で配布している jmaxml_20261118_Code.zip から生成しました。

* AreaCoastForecast-AreaCoastForecast.csv

20260226_AreaCoastForecast.xlsx の「AreaCoastForecast」シート

列:

1. 高潮予報区間の Name
2. 高潮予報区間の Code
3. 高潮予報区間のふりがな
4. 高潮予報海岸名の Name
5. 府県予報区等の Name
6. 水位基準地点の Name
7. 水位基準地点のふりがな
8. 水位基準地点の所在地
9. 水位基準地点の緯度（度）
10. 水位基準地点の緯度（分）
11. 水位基準地点の経度（度）
12. 水位基準地点の経度（分）

* AreaFloodForecast-AreaFloodForecast.csv

20260806_AreaFloodForecast.xlsx の「AreaFloodForecast」シート

列:

1. @code
2. @name
3. ふりがな

* AreaForecast-Sheet1.csv

20241031_AreaForecast.xlsx の「Sheet1」シート

列:

1. コードタイプ
2. XML名称
3. 備考
4. 新コード値

* AreaInformationCityAreaForecastLocalM-AreaForecastLocalM(コード表).csv

20261118_AreaInformationCity-AreaForecastLocalM.xlsx の「AreaForecastLocalM（コード表）」シート

列:

1. @code
2. @name
3. ふりがな
4. 【気象警報・注意報】【気象特別警報報知】【気象危険度通知】「市町村等をまとめた地域等」対象（1/0）
5. 【気象警報・注意報】【気象特別警報報知】【気象危険度通知】「一次細分区域等」対象（1/0）
6. 【気象警報・注意報】【気象特別警報報知】【気象危険度通知】「府県予報区等」対象（1/0）
7. 【府県天気予報】【警報級の可能性（明日まで）】「区域予報」対象（1/0）
8. 【府県天気予報】【警報級の可能性（明日まで）】「独自予報」対象（1/0）
9. 【府県天気概況】（1/0）
10. 【府県週間天気予報】【警報級の可能性（明後日以降）】「区域予報」対象（1/0）
11. 【土砂災害警戒情報】（1/0）
12. 【竜巻注意情報】「市町村等をまとめた地域等」対象（1/0）
13. 【竜巻注意情報】「一次細分区域等」対象（1/0）
14. 【竜巻注意情報】「対象細分」対象（1/0）
15. 【記録的短時間大雨情報】「対象細分」対象（1/0）
16. 【指定河川洪水予報】「府県予報区等」対象（1/0）
17. 【水位周知河川に関する情報】「府県予報区等」対象（1/0）
18. 【台風の暴風域に入る確率】「市町村等をまとめた地域等」対象（1/0）
19. 【台風の暴風域に入る確率】「府県予報区等」対象（1/0）
20. 【府県気象防災速報】【府県気象防災速報（潮位）】「一次細分区域等」対象（1/0）
21. 【地方気象解説情報】【地方気象解説情報（潮位）】【府県気象解説情報】【府県気象解説情報（潮位）】（1/0）

* AreaInformationCityAreaForecastLocalM-AreaForecastLocalM(関係表竜巻注意情報).csv

20261118_AreaInformationCity-AreaForecastLocalM.xlsx の「AreaForecastLocalM（関係表　竜巻注意情報」シート

列:

1. 市町村等をまとめた地域等のコード
2. 市町村等をまとめた地域等の名称
3. 一次細分区域等のコード
4. 一次細分区域等の名称
5. 発表細分のコード
6. 発表細分の名称

* AreaInformationCityAreaForecastLocalM-AreaForecastLocalM(関係表警報注意報).csv

20261118_AreaInformationCity-AreaForecastLocalM.xlsx の「AreaForecastLocalM（関係表　警報・注意報」シート

列:

1. 市町村等をまとめた地域等のコード
2. 市町村等をまとめた地域等の名称
3. 一次細分区域等のコード
4. 一次細分区域等の名称
5. 府県予報区等のコード
6. 府県予報区等の名称

* AreaInformationCityAreaForecastLocalM-AreaInformationCity.csv

20261118_AreaInformationCity-AreaForecastLocalM.xlsx の「AreaInformationCity」シート

列:

1. @code
2. コードが示す地域等
3. 気象関係の @name
4. 気象関係のふりがな
5. 属する「市町村等をまとめた地域等」（AreaForecastLocalM の @code）
6. "気象警報・注意報"及び"気象特別警報報知"で使用（1/0）
7. "竜巻注意情報"で使用（1/0）
8. 高潮特別警報・警報・注意報発表対象（1/0）
9. 波浪特別警報・警報・注意報発表対象（1/0）
10. "土砂災害警戒情報"で使用（1/0）
11. "指定河川洪水予報"で使用（1/0）
12. "水位周知河川に関する情報"で使用（1/0）
13. "気象解説情報"で使用（1/0）
14. 地震津波関係の @name
15. 地震津波関係のふりがな
16. 火山関係の @name
17. 火山関係のふりがな
18. "噴火警報・予報"、"降灰予報"、"噴火速報"で使用（1/0）
19. "火山灰警報・注意報"、"火山灰予報"で使用（1/0）
20. 紫外線観測データの @name
21. 紫外線観測データのふりがな
22. 大雨危険度通知の @name
23. 大雨危険度通知のふりがな

* AreaMarineAJ-AreaMarineA.csv

20260129_AreaMarineAJ.xlsx の「AreaMarineA」シート

列:

1. @code
2. @name
3. ふりがな

* AreaMarineAJ-AreaMarineJ.csv

20260129_AreaMarineAJ.xlsx の「AreaMarineJ」シート

列:

1. @code
2. @name
3. ふりがな
4. 地方海上警報、地方海上予報でとりうる値として出現するか（1/0）
5. 火山現象に関する海上警報・海上予報でとりうる値として出現するか（1/0）

* AreaRiver-AreaRiver.csv

20260806_AreaRiver.xlsx の「AreaRiver」シート

列:

1. 河川（指定河川洪水予報）の @code
2. 河川（水位周知河川に関する情報）の @code
3. @name
4. ふりがな
5. @name（2 つ目）
6. ふりがな（2 つ目）
7. @name（3 つ目）
8. ふりがな（3 つ目）

* AreaWaterLevelWarning-AreaWaterLevelWarning.csv

20241226_AreaWaterLevelWarning.xlsx の「AreaWaterLevelWarning」シート

データの行はありません（空のファイル）。

列:

1. @code
2. @name

* EarthquakeVolcano-11.csv

地震火山関連コード表.xlsx の「11」シート

列:

1. Code
2. Name

* EarthquakeVolcano-12.csv

地震火山関連コード表.xlsx の「12」シート

列:

1. Code
2. Name
3. 備考

* EarthquakeVolcano-14.csv

地震火山関連コード表.xlsx の「14」シート

列:

1. Code
2. Name
3. 備考

* EarthquakeVolcano-21.csv

地震火山関連コード表.xlsx の「21」シート

列:

1. Code
2. Name
3. ふりがな
4. 備考

* EarthquakeVolcano-22.csv

地震火山関連コード表.xlsx の「22」シート

列:

1. Code
2. Name
3. ふりがな
4. 備考

* EarthquakeVolcano-23.csv

地震火山関連コード表.xlsx の「23」シート

列:

1. Code
2. Name

* EarthquakeVolcano-24.csv

地震火山関連コード表.xlsx の「24」シート

列:

1. AreaForecastLocalE の Code
2. AreaForecastLocalE の Name
3. AreaForecastLocalE のふりがな
4. AreaInformationCity の Code
5. AreaInformationCity の Name
6. AreaInformationCity のふりがな
7. 震度観測点の Code
8. 震度観測点の Name
9. 震度観測点のふりがな

* EarthquakeVolcano-25.csv

地震火山関連コード表.xlsx の「25」シート

列:

1. AreaForecastLocalE の Code
2. AreaForecastLocalE の Name
3. AreaInformationCity の Code
4. AreaInformationCity の Name
5. リアルタイム震度観測点の Code
6. リアルタイム震度観測点の Name

* EarthquakeVolcano-26.csv

地震火山関連コード表.xlsx の「26」シート

列:

1. AreaForecastLocalE の Code
2. AreaForecastLocalE の Name
3. AreaForecastLocalE のふりがな
4. 長周期地震動観測点の Code
5. 長周期地震動観測点の Name
6. 長周期地震動観測点のふりがな

* EarthquakeVolcano-31.csv

地震火山関連コード表.xlsx の「31」シート

列:

1. Code
2. Name
3. ふりがな
4. 備考

* EarthquakeVolcano-34.csv

地震火山関連コード表.xlsx の「34」シート

列:

1. Code
2. Name
3. ふりがな

* EarthquakeVolcano-35.csv

地震火山関連コード表.xlsx の「35」シート

列:

1. Code
2. Name
3. ふりがな
4. ヘッダ部で使用する簡略化した観測点の Code
5. ヘッダ部で使用する簡略化した観測点の Name
6. 備考

* EarthquakeVolcano-41.csv

地震火山関連コード表.xlsx の「41」シート

列:

1. Code
2. Name

* EarthquakeVolcano-42.csv

地震火山関連コード表.xlsx の「42」シート

列:

1. Code
2. Name
3. 備考

* EarthquakeVolcano-43.csv

地震火山関連コード表.xlsx の「43」シート

列:

1. Code
2. Name

* EarthquakeVolcano-44.csv

地震火山関連コード表.xlsx の「44」シート

列:

1. Code
2. Name

* EarthquakeVolcano-51.csv

地震火山関連コード表.xlsx の「51」シート

列:

1. Code
2. Name

* EarthquakeVolcano-52.csv

地震火山関連コード表.xlsx の「52」シート

列:

1. Code
2. Name
3. 備考

* EarthquakeVolcano-62.csv

地震火山関連コード表.xlsx の「62」シート

列:

1. Code
2. Text

* EarthquakeVolcano-81.csv

地震火山関連コード表.xlsx の「81」シート

列:

1. Code
2. Name
3. 備考

* EarthquakeVolcano-82.csv

地震火山関連コード表.xlsx の「82 」シート

列:

1. Code
2. Name
3. ふりがな
4. 備考

* EarthquakeVolcano-83.csv

地震火山関連コード表.xlsx の「83」シート

列:

1. Code
2. Name
3. 備考

* ObservingPointByOthers-ObservingPointByOthers.csv

20261118_ObservingPointByOthers.xlsx の「ObservingPointByOthers」シート

列:

1. 都府県振興局
2. 観測所番号
3. 所管機関
4. 種類
5. 観測所名・気象解説情報等に表記する名称
6. 観測所名（ふりがな）
7. 所在地
8. 緯度（度）
9. 緯度（分）
10. 経度（度）
11. 経度（分）
12. 二次細分区域コード

* PhenologicalType-XML.csv

20201224_PhenologicalType.xlsx の「XML」シート

列:

1. Code
2. Name
3. ClassName

* PointAmedas-ame_master.csv

20261110_PointAmedas.xlsx の「ame_master」シート

列:

1. 都府県振興局
2. 観測所番号
3. 種類
4. 観測所名
5. ひらがな名
6. 所在地
7. 緯度（度）
8. 緯度（分）
9. 経度（度）
10. 経度（分）
11. 海面上の高さ(ｍ)
12. 風速計の高さ(ｍ)
13. 温度計の高さ(ｍ)
14. 観測開始年月日
15. 備考1
16. 備考2
17. 気象解説情報等に表記する名称
18. 二次細分区域コード

* PointAmedas-snow_master.csv

20261110_PointAmedas.xlsx の「snow_master」シート

列:

1. 都府県振興局
2. 観測所番号
3. 種類
4. 観測所名
5. ひらがな名
6. 所在地
7. 緯度（度）
8. 緯度（分）
9. 経度（度）
10. 経度（分）
11. 海面上の高さ（ｍ）
12. 観測開始年月日
13. 気象解説情報等に表記する名称
14. 二次細分区域コード

* PointTidalLevel-tidallevel_master.csv

20250630_PointTidalLevel.xlsx の「tidallevel_master」シート

列:

1. 潮位観測地点番号
2. 所管機関
3. 観測所名
4. 地点名（カナ）
5. 所在地
6. 緯度（度）
7. 緯度（分）
8. 経度（度）
9. 経度（分）
10. 観測方式

* RiverOffice-RiverOffice.csv

20260430_RiverOffice.xlsx の「RiverOffice」シート

列:

1. @code
2. @name

* WaterLevelStation-WaterLevelStation.csv

20261104_WaterLevelStation.xlsx の「WaterLevelStation」シート

列:

1. 水位観測所（指定河川洪水予報）の @code
2. 水位観測所（水位周知河川に関する情報）の @code
3. @name
4. （参考）予報区域名（指定河川洪水予報）

* WmoObservingStations-WmoObservingStations.csv

20241226_WmoObservingStations.xlsx の「WmoObservingStations.」シート

列:

1. @code
2. コードが示す地点
3. ふりがな
4. 緯度（度）
5. 緯度（分）
6. 経度（度）
7. 経度（分）
8. 特殊気象報、生物季節観測報告気象報の @name
9. "生物季節観測"で使用（1）
10. "季節観測"で使用（1）
11. "特殊気象報(各種現象）"で使用（1）
12. 環境気象情報の @name
13. 地方海上予報の @name
14. 指定河川洪水予報、水位周知河川に関する情報の @name
15. 天候情報の @name
