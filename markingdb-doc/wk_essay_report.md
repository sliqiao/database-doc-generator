# 用来记录表的中间值，使历史数据不再改变，也不需要重新调用智能评分的操作，以便加快速度(wk_essay_report)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|ans_id|int8||否|null|
|content|varchar||否|保持为json数据，记录报表需要的中间数值|
|time_update|timestamp||否|null|
