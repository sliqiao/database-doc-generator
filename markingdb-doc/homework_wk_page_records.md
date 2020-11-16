# 答题卡异常处理记录(homework_wk_page_records)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|wk_page_id|int8||否|homework_wk_page主键|
|wk_page_scanning_status|int4||否|wkpage的扫描状态
|
|machine_id|varchar||是|机器码|
|school_id|int8||否|学校ID|
|res_id|varchar||否|处理异常时，wkpage资源ID|
|res_path|varchar||是|处理异常时,wkpage资源路径|
|create_user_id|int8||否|异常处理人ID|
|create_user_name|varchar||是|处理人姓名|
|create_time|timestamp||否|null|
