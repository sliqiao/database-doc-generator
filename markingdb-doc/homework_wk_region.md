# 作业每个切割出来的业务区域(homework_wk_region)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_region_id|int8||否|ID|
|homework_process_id|int8||否|作业进度表ID|
|homework_wk_sheet_id|int8||否|作业答题卡id|
|tk_pap_id|int8||否|试卷ID（作业ID）|
|stu_id|int8||否|学生ID|
|stu_name|varchar||否|学生姓名|
|num_cells|int4||否|阅卷单元格数量|
|region_type|int4||否|阅卷答题卡区域类型|
|region_id|int8||否|(模版)答题卡区域id|
|que_id|int8||否|题目ID|
|que_type|int8||否|题目类型|
|que_name|varchar||否|题号|
|que_sort|int4||否|作业上的题目排序|
|que_score|numeric||是|原始题目分数|
|ans_type|int4||否|答案对错： 1全对，2半对，3全错 ；11优，12良，13中，14差|
|proofread_status|int4||否|校对状态，0未校对，1已校对|
|risk_level|int4||否|风险等级，0低风险，1高风险|
|correct_type|int4||否|批改方式：1机器，2人工，3AI识别|
|score|numeric||否|分数|
|ans_mark|_int4||是|答案备注 1优秀答案，2典型错误，3范文|
|marking_sort|int4||否|批阅顺序|
|last_correct_id|int8||否|最后批阅者id，机器或者AI是-1|
|last_correct_name|varchar||否|最后批阅者姓名|
|correct_status|int4||否|批阅状态：1批改完毕，0未批改|
|answer_status|int4||否|是否作答：0作答，1未作答|
|dx_que_type|int4||否|大小题类型: 1单题，2大题（存在小题），3小题|
|small_que_parent_region_id|int8||否|小题对应的regionID|
|create_time|timestamp||否|null|
|update_time|timestamp||否|null|
|status|int4||否|0正常，1删除|
|last_correct_time|timestamp||是|最后批阅时间|
|num_option|int4||是|答案个数，值从tk_que获得|
|marking_way|varchar||是|打分模式|
|jd_correct_model|int4||否|是否是简答题批阅模式，0否1是|
|jd_correct_status|int4||否|简答题批阅状态 0未完成，1完成|
|last_update_from|int4||否|region从哪里来:0裁切，1微信上传|
|subject_id|int8||否|科目ID|
|subject_code|varchar||否|科目编码|
