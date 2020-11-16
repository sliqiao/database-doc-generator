# 给每个阅卷老师指定任务的分配。从考试阅卷老师表里面选取老师(exam_task_assign)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|test_id|int8||否|null|
|pap_id|int8||否|null|
|ques_id|int8||否|null|
|tech_id|int8||否|null|
|num_check|int8||否|用来显示工作量用|
|score_check|int8||否|用来计算平均分用|
|status|int4||否|-1 不再阅卷 1 允许阅卷|
|update_time|timestamp||否|null|
|num_check_assign|int8||是|null|
|mode|int4||是|null|
|que_group_id|int8||是|null|
