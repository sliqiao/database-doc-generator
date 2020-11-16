# 作业报告日志表(homework_report_log)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|stu_id|int8||是|学生ID|
|type|int2||是|记录类型(1:微信作业报告详情页提示)|
|remark|varchar||是|记录备注|
