# 用户-课程包-考核通关记录表(eer_student_package_word)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|package_id|int8||是|关联课程包表（course_package）id|
|mean_status|int2||是|英文选义考核状态（0：未通过；1：通过）|
|dict_status|int2||是|中文选词考核状态（0：未通过；1：通过）|
|spell_status|int2||是|拼写填空考核状态（0：未通过；1：通过）|
|listen_status|int2||是|听音辨析考核状态（0：未通过；1：通过）|
|student_id|int8||是|null|
|is_finished_exam|int2||是|学生是否完成该包的考试任务，0表示没有，1表示已完成|
|type|int2||是| 背诵模式（0：普通模式；1：图文模式；2：全部）|
|exam_date|date||是|考试时间|
|total_right|int2||是|正确单词数|
|accuracy|varchar||是|正确率|
|score|int2||是|得分|
