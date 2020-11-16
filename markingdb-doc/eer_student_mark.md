# 用户-考试成绩表(eer_student_mark)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|answer_flag|int2||是|是否正确答案（0：否；1：是）|
|complete_date|date||是|完成时间|
|right_num|int2||是|正确单词数|
|right_percent|int2||是|正确百分比|
|score|int2||是|最终得分|
|package_word_id|int8||是|关联课程包-单词表（course_package_word）id|
|student_id|int8||是|关联学生表（student）id|
