# 记录题目AI识别后的作答区域(homework_que_position)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|tk_pap_id|int8||否|tk_pap_id|
|tk_que_id|int8||否|题目ID|
|tk_ans_cell_id|int8||否|tk_ans_cell主键|
|model_pic_res_id|varchar||否|题目模板图片的ID|
|model_pic_res_path|varchar||否|题目模板图片资源地址|
|sort_no|int4||否|一个题目多个cell时的排序|
|create_time|timestamp||否|null|
|update_time|timestamp||否|null|
|multi_tk_position|varchar||是|多空位置（相对于模板图）|
