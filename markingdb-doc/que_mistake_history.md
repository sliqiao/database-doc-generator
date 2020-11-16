# 报错修改历史表(que_mistake_history)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|que_id|int8||否|题目tk_que的que_id|
|grade|int8||否|null|
|sub_id|int8||否|null|
|time_create|timestamp||否|报错时间|
|time_modify|timestamp||是|修改时间|
|user_modify|int8||是|修改人|
|mistake_type|_int8||否|null|
|user_create|int8||否|报错人|
