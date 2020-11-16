# 系统QR信息存放表(sys_qr_info)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|type|int4||否|类型：0作业,1作业重新识别|
|content|varchar||否|QR内容json|
|create_time|timestamp||否|null|
