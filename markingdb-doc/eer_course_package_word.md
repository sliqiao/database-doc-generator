# 课程包-单词表(eer_course_package_word)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|course_package_id|int8||是|关联课程包表（course_package）id|
|school_word_id|int8||是|关联机构单词表（school_word）id|
|course_id|int8||是|关联课程表（course）id|
