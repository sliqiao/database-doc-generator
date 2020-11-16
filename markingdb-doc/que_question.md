# que_question(que_question)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|que_id|int8||否|null|
|que_code|varchar||是|null|
|src|int8||否|见字典表|
|title|varchar||是|题目标题|
|content|varchar||否|题目内容|
|content_cn|varchar||是|题目内容中文|
|note_head|varchar||否|前注|
|note_below|varchar||否|尾注|
|read_id|int8||是|0不属于文章|
|test_type|int8||是|见字典表|
|subject|int8||是|见字典表|
|grade|int8||否|所属年级|
|que_type|int8||是|（枚举，和考试类型无关）这个地方需要详细列举，托福就有很多种题型（根据不同的学科，不同的题型，需要穷举）|
|num_right|int4||否|正确答案数量：|
|num_ans|int4||否|选项数量|
|len_sec|int4||否|标准时长秒，默认60秒|
|lev|int4||否|官方难度值，根据考试科目、来源来寄送|
|lev_dk|int4||否|公司自定义难度值|
|ans|varchar||是|选择题，填id；填空题用如存在多答案用英文逗号隔开；如果是多纬答案，一级用逗号，二级用||
|ans_rule|varchar||是|题目规则：存数异常展示的题目规则，json格式|
|ans_order|int4||否|答案是否有顺序：0无序、1有序|
|num_file|int4||否|附件数量|
|art_desc|varchar||是|参考TOEFL的阅读|
|time_publish|timestamp||是|SRC=1就是考试日期、SRC=2就是官方日期、SRC=3添加日期|
|org_id|int8||是|默认为0，表示为爱赛达课所有，每个机构可以有自己的题目，只对这个机构自己范围可见。|
|user_create|int8||是|null|
|time_create|timestamp||是|null|
|status|int4||是|状态：-1停用、0为未发布，1为已发布|
|score|numeric||是|分数|
|time_update|timestamp||是|null|
|read_top|int8||否|阅读顶级ID|
|sort_no|int8||是|阅读(READ_ID)下的排序[2016.7.26增加]|
