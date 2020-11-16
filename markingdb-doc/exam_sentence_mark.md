# exam_sentence_mark(exam_sentence_mark)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|mark_id|int8||否|null|
|sentence_id|int8||否|null|
|content_false|varchar||否|null|
|wrong_type|int4||否|null|
|wrong_reason|varchar||否|null|
|create_time|timestamp||否|null|
|status|int2||否|0:正常；1：删除|
|operator_id|int8||否|操作人id|
|operator_name|varchar||是|null|
|update_time|timestamp||是|null|
