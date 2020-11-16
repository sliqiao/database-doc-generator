# homework_print_task(homework_print_task)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|print_task_id|int8||否|主键|
|download_type|int4||否|下载类型 0单页、1全册、2多章节|
|jf_id|int8||否|对应教辅ID|
|school_id|int8||否|对应学校ID|
|class_ids|varchar||否|对应班级ID集合|
|class_names|varchar||否|对应班级名称集合|
|paper_id|int8||是|对应作业ID|
|print_copies|int4||否|打印份数|
|print_status|int4||否|打印状态（0:未打印  1:PDF准备好  2:PDF未准备好 3:已打印）|
|download_url|varchar||是|下载链接|
|name_content|varchar||是|作业/试卷名称|
|print_time|timestamp||是|打印时间|
|print_shop_user_id|int8||是|创建时间|
|create_time|timestamp||是|创建时间  (记录创建的时间)|
|create_user_id|int8||是|创建生成用户ID|
|create_user_name|varchar||是|创建生成用户名称|
|subject_names|varchar||是|科目名称集合|
|grade_names|varchar||是|年级名称集合|
|batch_no|varchar||是|批次号|
|jf_mc|varchar||是|教辅名称|
|paper_down_type|int4||是|我的试卷下载类型：0学生pdf、1教师卷、2学生、教师卷|
