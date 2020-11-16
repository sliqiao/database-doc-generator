# 用户-课程包-考核成绩记录表(eer_student_package_record)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|answer_flag|int2||是|是否正确答案（0：否；1：是）|
|complete_date|date||是|完成时间|
|package_word_id|int8||是|关联课程包-单词表（course_package_word）id|
|student_id|int8||是|关联学生表（student）id|
|is_remember|int2||是|背诵模式下，是否已掌握，0表示没有，1表示已掌握|
|key_words|int2||是|背诵模式下，是否是重点词汇，0表示否，1表示是|
|exam_remember|int2||是|(由于和specll_check重复，作废)拼写考核中是否掌握，0表示未掌握，1表示已掌握|
|mean_check|int2||是|单词在英文选义考核中是否通过0表示未通过，1表示已通过|
|dict_check|int2||是|单词在中文选词选义考核中是否通过0表示未通过，1表示已通过|
|listen_check|int2||是|听写考核时是否记住，0表示未记住，1表示已记住|
|spell_check|int2||是|拼写考核时是否记住，0表示未记住，1表示已记住|
|temp_exam_remember|int2||是|考试时的单词状态，临时存储，0表示未记住，1表示已记住|
|temp_mean_check|int2||是|考核英文选意单词状态，0表示未记住，1表示已记住|
|temp_dict_check|int2||是|考核中文选词单词状态，0表示未记住，1表示已记住|
|temp_listen_check|int2||是|考核听写单词状态，0表示未记住，1表示已记住|
|temp_spell_check|int2||是|考核拼写单词状态，0表示未记住，1表示已记住|
