# exam_user_student(exam_user_student)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|user_id|int8||否|用户编号|
|school_id|int8||否|null|
|sid|varchar||否|学号|
|name|varchar||否|真实姓名|
|name_old|varchar||否|曾用名|
|sex|int8||否|默认-1未知，0女，1男|
|status|int8||否|状态：0无效、1正常|
|remark|varchar||否|备注|
|update_time|timestamp||否|更新时间|
|org_stu_id|varchar||是|null|
|mobile|varchar||是|null|
|user_passwd|varchar||是|null|
|mobile_stu|varchar||是|null|
|head_url|varchar||是|头像url|
|card_id|varchar||是|null|
|is_people_voice|int2||是|是否人声发音，0，否，1，是|
|is_american_voice|int2||是|是否美式发音，0，否，1，是|
