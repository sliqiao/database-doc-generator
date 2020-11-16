# que_paper(que_paper)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pap_id|int8||否|试卷ID|
|pap_code|varchar||否|试卷编号|
|pap_name|varchar||否|试卷主标题|
|pap_subname|varchar||否|试卷副标题|
|pap_info|varchar||否|试卷信息栏|
|grade|int8||否|年级|
|subject|int8||否|科目|
|dift|int8||否|题目难度累计和|
|score|int8||否|总分数|
|num_sec|int8||否|单元数|
|num_que|int8||否|题目数|
|len_min|int8||否|时长分钟|
|status_edit|int8||否|编辑状态：0未编辑、1编辑中|
|status|int8||否|状态：0草稿、1发布、-1作废|
|ext_zdx|int8||否|装订线|
|ext_bmbj|int8||否|保密标记|
|ext_srl|int8||否|考试输入栏|
|ext_yfl|int8||否|誊分栏|
|ext_zysxl|int8||否|注意事项栏|
|ext_jbjz|int8||否|卷标卷注|
|org_id|int8||否|所属机构|
|user_create|int8||否|创建人|
|time_create|timestamp||否|创建时间|
|time_update|timestamp||否|修改时间|
