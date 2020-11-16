# exam_user_teacher(exam_user_teacher)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|uoid|int8||否|用户流水号|
|user_id|int8||否|用户编号|
|school_id|int8||否|机构编号，这个字段作废，先用登录人员信息里面取|
|wid|varchar||是|工号|
|name|varchar||是|真实姓名|
|name_py|varchar||是|null|
|letter_first|varchar||是|null|
|gender|int8||否|默认-1未知，0女，1男|
|birthday|varchar||是|出生日期|
|job_title|varchar||是|职称|
|job_date|varchar||是|参加工作时间|
|mobile|varchar||是|联系电话|
|email|varchar||是|EMAIL|
|status|int8||否|状态：0无效、1正常|
|job_nature|int4||否|1全职 2 兼职 3临时|
|remark|varchar||是|备注|
|time_update|timestamp||否|更新时间|
|user_passwd|varchar||是|账户密码|
|duty|varchar||是|null|
|user_type|int4||是|0 普通老师 1 admin 2 学校管理员|
|region_code|varchar||是|null|
|source|int4||是|null|
|openid|varchar||是|微信openid|
