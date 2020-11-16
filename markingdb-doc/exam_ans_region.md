# 对一个答题卡，划分各个切割区域，每个区域有可能有多个单元格，按先后顺序一起组合显示，每个区域为一个显示单元，一个题按一个区域来显示(exam_ans_region)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|region_id|int8||否|null|
|sheet_id|int8||否|null|
|region_type|int4||否|null|
|page_id|int8||否|主要用于学生考场号这些，每个版面都有的区域，对于题目的这类，默认为0|
|num_cell|int4||否|null|
|ques_no|int8||否|如果类型是题目区域，这个值有意义|
|update_time|timestamp||否|null|
