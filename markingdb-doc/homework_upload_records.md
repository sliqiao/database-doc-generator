# 作业上传图片记录(homework_upload_records)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|resource_id|varchar||否|图片资源ID|
|machine_id|varchar||否|机器码|
|school_id|int8||否|学校ID|
|status|int4||否|0待处理，1已处理|
|resource_url|varchar||是|图片地址|
|create_time|timestamp||否|上传时间|
|update_time|timestamp||否|null|
