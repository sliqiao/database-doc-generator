# tk_que(tk_que)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|que_id|int8||否|题目ID|
|site_id|int8||否|网站ID|
|que_code|varchar||否|题目编码|
|que_type|int8||否|题型【字典】：选择题、填空题..|
|que_types|int8||否|题型【字典】：1-7类|
|sub_id|int8||否|学科ID|
|title|text||否|题干|
|num_option|int8||否|选项|
|answer_img|varchar||否|答案图片|
|answer|text||否|标准答案|
|analysis_img|varchar||否|解析图片|
|analysis|text||否|解析|
|que_up|int8||否|一题多个小题时,主题目的编号(类似阅读理解)|
|sort_up|int8||否|题目排序：一级题目没有排序，从1开始，默认0|
|dift|int8||否|难度【枚举】：0未定义、1容易、3普通、5困难|
|belong_org|int8||否|系统题库|
|belong_user|int8||否|所属人员|
|rule|varchar||否|判分规则|
|audit_user|int8||否|审核人|
|audit_time|timestamp||否|审核时间|
|audit_status|int8||否|审核状态：-1审核不通过、0待审、1审核通过|
|status|int8||否|状态：-1停用、0草稿、1正常|
|remark|varchar||否|备注|
|time_update|timestamp||否|更新时间|
|time_create|timestamp||否|添加时间|
|grade|int8||否|null|
|score|numeric||是|null|
|mistake_type|_int8||是|错误类型|
|answer2|text||是|null|
|area|varchar||是|null|
|year|int4||是|null|
|source|varchar||是|null|
|papertype|varchar||是|null|
|rule_type_arr|_int4||是|多选判分规则 11：选对但不全，12：每选对1个，21：有选错的，22：每选错1个，3：按不同选项判分|
|score_arr|_numeric||是|多选判分规则对应分值|
|latex_analysis_img|varchar||是|latex生成的解析图片|
|latex_answer_img|varchar||是|latex生成的答案图片|
|latex_title_img|varchar||是|latex生成的大题题干图片|
|cognitive_level|int8||是|认知层级|
|subject_literacy|int8||是|学科素养|
|literacy_level|int8||是|素养水平|
|capability_point|int8||是|能力点|
|listen_template|int4||是|听写模板 0不是，1是|
|answer_type|int4||是|题目答案类型:0.正常   1.填空题专用(表示多空的答案可以乱序)|
