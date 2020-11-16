# 100M初期用户的文件大小。(bas_resource)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|rec_id|varchar||否|guid|
|rec_idb|varchar||是|转换后的ID，有转换才有|
|name_ori|varchar||是|null|
|desc_res|varchar||是|null|
|range|int4||是|0私有|
|len_byte|int8||是|字节长度|
|ext|varchar||是|null|
|status|int4||是|1正常、0可删除|
|path_real|varchar||是|服务器上面现在存放的文件路径+文件名，为相对路径|
|path_url|varchar||是|url路径：只保存域名后的路径|
|num_down|int8||是|null|
|num_read|int8||是|null|
|user_create|int8||是|null|
|time_create|timestamp||是|null|
|time_update|timestamp||是|null|
|team_id|varchar||是|null|
|visit_path|varchar||是|null|
