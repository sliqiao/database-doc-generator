# 对应多个考点，一个考点对应多个考场(exam_place)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|place_id|int8||否|null|
|place_name|varchar||否|null|
|address|varchar||否|null|
|administrtice_code|varchar||否|null|
|longitude|numeric||否|null|
|latitude|numeric||否|null|
|capacity|int8||否|null|
|num_rooms|int8||否|null|
|status|int4||否|-1 作废 0-正常|
|update_time|timestamp||否|null|
