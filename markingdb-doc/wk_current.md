# 限制条件：
1、
2、当作业开始时新增记录
3、当作业结束时删除记录
4、作业过程中，每提交一题，修改时间最后的题目编号、数量、section编号等(wk_current)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_id|int8||否|null|
|user_id|int8||否|null|
|wk_type|int8||否|null|
|pap_id|int8||否|null|
|sec_id|int8||是|null|
|que_id|int8||是|null|
|time_end|timestamp||是|null|
