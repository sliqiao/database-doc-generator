# wrong_question_book(wrong_question_book)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wq_id|int8||否|主键唯一|
|que_id|int8||否|题目的id|
|pap_id|int8||是|试卷id|
|tk_que_id|int8||是|题库中的题目id，que_source_type为1是才有|
|cece_pap_id|int8||是|自组卷id|
|test_name|varchar||是|考试名称|
|full_score|float8||是|满分|
|score|float8||是|得分|
|stu_ans_img|varchar||是|答案图片，以，分割|
|is_auto|int4||是|是否是客观题，1为是0为否|
|content|varchar||是|机器识别答案|
|content_manu|varchar||是|人工校验后的答案|
|avage_score|float8||是|班级平均分|
|que_img|varchar||是|题干的图片地址，queSourceType为0时才有,以，分开|
|ana_img|varchar||是|题目解析的地址，以，分开,queSourceType为0时才有|
|que_title|text||是|题目的主干，queSourceType为1时才有|
|que_name|varchar||是|题目序号|
|status|int4||是|状态，是否已经被添加到错题本，默认为0(否)|
|stu_id|int8||否|学生id|
|que_type|int8||是|题目类型|
|correct_ans|varchar||是|正确答案|
|que_source_type|int4||是|题目题干的来源地址  默认0表示上传试卷，1表示从自组卷|
|test_id|int8||是|题目所属考试id|
|test_type|int4||否|0-考试，1-作业|
