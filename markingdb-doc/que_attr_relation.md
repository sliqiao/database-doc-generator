# que_attr_relation(que_attr_relation)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|ret_id|int8||否|关系编号，系统自动产生|
|attr_id|int8||否|属性编号|
|up_attr|int8||否|上级属性编号|
|lev|int8||否|级别|
|test_type|int8||否|考试类型|
|subject|int8||否|学科|
|attr_type|int8||否|属性类别|
|score_min|numeric||否|评分最小值|
|score_max|numeric||否|评分最大值|
|time_update|timestamp||否|维护时间|
