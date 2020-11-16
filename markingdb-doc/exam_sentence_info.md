# exam_sentence_info(exam_sentence_info)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|sentence_id|int8||否|主键|
|content_true|varchar||否|正确例句|
|create_time|timestamp||否|创建时间|
|grade_id|int8||是|对应的年级id|
|status|int2||否|0:正常；1：删除 ; 2:已标注|
|article_id|int8||否|对应文章id|
