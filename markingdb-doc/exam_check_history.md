# 记录每个老师阅卷的流水，此表记录只应该新增，没有删除和修改的操作(exam_check_history)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|tech_id|int8||否|null|
|wk_region_id|int8||否|null|
|score|numeric||否|null|
|time_update|timestamp||否|null|
|que_group_id|int8||是|null|
