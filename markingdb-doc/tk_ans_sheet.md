# 一个试卷可以对应多个答题卡，导入的时候选择答题卡，答题卡对应试卷的a、b或者c
一个答题卡有多个版面，每个版面有个多个区域，一个区域为阅卷时一起的图片，一个区域对应多个单元格。主要用于一个题跨域多个方块的地方，比如作文。(tk_ans_sheet)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|sheet_id|int8||否|null|
|pap_id|int8||否|null|
|sheet_type|int8||否|AB卷用，默认为A卷|
|sheet_name|varchar||否|null|
|page_num|int4||否|null|
|create_time|timestamp||否|null|
|status|int4||是|0 草稿 1正常 -1 作废|
|update_time|timestamp||否|null|
|option_type|int4||是|null|
|sheet_form|int4||是|null|
|ticket_figure_num|int4||是|null|
|sheet_source|int4||是|null|
|attr_id|int8||是|null|
|answer_type|int4||是|默认0填涂，1手写|
