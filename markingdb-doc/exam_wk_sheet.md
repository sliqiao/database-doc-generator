# 一张答题卡如果多次扫描并导入多次，则只取指定的某一张(exam_wk_sheet)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_sheet_id|int8||否|做题编号|
|test_id|int8||否|null|
|pap_id|int8||否|考试ID|
|school_id|int8||否|学校ID|
|ticket_no|varchar||否|准考证号|
|stu_id|int8||否|学生ID：根据准考证号自动关联|
|score|numeric||否|本次阅卷最终得分|
|status|int4||否|状态：-3违纪，-2,缺考-1作废、0草稿、1校对完毕、2选中、3批阅完成|
|sheet_id|int8||否|null|
|user_create|int8||否|新增人|
|time_create|timestamp||否|新增时间|
|time_update|timestamp||否|null|
|scan_status|int4||是|null|
|check_status|int4||是|null|
|place_id|int8||是|null|
|print_count|int4||是|学生有痕答题卡打印次数|
