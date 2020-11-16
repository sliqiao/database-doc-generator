# 记录每个题目的单个识别区域以及识别内容(homework_wk_cell)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_cell_id|int8||否|ID|
|tk_pap_id|int8||否|试卷ID(作业ID)|
|homework_wk_region_id|int8||否|阅卷区域id|
|homework_wk_page_id|int8||否|阅卷答题卡版面id|
|cell_type|int4||否|类型：0:题干 1:答案|
|cell_id|int8||否|(模版)单元格id|
|sort_no|int4||否|排序|
|res_id|varchar||否|答案图片地址|
|res_path|varchar||是|裁切图片路径|
|ans_status|int4||否|作答状态：0已作答 1未作答；可能存在AI判断已作答，但是只能识别不到内容的情况|
|content|varchar||是|识别的答案内容|
|content_manu|varchar||是|人工校正的内容|
|max_thresh_value|numeric||否|识别的最大阈值|
|correct_mark|varchar||是|人工批改标记JSON|
|is_diff|int4||否|差异状态：-1未识别内容(默认),0没有差异，1有差异，2填涂有差异，可以忽略，作为低风险值|
|create_time|timestamp||否|新增时间|
|update_time|timestamp||否|修改时间|
|status|int4||否|0正常，1删除|
|height|int4||是|图片高度(填空使用)|
|width|int4||是|图片宽度(填空使用)|
|answer_type|int4||是|答案对/错/半对(多空填空使用)，值含义详见枚举|
|last_correct_id|int8||是|最后批阅人id(多空填空使用)|
|last_correct_name|varchar||是|最后批阅人姓名(多空填空使用)|
|ocr_type|int4||是|ocr识别类型，详见HomeworkOcrType枚举|
|auto_judge_type|int4||是|自动判断的类型，例如：AI，英语超长，本地判断等；详见代码枚举|
