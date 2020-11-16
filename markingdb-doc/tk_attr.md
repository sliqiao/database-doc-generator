# 属性分类(tk_attr)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|attr_id|int8||否|属性ID|
|attr_up|int8||否|上级ID|
|site_id|int8||否|网站ID【枚举】：21世纪|
|sub_id|int8||否|学科ID|
|grade_type|int8||否|年级类型【枚举】：1一年级、2二年级..|
|term_type|int8||否|学期类型【枚举】：1上学期、2下学期|
|attr_type|int8||否|属性类型【枚举】：1知识点、2章节、3题型|
|attr_code|varchar||否|知识点编码|
|attr_name|varchar||否|知识点名称|
|status|int8||否|状态：-1停用、0待抓取、1正常|
|tree_path|varchar||否|树路径|
|tree_up|varchar||否|树上级编码|
|tree_lev|int8||否|树级别：lev|
|tree_leaf|int8||否|树叶子：0不是、1是|
|tree_sort|int8||否|树排序|
|time_update|timestamp||否|更新时间|
|time_create|timestamp||否|添加时间|
