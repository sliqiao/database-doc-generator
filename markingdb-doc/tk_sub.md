# 学科(tk_sub)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|sub_id|int8||否|学科流水|
|stage_id|int8||否|教学阶段【枚举】：1小学、2初中、3高中|
|sub_type|int8||否|学科类型【枚举】：语文、数学...|
|sub_name|varchar||否|学科名称|
|sub_code|varchar||否|学科编码|
|sort|int8||否|排序，在同一阶段下的排序|
|status|int8||否|状态：-1停用、1正常|
|remark|varchar||否|备注|
|time_create|timestamp||否|创建时间|
|time_update|timestamp||否|修改时间|
