# App更新(app_update)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键ID|
|platform_type|int4||否|1:Android  2:IOS|
|version|varchar||否|版本号|
|download_url|varchar||否|下载地址|
|md5|varchar||是|MD5|
|force_update|int4||否|0：不强制 1：强制|
|update_desc|text||是|更新描述|
|update_time|timestamp||否|更新时间|
|project_type|int4||否|项目类型 1：阅卷|
