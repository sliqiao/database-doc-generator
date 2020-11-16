# QQID、微信ID、支付宝ID只用于登陆，不提供给用户编辑，SYS_USER表中的email，QQID、微信web、微信mobile、微信ID、qq等字段将不在使用(sys_user_contact_his)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|contact|varchar||否|null|
|user_status|int4||否|状态：0申请、1正常|
|user_id|int8||否|null|
|contact_type|int4||否|1、邮箱 2、手机 3、qq 4、qqID 5、微信ID 6、支付宝ID|
|is_check|int4||否|null|
|update_time|timestamp||否|null|
