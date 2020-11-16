# pap_paper(pap_paper)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pap_id|int8||否|试卷ID|
|pap_code|varchar||否|试卷编号|
|pap_name|varchar||否|试卷主标题|
|pap_subname|varchar||否|试卷副标题|
|pap_type|int8||否|试卷类型：1手工组卷、2智能组卷|
|grade|int8||否|年级|
|dift|int8||否|题目难度累计和|
|score|numeric||否|总分数|
|num_sec|int8||否|单元数|
|num_que|int8||否|题目数|
|len_min|int8||否|时长分钟|
|status_edit|int8||否|编辑状态：0未编辑、1编辑中|
|status|int8||否|状态：0草稿、1发布、-1作废|
|show_name|int8||否|显示主标题|
|show_subname|int8||否|显示副标题|
|show_zdx|int8||否|显示装订线|
|show_bmbj|int8||否|显示保密标记|
|show_xxl|int8||否|显示试卷信息栏|
|show_srl|int8||否|显示考生输入栏|
|show_yfl|int8||否|显示誊分栏|
|show_zysxl|int8||否|显示注意事项栏|
|show_jbjz|int8||否|显示卷标卷注|
|txt_bmbj|varchar||否|保密标记内容|
|txt_xxl|varchar||否|试卷信息栏内容|
|txt_srl|varchar||否|考生输入栏内容|
|txt_yfl|varchar||否|誊分栏内容|
|txt_zysxl|varchar||否|注意事项栏内容|
|txt_jbjz|varchar||否|卷标卷注内容|
|json_sheet|text||否|答题卡JSON|
|org_id|int8||否|所属机构|
|user_create|int8||否|创建人|
|time_create|timestamp||否|创建时间|
|time_update|timestamp||否|修改时间|
|status_sort|int8||否|排序状态：0未排序、1已排序|
|subject|_int8||是|null|
|pap_source|int8||否|试卷来源：1题库、2班级错题|
|has_score|int4||是|赋分标识：1有分0无分|
|custom_pap_name|int4||是|自定义试卷名称标识：1是 0否|
|custom_score|int4||是|自定义分数：1是 0否|
|pdf_url|varchar||是|组卷预览pdf|
