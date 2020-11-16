# exam_bas_test_params(exam_bas_test_params)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|题目编号，题组是几道题一起批改，就像大题的概念|
|test_id|int8||否|null|
|param_code|varchar||否|null|
|param_name|varchar||否|null|
|param_value|varchar||否|题型：系统编码，枚举|
|create_time|timestamp||否|null|
