# AI接口返回异常数据记录(homework_ai_error)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|type|varchar||否|Compress图片压缩; BlankPic是否空白图片; UnderlineFind填空题作答区域坐标识别; HandWrite手写体分离; Recognition是否作答;|
|access_url|varchar||否|访问AI的地址|
|params|varchar||是|访问参数，太长可以不存|
|return_msg|varchar||是|AI接口返回数据|
|business_id|int8||是|业务ID，每个不同的类型对应不同的表ID|
|remarks|varchar||是|null|
|create_time|timestamp||否|null|
