# 记录这次考试的学生的考场位置(exam_seats_stu)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|seat_id|int8||否|null|
|room_id|int8||否|null|
|test_id|int8||否|null|
|seat_no|int4||否|在这个考场的座位号|
|stu_id|int8||否|null|
|ticket_no|varchar||是|null|
|update_time|timestamp||否|null|
|send_to_wechat|int4||否|学生作业推送到微信 0未推送1推送|
|class_id|int8||是|学生参加考试所在的班级Id|
