# 记录每一个老师的批改任务的上限，到达上限进行提示，让老师选择是否继续批改(exam_tech_limit)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||是|null|
|test_id|int8||否|null|
|pap_id|int8||是|null|
|tech_id|int8||否|null|
|top_limit|int4||否|null|
|update_time|timestamp||否|null|
|sub_code|int8||是|null|
