# 作业-教辅管理表(homework_jf_manager)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|update_user|int8||是|修改人id|
|school_id|int8||是|关联学校exam_school_info表school_id|
|school_name|varchar||是|使用学校|
|info_id|int8||是|关联教辅jf_info表jf_id|
|info_name|varchar||是|教辅名称|
|use_grade|varchar||是|使用年级|
|use_subject|varchar||是|使用科目|
|author|varchar||是|教辅作者|
|jf_edition|varchar||是|教辅版本|
