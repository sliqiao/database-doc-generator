# 试卷表(tk_paper)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pap_id|int8||否|试卷ID|
|site_id|int8||否|网站ID【字典】|
|pap_code|varchar||否|试卷编码|
|pap_name|varchar||否|试卷名称|
|pap_type|int8||否|试卷类型【字典】|
|score|int8||否|总分数|
|grade_type|int8||否|年级类型【枚举】：1一年级、2二年级|
|term_type|int8||否|学期类型【枚举】：1上学期、2下学期|
|reg_prov|varchar||否|省份编码|
|reg_city|varchar||否|城市编码|
|reg_county|varchar||否|区县编码|
|remark|varchar||否|备注|
|time_publish|timestamp||否|发布日期|
|time_update|timestamp||否|更新时间|
|time_create|timestamp||否|添加时间|
|type|int4||是|录入类型 0单题录入 1试卷录入 2教辅录入|
|textbook_id|int8||是|null|
|subject|_int8||是|null|
|len_min|int8||是|考试时长|
|sec_num|int8||是|单元数量|
|su_attr_id|int8||是|null|
|pap_grp|varchar||是|null|
|sheet_id|int8||是|是否生成答题卡|
|year|int4||是|年份|
|pdf_url|varchar||是|作业-卷卡一体答题卡pdf文件url|
|mark_status|int4||是|标注状态  0 : 未领取  1: 标注中  2 :标注完成|
|user_mark_id|int8||是|标注人的ID   0为没有标注.1.为admin|
|listen_template|int4||是|听写模板，0不是，1是|
|answer_pdf_url|varchar||是|答案解析url|
