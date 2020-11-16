# 记录每次考试付费的名单(exam_pay_user_info)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|test_id|int8||否|null|
|subject_id|int8||否|null|
|stu_id|int8||否|null|
|time_upload|timestamp||否|null|
|report_url|varchar||否|用于存放报告的url地址，用于下载|
|is_gen|int4||否|null|
|time_gen|timestamp||否|null|
|printed|int4||否|null|
|time_update|timestamp||否|null|
