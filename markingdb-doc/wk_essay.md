# wk_essay(wk_essay)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|wk_id|int8||否|null|
|que_id|int8||否|null|
|user_id|int8||否|评分人|
|score|numeric||否|老师评分|
|score_intel|numeric||否|智能评分|
|rule|int8||否|评分标准：系统编码|
|comment|varchar||否|评语|
|time_update|timestamp||否|null|
