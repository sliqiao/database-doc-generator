# 一个试卷对应多个原始扫描图片(exam_wk_page)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_page_id|int8||否|null|
|wk_sheet_id|int8||否|null|
|sheet_id|int8||否|null|
|page_id|int8||否|和版面无关的话，此处为0|
|res_id|varchar||否|null|
|res_id_ori|varchar||否|null|
|status|int4||否|0正常 -1作废|
|update_time|timestamp||否|null|
|match_value|numeric||是|null|
