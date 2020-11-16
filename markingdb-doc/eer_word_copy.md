# 单词表(eer_word_copy)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|name|varchar||是|null|
|explain_cn|varchar||是|中文释义|
|explain_en|varchar||是|英文释义|
|example|varchar||是|例子|
|similars|varchar||是|近义词|
|standard_en|varchar||是|英音音标|
|standard_am|varchar||是|美音音标|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|type|varchar||是|词性|
|voice_en|varchar||是|英音音标发音（存音频url）|
|voice_am|varchar||是|美音音标发音（存音频url）|
|voice_people|varchar||是|人声音轨|
