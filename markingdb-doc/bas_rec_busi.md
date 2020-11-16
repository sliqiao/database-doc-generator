# bas_rec_busi(bas_rec_busi)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|guids|varchar||否|业务GUIDS（GUIDS、REC_ID、REC_TP联合唯一）|
|rec_id|varchar||否|资源ID|
|rec_tp|varchar||是|附件的文件类型|
|res_desc|varchar||是|null|
|sort_id|int4||是|null|
|user_id|int8||是|null|
|time_update|timestamp||是|null|
