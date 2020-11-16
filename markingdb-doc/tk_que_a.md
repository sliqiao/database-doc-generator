# tk_que_a(tk_que_a)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|que_code|varchar||否|题目编码|
|que_id|int8||否|题目ID|
|que_type|int8||否|题型【字典】：选择题、填空题..|
|type_name|varchar||否|null|
|que_ability|int8||否|题型【字典】：简单应用、理解和掌握..|
|ability_name|varchar||否|null|
|que_dift|int8||否|题型【字典】：较易、一般..|
|dift_name|varchar||否|null|
|time_create|timestamp||否|添加时间|
|title|text||否|题干|
|answer|text||否|标准答案|
|analysis|text||否|解析|
|sub_id|int8||否|学科ID|
|is_download|int8||是|是否下载，0未下载，1已下载|
