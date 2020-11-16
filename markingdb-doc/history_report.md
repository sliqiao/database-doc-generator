# history_report(history_report)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|history_report_id|int8||否|null|
|report_name|varchar||否|null|
|class_id|int8||否|null|
|class_name|varchar||否|null|
|subject_id|int8||否|null|
|subject_name|varchar||否|null|
|school_id|int8||否|null|
|school_name|varchar||否|null|
|grade_id|int8||否|null|
|grade_name|varchar||否|null|
|create_time|timestamp||否|null|
|report_que_path|varchar||是|null|
|report_answer_path|varchar||是|null|
|kpoint_num|int4||否|null|
|ques_num|int4||否|null|
|start_time|timestamp||否|null|
|end_time|timestamp||否|null|
|status|bpchar||否|null|
|stu_num|int4||否|null|
|pap_group|varchar||否|原卷对应的精品卷ID|
|pap_group_ab|varchar||否|精品卷AB卷组|
|exam_pap_group|varchar||否|推送的考试原卷id|
