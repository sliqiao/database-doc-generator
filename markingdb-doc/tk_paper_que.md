# 试卷题目(tk_paper_que)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pq_id|int8||否|序号|
|pap_id|int8||否|试卷ID|
|que_id|int8||否|题目ID|
|pq_type|int8||否|分类ID|
|score|numeric||否|得分|
|desp|varchar||否|描述|
|tree_path|varchar||否|树路径|
|tree_up|int8||否|上级ID|
|tree_lev|int8||否|树级别|
|tree_sort|int8||否|树排序|
|sec_id|int8||是|null|
|que_name|varchar||是|题号|
|pap_que_in_id|int8||是|录入表pap_que_in的题目id|
