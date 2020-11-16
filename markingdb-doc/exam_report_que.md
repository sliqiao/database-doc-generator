# 考试错推题报告(exam_report_que)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|report_id|int8||否|null|
|batch_id|int8||是|null|
|school_id|int8||是|null|
|school_name|varchar||是|null|
|grade_id|int8||是|null|
|grade_name|varchar||是|null|
|class_id|int8||是|null|
|class_name|varchar||是|null|
|subject_id|int8||是|null|
|subject_name|varchar||是|null|
|stu_num|int4||是|null|
|status|int4||是|1--生成中   2--生成成功  3--生成失败|
|create_time|timestamp||是|null|
|complete_time|timestamp||是|null|
|test_ids|varchar||是|null|
|start_time|timestamp||是|null|
|end_time|timestamp||是|null|
