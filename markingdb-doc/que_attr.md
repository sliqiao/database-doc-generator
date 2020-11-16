# 包括能力、知识点等(que_attr)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|attr_id|int8||否|属性编号，系统自动产生|
|attr_code|varchar||否|属性编码|
|name|varchar||否|属性名称|
|name_cn|varchar||否|属性名称中文|
|name_short|varchar||否|简称|
|attr_up|int8||否|上级节点|
|lev|int4||否|级别：第1级为0|
|sort_no|int4||否|从小到大，从1开始|
|attr_type|int8||否|(枚举)属性分类信息 见字典表，这里主要是能力和知识点|
|org_id|int8||否|机构编号：0公司|
|subject|int8||否|null|
|key_stage|int8||否|null|
|user_create|int8||否|添加人|
|status|int4||否|-1删除 0草稿 1有效|
|time_update|timestamp||否|更新时间|
|remark|varchar||否|备注|
|grade|int8||是|null|
|term|int8||是|null|
|sys_code|int8||是|null|
