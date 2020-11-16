# 教辅信息表(jf_info)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|jf_id|int8||否|主键ID|
|stage|int4||是|学段  1：小学 2：初中 3：高中|
|subject|_int8||是|科目(多选)，exam_subject表中的subject_id|
|subject_mc|_varchar||是|与选择的科目进行对应，做冗余处理，简便查询|
|base_jc_bb|int8||是|基础教材版本，统一管理一套教材版本，在教材维护操作通过选取对应的教材版本即可|
|base_jc_bb_mc|varchar||是|基础教材版本名称|
|jc_bb|int8||是|教材版本 que_attr表中attr_type为2且attr_up=0的attr_id|
|jc_cb|_int8||是|教材册别 que_attr表中attr_type为2且attr_up等于教材版本的attr_id|
|grade|_int8||是|年级 exam_code_dirs表dir_type = 163007(年级)且sort_no与学段字段进行有一个范围对应，[1-6] 小学 [7-9]初中 [10-12] 高中|
|grade_mc|_varchar||是|年级名称|
|author|varchar||否|作者|
|jf_bc|varchar||否|版次(年月)|
|isbn|varchar||否|ISBN|
|jf_mc|varchar||否|教辅名称|
|pic_url|varchar||否|封面图片地址|
|slt_pic_url|varchar||否|封面缩略图片地址|
|create_time|timestamp||否|创建时间|
|create_user|int8||否|创建用户|
|update_time|timestamp||否|更新时间|
|update_user|int8||否|更新用户|
|delete_status|int4||否|删除状态  0：未删除 1：已删除|
|delete_time|timestamp||是|删除时间|
|jc_cb_mc|_varchar||是|教材册别名称|
