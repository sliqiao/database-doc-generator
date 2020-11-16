# 每个切割出来的业务区域(exam_wk_region)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_region_id|int8||否|null|
|wk_sheet_id|int8||否|null|
|num_cells|int4||否|null|
|region_type|int4||否|EXAM_ANS_REGION|
|region_id|int8||否|题目类型，这个id为0，因为题目的区域可能会跨版面|
|ques_no|int8||否|null|
|ans_type|int4||否|对于客观题，识别之后，自动给出对错|
|status|int4||否|0初始值 1批改中  2 已判  -1 作废 -2需要重裁|
|score_intel|numeric||否|null|
|score|numeric||否|null|
|ans_level|varchar||是|优秀答案、独立见解、典型错误、低级错误……|
|tech_id|int8||否|null|
|update_time|timestamp||否|null|
|chosen|int4||是|null|
|test_id|int8||是|null|
|pap_id|int8||是|null|
|is_auto|int4||是|null|
|zj_que_id|int8||是|null|
|repulse_reason|int4||是|null|
|marking_sort|int4||是|null|
|que_group_id|int8||是|null|
