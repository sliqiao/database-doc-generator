# 设备信息表(machine_info)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|machine_id|varchar||否|设备ID|
|machine_type|int4||否|设备类型，1安卓扫描仪|
|school_id|int8||否|学校ID|
|machine_name|varchar||否|机器名称|
|mark|varchar||是|备注信息|
|create_time|timestamp||否|创建时间|
|update_time|timestamp||否|更新时间|
|status|int4||否|0正常，1删除|
|notify_phone|varchar||是|负责人手机号码，用来接收通知,多个逗号分隔|
