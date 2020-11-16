# 报告学生(exam_report_que_stu)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|report_id|int8||是|null|
|stu_id|int8||是|null|
|stu_name|varchar||是|null|
|create_time|timestamp||是|null|
|complete_time|timestamp||是|null|
|status|int4||是|1--生成中  2--生成成功  3--生成失败|
|push_que_path|varchar||是|null|
|push_answer_path|varchar||是|null|
|report_head_path|varchar||是|null|
|report_foot_path|varchar||是|null|
|wrong_que_path|varchar||是|null|
|wrong_answer_path|varchar||是|null|
|ques|text||是|null|
