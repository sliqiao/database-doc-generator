# exam_wk_cell(exam_wk_cell)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_cell_id|int8||否|答案编号|
|wk_region_id|int8||否|null|
|wk_page_id|int8||否|null|
|res_id|varchar||否|答案图片地址|
|content|varchar||否|答案内容|
|content_manu|varchar||否|null|
|sort_no|numeric||否|null|
|status|int8||否|状态：-1 作废、0待识别、1已识别，2待重裁 |
|cell_id|int8||否|null|
|time_create|timestamp||否|新增时间|
|time_update|timestamp||否|修改时间|
|check_status|int4||是|null|
|max_thresh_value|numeric||是|null|
|is_diff|int4||是|null|
|pap_id|int8||是|null|
|test_id|int8||是|null|
