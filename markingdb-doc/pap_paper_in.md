# pap_paper_in(pap_paper_in)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pap_id|int8||否|试卷ID|
|pap_code|varchar||否|试卷编号|
|pap_name|varchar||否|试卷主标题|
|pap_subname|varchar||否|试卷副标题|
|pap_type|int8||否|试卷类型：1手工组卷、2智能组卷|
|grade|int8||否|年级|
|subject|_int8||否|科目|
|dift|int8||否|题目难度累计和|
|score|int8||否|总分数|
|num_sec|int8||否|单元数|
|num_que|int8||否|题目数|
|len_min|int8||否|时长分钟|
|status_sort|int8||否|排序状态：0未排序、1已排序|
|status_edit|int8||否|编辑状态：0未编辑、1编辑中|
|status|int8||否|状态：0草稿、1、提交审核 2 审核通过 -1 审核不通过 -2 作废|
|org_id|int8||否|所属机构|
|user_create|int8||否|创建人|
|time_create|timestamp||否|创建时间|
|auditor|int8||否|null|
|audit_time|timestamp||否|null|
|src|int8||是|见《系统编码表》|
|region_code|varchar||是|null|
|time_publish|int8||是|null|
|tk_pap_id|int8||否|null|
|remark|varchar||是|null|
|time_update|timestamp||否|修改时间|
|type|int4||是|null|
|textbook_id|int8||是|null|
|input_type|int4||是|录入类型 0单题录入 1:试卷录入 2:老教辅录入 3:AB卷 4:附件试卷 5:新教辅|
|su_attr_id|int8||是|null|
|year|int4||是|null|
|queattr_id|varchar||是|教材来源|
|edua_name|varchar||是|Educational Assistance 教辅名称|
|user_check|int8||是|审核人|
|err_count|int8||是|null|
|jf_info_id|int8||是|教辅信息表的id|
|jf_content_id|int8||是|教辅目录的id|
|pdf_url|varchar||是|作业-卷卡一体答题卡pdf文件url|
|pap_version|int8||是|试卷ab卷版本, 0:a卷  1:b卷  2:c卷|
|mark_status|int4||是|标注状态  0 : 未领取  1: 标注中  2 :标注完成|
|user_mark_name|varchar||是|标注人的姓名|
|user_mark_id|int8||是|标注人的ID   0为没有标注.1.为admin|
|listen_template|int4||是|听写模板，0不是，1是|
