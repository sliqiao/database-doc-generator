# homework_visit(homework_visit)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|visit_id|int8||否|主键id|
|homework_id|int8||否|作业id|
|tea_id|int8||否|教师id|
|class_id|int8||否|班级id|
|grade_id|int8||否|年级id|
|school_id|int8||否|学校id|
|token|varchar||否|令牌|
|session_id|varchar||是|会话id|
|type|int4||否|访问类型,1-查看报告|
|start_time|timestamp||否|第一次汇报的开始时间|
|end_time|timestamp||是|最后一次汇报的结束时间|
|receive_time|timestamp||是|最后一次汇报服务端收到的时间|
|sum_time|int4||否|统计的累加时间,单位秒|
|seqno|int4||否|一次访问历史中多次汇报的序列号,按1递增|
|devices|varchar||是|访问使用的终端|
|create_time|timestamp||否|数据创建的时间|
|update_time|timestamp||是|数据最后修改的时间|
