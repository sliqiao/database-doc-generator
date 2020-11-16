# pap_section(pap_section)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|sec_id|int8||否|题型ID|
|pap_id|int8||否|试卷ID|
|que_type|int8||否|题型|
|que_types|int8||否|综合题型：1-7|
|sec_name|varchar||否|题型名称|
|note_head|varchar||否|前注|
|note_below|varchar||否|尾注|
|len_min|int8||否|时长|
|num_que|int8||否|题目数|
|content|varchar||否|内容|
|score_sec|numeric||否|总分数|
|score_que|numeric||否|每题分数|
|sort_pap|int8||否|排序|
|is_choose|int8||否|是否选做|
|time_update|timestamp||否|更新时间|
|tk_sec_id|int8||是|null|
|group_que_type_name|varchar||是|分组题型名称|
