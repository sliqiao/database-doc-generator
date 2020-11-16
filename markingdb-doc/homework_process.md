# homework_process(homework_process)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|homework_process_id|int8||否|试卷编号|
|homework_name|varchar||是|作业名称|
|tk_paper_id|int8||否|试卷ID(作业ID)|
|school_id|int8||否|学校ID|
|school_name|varchar||否|学校名称|
|grade_id|int8||否|年级ID|
|grade|varchar||否|年级编码，不是ID|
|class_id|int8||否|班级ID|
|class_name|varchar||否|班级名称|
|subject_ids|_int8||否|科目，数组|
|page_total|int4||否|作业总页数(一张两页)|
|page_submit|int4||否|已提交页数（一张两页）|
|stu_total|int4||否|班级总人数，应交人数|
|submit_total|int4||否|已交人数|
|objective_que_total|int4||否|客观题数|
|objective_que_correct|int4||否|客观题正确数|
|subjective_que_total|int4||否|主观题数|
|subjective_que_correct|int4||否|主观题正确数|
|que_total|int4||否|本次作业有几个题目(不含大题)|
|corrected_total|int4||否|已批改题目数量|
|has_score|int4||否|1有0无|
|threshold|numeric||否|阈值|
|report_push_status|int4||否|0未推送，1已推送|
|report_push_time|timestamp||是|报告推送时间|
|create_time|timestamp||否|null|
|update_time|timestamp||否|null|
|status|int4||否|0正常，1删除|
|ans_sheet_answer_type|int4||否|客观题类型，0填涂，1手写|
|scanning_que_total|int4||否|已扫描的题目总数(一个学生一道题算一个，不含大题)|
|last_upload_time|timestamp||否|最后一个答题卡的上传时间|
|last_correct_complete_time|timestamp||是|最后一次批阅完成时间|
|teacher_ids|_int8||是|任课教师|
|listen_template|int4||否|听写模板(双栏)：0否，1是|
