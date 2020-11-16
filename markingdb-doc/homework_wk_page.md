# 一个作业对应多个原始扫描图片(homework_wk_page)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_page_id|int8||否|ID|
|homework_wk_sheet_id|int8||否|阅卷答题卡id|
|sheet_id|int8||否|(模板)答题卡id|
|stu_id|int8||否|学生ID|
|page_id|int8||否|版面id|
|page_no|int4||否|版面顺序|
|res_id|varchar||是|定位后的图片|
|res_id_ori|varchar||是|上传的原图|
|machine_id|varchar||是|上传图片的机器编码|
|school_id|int8||否|学校ID|
|scanning_status|int4||否|扫描识别状态 0正常,1二维码识别失败，2图片定位失败|
|print_status|int4||否|原卷打印状态：0未打印，1已打印|
|update_time|timestamp||否|null|
|create_time|timestamp||否|null|
|status|int4||否|0正常，1删除|
|last_upload_from|int4||是|最后一次上传的来源：0机器扫描,1手机拍照|
|last_upload_time|timestamp||是|最后一次上传解析的时间|
|tk_paper_id|int8||否|tk_paper_id|
|class_id|int8||否|班级id|
