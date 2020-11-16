# class_wrong_que_report_task(class_wrong_que_report_task)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键id|
|start_time|timestamp||是|开始时间|
|end_time|timestamp||是|结束时间|
|school_id|int8||是|学校id|
|school_name|varchar||是|学校名称|
|grade_id|int8||是|年级id|
|grade_name|varchar||是|年级名称|
|class_id|int8||是|班级id|
|class_name|varchar||是|班级名称|
|subject_id|int8||是|科目id|
|subject_name|varchar||是|科目名称|
|stu_count|int4||是|符合条件范围内参考学生个数|
|create_time|timestamp||是|任务创建时间|
|status|int4||是|任务状态 0初始化  1报告生成中，2报告已经生成，3报告生成失败|
|operator|varchar||是|任务发布者|
|pdf_path|varchar||是|pdf生成的路径|
|finish_time|timestamp||是|任务结束时间|
|operator_id|int8||是|任务创建者的id|
|stu_ids|_int8||是|null|
|pdf_answer_path|varchar||是|错题答案pdf地址|
|test_ids|_int8||是|筛选的考试|
