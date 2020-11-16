# 课程包表(eer_course_package)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|course_id|int8||是|关联课程表id|
|total_dicts|int4||是|单词总量|
|package_name|varchar||是|课程包名称|
|end_date|date||是|截止时间|
|voice_status|int2||是|机器音轨状态（0：未校验；1：已校验）|
|lock_status|int2||是|停/启用状态（0：停用；1：启用）|
|publish_status|int2||是|课程包发布状态（0：未发布；1：已发布；2：预发布）|
|publish_date|date||是|发布时间|
|recite_type|int2||是|背诵模式（0：普通模式；1：图文模式；2：全部）|
