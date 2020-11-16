# 试卷录入的题目信息（包含教辅）(pap_que_in)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pq_id|int8||否|试卷题目ID|
|pq_up|int8||否|上级试卷题目ID|
|pap_id|int8||否|试卷ID|
|sec_id|int8||否|null|
|sort_sec|int8||否|null|
|sort_pap|int8||否|null|
|que_id|int8||否|null|
|que_up|int8||否|null|
|que_type|int8||否|null|
|que_types|int8||否|null|
|sub_id|int8||否|null|
|title|text||否|null|
|answer_img|varchar||否|null|
|answer|text||否|null|
|analysis_img|varchar||否|null|
|analysis|text||否|null|
|num_option|int8||否|null|
|dift|int8||否|null|
|score|numeric||否|null|
|time_update|timestamp||否|null|
|tk_que_id|int8||是|对应que_id，查重和审核时使用|
|status|int8||是|null|
|error_desc|text||是|注释内容|
|grade_id|int8||是|题目年级|
|que_dianxing|int4||是|0.不是典型题 1.典型题|
|que_jingpin|int4||是|0.不是精品题 1.精品题|
|que_cebie_id|int8||是|题目教辅冊别|
|que_mold_id|int8||是|题目类型(高考真题、高考模拟题、学考真题、学考模拟题等)|
|answer_area_size|int4||是|作答区域尺寸，简答题-行数，英语作文-行数，语文作文-格子数量|
|rule_type_arr|_int4||是|多选判分规则 11：选对但不全，12：每选对1个，21：有选错的，22：每选错1个，3：按不同选项判分|
|score_arr|_numeric||是|多选判分规则对应分值|
|que_mark_status|int8||是|题目标注状态   0: 未标注  1: 人工已经标注  2:智能已经标注|
|cognitive_level|int8||是|认知层级|
|subject_literacy|int8||是|学科素养|
|literacy_level|int8||是|素养水平|
|capability_point|int8||是|能力点|
|answer_type|int4||是|题目答案类型:0.正常   1.填空题专用(表示多空的答案可以乱序)|
