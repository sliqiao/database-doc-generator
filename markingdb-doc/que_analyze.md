# que_analyze(que_analyze)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|ana_id|int8||否|ANA_ID|
|busi_id|int8||否|业务编号：题目ID、文章ID、选项ID|
|ana_type|int8||否|解析类型：1文本、2音频、3视频|
|content|varchar||是|内容|
|org_id|int8||是|机构ID|
|sort_no|int4||是|机构内部及排序|
|status|int4||是|状态：-1停用、0草稿、1启用|
|time_update|timestamp||是|更新时间|
