# 所有的做题记录保存在此(wk_work)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_id|int8||否|null|
|user_id|int8||否|null|
|job_id|int8||否|作业ID：JOB_ID>0、STU_ID联合唯一|
|class_id|int8||否|布置作业所在的班级|
|org_id|int8||否|布置作业的机构|
|tech_id|int8||否|布置作业的老师ID|
|time_start|timestamp||否|实际开始时间|
|time_end|timestamp||否|实际结束时间|
|len_sec|int4||否|由于现在的sat改版，每题里面的耗时已经没办法计算，只能计算总耗时|
|test_id|int8||否|考试编码|
|subjects|_int8||否|科目列表|
|pap_id|int8||是|试卷编号：整套试卷才填写|
|wk_rule|int8||是|见数据字典表|
|wk_type|int8||否|见字典表|
|status|int4||是|见字典表|
|score|numeric||是|模考得分：全套模考有效|
|remark|varchar||是|null|
|score_tech|numeric||是|作业成绩0-12对应F到A+；|
|comment|varchar||是|老师评语|
|time_update|timestamp||是|null|
