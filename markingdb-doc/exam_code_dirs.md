# 学校类型、班级类型、学生类型、考试类型，科目类型、年级(exam_code_dirs)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|dir_id|int8||否|null|
|dir_code|varchar||否|null|
|dir_name|varchar||否|null|
|dir_type|int4||否|学校类型、班级类型、学生类型、考试类型，科目类型，这个见系统编码表|
|status|int4||否|null|
|sort_no|numeric||否|null|
|update_time|timestamp||否|null|
