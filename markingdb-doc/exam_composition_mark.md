# exam_composition_mark(exam_composition_mark)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|mark_id|int8||否|null|
|info_id|int8||否|null|
|grade_id|int8||否|年级id|
|topic_type|int4||否|题材类型|
|score|numeric||否|分数|
|teacher_id|int8||否|老师id|
|create_time|timestamp||否|创建时间|
|status|int4||否|状态：0正常-1删除|
|update_time|timestamp||否|更新时间|
|comment|varchar||否|评语:默认,逗号隔开|
