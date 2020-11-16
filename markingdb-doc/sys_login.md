# sys_login(sys_login)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|dbid|int8||否|null|
|user_id|int8||是|null|
|land_dir|int4||是|1登录
-1超时
0退出|
|stamp|timestamp||是|null|
|online_time|int8||是|null|
|ip|varchar||是|null|
|mac|varchar||是|null|
|port|varchar||是|null|
|os|varchar||是|null|
|os_ver|varchar||是|null|
|prog_cate|varchar||是|null|
|prog|varchar||是|客户端系统类型：IE、ios、android|
|prog_ver|varchar||是|客户端系统版本：maxthon、ie、火狐、ios7|
|dev_brand|varchar||是|设备品牌：小米、三星、华为|
|dev_type|varchar||是|null|
|dev_id|varchar||是|针对移动端通讯设备ID|
|pattern|varchar||是|null|
|tid|varchar||是|null|
|user_role|varchar||是|null|
|client_app|varchar||是|null|
