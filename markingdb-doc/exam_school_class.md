# 每个学校当前的班级表，每个学校的班级名称是唯一的，历史的班级通过年、学期（寒暑假）来区分，可以物理删除(exam_school_class)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|class_id|int8||否|null|
|school_d|int8||否|null|
|class_name|varchar||否|null|
|operator|int8||否|null|
|time_create|timestamp||否|null|
|time_update|timestamp||否|null|
