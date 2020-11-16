# 这里不涉及到题目的具体信息，仅用来阅卷(exam_paper)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pap_id|int8||否|试卷编号|
|pap_name|varchar||否|试卷名称|
|sub_title|varchar||否|命题组说明|
|region_code|varchar||否|考试范围（地区），试卷的课时范围|
|subject_id|_int8||否|所属科目：语数外等，全空为全科|
|pap_id_cece|int8||否|cece试卷编号，有这个试卷，则属性值，取自里面的属性|
|school_id|int8||否|所属机构编号：0全部|
|grade|int8||否|所属年级|
|num_que|int8||否|题目数量|
|len_sec|int8||否|考试时长|
|score|numeric||否|满分|
|user_create|int8||否|创建人：0为管理员|
|time_create|timestamp||否|创建时间|
|time_update|timestamp||否|更新时间|
|time_publish|timestamp||否|发布时间|
|status|int8||否|状态：-1作废 0草稿、1发布（不可增删子表）|
|remark|varchar||否|备注|
|sheet_name|varchar||是|冗余字段，方便查询|
|step|int4||是|null|
|paper_type|varchar||是|null|
|tk_paper_id|int8||是|null|
|exam_type|int4||是|考试类型:0或空为考试,2为作业|
|sheet_type|int8||是|null|
