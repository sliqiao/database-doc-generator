# que_article(que_article)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|art_id|int8||否|文章编号|
|art_code|varchar||是|试卷编号6+section2+阅读1+文章序号1|
|read_id|int8||否|阅读编号|
|title|varchar||否|标题|
|title_cn|varchar||否|题目译文|
|content|varchar||否|内容|
|content_cn|varchar||是|中文译文|
|note_head|varchar||是|前注|
|note_below|varchar||是|尾注|
|source|varchar||是|出处|
|theme|varchar||是|主题|
|sort_no|int4||是|阅读内排序，从小到大|
|time_update|timestamp||是|更新时间|
