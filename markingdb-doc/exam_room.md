# 一个考点有多个考场，比如有多个教室。(exam_room)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|room_id|int8||否|null|
|place_id|int8||否|null|
|room_name|varchar||否|null|
|address|varchar||否|null|
|num_seats|int4||否|null|
|sort_no|int4||否|一个考点内，考场号唯一，扫描时候需要传入考点|
|status|int4||否|-1作废 0 正常|
|update_time|timestamp||否|null|
