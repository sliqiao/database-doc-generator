# 用来记录答题卡的具体信息(exam_custom_sheet)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pap_id|int8||否|null|
|sheet_name|varchar||是|null|
|content|varchar||是|null|
|status|int4||否|-1作废 0 草稿 1 发布|
|opeator|int8||否|null|
|org_id|int8||否|null|
|time_update|timestamp||否|null|
