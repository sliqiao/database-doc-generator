# exam_school_info(exam_school_info)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|school_id|int8||否|null|
|school_code|varchar||是|null|
|parent_school_id|int8||否|允许学校有上下级|
|school_name|varchar||否|null|
|name_short|varchar||否|null|
|region_code|varchar||否|null|
|address|varchar||否|null|
|type|int4||否|null|
|longitude|numeric||否|null|
|latitude|numeric||否|null|
|full_time|int4||否|null|
|update_time|timestamp||否|null|
|school_class|int4||是|null|
|class_comparison_status|int4||否|班级对比开关：0为开启，1为关闭；默认为0；
学校类型为省教育局 0、市教育局  1、区县教育局2 时，此字段无效|
