# TaiwanRailwayData

台鐵公開資料（Open Data）應用：時刻表查詢

使用方式

參數argv_start_station：起始車站代碼
參數argv_end_station：目的地車站代碼
參數argv_time：起始時間
參數argv_carclass：車種類別，請參照dict_car_select此字典

主要以台鐵時刻表JSON交換檔進行查詢，請至http://163.29.3.98/json/下載，輸出資料也是JSON格式，主要輸出車次、車種、開車時間、到站時間與備註
