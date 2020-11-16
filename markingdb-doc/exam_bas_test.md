# 报名对应的考试，允许一次考试，分为多个小考试，可以采用多个卷子，比如中考、高考。每组织一次考试，建立一条记录(exam_bas_test)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|test_id|int8||否|null|
|test_name|varchar||否|null|
|begin_time|timestamp||是|null|
|end_time|timestamp||是|null|
|entry_begin_time|timestamp||否|null|
|entry_end_time|timestamp||否|null|
|region_code|varchar||是|填写行政区划，各行政区划下面用分号隔开|
|status|int4||否|-1停用 1 正常 2 发布分数|
|update_time|timestamp||否|null|
|school_id|int8||是|null|
|creator|int8||否|null|
|exam_type|varchar||是|null|
|class_id|_int8||是|布置班级，作业用|
|sub_type|varchar||是|考试子类型：1入学考试，2周考，3月考，4期中考试，5期末考试，6学业水平考试，7联考/调考|
