# 教辅目录信息表(jf_content)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|name|varchar||是|教辅目录名称|
|parent_id|int8||是|上级目录id，没有默认为0|
|sort|int2||是|同级目录排序标识|
|info_id|int8||是|关联教辅基础信息表(jf_info)主键|
|paper_id|int8||是|关联pap_paper_in表pap_id|
|update_user|int8||是|修改人id|
|listen_template|int4||是|听写模版  0不是，1是|
|load_message|text||是|导入日志信息|
