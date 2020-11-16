# 一个区域划分多个单元格(tk_ans_cell)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|cell_id|int8||否|null|
|region_id|int8||否|null|
|page_id|int8||否|单元格不能跨越版面|
|sort_no|numeric||否|null|
|top_x|int4||否|null|
|top_y|int4||否|null|
|bottom_x|int4||否|null|
|bottom_y|int4||否|null|
|update_time|timestamp||否|null|
|option_size|int4||是|null|
|block_id|int8||是|null|
|option_w|int4||是|null|
|option_h|int4||是|null|
|option_th|int4||是|null|
|page_no|int4||否|坐标点所在页码|
|correcting_cells|varchar||是|客观题题干校正区域|
