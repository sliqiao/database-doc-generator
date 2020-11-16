# pap_que(pap_que)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pq_id|int8||否|试卷题目ID|
|pq_up|int8||否|上级试卷题目ID|
|pap_id|int8||否|试卷ID|
|sec_id|int8||否|题型ID|
|sort_sec|int8||否|题型排序|
|sort_pap|int8||否|试卷排序|
|que_id|int8||否|原始题目ID|
|que_up|int8||否|原始上级题目ID|
|que_type|int8||否|题型|
|que_types|int8||否|综合题型|
|sub_id|int8||否|学科ID|
|title|text||否|题干|
|answer_img|varchar||否|答案图片URL|
|answer|text||否|标准答案|
|analysis_img|varchar||否|解析图片URL|
|analysis|text||否|解析|
|num_option|int8||否|选项|
|dift|int8||否|难度【枚举】：0未定义、1容易、3普通、5困难|
|time_update|timestamp||否|更新时间|
|score|numeric||否|分值|
|grade_id|int8||是|年级id|
|grade_name|varchar||是|年级名称|
|grade_sort_no|numeric||是|年级顺序|
|stage|int4||是|学段|
|sub_name|varchar||是|科目名称|
|sub_sort_no|numeric||是|科目顺序|
