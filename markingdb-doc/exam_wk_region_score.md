# 一个区域可能有多个小题，每个小题单独打分，每个题目可能有不同的给分点，图片标记也存放这里，图片的大小是系统默认(exam_wk_region_score)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|busi_type|int4||否|1-小题给分 2-得分点给分，3-评分标注 默认1|
|mark_type|int8||否|用于系统内置的标记类型，比如对、错、疑问等，见《系统编码》|
|que_id|int8||否|null|
|scoring_rule_id|int8||否|根据上面的类型来，如果不是评分点给分，这个值为0|
|score|numeric||否|null|
|wk_region_id|int8||否|null|
|pos_x|int4||否|对图片上点击评分有用|
|pos_y|int4||否|null|
|mark_content|varchar||是|null|
|operator|int8||否|null|
|time_update|timestamp||否|null|
|ans_level|varchar||是|null|
|bottom_x|int4||是|null|
|bottom_y|int4||是|null|
|sort_no|int4||是|null|
|score_intel|numeric||是|null|
