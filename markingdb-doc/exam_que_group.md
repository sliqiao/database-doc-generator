# 将几道题目合成一个题块进行阅卷，记录题块的信息(exam_que_group)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|group_name|varchar||否|null|
|questions|_int8||否|null|
|is_merger_score|int4||否|null|
|creator|int8||否|null|
|create_time|timestamp||否|null|
|test_id|int8||否|null|
|pap_id|int8||否|null|
|subject_id|int8||否|null|
|sort_no|int4||是|null|
