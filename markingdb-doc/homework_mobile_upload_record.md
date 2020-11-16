# 手机上传文件记录(homework_mobile_upload_record)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|rec_id|varchar||否|资源id|
|rec_path|varchar||否|资源路径|
|school_id|int8||否|学校id，从哪个学校上传过来的|
|status|int4||否|状态0处理中，1二维码识别失败，2图片定位失败，3处理完毕|
|wk_page_id|int8||是|homework_wk_page表id|
|create_time|timestamp||否|null|
|update_time|timestamp||是|null|
