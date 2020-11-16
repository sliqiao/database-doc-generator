# exam_composition_info(exam_composition_info)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|info_id|int8||否|null|
|test_id|int8||否|null|
|pap_id|int8||否|null|
|path_real|varchar||否|null|
|title|varchar||否|null|
|content|varchar||否|null|
|update_time|timestamp||否|null|
|create_time|timestamp||否|null|
|status|int4||否|0:草稿;1:校对完成;2:部分批阅;3:批阅完成|
|full_score|numeric||否|null|
|grade_id|int8||否|年级id|
|original_content|varchar||否|ocr识别的原始内容|
