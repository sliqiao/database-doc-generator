# 教辅目录视频信息表(jf_content_video)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|name|varchar||是|视频名称|
|sort|int2||是|排序标识|
|content_id|int8||是|关联jf_content表id|
|video_resource_id|varchar||是|关联bas_resource表rec_id|
|video_image_id|varchar||是|关联bas_resource表rec_id|
|description|varchar||是|视频描述|
