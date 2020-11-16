# sys_region(sys_region)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|reg_code|varchar||否|国家发布的行政区域编码|
|name_cn|varchar||否|中文名称|
|name_en|varchar||是|名称英文|
|short_cn|varchar||否|中文简称|
|shrot_en|varchar||是|简称英文|
|spell_all|varchar||否|中文全拼|
|spell_first|varchar||否|中文简拼|
|timespan|numeric||是|时差：与北京的时差|
|up_code|varchar||否|null|
|lev|int4||否|从1开始|
|sort|int4||否|同级别里的排序，从小到大|
|status|int4||否|1启用、0停用|
|remark|varchar||否|备注|
|area_code|varchar||否|区域划分|
|zip|varchar||是|右边|
|time_update|timestamp||否|更新时间|
