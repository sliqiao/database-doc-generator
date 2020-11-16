# 存储系统的各类配置参数缓存(sys_set)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|skey|varchar||否|null|
|sname|varchar||是|null|
|svalue|varchar||是|null|
|sort|int4||是|null|
|class|varchar||是|null|
|remark|varchar||是|null|
|time_update|timestamp||是|null|
|user_id|int8||是|null|
|status|int4||是|1正常     0删除|
