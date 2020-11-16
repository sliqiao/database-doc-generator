# homework_create_info(homework_create_info)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|create_info_id|int8||否|作业生成信息主键|
|download_type|int4||否|下载类型 0单页、1全册、-1无意义|
|jf_id|int8||否|对应教辅ID|
|class_id|int8||是|对应班级ID|
|class_name|varchar||是|对应班级名称|
|stu_num|int4||否|学生数量|
|tk_paper_id|int8||是|对应作业（试卷）ID|
|create_status|int4||否|生成状态 0生成中、1生成成功、2生成失败|
|create_time|timestamp||是|创建时间  (记录创建的时间)|
|download_url|varchar||是|下载链接|
|school_id|int8||是|对应学校ID|
|create_user_id|int8||否|创建生成用户的ID|
|name_content|varchar||是|对应教辅名称|
|complete_time|timestamp||是|生成完成时间（该记录对应pdf生成完成的时间）|
|class_ids|varchar||是|classId集合|
|grade_names|varchar||是|年级名称集合|
|batch_no|varchar||是|批次号|
|jf_mc|varchar||是|教辅名称|
|paper_down_type|int4||是|我的试卷下载类型：0学生pdf、1教师卷、2学生、教师卷|
