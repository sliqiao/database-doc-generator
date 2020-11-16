# error_type(error_type)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pap_id|int8||否|试卷编号|
|que_id|int8||是|题目编号|
|sub_id|int4||是|年级编号|
|stage|varchar||是|年级名字|
|errortype|varchar||是|错误类型|
|submit_time|timestamp||是|错误报告时间|
|memo|text||是|备注信息|
