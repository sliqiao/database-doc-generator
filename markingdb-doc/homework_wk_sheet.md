# 每个学生，每次作业上传的主信息(homework_wk_sheet)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_sheet_id|int8||否|ID|
|homework_process_id|int8||否|作业进度ID|
|tk_pap_id|int8||否|题库里的作业id|
|sheet_id|int8||否|答题卡id|
|school_id|int8||否|学校ID|
|grade_code|varchar||否|年级编码,注意不是ID|
|class_id|int8||否|班级ID|
|stu_id|int8||否|学生ID|
|stu_name|varchar||否|学生姓名|
|upload_page_total|int4||否|已上传上传页数（一张两页）|
|score|numeric||否|本次阅卷最终得分|
|report_push_status|int4||否|报告推送状态：0未推送，1已推送，2推送失败|
|last_submit_time|timestamp||否|当前学生最后一次上传作业的时间|
|create_time|timestamp||否|null|
|update_time|timestamp||否|null|
|status|int4||否|0正常，1删除|
