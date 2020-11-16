# 机构（学校）单词-资源表(eer_school_word_resource)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|type|int2||否|资源类型：暂时只有图片（1：图片）|
|school_word_id|int8||是|关联机构单词表（school_word）id|
|resource_url|varchar||是|资源内容地址|
|resource_id|int8||是|关联bas_resource表rec_id|
