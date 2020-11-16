# 所有学生回答的内容填写在此，去掉专门的自编题答案表，上传的附件保存在BAS_REC_BUSI(wk_ans)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|ans_id|int8||否|null|
|wk_id|int8||否|null|
|que_id|int8||否|null|
|user_id|int8||否|null|
|sort_no|int4||否|作业内排序：从1开始，按学科ERMWN排列|
|time_start|timestamp||否|第一次进入题目时间，如果是默认值则表示未开始|
|time_end|timestamp||否|最后一次离开时间|
|len_sec|int4||否|每次时间累计停留时间|
|len_ans|int4||否|进入题目到最后一次修改答案的累计停留时间|
|answer|varchar||否|学生答案：|
|num_words|int4||否|用于作文，显示内容的总词数|
|is_fill|int4||否|是否填写答案：-1未看未填、0看了未填、1已填|
|ans_type|int4||否|客观题对错：-2未看，-1错误、0未做、1正确|
|score_teach|numeric||否|老师评分：作文0-12、自主题0-12对应F-A+、客观题:ANS_TYPE|
|score_intel|numeric||否|智能评分：|
|status|int4||否|状态：0未开始、2作业中、3交卷待批改、4批改中、5批改完毕，如果没有作文，直接由2到5|
|num_file|int4||否|null|
|tech_note|varchar||否|暂时只考虑一个老师的批注|
|tech_comment|varchar||否|null|
|remark|varchar||否|null|
|time_correct|timestamp||否|批改时间|
|time_update|timestamp||否|更新时间|
|tech_id|int8||是|null|
