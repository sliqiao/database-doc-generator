# 课程表(eer_course)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|name|varchar||是|名称|
|dicts|int2||是|单词总量|
|total_packages|int2||是|课程包总量|
|school_id|int8||是|关联机构（学校）表（exam_school_info）id|
|publish_date|date||是|发布时间|
|expiry_date|date||是|null|
