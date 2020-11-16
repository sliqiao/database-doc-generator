# 作业答题卡区域修改历史(homework_wk_region_his)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_region_his_id|int8||否|ID|
|homework_wk_region_id|int8||否|homework_wk_region表主键|
|score_before|numeric||否|修改之前的分数|
|score_after|numeric||否|修改之后的分数|
|remark|varchar||是|备注|
|before_json|varchar||否|null|
|after_json|varchar||否|null|
|create_time|timestamp||否|null|
|create_user|int8||否|null|
|create_user_name|varchar||否|null|
