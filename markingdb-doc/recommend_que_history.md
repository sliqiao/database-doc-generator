# 记录每个学生的推题历史，推过的题目不再推送(recommend_que_history)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|test_id|int8||否|null|
|subject_id|int8||否|null|
|stu_id|int8||否|null|
|que_id|int8||否|对应题库的题目ID|
|time_update|timestamp||否|null|
