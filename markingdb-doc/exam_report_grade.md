# exam_report_grade(exam_report_grade)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|题目编号，题组是几道题一起批改，就像大题的概念|
|grade|int8||否|试卷编号|
|school_id|int8||否|null|
|test_id|int8||否|null|
|param_code|varchar||否|null|
|param_value|varchar||否|题型：系统编码，枚举|
|score|numeric||否|分值|
|stu_num|int4||否|null|
|sort|int4||否|null|
|max_score|int4||否|null|
|min_score|int8||否|null|
|create_time|timestamp||否|null|
