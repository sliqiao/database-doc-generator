# 这个表和cece题目共用一个属性表，如果exam_paper表中的pap_id_cece有值，则表示是通过测测的试卷维护进来的，则用pap_id_cece来查询，否则用exam_paper中的pap_id来查询，题目、试卷的相关属性存放这里(que_attr_busi)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|busi_id|int8||否|业务ID：阅读ID、文章ID、题目ID|
|attr_id|int8||否|null|
|time_update|timestamp||是|null|
