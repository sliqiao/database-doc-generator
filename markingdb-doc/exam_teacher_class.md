# 记录老师的任课历史(exam_teacher_class)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|subject_id|int8||是|null|
|class_id|int8||否|null|
|grade_id|int8||否|null|
|role|int4||否|165001-任课老师 165005-班主任 165003-年级主任，年级主任时候，class_id为0|
|teach_id|int8||否|null|
|time_update|timestamp||否|null|
|stage|int4||否|学段，role为学校领导（165004）时有效，其他为0|
