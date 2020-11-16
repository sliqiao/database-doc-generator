# exam_bas_class(exam_bas_class)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|class_id|int8||否|null|
|school_id|int8||否|null|
|class_name|varchar||否|null|
|class_code|varchar||否|null|
|class_type|int8||否|重点班、普通班，建分类目录表|
|sub_dirs|int8||否|文科、理科、不分科，见分类目录表|
|update_time|timestamp||否|null|
|school_year|int4||否|届|
|grade_id|int8||否|年级ID|
|source|int4||是|null|
|sub_id|int8||否|班级所属科目|
