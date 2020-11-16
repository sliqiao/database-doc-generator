# markingdb数据库设计文档

#### tiku_type_subject(tiku_type_subject)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||是|null|
|tiku_type_id|int8||否|null|
|subject_id|int8||否|null|
#### zj_question_12(zj_question_12)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time|timestamp||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_13(zj_question_13)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time|timestamp||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_14(zj_question_14)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|#### exam_composition_mark(exam_composition_mark)int8||是|null|
|ability_name|
varchar|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar|||是mark_id||int8|null|
|time|timestamp||否||null否|null|
|
|question_body|text|||info_id|否int8||null|
||question_answer|否|text|null|
|是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
||grade_id|subject|int8|int8||否|年级id|
|topic_type||int4是||null|
|否|题材类型|
|score|numeric||#### zj_question_15(zj_question_15)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |否|
| ---- | ---- | ---- | ---- | ---- |
分数|
||teacher_id|id|int8|int8||否||老师id否|null|
|
|question_zu_juan_id|int8|||create_time|是|timestampnull|
||question_type_id|int8|||否|是|创建时间null|
|
||question_type_name|varchar|status||int4|是|null|
#### hr_menu(hr_menu)
|ability_id|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
||menu_id|varchar||否|否菜单编号|
||状态：0正常-1删除up_id||
varchar|||否|update_time上级菜单编号||
timestamp||menu_name|varchar|||否否||菜单名称更新时间|
|
||comment|varchar|sub_id|varchar|||否|否节点编号||
评语:默认,逗号隔开|lev|
|int4||否|级别|
|sort|int4|#### exam_correct_record(exam_correct_record)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|record_id|int8||否|null|
|que_id|int8||否|null|
|wk_que_id|int8||否|null|
|check_seq|int4||否|null|
|tech_id|int8||否|null|
|arbitration|int4||否|null|
|update_time|timestamp||否|null|
|score|numeric||否|null|
|test_id|int8||否|null|
|marking_sort|int4||是|null|
|que_group_id|int8||是|题块id|
int8||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time|timestamp||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_16(zj_question_16)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time|timestamp||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_17(zj_question_17)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|#### exam_report_test_joint(exam_report_test_joint)
question_zu_juan_id|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
int8||是|null||
id||question_type_id|int8||是|null|
int8||question_type_name|varchar||||否|null|
否是||排序null|
|
|ability_id|int8||是|null|
|ability_name|varchar||status|int4||是|null|
||否|question_different_id|状态：1正常、0停用|
#### zj_question_category_13(zj_question_category_13)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |int8|
| ---- | ---- | ---- | ---- | ---- |
|是|null||
id||int8|question_different_name||varchar|否|null|
||是question_zu_juan_id||null|
int8||time|||是|act_idnull||
int8|subject_zu_juan_id|int8||是|null|
||type_id|int8|否|null|
||是|timestamp|nullcreate_time||
timestamp|||type否|null|
|max_score|numeric||int8||否|||是null||
null|
||min_scorepath_ids||numeric||否|null|
varchar||param_code|是||null|
varchar||否||null否|
|null|question_body|text|||
否||null#### zj_question_category_14(zj_question_category_14)param_value
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |varchar|
| ---- | ---- | ---- | ---- | ---- ||
|
否|null|
|||id|scoreint8||numeric||否|否|null|
||null|
|question_zu_juan_id|int8|question_answer||是|null|
|subject_zu_juan_id|int8|stu_num|int4|||是|否|null|
null|
|type_id|int8||是|null|
|type|int8||是|null#### exam_review_conf(exam_review_conf)|

|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
path_ids|| ---- | ---- | ---- | ---- | ---- |varchar
||是|null|
|que_id|int8||否|null|
#### zj_question_category_15(zj_question_category_15)|
test_id|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
int8| ---- | ---- | ---- | ---- | ---- |
||id|int8|||否|否null||
null||
question_zu_juan_id||paper_idint8|||是|null|
int8||subject_zu_juan_id|int8|||是|否null|
||nulltype_id|
|int8||是|null|
|count||int4|type||int8|否||是null||
null|
|arbitrators||path_idsint8||varchar|||否是||nullnull|
|
|error_value|numeric||否|null|
#### zj_question_category_16(zj_question_category_16)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
update_time|| ---- | ---- | ---- | ---- | ---- |
timestamp|||id否||int8|null|
|否|null||
arbitrators2||question_zu_juan_id_int8||int8||是|null|
|是|null|
|subject_zu_juan_id|int8||是|null|
|type_id|int8||是|null|
|type|int8||是|null|
|path_ids|varchar||是|null|
#### zj_question_category_17(zj_question_category_17)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|subject_zu_juan_id|int8||是|null|
|type_id|int8||是|null|
|type|int8||是|null|
|path_ids|varchar||是|null|
#### zj_question_category_18(zj_question_category_18)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|subject_zu_juan_id|int8||是|null|
|type_id|int8|text|是|null|
||type|int8||是||null是|
|null|
|question_parse||textpath_ids|||varchar是||null|
||是is_download||null|
int8|#### zj_question_category_19(zj_question_category_19)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8|||是|null|
|subject|int8||是|null|
否|null|
|#### zj_question_18(zj_question_18)
question_zu_juan_id|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
int8|| ---- | ---- | ---- | ---- | ---- |
|是|null|
||subject_zu_juan_id|idint8|||int8|是|null|
|否|null|
||question_zu_juan_idtype_id||int8||是|null|
int8||question_type_id|是|null|
|int8||type|int8|||是|是|null|
null|
||question_type_name|path_idsvarchar||varchar|||是|是|null|
null|
|ability_id|int8||是|null|
|ability_name|varchar|#### zj_question_category_2(zj_question_category_2)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|是|null|
|question_different_id||int8|id||int8|是||null|
否||question_different_namenull|
||varchar|question_zu_juan_id||int8|是|null|
|是||nulltime||
timestamp||subject_zu_juan_id|int8|||否是||null|
null|
|type_id|int8|||question_body是||null|
text||type|int8|||否|null是|
|null||
question_answer||text|path_ids|varchar|||是是||null|
#### zj_question_category_20(zj_question_category_20)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|subject_zu_juan_id|int8||是|null|
|type_id|int8||是|null|
|type|int8||是|null|
|path_ids|varchar|null|
|是||null|
question_parse|text||是|null|
|is_download|int8||是|null|
#### zj_question_category_21(zj_question_category_21)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |subject|
int8||是|null||
id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|subject_zu_juan_id#### zj_question_19(zj_question_19)|
int8|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- ||
是|null|
|type_id||idint8|||int8是||null|
||否type||null|
int8||question_zu_juan_id||是int8||null|
|是||nullpath_ids|
|varchar|||是question_type_id||int8|null|
|是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time|timestamp||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_2(zj_question_2)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
#### zj_question_4(zj_question_4)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|ability_id|int8||是|null|
||idability_name||int8||否|null|
varchar||question_zu_juan_id||是int8||null|
||是question_different_id||nullint8|
||question_type_id||是|int8null||
|是||nullquestion_different_name|
|varchar||question_type_name||varchar|是|null|
||time是||timestampnull||
||否|ability_id|nullint8|
|||是question_body||nulltext||
|否||ability_namenull|
||varcharquestion_answer||text|||是是||null|
|question_different_id|int8|null|
|是|null|
|question_different_name|varchar||是|null|
|time|timestamp||否|null|
|question_body|text||否|null|
|question_answer|text|question_parse|text||是|null|
|is_download|int8||||是|null|
|question_parse|text||是|null|
|is_download|int8|是|null|
|是|null|
|subject||int8|subject|int8||是||null|
是|null|
#### zj_question_5(zj_question_5)#### zj_question_20(zj_question_20)

| 列名   | 类型   | KEY  | 可否为空 | 注释   || 列名   | 类型   | KEY  | 可否为空 | 注释   |

| ---- | ---- | ---- | ---- | ---- || ---- | ---- | ---- | ---- | ---- |

|id||int8id||int8|||否否||null|
null||
question_zu_juan_id||int8|question_zu_juan_id|int8||是|null|
|是||null|
question_type_id||question_type_id|int8int8||||是是||null|
null||
question_type_name||question_type_namevarchar||varchar||是||null是||
null|
|ability_id||int8ability_id||int8|||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time是||timestamp|null||
否|null|
|ability_name||question_bodyvarchar||text||是||null否|
|null|
|question_different_id||int8|question_answer|text||是|null|
||是question_parse||null|
text|||question_different_name是||varchar|null|
|是||is_download|nullint8|
|||time是||timestamp|null|
|否||null|
subject||question_body|int8|text||是||否|nullnull|
|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_6(zj_question_6)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time|timestamp||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_7(zj_question_7)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar||是|null|
|question_different_id#### zj_question_21(zj_question_21)
| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
| ---- | ---- | ---- | ---- | ---- |
int8||是|null|
||question_different_name|idvarchar|||int8是||null|
|否|null|
|time||question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time|timestamp||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_22(zj_question_22)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time|timestamp||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_23(zj_question_23)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8|timestamp|是||null|
|question_type_name|varchar|||否|null|
是||question_body|null|
text||ability_id|否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
|#### zj_question_8(zj_question_8)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |int8
||id|int8||否|null|
|question_zu_juan_id||int8|是||是|null|
null|
|question_type_id|int8||是||null|
ability_name|varchar||是|null|
||question_different_id|question_type_name|int8|varchar|||是|null|
是||ability_id|int8||null|
是|null|
|question_different_name||varchar|ability_name|varchar|||是|null|
|是|null|
question_different_id|time|int8||timestamp||是||否|null|
null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_24(zj_question_24)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time|timestamp||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_25(zj_question_25)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar|||question_different_name|varchar|是||null|
是|null|
|question_different_id||int8|time|timestamp|是|null|
||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
|question_different_name|varchar|#### zj_question_9(zj_question_9)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
||是id||int8|null|
|否|null|
||timequestion_zu_juan_id|int8||timestamp||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_26(zj_question_26)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
||question_zu_juan_id是|null||
int8||是||question_type_id|null|
int8|||question_type_id|是|null|
int8||question_type_name|varchar|||是|null|
是|ability_id|int8|||null|
是||null|
question_type_name|varchar||ability_name|varchar|||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time|timestamp||否|null|
#### 一个区域划分多个单元格(tk_ans_cell)
|question_body|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
text||否|null|
||question_answer|cell_id|text|int8||是|null|
|question_parse||text|否||是|null|
null||
is_download|int8|||region_id|int8|是||否|null|
null|
||subject|page_id|int8|int8||否||是|null|
单元格不能跨越版面|
|sort_no|numeric||否|null|
|top_x|int4||否|#### zj_question_category_1(zj_question_category_1)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
null||
id|int8|||top_y|int4||否|null|
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
#### 这个这需要把FileCenter也部署到新东方(tk_ans_page)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|page_id|int8||否|null|
|sheet_id|int8||否|null|
|page_no|int4||否|null|
|res_id|varchar||否|校正之后的图片资源|
|res_id_ori|varchar||否|null|
|top_x|int4||否|null|
|top_y|int4||否|null|
|bottom_x|int4||否|null|
|bottom_y|int4||否|null|
|length|int4||否|null|
|width|int4||否|null|
|update_time|timestamp||否|null|
是|null|
|ability_id|int8|#### 对一个答题卡，划分各个切割区域，每个区域有可能有多个单元格，按先后顺序一起组合显示，每个区域为一个显示单元，一个题按一个区域来显示(tk_ans_region)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
#### 记录双评的历史(exam_review_record)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
||region_id|int8|region_id|int8||否||否|nullnull|
|
||current_timessheet_id||int4int8||||否|否|nullnull|
|
||region_typenoted_times||int4int4||||否否||nullnull|
|
|page_id||teacher_aint8||int8|||否否||null主要用于学生考场号这些，每个版面都有的区域，对于题目的这类，默认为0|
|
||score_anum_cell||numeric|int4|||否否||null|
null||
teacher_b|int8||否|null|
|score_b|numeric||否||nullques_no|
|int8|||score_ar否||numeric如果类型是题目区域，这个值有意义||
||否update_time||null|
|arbitratorstimestamp||int8|||否否||null|
null|
|update_time|timestamp||否|null|
#### 教辅目录信息表(jf_content)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
#### 一个试卷可以对应多个答题卡，导入的时候选择答题卡，答题卡对应试卷的a、b或者c
一个答题卡有多个版面，每个版面有个多个区域，一个区域为阅卷时一起的图片，一个区域对应多个单元格。主要用于一个题跨域多个方块的地方，比如作文。(tk_ans_sheet)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |#### exam_role(exam_role)

| ---- | ---- | ---- | ---- | ---- || 列名   | 类型   | KEY  | 可否为空 | 注释   |
|
| ---- | ---- | ---- | ---- | ---- ||
sheet_id|id|int8||role_id||否|int8主键||
|create_time|timestamp||是|创建时间|
||update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|name|varchar||是|教辅目录名称|
|parent_id|int8||是|上级目录id，没有默认为0|
|sort|int2||是|同级目录排序标识|
|info_id|int8||是|关联教辅基础信息表(jf_info)主键|
|paper_id|int8||是|关联pap_paper_in表pap_id|
|update_user|int8||是|修改人id|
|listen_template|int4||是|听写模版  0不是，1是|
|load_message|text||是|导入日志信息|
#### 教辅目录视频信息表(jf_content_video)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|name|varchar||是|视频名称|
|sort|int2||是|排序标识|
|content_id|int8||是|关联jf_content表id|
|video_resource_id|varchar||是|关联bas_resource表rec_id|
|video_image_id|varchar||是|关联bas_resource表rec_id|
|description|varchar||是|视频描述|
#### 教辅信息表(jf_info)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|jf_id|int8||否|主键ID|
|stage|int4||是|学段  1：小学 2：初中 3：高中|
|subject|_int8||是|科目(多选)，exam_subject表中的subject_id|
|subject_mc|_varchar||是|与选择的科目进行对应，做冗余处理，简便查询|
|base_jc_bb|int8||是|基础教材版本，统一管理一套教材版本，在教材维护操作通过选取对应的教材版本即可|
|base_jc_bb_mc|varchar||是|基础教材版本名称|
|jc_bb|int8||是|教材版本 que_attr表中attr_type为2且attr_up=0的attr_id|
|jc_cb|_int8||是|教材册别 que_attr表中attr_type为2且attr_up等于教材版本的attr_id|
|grade|_int8||是|年级 exam_code_dirs表dir_type = 163007(年级)且sort_no与学段字段进行有一个范围对应，[1-6] 小学 [7-9]初中 [10-12] 高中|
|grade_mc|_varchar||是|年级名称|
|author|varchar||否|作者|
|jf_bc|varchar||否|版次(年月)|
|isbn|varchar||否|ISBN|
|jf_mc|varchar||否|教辅名称|
|pic_url|varchar||否|封面图片地址|
|slt_pic_url|varchar||否|封面缩略图片地址|
|create_time|timestamp||否|创建时间|
|create_user|int8||否|创建用户|
|update_time|timestamp||否|更新时间|
|update_user|int8||否|更新用户|
|delete_status|int4||否|删除状态  0：未删除 1：已删除|
|delete_time|timestamp||是|删除时间|
|jc_cb_mc|_varchar||是|教材册别名称|
#### latex_dir(latex_dir)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|tag|varchar||是|标签名称|
|latex|varchar||是|latex值|
|type|int4||是|类型 0.嵌入型 1.替换型|
#### 设备信息表(machine_info)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|machine_id|varchar||否|设备ID|
|machine_type|int4||否|设备类型，1安卓扫描仪|
|school_id|int8||否|学校ID|
|machine_name|varchar||否|机器名称|
|mark|varchar||是|备注信息|
|create_time|timestamp||否|创建时间|
|update_time|timestamp||否|更新时间|
|status|int4||否|0正常，1删除|
|notify_phone|varchar||是|负责人手机号码，用来接收通知,多个逗号分隔|
#### newt(newt)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||是|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
|time|timestamp||是|null|
|question_body|text||是|null|
|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### pap_paper(pap_paper)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pap_id|int8||否|试卷ID|
|pap_code|varchar||否|试卷编号|
|pap_name|varchar||否|试卷主标题|
|pap_subname|varchar||否|试卷副标题|
|pap_type|int8||否|试卷类型：1手工组卷、2智能组卷|
|grade|int8||否|年级|
|dift|int8||否|题目难度累计和|
|score|numeric||否|总分数|
|num_sec|int8||否|单元数|
|num_que|int8||否|题目数|
|len_min|int8||否|时长分钟|
|status_edit|int8||否|编辑状态：0未编辑、1编辑中|
|status|int8||否|状态：0草稿、1发布、-1作废|
|show_name|int8||否|显示主标题|
|show_subname|int8||否|显示副标题|
|show_zdx|int8||否|显示装订线|
|show_bmbj|int8||否|显示保密标记|
|show_xxl|int8||否|显示试卷信息栏|
|show_srl|int8||否|显示考生输入栏|
|show_yfl|int8||否|显示誊分栏|
|show_zysxl|int8||否|显示注意事项栏|
|show_jbjz|int8||否|显示卷标卷注|
|txt_bmbj|varchar||否|保密标记内容|
|txt_xxl|varchar||否|试卷信息栏内容|
|txt_srl|varchar||否|考生输入栏内容|
|txt_yfl|varchar||否|誊分栏内容|
|txt_zysxl|varchar||否|注意事项栏内容|
|txt_jbjz|varchar||否|卷标卷注内容|
|json_sheet|text||否|答题卡JSON|
|org_id|int8||否|所属机构|
|user_create|int8||否|创建人|
|time_create|timestamp||否|创建时间|
|time_update|timestamp||否|修改时间|
|status_sort|int8||否|排序状态：0未排序、1已排序|
|subject|_int8||是|null|
|pap_source|int8||否|试卷来源：1题库、2班级错题|
|has_score|int4||是|赋分标识：1有分0无分|
|custom_pap_name|int4||是|自定义试卷名称标识：1是 0否|
|custom_score|int4||是|自定义分数：1是 0否|
|pdf_url|varchar||是|组卷预览pdf|
#### pap_paper_in(pap_paper_in)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pap_id|int8||否|试卷ID|
|pap_code|varchar||否|试卷编号|
|pap_name|varchar||否|试卷主标题|
|pap_subname|varchar||否|试卷副标题|
|pap_type|int8||否|试卷类型：1手工组卷、2智能组卷|
|grade|int8||否|年级|
|subject|_int8||否|科目|
|dift|int8||否|题目难度累计和|
|score|int8||否|总分数|
|num_sec|int8||否|单元数|
|num_que|int8||否|题目数|
|len_min|int8||否|时长分钟|
|status_sort|int8||否|排序状态：0未排序、1已排序|
|status_edit|int8||否|编辑状态：0未编辑、1编辑中|
|status|int8||否|状态：0草稿、1、提交审核 2 审核通过 -1 审核不通过 -2 作废|
|org_id|int8||否|所属机构|
|user_create|int8||否|创建人|
|time_create|timestamp||否|创建时间|
|auditor|int8||否|null|
|audit_time|timestamp||否|null|
|src|int8||是|见《系统编码表》|
|region_code|varchar||是|null|
|time_publish|int8||是|null|
|tk_pap_id|int8||否|null|
|remark|varchar||是|null|
|time_update|timestamp||否|修改时间|
|type|int4||是|null|
|textbook_id|int8||是|null|
|input_type|int4||是|录入类型 0单题录入 1:试卷录入 2:老教辅录入 3:AB卷 4:附件试卷 5:新教辅|
|su_attr_id|int8||是|null|
|year|int4||是|null|
|queattr_id|varchar||是|教材来源|
|edua_name|varchar||是|Educational Assistance 教辅名称|
|user_check|int8||是|审核人|
|err_count|int8||是|null|
|jf_info_id|int8||是|教辅信息表的id|
|jf_content_id|int8||是|教辅目录的id|
|pdf_url|varchar||是|作业-卷卡一体答题卡pdf文件url|
|pap_version|int8||是|试卷ab卷版本, 0:a卷  1:b卷  2:c卷|
|mark_status|int4||是|标注状态  0 : 未领取  1: 标注中  2 :标注完成|
|user_mark_name|varchar||是|标注人的姓名|
|user_mark_id|int8||是|标注人的ID   0为没有标注.1.为admin|
|listen_template|int4||是|听写模板，0不是，1是|
否#### 组卷试卷辅助信息表(pap_paper_relation)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8|||否|null|
主键ID|
|pap_id|int8||question_zu_juan_id||否|int8组卷试卷id|
||pap_key|varchar||是|null|
|subject_zu_juan_id|否|字段key|
|int8|pap_value|varchar||||是|null|
否|字段value|
|type_id|int8||是|null|
|type|int8||是|null|
|path_ids|varchar||是|null|
#### pap_que(pap_que)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pq_id|int8||否|试卷题目ID|
|pq_up|int8||否|上级试卷题目ID|
|pap_id|int8||否|试卷ID|
|sec_id|int8|#### zj_question_category_10(zj_question_category_10)|否|题型ID|
|sort_sec|int8||否|题型排序|
|sort_pap|int8||否|试卷排序|
|que_id|int8||否|原始题目ID|
|que_up|int8||
否|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
原始上级题目ID|
| ---- | ---- | ---- | ---- | ---- |
|que_type|int8||否|题型|
|que_types|int8|||id|int8|否|综合题型|
||sub_id|int8|否||否|学科ID|
|title|text||否|题干|
|answer_img|varchar||否|答案图片URL|
|answer|text||否|标准答案|
|analysis_img|varchar||否|解析图片URL|
|analysis|text||否|解析|
|num_option|int8||否|选项|
|dift|int8||否|难度【枚举】：0未定义、1容易、3普通、5困难|
|time_update|timestamp||否|更新时间|
|score|numeric||否|分值|
|grade_id|int8||是|年级id|
|grade_name|varchar||是|年级名称|
|grade_sort_no|numeric||是|年级顺序|
|stage|int4||是|学段|
|sub_name|varchar||是|科目名称|
|sub_sort_no|numeric||是|科目顺序|
#### 试卷题目属性关系(pap_que_attr)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pqa_id|int8||否|关系ID|
|attr_id|int8||否|属性ID|
|pq_id|int8||否|题目ID|
#### 试卷题目属性关系(pap_que_attr_in)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pqa_id|int8||否|关系ID|
|attr_id|int8||否|属性ID|
|pq_id|int8||否|题目ID|
#### 试卷录入的题目信息（包含教辅）(pap_que_in)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pq_id|int8||否|试卷题目ID|
|pq_up|int8||否|上级试卷题目ID|
|pap_id|int8||否|试卷ID|
|sec_id|int8||否|null|
|sort_sec|int8||否|null|
|sort_pap|int8||否|null|
|que_id|int8||否|null|
|que_up|int8||否|null|
|que_type|int8||否|null|
|que_types|int8||否|null|
|sub_id|int8||否|null|
|title|text||否|null|
|answer_img|varchar||否|null|
|answer|text||否|null|
|analysis_img|varchar||否|null|
|analysis|text||否|null|
|num_option|int8||否|null|
|dift|int8||否|null|
|score|numeric||否|null|
|time_update|timestamp||否|null|
|tk_que_id|int8||是|对应que_id，查重和审核时使用|
|status|int8||是|null|
|error_desc|text||是|注释内容|
|grade_id|int8||是|题目年级|
|que_dianxing|int4||是|0.不是典型题 1.典型题|
|que_jingpin|int4||是|0.不是精品题 1.精品题|
|que_cebie_id|int8||是|题目教辅冊别|
|que_mold_id|int8||是|题目类型(高考真题、高考模拟题、学考真题、学考模拟题等)|
|answer_area_size|int4||是|作答区域尺寸，简答题-行数，英语作文-行数，语文作文-格子数量|
|rule_type_arr|_int4||是|多选判分规则 11：选对但不全，12：每选对1个，21：有选错的，22：每选错1个，3：按不同选项判分|
|score_arr|_numeric||是|多选判分规则对应分值|
|que_mark_status|int8||是|题目标注状态   0: 未标注  1: 人工已经标注  2:智能已经标注|
|cognitive_level|int8||是|认知层级|
|subject_literacy|int8||是|学科素养|
|literacy_level|int8||是|素养水平|
|capability_point|int8||是|能力点|
|answer_type|int4||是|题目答案类型:0.正常   1.填空题专用(表示多空的答案可以乱序)|
#### pap_que_opts(pap_que_opts)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pqo_id|int8||否|null|
|pq_id|int8||否|null|
|sort|int8||否|null|
|opts_code|varchar||否|null|
|opts_txt|text||否|null|
#### pap_que_opts_in(pap_que_opts_in)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pqo_id|int8||否|null|
|pq_id|int8||否|null|
|sort|int8||否|null|
|opts_code|varchar||否|null|
|opts_txt|text||否|null|
#### pap_section(pap_section)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|sec_id|int8||否|题型ID|
|pap_id|int8||否|试卷ID|
|que_type|int8||否|题型|
|que_types|int8||否|综合题型：1-7|
|sec_name|varchar||否|题型名称|
|note_head|varchar||否|前注|
|note_below|varchar||否|尾注|
|len_min|int8||否|时长|
|num_que|int8||否|题目数|
|content|varchar||否|内容|
|score_sec|numeric||否|总分数|
|score_que|numeric||否|每题分数|
|sort_pap|int8||否|排序|
|is_choose|int8||否|是否选做|
|time_update|timestamp||否|更新时间|
|tk_sec_id|int8||是|null|
|group_que_type_name|varchar||是|分组题型名称|
#### pap_section_in(pap_section_in)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|sec_id|int8||否|题型ID|
|pap_id|int8||否|试卷ID|
|que_type|int8||否|题型|
|que_types|int8||否|综合题型：1-7|
|sec_name|varchar||否|题型名称|
|note_head|varchar||否|前注|
|note_below|varchar||否|尾注|
|len_min|int8||否|时长|
|num_que|int8||否|题目数|
|content|varchar||否|内容|
|score_sec|int8||否|总分数|
|score_que|int8||否|每题分数|
|sort_pap|int8||否|排序|
|is_choose|int8||否|是否选做|
|time_update|timestamp||否|更新时间|
#### que_analyze(que_analyze)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
#### 机构（学校）单词表(eer_school_word)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|ana_id|int8||否|ANA_ID|
|busi_id|int8||id|int8||否|业务编号：题目ID、文章ID、选项ID|
|ana_type|int8||否|解析类型：1文本、2音频、3视频|
|content|varchar||是|内容|
|org_id|int8||是|机构ID|
|sort_no|int4||是|机构内部及排序|
|status|int4||是|状态：-1停用、0草稿、1启用|
|time_update|timestamp||是|更新时间|
#### que_answer(que_answer)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|ans_id|int8||否|选项ID|
|que_id|int8||否|题目ID|
|sort_no|int4||否|排序|
|content|varchar||是|内容|
|content_cn|varchar||是|内容中文|
|num_file|int4||是|附件数量|
|time_update|timestamp||是|更新时间|
|否|null|
|name|varchar||是|null|
#### 填空题每region的空对应的所有位置信息(homework_que_position_tk)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|explain_cn||tk_ans_region_id|int8|varchar||否||是|主键，和tkansregion表ID一致中文释义|
|
|positions||explain_en|varchar|varchar||是||位置信息，json|
是|英文释义|
||create_timeexample||varchar|timestamp|||否|null|
#### 作业报告日志表(homework_report_log)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|stu_id|int8||是|学生ID|
|type|int2||是|记录类型(1:微信作业报告详情页提示)|
|remark|varchar||是|记录备注|
是|例子|
|similars|varchar||是|近义词|
|standard_en|varchar||是|英音音标|
#### 作业上传图片记录(homework_upload_records)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|standard_am|varchar||resource_id|是|美音音标|
|create_time|timestamp||varchar||是|创建时间|
||否update_time||timestamp|图片资源ID|是|修改时间|
|
|del_flag||machine_idint2||varchar||是||否删除标识。默认为 0：未删除；1：已删除|
|机器码|
|create_user||school_id|int8|int8||否|学校ID|
|是|创建人id|
|word_id|int8||是|关联单词表（word）id|
|school_id|int8||是|关联机构（学校）表（exam_school_info）id|
|type|varchar||是|词性|
|voice_en|varchar||是|英音音标发音（存音频url）|
|voice_am|varchar||是|美音音标发音（存音频url）|
|voice_people|varchar||是|人声音轨|
|example_answer|varchar||是|例句答案|
#### 机构（学校）单词-资源表(eer_school_word_resource)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|type|int2||否|资源类型：暂时只有图片（1：图片）|
|school_word_id|int8||是|关联机构单词表（school_word）id|
|resource_url|varchar||是|资源内容地址|
|resource_id|int8||是|关联bas_resource表rec_id|
#### 用户-考试成绩表(eer_student_mark)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|answer_flag|int2||是|是否正确答案（0：否；1：是）|
|complete_date|date||是|完成时间|
|right_num|int2||是|正确单词数|
|right_percent|int2||是|正确百分比|
||score|statusint2|||是|最终得分|
int4||package_word_id||int8|否||是0待处理，1已处理||
关联课程包-单词表（course_package_word）id|
|student_id|int8|||resource_url|是|关联学生表（student）id|
varchar||是|图片地址|
|#### 用户-课程包-考核成绩记录表(eer_student_package_record)create_time
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |timestamp
| ---- | ---- | ---- | ---- | ---- ||
|否|上传时间||
id||int8update_time||timestamp|||否否||null|
null|
|create_time|timestamp||是|创建时间|
|update_time|timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|answer_flag|int2||是|是否正确答案（0：否；1：是）|
|complete_date|date||是|完成时间|
|package_word_id|int8||是|关联课程包-单词表（course_package_word）id|
|student_id|int8||是|关联学生表（student）id|
|is_remember|int2||是|背诵模式下，是否已掌握，0表示没有，1表示已掌握|
|key_words|int2||是|背诵模式下，是否是重点词汇，0表示否，1表示是|
|exam_remember|int2||是|(由于和specll_check重复，作废)拼写考核中是否掌握，0表示未掌握，1表示已掌握|
|mean_check|int2||是|单词在英文选义考核中是否通过0表示未通过，1表示已通过|
|dict_check|int2||是|单词在中文选词选义考核中是否通过0表示未通过，1表示已通过|
|listen_check|int2||是|听写考核时是否记住，0表示未记住，1表示已记住|
|spell_check|int2||是|拼写考核时是否记住，0表示未记住，1表示已记住|
|temp_exam_remember|int2||是|考试时的单词状态，临时存储，0表示未记住，1表示已记住|
|temp_mean_check|int2||是#### homework_visit(homework_visit)#### 用来记录答题卡的具体信息(exam_custom_sheet)

| 列名   | 类型   | KEY  | 可否为空 | 注释   || 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|
| ---- | ---- | ---- | ---- | ---- |
pap_id|int8||否|null||
visit_id||int8sheet_name||varchar|否|null|
#### 科目不考虑上下级(exam_subject)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |是|null|

| ---- | ---- | ---- | ---- | ---- ||
content|varchar||int8||subject_id|int8||否|null|
|subject_code|varchar||否||null|
否||nullsubject_name|
|varchar||否|null|
||status|pap_id|int4||int8否||null|
||否sort_no||numeric|null|否|null|
|update_time|timestamp|
||否|null|
||sheet_type|stageint8||int8|||否|AB卷用，默认为A卷|
是||sheet_name|null|
varchar||否|null|
|page_num|int4||否|null|
#### 比如主副科、文理科的，也包括每个年级有那些科目，先不考虑地区之间的差异(exam_subject_classify)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|subject_id|int8||否|null|
||dir_id|int8|create_time||timestamp|否|null|
|否|null|
||status|int4|update_time||是timestamp||0 草稿 1正常 -1 作废|
|否||update_time|timestamp||否|null|
|option_type|int4||是|null|
|sheet_form|int4||是|null|
|ticket_figure_num|int4||是|null|
|sheet_source|int4||是|null|
|attr_id|int8||是|null|
|answer_type|int4|是|是||默认0填涂，1手写|
null|
|status|int4||否|-1作废 0 草稿 1 发布|
|opeator|int8||否|null|
|org_id|int8||否|null|
|time_update|timestamp||否|null|
#### 属性分类(tk_attr)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|attr_id|int8||否|属性ID|
#### 记录学生的入学记录(exam_entrance_experience)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|attr_up||int8entrance_id|int8|||否||null否|
|上级ID||
stu_id|int8||site_id|int8||否|否|网站ID【枚举】：21世纪|
|null|
|year|int4||否|null|
|half_year|int4||否|null|
|grade|int8||否|null|
|class_id|int8||否|null|
|school_id|int8||否|null|
|update_time|timestamp||否|null|
|seat_no|int8||是|null|
||ticket_no|varchar||是|null|
sub_id||source|int4|int8||是|null|
|否|学科ID|
|grade_type|int8||否|年级类型【枚举】：1一年级、2二年级..|
|term_type|int8||否|学期类型【枚举】：1上学期、2下学期|
|attr_type|int8||否|属性类型【枚举】：1知识点、2章节、3题型|
|attr_code|varchar||否|知识点编码|
|attr_name|varchar||否|知识点名称|
|status|int8||否|状态：-1停用、0待抓取、1正常|
|tree_path|varchar||否|树路径|
|tree_up|varchar||否|树上级编码|
|tree_lev|int8||否|树级别：lev|
|tree_leaf|int8||否|树叶子：0不是、1是|
|tree_sort|int8|#### 2018-3-9修改(exam_img_deal)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|否||guid|varchar|树排序|
||否|time_update|null|
timestamp|res_id||varchar|||否|否图片编号||
更新时间||
dir|varchar||是||null|
time_create||timestamp|sort_no||int4|否||是|添加时间null|
|
|mac|varchar||是|null|
|opeartor_id|int8||是|null|
|batch_no|varchar||是|null|
|test_id|int8||是|null|
|place_id|int8||是|null|
|sheet_id|#### tk_attr_a(tk_attr_a)int8||
是|| 列名   | 类型   | KEY  | 可否为空 | 注释   |null|

| ---- | ---- | ---- | ---- | ---- ||
wk_page_id|int8||是|null|
|time_update||timestamp|attr_code||否int8||修改时间|
|是|null|
|name|varchar||是#### 由于page_Id在生成图片时候并没有生成，这里改为查询条码时候，先生成(exam_page_no)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |null
|
||attr_idpage_id|int8||int8||否|null|
||否sheet_id||int8||否|null|
|page_no|int4||否|null|
|time_update|timestamp||否|null|
#### 这里不涉及到题目的具体信息，仅用来阅卷(exam_paper)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pap_id|int8||否|试卷编号|
|pap_name|varchar||否|试卷名称|
|sub_title|varchar||否|命题组说明|
|region_code|varchar||否|考试范围（地区），试卷的课时范围|
|subject_id|_int8||否|所属科目：语数外等，全空为全科|
|pap_id_cece|int8||否|cece试卷编号，有这个试卷，则属性值，取自里面的属性|
|school_id|int8||否|所属机构编号：0全部|
|grade|int8||否|所属年级|
|num_que|int8||否|题目数量|
|len_sec|int8||否|考试时长|
|score|numeric||否|满分|
|user_create|int8||否|创建人：0为管理员|
|time_create|timestamp||否|创建时间|
|time_update|timestamp||否|更新时间|
|time_publish|timestamp||否|发布时间|
|status|int8||否|状态：-1作废 0草稿、1发布（不可增删子表）|
|remarknull|varchar|
||否|备注|
|sheet_name|varchar||是|冗余字段，方便查询|
||step|sub_id|int4|int8||是|null|
||paper_type|varchar|是||是|null|
null||
tk_paper_id||int8parent_id|int8||是|null|
|attr_type|int8||是|null|
|path_ids|varchar||是|null|
#### tk_attr_b(tk_attr_b)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|attr_code|int8||是|null|
|name|varchar||是|null|
|attr_id|int8||否|null|
|sub_id|int8||是|null|
|parent_id|int8||是|null|
|path_ids|varchar|||是|role_namenull||
varchar||否|null|
|role_desc|varchar||否|null|
|status|int4||否|null|
|update_time|timestamp|#### 试卷表(tk_paper)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |否
|| ---- | ---- | ---- | ---- | ---- |null
|
|pap_id|int8||否|试卷ID|
|site_id|int8||否|网站ID【字典】|
|pap_code|varchar||否|试卷编码#### 一个考点有多个考场，比如有多个教室。(exam_room)|

| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |pap_name|varchar|
|否|试卷名称|
|room_id||int8pap_type|int8||否|试卷类型【字典】||
|否|null||
score|place_id||int8int8||||否否||null总分数|
|
||room_name|grade_typevarchar||int8||否||null否|
|年级类型【枚举】：1一年级、2二年级||
address||varchar|term_type||int8否||null|
|否||学期类型【枚举】：1上学期、2下学期num_seats|
|int4|||reg_prov否||varchar|null|
|否|省份编码||
sort_no||int4reg_city||varchar||否||否一个考点内，考场号唯一，扫描时候需要传入考点||
城市编码|
|status||reg_countyint4||varchar|||否否||-1作废 0 正常区县编码|
|
|update_time||remarktimestamp||varchar||否||否null||
备注|
|time_publish|timestamp||否|发布日期|
|time_update|timestamp|#### 每个学校当前的班级表，每个学校的班级名称是唯一的，历史的班级通过年、学期（寒暑假）来区分，可以物理删除(exam_school_class)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
否| ---- | ---- | ---- | ---- | ---- ||
更新时间|
|time_create|timestamp||class_id|int8||否||null否|
||添加时间school_d|int8||
|否||nulltype|
|int4||class_name||是|录入类型 0单题录入 1试卷录入 2教辅录入|
|textbook_id|int8||是|null|
|subject|_int8||是|null|
|len_min|int8||是|考试时长|
|sec_num|int8||是|单元数量|
varchar||su_attr_id|否|null|
|operator|int8||否|null|
|time_create||int8||timestamp|是|||否|null|
|是|nullnull|
|
|pap_grp||varchar|exam_type|int4||是|null||
是|考试类型:0或空为考试,2为作业||
sheet_id||sheet_typeint8||int8||是||是否生成答题卡是|
||nullyear|
|int4||是|年份|
|pdf_url|varchar||是|作业-卷卡一体答题卡pdf文件url|
|mark_status|int4||是|标注状态  0 : 未领取  1: 标注中  2 :标注完成|
|user_mark_id|int8||是#### 一个试卷可以有多个图片(exam_paper_pic)|
标注人的ID   0为没有标注.1.为admin| 列名   | 类型   | KEY  | 可否为空 | 注释   ||

| ---- | ---- | ---- | ---- | ---- |
|listen_template|int4||是||听写模板，0不是，1是pap_page_id|int8||
|否||nullanswer_pdf_url|
||varcharpap_id|||int8是|||答案解析url|
否|null|
||#### tk_paper_c(tk_paper_c)sort_no
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |int4
|| ---- | ---- | ---- | ---- | ---- ||
否是||nullpap_id|
|int8||res_id||否int8||null|
|否||nullsite_id|
|int8||operator||否int8||null||
否||null|
pap_code||varchartime_update||timestamp||否||否null||
null|
|pap_name|varchar||否|null|
|pap_type|#### 记录每次考试付费的名单(exam_pay_user_info)int8
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |否
|null|
|score||idint8||int8||否||否null|
|null|
|grade_type||int8test_id||int8|||否否||nullnull|
|
|term_type|int8||subject_id||否int8||null|否|null|
|stu_id|
||int8reg_prov||否|null|
|time_upload|timestamp||否||nullvarchar||
|否||nullreport_url|
|varchar||reg_city|varchar||否|null|
|reg_countynull||
varchar||否|null|
|remark|varchar#### 教辅材料(exam_supplemental)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |
否|null|
||time_publish|su_id|timestamp||int8|否|null|否||
null|
|time_update|timestamp|||su_name否||nullvarchar|
||否|null|
|publisher|varchar||否|null|
|textbook_id|int8||否|null|
|grade|int8||否|null|
|subject_id|int8||||time_create|timestamp否|||否|用于存放报告的url地址，用于下载null|
|
|type|int4||是|null|
|textbook_id||is_gen|int8|int4||是||否null|
||nullsubject|
|_int8|||time_gen否|timestamp|||否|nullnull|
|
||publish_time|timestamp|printed|int4|||否否|null|
||time_update|null|
timestamp|||否|update_timenull||
timestamp||否|null|
#### exam_task(exam_task)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
#### 对应多个考点，一个考点对应多个考场(exam_place)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|task_id||place_id|int8|int8||否||否null|
|null||
ans_id||place_name|int8||是|null|
|img_id|int8||是|null|
varchar||否|null|
|address|varchar||否|null|
|administrtice_code|varchar||否|null|
|longitude|numeric||否|null|
|latitude|numeric||否|null|
|capacity|int8||否|null#### 给每个阅卷老师指定任务的分配。从考试阅卷老师表里面选取老师(exam_task_assign)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|test_id|int8||否|null|
|pap_id|int8||否|null|
|ques_id|int8||否|null|
|tech_id|int8||否|null|
|num_check|int8||否|用来显示工作量用|
|score_check|int8||否|用来计算平均分用|
|status|int4||否|-1 不再阅卷 1 允许阅卷|
|update_time|timestamp||否|null|
|num_check_assign|int8||是|null|
|mode|int4||是|null|
|que_group_id|int8|
|num_rooms|int8||否|null|
|status|int4||否|-1 作废 0-正常|
|update_time|timestamp||否|null|
||是|null|
#### 记录老师的任课历史(exam_teacher_class)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|subject_id|int8||是|null|
#### 记录每次考试的条码信息(exam_barcode)
| 列名   | 类型   | KEY  | 可否为空 | 注释   ||class_id|int8||否|
null|
| ---- | ---- | ---- | ---- | ---- ||
grade_id|int8||否|null|
|role|int4||否|165001-任课老师 165005-班主任 165003-年级主任，年级主任时候，class_id为0|
||teach_id|int8||否|null|
barcode_id|time_update|timestamp|||int8否||null|
||stage|int4|否||否null|
|学段，role为学校领导（165004）时有效，其他为0|
|place_id|int8||否|null|
|room_id|#### 记录每一个老师的批改任务的上限，到达上限进行提示，让老师选择是否继续批改(exam_tech_limit)
int8| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
| ---- | ---- | ---- | ---- | ---- |
|否|null||
id||seat_no|int4|int8|||否是||nullnull|
|
|test_id||int8ticket_no|||否|varchar|null|
|pap_id|int8|||是|null|
否||tech_id|int8|null|
|否|null|
|top_limit|int4||否|null|
|update_time|timestamp||否|null|
|sub_code|int8||是|null|
#### 学生和家长的菜单是固定的，而老师是根据角色不同，显示不同的内容(exam_tech_role)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|tech_id|int8||否|null|
|role_id|int8||否|null|
|update_time|timestamp||否|null|
#### 记录每个老师教的科目(exam_tech_subject)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|tech_id|int8||否|null|
|subject_id|int8||否|null|
|grade|int8||否||null|
|否update_time||timestamp||主键id|
否|null|
|#### 一个考试，可以分为多次小考试，比如上午、下午，语、数、外等，用来列出这次考试可选的试卷(exam_test_detail)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|spec_test_id|int8||否|null|
|parent_test_id|int8||否|null|
|spec_test_name|varchar||否|null|
|pap_id|int8||否|允许采用多个试卷|
|begin_time|timestamp||否|null|
|end_time|timestamp||否|null|
|update_time|timestamp||否|null|
|solioquy|varchar||是|null|
|so_res_id|int8||是|null|
考核英文选意单词状态，0表示未记住，1表示已记住|
|temp_dict_check|int2||是|考核中文选词单词状态，0表示未记住，1表示已记住|
|homework_id|int8||temp_listen_check|int2||是|考核听写单词状态，0表示未记住，1表示已记住|
|temp_spell_check|int2||是|考核拼写单词状态，0表示未记住，1表示已记住|
#### 指定这次考试的阅卷老师，如果老师不阅这次卷，则可以删除(exam_test_tech)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|test_id|int8||否|null|
|pap_id|int8||是|null|
|tech_id|int8||否|null|
|update_time|timestamp||否|null|
|sub_code|int8|#### 用户-课程包-考核通关记录表(eer_student_package_word)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|主键|
||create_time|timestamp|否|是|创建时间|
|update_time||timestamp|作业id|
|是|修改时间|
|tea_id||int8|del_flag||否|教师id|
int2||class_id|int8|||否|是|删除标识。默认为 0：未删除；1：已删除|
班级id|
|create_user||grade_id|int8int8|||否|是|创建人id|
|package_id|int8||是|关联课程包表（course_package）id|
|mean_status|int2||是|英文选义考核状态（0：未通过；1：通过）|
|dict_status|int2|null|
||是|null|
question_zu_juan_id|int8||是||nullstu_id|int8||
||否subject_zu_juan_id||null|
int8|||test_id|是#### 记录无法识别的自定义答题卡(exam_unknown_pic)
int8|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|null|
||否|type_id是||null|
int8||sheet_id|int8||否|null|
|create_time|timestamp||是|null|
|是|null|
|type|int8||是|null|
|path_ids|varchar||是|null|
#### exam_bas_class(exam_bas_class)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|class_id|int8||否|null|
|school_id|int8||#### zj_question_category_11(zj_question_category_11)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
否|null|
|class_name||id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|subject_zu_juan_id|int8||是|null|
|type_id|int8||是|null|
|type|int8||是|null|
|path_ids|varchar||是|null|
#### zj_question_category_12(zj_question_category_12)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|subject_zu_juan_id|int8||是|null|
|type_id|int8||是|null|
|type|int8||是|null|
|path_ids|varchar||是|null|
|年级id|
|school_id|int8||否|#### zj_question_category_5(zj_question_category_5)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |学校id|

|token||varcharid||int8|||否|否null|
||question_zu_juan_id|int8||是是||null|
null|
|subject_zu_juan_id|int8||是|null|
|type_id|int8||是|null|
|type|int8||是|null|
|path_ids|varchar||是|null|
#### zj_question_category_6(zj_question_category_6)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
||null|
subject_zu_juan_id|int8||是|null|
||type_id|ability_name|int8|varchar||是|null|
||type|是|int8null|
||是|null|
|path_ids|varchar|||question_different_id|是|null|
int8||是#### zj_question_category_7(zj_question_category_7)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |null
|
| ---- | ---- | ---- | ---- | ---- |
|question_different_name||id|int8|varchar||否|null|
||question_zu_juan_id|是int8|||是|null|
null|
|subject_zu_juan_id|int8||time||timestamp|是|null||
否||type_idnull||
int8|||是question_body||null|
text||type|int8|||是否||nullnull|
|
|path_ids|varchar||question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
#### zj_question_27(zj_question_27)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
||time_updatequestion_type_name|varchar||是|null|
#### test2(test2)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int4||否|null|
|#### tiku(tiku)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
ability_id||int8|id|int8||是|null|否|null|
|diff_id|int4||是|null|
|type_id|int4||是|null|
|paper_id|int4||是|null|
|title|varchar||是|null|
|body|text||是|null|
|answer|text||是|null|
||analysis|text|timestamp||是|null||
否|date|timestamp||是|null|
#### tiku_assoc(tiku_assoc)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||是|null|
|catid|int8||是|null|
|tid|int8|是|null|
#### zj_question_category_8(zj_question_category_8)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|subject_zu_juan_id|int8||是|||是|null|
#### tiku_category(tiku_category)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|cid|int8||是|null|
|subject_id|int4||是|null|
|parent_id|int8||是|null|
|type|varchar||是|null|
|name|varchar||是|null|
|depth|int4||是|null|
|list_order|int8||是|null|
|xkw_id|int8||是|null|
#### tiku_diff(tiku_diff)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||是||null|
null||
name|varchar||是|null|
#### tiku_paper(tiku_paper)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||是|null|
|title|varchar||是|null|
|subject_id|int4||是|null|
|province_id|int4|#### exam_school_info(exam_school_info)
| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
是| ---- | ---- | ---- | ---- | ---- ||
null|
|year||null|
school_id|int4||int8|type_id|int8||否|null||
是|null|
|school_code||type|int8varchar|||是||是null||
null|
|parent_school_id||path_idsint8||varchar||否||允许学校有上下级是|
|null|
|school_name|varchar||否|null|
|name_short|varchar||否|null|
|region_code|varchar||否|null|
|address|#### zj_question_category_9(zj_question_category_9)varchar
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |否
|null|
|type||int4id||int8||否||null否|
|null|
||question_zu_juan_idlongitude||int8numeric||否|null|
|||latitude是||numericnull|
|||subject_zu_juan_id|int8否||null|
|full_time|int4||否|null|
|update_time|timestamp||否|null|
||是school_class||null|
int4|||是type_id|int8||null|
|是||class_comparison_statusnull||
int4|||type否||int8班级对比开关：0为开启，1为关闭；默认为0；
学校类型为省教育局 0、市教育局  1、区县教育局2 时，此字段无效||
|是|null|
|path_ids|varchar||是|null|
#### zj_question_type(zj_question_type)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|#### 记录这次考试的学生的考场位置(exam_seats_stu)
int8| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
|| ---- | ---- | ---- | ---- | ---- |
否|null|
|question_type_zu_juan_id||int8|seat_id||是|null|
|name|varchar||否|null|
|subject_zu_juan_id|int8|int8|||是否||nullnull|
|
|room_id|int8||否|null|
|test_id|int8||#### zj_special(zj_special)否
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |null
|
| ---- | ---- | ---- | ---- | ---- |
|seat_no|int4|||id否||int8在这个考场的座位号||
||否stu_id|null|
|name|varchar||int8||否|令牌|null|
|
|special_zu_juan_id|int8||否|否null||
||subject_zu_juan_id|session_idint8||varchar||是|会话id|
||是type|int4||null||
否|parent_id|int8||是|null|
|path_ids|varchar||是|null|
|访问类型,1-查看报告|
|#### zj_subject(zj_subject)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
start_time|timestamp||id||否|第一次汇报的开始时间|
|end_time|timestamp||int8|是|最后一次汇报的结束时间|
varchar|||否receive_time||timestamp否||null|
|是|最后一次汇报服务端收到的时间|
|class_code||varcharsum_time||int4|||否|统计的累加时间,单位秒|
否||null|
seqno|| ---- | ---- | ---- | ---- | ---- ||int4class_type
|||否|一次访问历史中多次汇报的序列号,按1递增|
|devices||varchar|id|int8||是|int8|访问使用的终端||
|否||null|
create_time||timestamptest_id|否||重点班、普通班，建分类目录表中文选词考核状态（0：未通过；1：通过）|
||
spell_status|int8|int2||sub_dirs||否|null|
||sheet_id|int8||否|是int8||拼写填空考核状态（0：未通过；1：通过）|
||否listen_status||文科、理科、不分科，见分类目录表int2||
|是||听音辨析考核状态（0：未通过；1：通过）update_time|
|timestamp||student_id|int8||否|null|||是否|null|
||数据创建的时间|
is_finished_exam|update_time|timestamp|||是|数据最后修改的时间|
|#### 记录每个题目的单个识别区域以及识别内容(homework_wk_cell)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
int2|wk_cell_id|int8||null|||
否|ID是||
|学生是否完成该包的考试任务，0表示没有，1表示已完成|
|type|int2|||tk_pap_id|是|int8 背诵模式（0：普通模式；1：图文模式；2：全部）|
||exam_date||date否|试卷ID(作业ID)|
|homework_wk_region_id|int8||否|阅卷区域id|
|homework_wk_page_id|int8|||否|阅卷答题卡版面id|
|cell_type||是|考试时间|
|total_right|int2||是|正确单词数|
|accuracy|varchar||是|正确率|
|score|int2||是|得分|
name|varchar||是|null|
|full_name|#### eer_student_word(eer_student_word)
varchar|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|是||nullid|int8||
|否|school_phase_id|int4||null|
|student_id|int8||是|null|
|word_id|int8||是|null|
|create_date|timestamp||是|首次记单词的时间|
|end_date|timestamp||是|null|
null#### 单词表(eer_word)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|是|null|
|type_id|int4||是|null|
|
||
|name|varchar|level_id|int4|||是是||null|
null|
||explain_cngrade_id||varchar|int4||是|中文释义|
||是explain_en||null|
varchar||string_ids|text||是|null|
|date|timestamp||是|null|
#### tiku_paper_level(tiku_paper_level)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|是|英文释义|
|id|int8||是|null|
||nameexample||varchar|varchar||是|null|
|是|例子|
||similars|varchar||是|ticket_no近义词|
||varcharstandard_en||varchar||是|是|英音音标|
|standard_am|varchar||是|美音音标|
|null|
|create_time||update_time|timestamp||否|null|
|send_to_wechat|int4||否|学生作业推送到微信 0未推送1推送|
|
||ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|class_id|int8|question_different_name|varchar||是|null|
|time|timestamp||否|null|
|question_body|text||否|null|
|question_answer|text||是|null|
|question_parse|text||timestamp是||是|创建时间|
|null|
|is_download|int8||是|null|
#### tiku_paper_type(tiku_paper_type)|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|subjectint8|||是int8||null|
||是name||null|
varchar||否|null|
#### zj_question_28(zj_question_28)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
#### tiku_type(tiku_type)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||是|null|
|name|varchar||是|null|
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
||是|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
||question_different_name|varchar||是|null|
update_time|timestamp||time|timestamp||是||修改时间|
否|null|
|question_body||del_flag|text|int2||否||是null|
|删除标识。默认为 0：未删除；1：已删除||
question_answer|text||#### tk_que_attr_b(tk_que_attr_b)create_user||int8|是||是null||
创建人id||
question_parse||type|textvarchar||||是是||词性null|
|
|voice_en||varcharis_download|||int8|是||是英音音标发音（存音频url）||
null|
|voice_am||varcharsubject||int8|||是是||美音音标发音（存音频url）null|
|
|voice_people|varchar||是|人声音轨|
#### zj_question_29(zj_question_29)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8|#### 单词表(eer_word_copy)
| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
是| ---- | ---- | ---- | ---- | ---- ||
null|
|question_type_name|varchar||是|null|
|ability_id|int8||是|null|
|ability_name|varchar||是|null|
|nullquestion_different_id||
int8||是|null|
|question_different_name|varchar||subject_zu_juan_id||int8|是|null|
||time|是timestamp||null||
否|int4null||否|类型：0:题干 1:答案|
|
|question_body||text#### zj_textbook(zj_textbook)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |cell_id||
| ---- | ---- | ---- | ---- | ---- ||
否|null|
||id|int8|question_answer|text||是|null|
|question_parse|text||是|null|
|is_download|int8||是|null|
|subject|int8||是|null|
int8||否|#### zj_question_3(zj_question_3)(模版)单元格id|

|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |sort_no|
int4||否|排序|
|res_id|varchar||id|否|答案图片地址|
|res_path|varchar||是|裁切图片路径|
|ans_status|int4||否|作答状态：0已作答 1未作答；可能存在AI判断已作答，但是只能识别不到内容的情况|
|content|varchar||是|识别的答案内容|
|content_manu|varchar||是|人工校正的内容|
|max_thresh_value|numeric||否|识别的最大阈值|
|correct_mark|varchar||是|人工批改标记JSON|
|is_diff|int4||否|差异状态：-1未识别内容(默认),0没有差异，1有差异，2填涂有差异，可以忽略，作为低风险值|
|create_time|timestamp||否|新增时间|
|update_time|timestamp||否|修改时间|
|status|int4||否|0正常，1删除|
|height|int4|||是|int8图片高度(填空使用)|
|width|int4||是|图片宽度(填空使用)|
||answer_type|int4||是id||答案对/错/半对(多空填空使用)，值含义详见枚举int8|
||last_correct_id||int8|否||null是|
|最后批阅人id(多空填空使用)|
|name|varchar||是|null||
last_correct_name|varchar||explain_cn||是varchar|||最后批阅人姓名(多空填空使用)是|
||中文释义|
|explain_en|varchar||是|英文释义|
|example|varchar||是|例子|
|similars|varchar||是|近义词|
|standard_en|varchar||是|英音音标|
|standard_am|varchar||是|美音音标|
|create_time|timestamp||是|创建时间|
ocr_type|update_time||timestampint4|||是||是|修改时间ocr识别类型，详见HomeworkOcrType枚举|
|
|del_flag|int2||auto_judge_type||是|int4删除标识。默认为 0：未删除；1：已删除||
||是create_user||自动判断的类型，例如：AI，英语超长，本地判断等；详见代码枚举int8|
|||是|创建人id|
||type|否|varcharnull|
||question_zu_juan_id|int8|#### 一个作业对应多个原始扫描图片(homework_wk_page)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |是|
null|
| ---- | ---- | ---- | ---- | ---- |
|question_type_id||wk_page_id||是int8||词性|
|否||ID|
voice_en||varcharhomework_wk_sheet_id||int8||是||英音音标发音（存音频url）否|
|阅卷答题卡id|
|voice_am|varchar||sheet_id|int8|||是否||美音音标发音（存音频url）(模板)答题卡id|
|
|stu_id|int8||否|学生ID|
|voice_people||varcharpage_id||int8|是|人声音轨|
||否|版面id|
|page_no|int4||否|版面顺序|
|res_id|varchar|#### 单词-资源表(eer_word_resource)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |是|
定位后的图片| ---- | ---- | ---- | ---- | ---- ||

|res_id_ori|varchar||是|上传的原图|
|id||machine_idint8||varchar||否||null是|
|上传图片的机器编码|create_time|timestamp||是||
创建时间||
school_id||update_timeint8|timestamp||是|修改时间|
|del_flag||int2|||否是||学校ID删除标识。默认为 0：未删除；1：已删除|
|
|
|create_user|int8||是|创建人id|
|||type|scanning_statusint2||int4||否||否资源类型：暂时只有图片（1：图片）|扫描识别状态 0正常,1二维码识别失败，2图片定位失败|
|
|resource_url|varchar||是|资源内容地址|
||word_idprint_status|int8||是|关联单词表（word）id|
|resource_id|int8|||int4是|||关联bas_resource表rec_id否|
|原卷打印状态：0未打印，1已打印|
|update_time|timestamp||否|null|
|#### eer_wrong_words(eer_wrong_words)create_time
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |timestamp
|| ---- | ---- | ---- | ---- | ---- ||
否|null|
|status||int4|id||否int8||否||0正常，1删除null|
|
||word_idlast_upload_from||int8|int4||是||null|
|counts|int8||是|错误次数|
是|最后一次上传的来源：0机器扫描,1手机拍照|
|last_upload_time|timestamp|null|
||是|最后一次上传解析的时间|
place_id||tk_paper_id|int8||否|tk_paper_id|
|class_id|int8||否|班级id|
#### error_type(error_type)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
#### 答题卡异常处理记录(homework_wk_page_records)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
||idpap_id||int8int8|||否|null|
|wk_page_id|int8||否||homework_wk_page主键|
否||wk_page_scanning_status试卷编号|
|que_id|int8||是|题目编号|
|int4|||sub_id否||int4wkpage的扫描状态
||
|是||年级编号machine_id|
|varchar|||stage是||varchar机器码||
|是||年级名字school_id|
|int8||errortype||varchar|否||学校ID是||
错误类型|
|res_id||varcharsubmit_time||timestamp||否||处理异常时，wkpage资源ID是|
|错误报告时间||
res_path|varchar||memo||是|text处理异常时,wkpage资源路径||
||是create_user_id||备注信息|
int8||否|异常处理人ID|
|create_user_name|varchar||#### essay_valid_t(essay_valid_t)是
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |处理人姓名
|
| ---- | ---- | ---- | ---- | ---- |
|create_time|timestamp|||否|prediction_idnull||
int8||否|null|
|essay_id|int8||是|null|
|#### 作业每个切割出来的业务区域(homework_wk_region)essay_set|int8|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |
是|null|
||school_yearessay_weightwk_region_id||int8|int4|||numeric否||ID||
是||nullhomework_process_id||
int8|||predicted_score|否int4|||作业进度表ID是|
|null|
|homework_wk_sheet_id|int8||否|作业答题卡id#### exam_ad_visit(exam_ad_visit)|

| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
tk_pap_id| ---- | ---- | ---- | ---- | ---- ||
int8|id|int8||否|null|
||visit_id||varchar否||试卷ID（作业ID）||
否||nullstu_id|
|int8||visit_ip||varchar|否||学生ID否|
|null|
|stu_name||visit_url|varcharvarchar|||否||否学生姓名||
null|
|num_cells||int4visit_time|||timestamp否|int8||否||null|
|是|阅卷单元格数量null|
|
#### 一个区域划分多个单元格(exam_ans_cell)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |region_type|
| ---- | ---- | ---- | ---- | ---- |
int4||question_type_namecell_id||varcharint8|||是|null|
||否ability_id|int8||是|null|
|ability_name||varchar|null||
是|null|
|question_different_id||int8region_id|int8||否||null|
|是|null||
page_id|int8||question_different_name|varchar|||否|单元格不能跨越版面否|
|null||
sort_no|numeric|||name|否varchar|
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
null|
| ---- | ---- | ---- | ---- | ---- |
|否|null||
top_x||int4|||textbook_zu_juan_id|qa_id|int8int8||||是|null|
否||null|
subject_zu_juan_id||int8attr_id|||是|是|null|
|parent_id|int8||是|null|
|textbook_type|int8||是|null|
||path_ids|学生参加考试所在的班级Idvarchar|
||是|null|
int8#### zj_tiku_category_busi(zj_tiku_category_busi)||否|null|

| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|que_id|zj_attr_id||int8int8|||否|null|
|dift|int8||否|null|
|time_create|timestamp||否|null|
|是#### tk_que_attr_bak(tk_que_attr_bak)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|null|
|qa_id|#### exam_sentence_info(exam_sentence_info)int8||tiku_attr_id||int8是||null|
|attr_id|int8||是|null|
|que_id|int8||是|null|
|dift|int8||是|null|
|time_create|timestamp||是否||null|
null|top_y|int4||
||#### tk_que_attr_c(tk_que_attr_c)否|null|
是|bottom_x|
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |null
|
||qa_idtime|||int8|timestamp|||否||null|
否|阅卷答题卡区域类型|
|region_id|int8||否|(模版)答题卡区域id|
|que_id|int8||否|题目ID|
|que_type|int8||否|题目类型|
|que_name|varchar||否|题号|
|que_sort|int4||否|作业上的题目排序|
|que_score|numeric||是|原始题目分数|
|ans_type|int4||否|答案对错： 1全对，2半对，3全错 ；11优，12良，13中，14差|
|proofread_status|int4||否|届|
|否|校对状态，0未校对，1已校对|
||risk_level|int4|grade_id|否|风险等级，0低风险，1高风险|
|int8||correct_type|int4||否||批改方式：1机器，2人工，3AI识别否|
||score|年级ID|
|sourcenumeric||否|分数|
||int4ans_mark|_int4||是|答案备注 1优秀答案，2典型错误，3范文|
|||marking_sort|是|null|
int4||sub_id||否|int8|批阅顺序|
|否||班级所属科目|
last_correct_id|int8||否|最后批阅者id，机器或者AI是-1|
|last_correct_name|varchar||否|最后批阅者姓名|
|correct_status|int4|#### exam_bas_joint(exam_bas_joint)
| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
| ---- | ---- | ---- | ---- | ---- |否
|批阅状态：1批改完毕，0未批改|
||answer_status|int4|act_id||int8|否||否|是否作答：0作答，1未作答|
null|
||dx_que_typeact_name||varcharint4|||否||否|null大小题类型: 1单题，2大题（存在小题），3小题|
|
|create_time||small_que_parent_region_id|timestamp|int8|||否|否小题对应的regionID|
|null|
|create_time||creator|int8||否|timestamp|null|
|否||status|null|
int4||update_time|timestamp||否|null|否|null|
|status|int4||否|0正常，1删除|
|last_correct_time|timestamp||是|最后批阅时间|
|num_option|int4||是|答案个数，值从tk_que获得|
|marking_way|varchar||是|打分模式|
|jd_correct_model|int4||否|是否是简答题批阅模式，0否1是|
|jd_correct_status|int4||否|简答题批阅状态 0未完成，1完成|
|last_update_from|int4||否|region从哪里来:0裁切，1微信上传|
|subject_id|int8||否|科目ID|
|subject_code|varchar||否|科目编码|
int8||否|null|
|res_ids|varchar||否|null|
|status|int4||是|null|
|update_time|timestamp||否|null|
#### exam_user_student(exam_user_student)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|user_id|int8||否|用户编号|
|school_id|int8||否|null|
|sid|varchar||否|学号|
|name|varchar||否|真实姓名|
|name_old|varchar||否|曾用名|
|sex|int8||否|默认-1未知，0女，1男|
|status|int8||否|状态：0无效、1正常|
|remark|varchar||否|备注|
|update_time|timestamp||否|更新时间|
|org_stu_id|varchar||是|null|
|mobile|varchar||是|null|
|user_passwd|varchar||是|null|
|mobile_stu|varchar||是|null|
|head_url|varchar||是|头像url|
|card_id|varchar||是|null|
|is_people_voice|int2||是|是否人声发音，0，否，1，是|
|is_american_voice|int2||是|是否美式发音，0，否，1，是|
#### exam_user_teacher(exam_user_teacher)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|uoid|int8||否|用户流水号|
|user_id|int8||否|用户编号|
|school_id|int8||否|机构编号，这个字段作废，先用登录人员信息里面取|
|wid|varchar||是|工号|
|name|varchar||是|真实姓名|
|name_py|varchar||是|null|
|letter_first|varchar||是|null|
|gender|int8||否|默认-1未知，0女，1男|
|birthday|varchar||是|出生日期|
|job_title|varchar||是|职称|
|job_date|varchar||是|参加工作时间|
#### 作业答题卡区域修改历史(homework_wk_region_his)
|mobile|varchar||是|联系电话|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|email|varchar||是|EMAIL|
|status|int8||否||状态：0无效、1正常|
wk_region_his_id||job_nature|int4|int8||否|1全职 2 兼职 3临时|
|remark|varchar|||是|否|备注|
ID|
|time_update|timestamp|||homework_wk_region_id否||int8更新时间|
||user_passwd||varchar|否|homework_wk_region表主键|是||
账户密码|
||score_before|dutynumeric||varchar||是||null否||
修改之前的分数||
user_type|int4|||是score_after||0 普通老师 1 admin 2 学校管理员|
numeric||region_code|varchar|||是否||null修改之后的分数|
|
|source|int4||是|null|
||remark|openid|varcharvarchar||||是|是微信openid||
备注|
|before_json|varchar#### exam_wk_cell(exam_wk_cell)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|||否|nullwk_cell_id|int8||否|答案编号|
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
|test_id|int8||
|是|null|
|after_json|varchar||否|null|
|create_time|timestamp||否|null|
|create_user|int8||否|null|
|create_user_name|varchar||否|null|
#### 每个学生，每次作业上传的主信息(homework_wk_sheet)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_sheet_id|int8||
|update_time|timestamp||否|否||IDnull|
|
|test_id||homework_process_id|_int8||否|null|
int8||question_body|text||#### exam_bas_joint_params(exam_bas_joint_params)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|否|作业进度ID|id|int8||
否|tk_pap_id||null|
|attr_id|int8|int8|||否否||题库里的作业id|
null|
|否sheet_id||que_idnull|int8||
|否||question_answer|nulltext||
|是|null|
||dift|int8|question_parse|text|||否是|null|
||null|
is_download||int8time_create|timestamp|||否|是|null|
|subject|int8||是|null|
#### 一个试卷对应多个原始扫描图片(exam_wk_page)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_page_id|int8||否|null|
|wk_sheet_id|int8||否|null|
int4||否|null|
|bottom_y|int4|#### 用来记录表的中间值，使历史数据不再改变，也不需要重新调用智能评分的操作，以便加快速度(wk_essay_report)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |否
|| ---- | ---- | ---- | ---- | ---- |
null|
||update_time|ans_idtimestamp||int8||否||否null||
null|
|option_size||content|varchar|int4|||否是||保持为json数据，记录报表需要的中间数值null|
|
||block_idtime_update||timestampint8||||是否||nullnull|
|
|option_w|int4||是|null|
|option_h|int4||是|#### 每个模考都填写(wk_section)null
|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|option_th|int4|||wk_id|是int8||null|
|否||nulloption_json|varchar||
||是|sec_id|nullint8|
||否|null|
|user_id|int8||否|null|
|pap_id|int8||是|null|
|time_start#### 这个这需要把FileCenter也部署到新东方(exam_ans_page)|
timestamp| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |
|否|null|
|time_end||timestamppage_id||int8||否||否null||
null|
|len_sec|int4||sheet_id||否int8||做题时间秒|
|否|null|
|num_que||page_noint4||int4|||否否||nullnull|
|
|res_id||varchar|num_not||int4否|||校正之后的图片资源否|
|null|
|res_id_ori||num_rightvarchar|||int4|否||null|
否|null|
|top_x||num_wrongint4||int4||否||否null|
|null||
top_y||time_updateint4||timestamp||否|否||nullnull|
|
|bottom_x|int4||否|null|
|bottom_y|int4|#### 所有的做题记录保存在此(wk_work)|
否| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |null
|
|length||wk_idint4||int8||否|null||
否||nullwidth|int4||
|否||nulluser_id|
||int8|update_time||timestamp否|||null否|
|null|
|job_id|int8||否|作业ID：JOB_ID>0、STU_ID联合唯一|
|class_id|int8||#### 记录客观题块信息(exam_ans_que_block)否
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |布置作业所在的班级
|
| ---- | ---- | ---- | ---- | ---- |
|org_id|int8||block_id||否|int8|布置作业的机构||
否|null|
||tech_id|top_x|int8|int4||否||布置作业的老师ID否||
null|
|time_start||timestamptop_y|||int4|否||实际开始时间否|
|null|
|time_end||bottom_xtimestamp||int4|||否|否null||
实际结束时间|
|bottom_y||len_sec|int4|int4||否||否null||
由于现在的sat改版，每题里面的耗时已经没办法计算，只能计算总耗时|
|time_update||timestamptest_id|||int8否||null|
|否|考试编码|
|subjects|_int8||否|科目列表|
#### 对一个答题卡，划分各个切割区域，每个区域有可能有多个单元格，按先后顺序一起组合显示，每个区域为一个显示单元，一个题按一个区域来显示(exam_ans_region)|
pap_id| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |
int8||是|试卷编号：整套试卷才填写||
region_id||wk_ruleint8|||int8|否||null是|
|见数据字典表|
|sheet_id||wk_type|int8|int8||否||否见字典表||
null|
|status||region_typeint4||int4||是||否见字典表||
null|
|score||page_idnumeric||int8|||否是||模考得分：全套模考有效主要用于学生考场号这些，每个版面都有的区域，对于题目的这类，默认为0|
|
|remark|varchar||num_cell|int4|||是否||null|
null|
|score_tech||numeric|ques_no||int8是||作业成绩0-12对应F到A+；||
否||如果类型是题目区域，这个值有意义comment|
|varchar|||update_time是||timestamp老师评语||
|否||null|
time_update|timestamp||是|null|
#### 一个试卷可以对应多个答题卡，导入的时候选择答题卡，答题卡对应试卷的a、b或者c
一个答题卡有多个版面，每个版面有个多个区域，一个区域为阅卷时一起的图片，一个区域对应多个单元格。主要用于一个题跨域多个方块的地方，比如作文。(exam_ans_sheet)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
#### wrong_question_book(wrong_question_book)| ---- | ---- | ---- | ---- | ---- |

| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|sheet_id||int8wq_id||int8|||否否||主键唯一null|
|
|pap_id||int8que_id|||int8否||null|
|否||题目的idsheet_type|
|int8||pap_id||int8否||AB卷用，默认为A卷||
是|试卷id||
sheet_name||tk_que_idvarchar||int8||否||null是|
|题库中的题目id，que_source_type为1是才有||
page_num|int4||cece_pap_id||int8否|||null是|
|自组卷id||
create_time||timestamptest_name||varchar||否|null||
是||考试名称status|
|int4|||full_score是||float8|0 草稿 1正常 -1 作废||
是|满分||
update_time|timestamp||score||否|float8null|
|||option_type是||int4|得分|
|是||nullstu_ans_img||
varchar|||sheet_form|是int4||答案图片，以，分割||
是||nullis_auto|
|int4|||ticket_figure_num是||int4|是否是客观题，1为是0为否||
是|null||
content||sheet_sourcevarchar||int4||是||是机器识别答案||
null|
||content_manuattr_id||varcharint8|||是||是|null|
人工校验后的答案|
|avage_score|float8||是#### exam_article_info(exam_article_info)|
班级平均分| 列名   | 类型   | KEY  | 可否为空 | 注释   ||

| ---- | ---- | ---- | ---- | ---- |
|que_img|varchar|||article_id是||int8题干的图片地址，queSourceType为0时才有,以，分开||
||否|ana_img|主键varchar|
|||grade_id是||题目解析的地址，以，分开,queSourceType为0时才有int8|
|||是|que_title年级id||
text||create_time||是timestamp||题目的主干，queSourceType为1时才有|
|否|创建时间||
que_name||varchar|file_path||varchar是||题目序号||
是|文件路径||
status|int4||是|状态，是否已经被添加到错题本，默认为0(否)|
#### exam_audit(exam_audit)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |stu_id
|| ---- | ---- | ---- | ---- | ---- |int8
||否|学生id|
|id||que_type|int8|int8||否||是null|
||题目类型op_id|
|int8||correct_ans||varchar否||null|
|是||正确答案url|
|varchar|||que_source_type否||int4|null|
|是||source_ip题目题干的来源地址  默认0表示上传试卷，1表示从自组卷||
varchar||test_id||否|int8null||
|是|题目所属考试id||
content||test_typevarchar||int4||否||否超过300截断||
0-考试，1-作业|
|update_time|timestamp||否|null|
#### zj_paper(zj_paper)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|paper_zu_juan_id|int8||否|null|
|title|varchar||是|null|
|subject_zu_juan_id|int8||是|null|
|learn_grade_id|int8||是|null||
sheet_id|learn_grade_name||varchar|int8||是|null|
|learn_grade_paper_type_list|varchar|||是|null否|
|#### common_table_field(common_table_field)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|paper_type_id| ---- | ---- | ---- | ---- | ---- ||
int8||是||nullid|
|int8||paper_type_name||否varchar||主键|
|是||nullcreate_time||
timestamp|||是province_id||创建时间int8|
|||是update_time||nulltimestamp|
||province_name||是varchar||是|null|
|province_short_name|varchar|||修改时间是|
||nulldel_flag|
||int2|是|null||
是|删除标识。默认为 0：未删除；1：已删除|
|||create_usercreate_timepaper_year_id||int8int8||||是|是创建人id||
null|
|paper_year_name|varchar||是|null|
#### courseware(courseware)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |time
|timestamp|||id否||int8null|
|||否|paper_ques_countnull||
int8||courseware_name||varchar否|||null否|
|null|
|attr_id
#### zj_paper_province(zj_paper_province)|
int8| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |否
| ---- | ---- | ---- | ---- | ---- ||
null|
|status| ---- | ---- | ---- | ---- | ---- ||
int2|||sentence_id|int8|id||否|主键int8|
||content_true|varchar||否|正确例句|
|create_time|timestamp||否|创建时间|
|否|null|
|grade_id|int8|||paper_province_zu_juan_id|int8是|||是|null|
|name|varchar||否|null|
对应的年级id|
|status|int2||否|0:正常；1：删除 ; 2:已标注|
#### zj_paper_type(zj_paper_type)|
article_id| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|int8||id|否||对应文章idint8|
||否|null|
|paper_type_zu_juan_id|int8||是|null|
||#### exam_sentence_mark(exam_sentence_mark)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
date|mark_id||int8||是name||null|
varchar||否|null|
|subject_zu_juan_id|int8||attr_type|int8|||是是|null|
|null|
|zj_attr_up|int8||是|#### zj_question_1(zj_question_1)null|

| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|zj_attr_code||int8|id|int8||是|null|
|否|null|
|question_zu_juan_id|null|int8tiku_attr_code||
int8|page_id||int8||是||null否|和版面无关的话，此处为0|
|
|res_id|varchar||否|null|
|res_id_ori|varchar||否|null|
|status|int4||否|0正常 -1作废|
|update_time|timestamp||否|null|
|match_value|numeric||是|null|
|#### 每个切割出来的业务区域(exam_wk_region)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|wk_region_id|int8||否|null|
|wk_sheet_id|int8||否|null|
|num_cells|int4||否|null|
null|
|region_type|int4|#### zj_question_category_22(zj_question_category_22)|否|EXAM_ANS_REGION|

| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||#### tk_que_attr_d(tk_que_attr_d)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- ||region_id|int8||否|答题卡id|
int8||否||题目类型，这个id为0，因为题目的区域可能会跨版面|
school_id||ques_noint8||int8||否||否学校ID||
null|
|grade_code||ans_typevarchar||int4||否||否年级编码,注意不是ID|
||class_id|int8||否|对于客观题，识别之后，自动给出对错班级ID|
|
||statusstu_id|int4||否|0初始值 1批改中  2 已判  -1 作废 -2需要重裁|
|score_intel|numeric|||否|int8null||
|否||学生IDscore|
|numeric||stu_name||varchar否||null|
|否||学生姓名ans_level|
|varchar|||upload_page_total是||int4|优秀答案、独立见解、典型错误、低级错误……||
否|已上传上传页数（一张两页）|
||tech_idscore|int8||否|null|
|update_time|timestamp||numeric||否||null否|
|本次阅卷最终得分||
chosen||report_push_statusint4||int4|||否是||报告推送状态：0未推送，1已推送，2推送失败null|
|
|test_id||int8last_submit_time||timestamp||是||否null|
|当前学生最后一次上传作业的时间||
|create_time|timestamp||否|pap_id|nullint8|
||是|null|
|is_auto|int4||update_time||timestamp是||null|
|否|null||
zj_que_id||int8|status|int4|||是否||null|
0正常，1删除|
|repulse_reason|int4||是|null|

||qa_id|int8|marking_sort|int4||否||null|
是|null|attr_id|int8||否|null|
|que_id|int8||否|null|
|dift|int8||否|null|
|time_create|timestamp||否|null|
#### tk_que_bak(tk_que_bak)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|que_id|int8|#### grade(grade)|是|null|

| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |
site_id|int8|||id|int8|否||null|
是|null|
|name|varchar||是|null|
|question_zu_juan_id|int8|#### history_report(history_report)
| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
是| ---- | ---- | ---- | ---- | ---- ||
null|
||subject_zu_juan_id||history_report_idint8||是|null|
|是||nulltype_id||
int8||是||null|
question_type_id|type|int8||是|null|
|path_ids|varchar||是|null|
#### zj_question_category_23(zj_question_category_23)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8|否|null|
|sentence_id|||否int8||null|
|否|null|
|question_zu_juan_id|int8||content_false|varchar||否|null|
|wrong_type|int4||否|null|
|wrong_reason|varchar||否|null|
|create_time|timestamp||否|null|
|status|int2||否|0:正常；1：删除|
|operator_id|int8||否|操作人id|
|operator_name|varchar||是|null|
|update_time|timestamp||是|null|
#### 目前没用(exam_report_school)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|题目编号，题组是几道题一起批改，就像大题的概念|
|school_id|int8||否|null|
|test_id|int8||否|null|
|param_code|varchar||否|null|
|param_value|varchar||否|题型：系统编码，枚举|
|score|numeric||否|分值|
|stu_num|int4||否|null|
|max_score|int4||否|null|
|min_score|int8||否|null|
|create_time|timestamp||否|null|
#### exam_report_school_joint(exam_report_school_joint)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|act_id|int8||否|null|
|create_time|timestamp||否|null|
|max_score|numeric||否|null|
|min_score|numeric||否|null|
|param_code|varchar||否|null|
|param_value|varchar||否|null|
|school_id|int8||否|null|
|score|numeric||否|null|
|stu_num|int4||否|null|
#### exam_report_score(exam_report_score)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|test_id|int8||是|null|
|pap_id|int8||是|null|
|space|int8||是|null|
|max_score|numeric||是|null|
|min_score|numeric||是|null|
|stu_num|int8||是|null|
|proportion|numeric||是|null|
|create_time|timestamp||是|null|
#### exam_report_sta(exam_report_sta)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|test_id|int8||是|null|
|pap_id|int8||是|null|
|stu_entry_num|int8||是|null|
|stu_join_num|int8||是|null|
|stu_unjoin_num|int8||是|null|
|score|numeric||是|null|
|max_score|numeric||是|null|
|min_score|numeric||是|null|
|average_score|numeric||是|null|
|median_score|numeric||是|null|
|modeno_score|numeric||是|null|
|create_time|timestamp||是|null|
#### exam_report_stu(exam_report_stu)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|stu_id|int8||是|null|
|test_id|int8||否|null|
|param_code|varchar||否|null|
|param_value|varchar||否|null|
|score|numeric||否|null|
|sort|int4||否|null|
|class_sort|int4||是|null|
|grade_sort|int4||是|null|
|create_time|timestamp||否|null|
|stand_score|numeric||否|null|
#### exam_report_stu_bak(exam_report_stu_bak)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||是|null|
|stu_id|int8||是|null|
|test_id|int8||是|null|
|param_code|varchar||是|null|
||否|null|
|param_value|varchar||是|null|
|score|numeric||是|null|
|sort|int4||是|null|
|class_sort|int4||是|null|
|grade_sort|int4||是|null|
|create_time|timestamp||是|null|
|stand_score|numeric||是|null|
#### exam_report_stu_joint(exam_report_stu_joint)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
||是|null|
id|int8||否|null|
|act_id||int8subject_zu_juan_id|int8|||是|null|
|type_id|int8||是|null|
|type|int8||是|null|
|path_ids|varchar||是|null|
#### zj_question_category_24(zj_question_category_24)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||int8||是|null|
|question_type_name|varchar||是|null|
||否|nullability_id|
||int8question_zu_juan_id|int8||是|null|
||ability_name|varchar||是|null|
|subject_zu_juan_id|int8||是|null|
|type_id|int8||是|null|
|type|int8||是|null|
|path_ids|varchar|||是int8||否|null|
|null|
|report_name|varchar||否#### zj_question_category_25(zj_question_category_25)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|null|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|subject_zu_juan_id|int8||是|null|
|type_id|int8||是|null|
|type|int8||是|null|
|path_ids|varchar||是|null|
#### zj_question_category_26(zj_question_category_26)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
||是|null|
question_zu_juan_id|int8|||que_code是|varchar|null|
||subject_zu_juan_id||是|null|
|que_type|int8||是|null|
|que_types|int8||是|null|
|sub_id|int8||是|
||que_group_id|int8||是|null|
null|
|title|text||是|null|
|num_option|int8||是|null|
|answer_img|varchar||是|null|
#### 一个区域可能有多个小题，每个小题单独打分，每个题目可能有不同的给分点，图片标记也存放这里，图片的大小是系统默认(exam_wk_region_score)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|answer| ---- | ---- | ---- | ---- | ---- |
|id|int8||否||null|
|busi_type|int4||否|1-小题给分 2-得分点给分，3-评分标注 默认1|
text|||否mark_type||null|
int8||否|用于系统内置的标记类型，比如对、错、疑问等，见《系统编码》|
||是act_id|int8||null|
||否analysis_img||nullvarchar||
|是||null|
create_time||analysistimestamp||text||否||null|
是|null|
|param_code||que_upvarchar||int8||否||null|
是int8||param_name||varchar||否|null|
|null是|
|null||
param_value|varchar||type_id|int8||是|null|
|type|int8|||是|否null||
null|
|
||class_id|int8||否|null|
path_ids|varchar||是|#### 报名对应的考试，允许一次考试，分为多个小考试，可以采用多个卷子，比如中考、高考。每组织一次考试，建立一条记录(exam_bas_test)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |null|
|
class_name|varchar||否|null|
|subject_id|int8||#### zj_question_category_27(zj_question_category_27)否|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|subject_zu_juan_id|int8|null||
是|null|
|type_id|int8||是|null|
|type|int8||是|null|
||subject_name|varchar||否|null|
||school_id是|null|
|question_different_id|int8||是|null|
|int8||question_different_name|varchar||是||null否|
||time|timestamp|null|
|否||null|school_name否||null|
|class_sort|int4|varchar|||否否||nullnull|
|
||create_time|timestamp|grade_id|int8|||否否||nullnull|
|
||grade_sortgrade_name||varcharint4||||否否||null|
null|
|create_time||param_codetimestamp||varchar|||否否||null|
|report_que_path|varchar||是|null|
|report_answer_path|varchar|null|
||是|param_valuenull||
varchar||kpoint_num||否int4|||否null||
null|
|score||numeric|ques_num||int4否||null||
否||nullsort|
|int4|||start_time|否timestamp||null|
||否stand_score||numericnull||
||end_time否||timestampnull||
|否||stu_idnull||
int8||status||否bpchar||null|
|否|null|
|stu_num|int4||否|null|
|pap_group|varchar||否|原卷对应的精品卷ID|
|pap_group_ab|varchar||否|精品卷AB卷组|
#### exam_report_test(exam_report_test)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |exam_pap_group
| ---- | ---- | ---- | ---- | ---- ||
varchar||否|推送的考试原卷id|
|id|int8||否|题目编号，题组是几道题一起批改，就像大题的概念|
|test_id|int8||否|null|
|param_code|varchar#### history_report_pushque(history_report_pushque)|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |
|report_id|int8||否否||nullnull|
|
||param_value|varchar|history_report_id||int8否||题型：系统编码，枚举||
否|null|
create_time||score|numeric|||否|timestamp|分值class_id|
|int8||stu_num||int4|否||null否|
|null|
||class_name|varcharmax_score||numeric||否||null否|
|null|
|subject_id||
min_score||int8numeric|||否|null|
|create_time|||timestamp否||否||nullnull|
|
question_body|path_ids|#### exam_report_test_bak(exam_report_test_bak)
subject_name||varchar||是|null|
varchar||否|null|
|school_id|int8||否|null#### zj_question_category_28(zj_question_category_28)|

| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
|school_name|test_idvarchar|||int8|否|| ---- | ---- | ---- | ---- | ---- ||
否|null|
|id|int8|||sort_uptest_name|varchar||int8|||否|null|
否||nullquestion_zu_juan_id|
|int8|||begin_time|是|null|
|timestamp|subject_zu_juan_id|int8|||que_id是||int8|null|
|否|null|
||是|null|
end_time|scoring_rule_id|int8||timestamp|否|根据上面的类型来，如果不是评分点给分，这个值为0|
||score|numeric|||是|否null||
null|
|wk_region_id||int8|entry_begin_time|||是|null|
|dift|否|nullint8||
||是|pos_x|int4||否|对图片上点击评分有用|
null|
|pos_y|int4|||否belong_org||null|
int8|null|mark_content|是|null|
|
|belong_user|int8||是|null|
|rule||grade_id||int8|varchar|||否是||nullnull|
|
|audit_user||int8||是|null|
|audit_time|timestamp||是|null|
|audit_status|int8||是|null|
|status|int8|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||是|null|
|是||test_id|int8||是null|
|null|
||remarkparam_code|varchar||是|null|
|param_value|varchar||是|null|
||score|numeric||是varchartext||null|否|null|
|
|stu_num|int4||是|null|
||max_score|numeric||question_answer|是|null|
text|min_score|numeric||是||null|
|是|null|
|question_parse|text||是|null|
|is_download|int8||是|图片下载状态  0未下载  1已下载完成|
|subject|int8||是|null|
#### zj_question_10(zj_question_10)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|question_zu_juan_id|int8||是|null|
|question_type_id|int8||是|null|
||是|null|
|update_time|question_type_name|varchar||是|null|
timestamp||ability_id|int8||是||是|null|
|ability_name|varchar||是|null|
|question_different_id|int8||是|null|
|question_different_name|varchar||是|null|
null|time|||
create_time|timestamp||#### courseware_resource(courseware_resource)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
是|null|
|id|int8||否|null|
||是|null|
|time_update|timestamp||是|null|
|time_create|timestamp||是|null|
|grade|int4||是|null|
grade_name||#### tk_que_c(tk_que_c)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
varchar||否|courseware_id||que_idint8|null|
|int8|||stu_id否||null|
|rec_id|varchar||是|null|
|status|int2||否|null|
|insert_time|timestamp||是|null|
|delete_time|timestamp||是|null|
|courseware_content|varchar||是|null|
varchar#### ad_joint_exam(ad_joint_exam)|#### delay_task(delay_task)

| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| 列名   | 类型   | KEY  | 可否为空 | 注释   || ---- | ---- | ---- | ---- | ---- |

| ---- | ---- | ---- | ---- | ---- |
|id|int8||ad_id|int8|否|null|
||message|varchar|||否否||null消息内容|
|
||res_idstate||varcharint4|||否|消息状态|
|start_time|int8|||是否||开始时间null|
|
||create_time|pic_url|timestampvarchar||||是|是null||
创建时间|
|ad_location|varchar||是|null|
|ad_url|varchar||是|null|
|create_time|timestamp||是|timestampnull#### 课程表(eer_course)|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|否|null|
||
id||int8|||entry_end_time|否|timestamp主键|
|||否|null|
create_time|timestamp||region_code||type_idvarchar|int8||是|null|
|type|int8|||是|null||
是|填写行政区划，各行政区划下面用分号隔开||
path_ids||varchar|status||int4|是||null|
否|-1停用 1 正常 2 发布分数|
|update_time|timestamp||否|null|
update_time||#### zj_question_category_29(zj_question_category_29)
timestamp|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |是|
null|
school_id|int8|||是id||null|
|creatorint8||int8||否||null否|
|null|
||question_zu_juan_idexam_type||int8|varchar||是||null是|
|null|
||class_idsubject_zu_juan_id||_int8|int8||是||是布置班级，作业用||
null|
|sub_type|int8|type_id||#### 记录看报告时候的广告设置(ad_report_conf)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |否|
nullvarchar|| ---- | ---- | ---- | ---- | ---- |
|
|是|||test_idstu_name|考试子类型：1入学考试，2周考，3月考，4期中考试，5期末考试，6学业水平考试，7联考/调考|varcharint8||||否||否null||
null|
|create_time||subject_ids|timestampvarchar|||否||否采用字符串类型，允许多个学科||
null|
|report_que_path|varchar||是|null|
|report_answer_path|varchar||是|null|
|ad_url||varcharreport_path||varchar|||否是||nullnull|
|
|kpoint_num|int4|||score_b否||numericnull|
||否|null||
ques_num||int4score_e|||numeric|否||null否|
|null||
que_attrs|time_update|timestamp||是|null|
|text||否|null|
|ques|text||否|null|
#### advert_school(advert_school)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |start_time
| ---- | ---- | ---- | ---- | ---- |
|timestamp||否|null|
|id||end_timeint8|||否|null|
|address|varchar||是|timestampnull||
|否|null|
|area||varcharstatus||bpchar||是||null否||
null|
||before_last_year_arts_alignment|ticket_novarchar||varchar||是||是null||
null|
|before_last_year_arts_average_rank||report_head_pathvarchar||是|null|
|before_last_year_arts_rank||varchar||是|null|
|before_last_year_science_alignmentvarchar||varchar|||是是||nullnull|
|
|before_last_year_science_average_rank||report_foot_pathvarchar||varchar||是||是null||
null|
|before_last_year_science_rank|varchar||是|null|
|code|varchar||否|null|
|cooperation|int4#### AI接口返回异常数据记录(homework_ai_error)|
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |否
|| ---- | ---- | ---- | ---- | ---- |null
|
|honor|varchar||是||null|
id||int8last_year_arts_alignment|varchar|||是|null|
||否last_year_arts_average_rank||varchar||是|null|
|last_year_arts_rank|varchar||null是||
null|
|last_year_science_alignment||varchar|type||varchar是||null|
||last_year_science_average_rank否||varchar|Compress图片压缩; BlankPic是否空白图片; UnderlineFind填空题作答区域坐标识别; HandWrite手写体分离; Recognition是否作答;|
|是|null||
access_url||varcharlast_year_science_rank|varchar||||是|null|
|logo_url|varchar否||是|null|
|name|varchar|||访问AI的地址否|
|null|
||paramsoffice_url||varcharvarchar|||是||是null|
|访问参数，太长可以不存||
student_url||varcharreturn_msg|||varchar|是||null|
是|AI接口返回数据|
||telbusiness_id||varcharint8||||是|否|null|
null|
||web_href是||varcharsite_id|||业务ID，每个不同的类型对应不同的表ID|
|是||remarks|nullvarchar|
|||是create_time|timestamp||null|
|是||nullcreate_time|
|timestamp||否|null|
timestamp#### homework_create_info(homework_create_info)#### App更新(app_update)

| 列名   | 类型   | KEY  | 可否为空 | 注释   || 列名   | 类型   | KEY  | 可否为空 | 注释   |

| ---- | ---- | ---- | ---- | ---- || ---- | ---- | ---- | ---- | ---- |
|create_info_id|int8||否
|作业生成信息主键|
||download_typeid||int4int8|||否||下载类型 0单页、1全册、-1无意义|
否|主键ID||
jf_id||platform_type|int8int4||||否否||1:Android  2:IOS|
对应教辅ID|
|version||class_idvarchar||int8||否||是|版本号对应班级ID|
|
|download_url||class_namevarchar||varchar|||是否||对应班级名称下载地址|
|
|int8stu_num|md5||varchar|||否是||null|
|MD5int4|
||force_update||否int4||学生数量||
否||0：不强制 1：强制tk_paper_id|
|int8||update_desc||text是|||对应作业（试卷）ID是|
|更新描述|
|create_status||int4update_time||timestamp||否||生成状态 0生成中、1生成成功、2生成失败否|
|更新时间|
|create_time||project_typetimestamp||int4||是||是否创建时间  (记录创建的时间)|
||download_urlnull|
|varchar||项目类型 1：阅卷||
|是|下载链接|
operator#### area(area)|
school_id| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
int8| ---- | ---- | ---- | ---- | ---- ||
|是|对应学校ID|
|id||create_user_id|int8int8|||是||否null|
||parentid创建生成用户的ID||
int8||name_content||是varchar|
||null|
|name|varchar||是|null|
|是||level对应教辅名称||
int4|||complete_time是||nulltimestamp|
|||是first||生成完成时间（该记录对应pdf生成完成的时间）bpchar|
|#### exam_bas_test_params(exam_bas_test_params)|class_ids||是varchar||null|
|是||classId集合ismunicipality|
|int4||grade_names||是|varcharnull||

||是hasschool|int8| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
|是|null|
|type|int8| ---- | ---- | ---- | ---- | ---- ||
|是|null|
|path_ids|varchar|||是|nullid|
|int8||否|题目编号，题组是几道题一起批改，就像大题的概念|
|test_id|int8||否|null|
|param_code|varchar||否|#### zj_question_category_3(zj_question_category_3)null
|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|param_name|varchar||id||int8|是||创建时间否|
|null|
|否|||nullquestion_zu_juan_id||
int8update_time|||param_value||varchar|是||null否||
题型：系统编码，枚举|
|subject_zu_juan_id||create_time|int8timestamp||||是否||nullnull|
|
|type_id|int8|年级名称集合|
#### 记录每个老师阅卷的流水，此表记录只应该新增，没有删除和修改的操作(exam_check_history)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|batch_no||varchar|id||int8是||是null||
批次号|
||typejf_mc||varcharint8|||是|null|
|||int4path_ids|varchar|||是|是是||null|
教辅名称|
|paper_down_type|int4||是|我的试卷下载类型：0学生pdf、1教师卷、2学生、教师卷|
#### bas_rec_busi(bas_rec_busi)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
#### 作业-教辅管理表(homework_jf_manager)|
guids|| 列名   | 类型   | KEY  | 可否为空 | 注释   |varchar
|| ---- | ---- | ---- | ---- | ---- |
|否|业务GUIDS（GUIDS、REC_ID、REC_TP联合唯一）|
|rec_id|varchar||否|资源ID|
||rec_tpid|varchar||是|附件的文件类型|
|res_desc|varchar||int8|||是否||null主键|
|
|sort_id||create_time|int4timestamp||||是是||创建时间null|
|
||update_timeuser_id||int8timestamp||||是int8||null|
|否||null|
time_update||是timestamp||修改时间|time_update|
||timestamp|是||del_flagnull|
|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|#### 100M初期用户的文件大小。(bas_resource)update_user|
int8| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
| ---- | ---- | ---- | ---- | ---- |
|rec_id||varchar|是||否修改人id||
guid|
|school_id||rec_idbint8|||是|关联学校exam_school_info表school_id|
|school_name|varchar||是|使用学校|
|info_id|varcharint8|||是||是转换后的ID，有转换才有||
关联教辅jf_info表jf_id||
name_ori||varcharinfo_name|varchar||||是是||null教辅名称|
|
||desc_res|use_gradevarchar||varchar|||是是||使用年级null|
|
|use_subject||varcharrange||int4||是||使用科目是|
|0私有||
author||varcharlen_byte|||int8que_code||varchar||是||是字节长度||
教辅作者|
|||extjf_edition||varcharvarchar|||是||是null||
教辅版本|
|status|int4||是|1正常、0可删除|
|path_real|varchar||是|服务器上面现在存放的文件路径+文件名，为相对路径|
|path_url#### 手机上传文件记录(homework_mobile_upload_record)|
varchar| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
| ---- | ---- | ---- | ---- | ---- |
|是|url路径：只保存域名后的路径|
|num_down||int8rec_id||varchar||否|资源id|
|rec_path|varchar||是||否null||
资源路径||
num_read|int8|||是|school_idnull||
int8||user_create||否|学校id，从哪个学校上传过来的|
||int8status|||否|nullint4|||是否||null状态0处理中，1二维码识别失败，2图片定位失败，3处理完毕|
|
|time_create||wk_page_idtimestamp||int8||是||是null||
homework_wk_page表id||
time_update||create_timetimestamp||timestamp||是|null||
否||team_idnull||
varchar||update_time||是timestamp||null||
是||visit_pathnull||
varchar||是|null|
否#### class_wk_wrong_que_report_task(class_wk_wrong_que_report_task)#### homework_print_task(homework_print_task)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
null|
| ---- | ---- | ---- | ---- | ---- |

| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
||que_type||print_task_idid||int8int8|||否||主键否|
|主键id|
|download_type||start_time|int4|timestamp||否||下载类型 0单页、1全册、2多章节是||
开始时间|
|jf_id|end_time||int8timestamp||||否|是对应教辅ID||
结束时间|
|school_id||school_idint8||否|对应学校ID|
|class_ids||int8varchar||||是否||学校id对应班级ID集合|
|
|school_name||class_namesvarchar||varchar||是||学校名称|
否|null|
|grade_id|int8||否|ans_level|||对应班级名称集合是|
|年级id||
paper_id|int8||grade_name||是|varchar对应作业ID||
|是||年级名称print_copies|
|int4|||class_id否||int8打印份数||
||是print_status||班级idint4|
|||否class_name||打印状态（0:未打印  1:PDF准备好  2:PDF未准备好 3:已打印）varchar|
|||download_url是||varchar班级名称||
||是|下载链接|
|name_content|varchar||是subject_id||作业/试卷名称int8|
|||是print_time||科目idtimestamp|
|||subject_name|nullvarchar|
||是||科目名称是|
|打印时间|
|stu_count||print_shop_user_idint4||int8|||是是||创建时间符合条件范围内参考学生个数|
|
|create_time||create_timetimestamp||timestamp||是||#### zj_question_category_4(zj_question_category_4)创建时间  (记录创建的时间)
|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|||id|int8||否|create_user_id|否||int8null||
|是||创建生成用户ID|
question_zu_juan_idnull|||
int8create_user_name|||tech_id|varcharint8||是|||null|
|否||subject_zu_juan_idnull||
int8||是|wk_region_id|是int8||null|
||否type_id||int8||是|null|
null||
type||int8|score|numeric||是||null否||
null|
|path_ids||varchartime_update||timestamp||否|null|
|que_group_id||是int8||null|
|是|null|
timestamp#### 学校类型、班级类型、学生类型、考试类型，科目类型、年级(exam_code_dirs)||是|修改时间|
|del_flag|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
int2|| ---- | ---- | ---- | ---- | ---- |
|是|删除标识。默认为 0：未删除；1：已删除|
|dir_id|int8||create_user|int8|||创建生成用户名称|是||
创建人id|
|name||varcharsubject_names|||varchar是||名称|
|否||dicts|int2|null|
|是||dir_code|单词总量|
是|#### exam_report_class_que_ans_joint(exam_report_class_que_ans_joint)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|nulltotal_packages||
int2||act_id|int8||否|null|
|class_id|int8|||varchar是否|null|
||create_time|timestamp|||是||null课程包总量|
|
|school_id||int8|bottom_x||int4|是||关联机构（学校）表（exam_school_info）id是|
|null|
|publish_date||bottom_ydate||int4||是||是发布时间|
|null|
|expiry_date||sort_nodate||int4|||是是||nullnull|
|
|score_intel|numericint8|||否|null|
|que_types|int8||否|null|
|是||null#### 课程包表(eer_course_package)|

sub_id|| 列名   | 类型   | KEY  | 可否为空 | 注释   |int8
| ---- | ---- | ---- | ---- | ---- |
||否|id|int8|||否null#### 一张答题卡如果多次扫描并导入多次，则只取指定的某一张(exam_wk_sheet)|
主键| 列名   | 类型   | KEY  | 可否为空 | 注释   ||

| ---- | ---- | ---- | ---- | ---- |
|title|
|
||create_time|timestamp|||是|question_bodywk_sheet_id创建时间|
||int8update_time||否|做题编号|
|test_id||int8timestamp||||是否||null修改时间|
|
||del_flagpap_id||int2int8||||是否||删除标识。默认为 0：未删除；1：已删除考试ID|
|
|create_user||school_idint8||int8|||是否||创建人id|
学校ID||
course_id||int8ticket_no||varchar||是|否关联课程表id||否|null准考证号|
|
|
|stu_id|||gradeint8||int8||否|否||null||
任务创建时间|
|status|int4||是|任务状态 0初始化  1报告生成中，2报告已经生成，3报告生成失败|param_code||
varchar||否|null|
|param_value|varchar|||否operator||nullvarchar|
|||是que_id||任务发布者int8|
|||pdf_path否||varchar||是|nullpdf生成的路径|
|
||finish_timeschool_id||timestamp||是|任务结束时间|
int8|||operator_id否||nullint8||是|任务创建者的id|
|stu_ids||
_int8||stu_num|int4|||是否||nullnull|
|
|pdf_answer_path|varchar||是|错题答案pdf地址|
|homework_ids|_int8||是|筛选的作业|
varchar#### exam_report_gov(exam_report_gov)#### class_wrong_que_report_task(class_wrong_que_report_task)

| 列名   | 类型   | KEY  | 可否为空 | 注释   || 列名   | 类型   | KEY  | 可否为空 | 注释   |

| ---- | ---- | ---- | ---- | ---- || ---- | ---- | ---- | ---- | ---- |

||idid||int8int8||||否否||null主键id|
|
||start_timeschool_id||timestampint8||||是否||开始时间null|
|
|end_time||timestamptest_id|||int8|是||结束时间否|
|null||
school_id|int8||param_code|varchar||是||学校id|
否|null||
school_name|varchar||param_value|varchar|||否|null|
|score|是numeric||学校名称|
|否||null|
grade_id||int8stu_num||int8||是|否|null|
|max_score|numeric||否|null||
年级id|
|min_score||numericgrade_name|||varchar否||null|
|是|年级名称||
sort_no||int4class_id||int8||否||null是|
|班级id||
create_time|timestamp||class_name||varchar|否||null是|
|班级名称|
是#### exam_report_grade(exam_report_grade)|
subject_id||| 列名   | 类型   | KEY  | 可否为空 | 注释   |科目名称集合
|
| ---- | ---- | ---- | ---- | ---- |
||int8idgrade_names||int8|varchar||否|||题目编号，题组是几道题一起批改，就像大题的概念|否|null|
|dir_name|varchar||
||否grade||nullint8|
|||dir_type|int4否||试卷编号||
|school_id|int8||否|null|
否|test_id||int8学校类型、班级类型、学生类型、考试类型，科目类型，这个见系统编码表||
|否||nullstatus|
|int4||param_code||否varchar||null|
|否||null|
sort_no||numeric|param_value|varchar|||否|否null||
题型：系统编码，枚举|
||scoreupdate_time||numerictimestamp|||否||否null||
分值|
学生ID：根据准考证号自动关联#### exam_composition_info(exam_composition_info)|stu_num|int4||
|否|null
|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|sort||int4||info_id||int8否||null|
|score否||max_scorenull||
int4||numeric|test_id||int8否||本次阅卷最终得分|
|status||int4否|null|
|pap_id|int8||否|null|
|||否path_real|varchar|状态：-3违纪，-2,缺考-1作废、0草稿、1校对完毕、2选中、3批阅完成|
|sheet_id||int8|||否否||nullnull|
|
|user_create||int8title||varchar||否||否nulltotal_dicts|
|新增人|
||time_createint4||timestamp||content||是varchar||单词总量|
|否|null|
|update_time||package_name|timestampvarchar|||是||否课程包名称||
null|
|end_date|create_time||date|timestamp|||否是||截止时间null|
|
||voice_statusstatus||int2int4||||是|否|机器音轨状态（0：未校验；1：已校验）text||否|null|
|question_answer||
text|||是|null|
|question_parse|text||是|null|
|lock_statusis_download||int8int2||text|||否|null|
|num_option是||int8停/启用状态（0：停用；1：启用）||
|否|null|
||publish_statusanswer_img||int2varchar||||是否||课程包发布状态（0：未发布；1：已发布；2：预发布）|
null|
|publish_date||dateanswer||text||是|发布时间||
否|null|
|recite_type||analysis_img|int2varchar||||是否||null|
背诵模式（0：普通模式；1：图文模式；2：全部）|
||analysis0:草稿;1:校对完成;2:部分批阅;3:批阅完成|
|full_score|numeric||text||#### 课程包-单词表(eer_course_package_word)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- ||
否|否||nullid|
|null|
|int8que_up|||int8||否||主键否|
|null||
create_time||timestamp否||新增时间|
|是||创建时间sort_up|
|||int8update_time||timestamp||否||null|
是||修改时间dift|
|int8||del_flag||int2否||null||
是|删除标识。默认为 0：未删除；1：已删除|
||belong_org||create_userint8|int8|||是否||创建人id|null|
|否||course_package_idnull|
|int8||belong_user||int8是||关联课程包表（course_package）id|
|否||null|
school_word_id||int8rule|||varchar是|||关联机构单词表（school_word）id否|
|null|
|course_id||audit_user|int8int8||||是否||关联课程表（course）idnull|
|
|audit_time|timestamp||否|null|
|audit_status|int8||否|null|
#### 首页轮播图(eer_first_page_image)|
status|| 列名   | 类型   | KEY  | 可否为空 | 注释   |int8
| ---- | ---- | ---- | ---- | ---- |
||id||int8否|||否|null|
|smaller_image_url|null|
varchar|是|remark||varchar||年级名称集合|
否|null||
是||缩略图urltime_update|
|timestamp|||否image_url||null|
varchar||time_create||是timestamp||大图url||
否|null|
|image_name||varchargrade|||int4是|||图片名称否||
null|
|create_time|timestamp|||是#### tk_que_d(tk_que_d)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |是|
| ---- | ---- | ---- | ---- | ---- ||
创建时间|
科目id||
update_time||timestampque_id||int8||subject_name||varchar|否||是|null科目名称|
|stu_count|int4||是|符合条件范围内参考学生个数|
|
|create_time|site_id|int8||否|null|
|que_code|varchar||否|null|
|que_type|int8||否||null|
timestamp|que_types|int8|||否||是|null任务创建时间|
|
|sub_id|int8||否|null|
|title|text||||否|null|
|batch_nonum_option|int8||否|null|
status||int4answer_img|||varchar是||任务状态 0初始化  1报告生成中，2报告已经生成，3报告生成失败|
||否operator|varchar||是|任务发布者|
|pdf_path|varchar||是|pdf生成的路径|
||null|
|
|min_score|int8|||answer|text|否||否null||
null|
|create_time||analysis_img|timestampvarchar||||否否||nullnull|
|
|analysis|text||否|null|
|que_up|int8||否|nulltime_update#### exam_report_grade_bak(exam_report_grade_bak)|

|| 列名   | 类型   | KEY  | 可否为空 | 注释   |sort_up
|| ---- | ---- | ---- | ---- | ---- |
|id|int8||int8是||null||
否|null|
|grade||diftint8|grade_idint8|||int8是||null|
|||school_id||否|int8null||
|是||belong_orgnull||
int8||test_id||否int8||null||
是|null|
|belong_user||param_codeint8|varchar||是|null|
|param_value|varchar|||是||null|
否|null|
|score||numeric|rule||varchar是||null||
否||nullstu_num|
|int4|||audit_user是||int8null||
||否sort||nullint4|
|||audit_time是||timestampnull||
|||否|null|
||audit_status是||null|
int8||max_score否||int4null||
||是status||null|
int8|||min_score否||int8null||
|是||nullremark|
|varchar||create_time|timestamp||是|null|
否#### exam_report_grade_joint(exam_report_grade_joint)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
||否id||nullint8|
||年级id|
|否||original_content|nullvarchar|
|||否|ocr识别的原始内容|
act_id||timestamp||否|null|
|int8scan_status||int4||否||是null||
null|
|create_time|timestamp|||check_status否||int4null||
||是grade||nullint8|
||否|null|
|place_id||max_scoreint8||numeric||是||否null||
null|
|print_count||int4min_score||numeric||是|学生有痕答题卡打印次数||
否|null|
|param_code|varchar||否|null|
|param_value|#### excel_url_joint(excel_url_joint)
varchar|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- ||
否|null|
||school_id|idint8||int8||否||否null|
|null|
||score|name|varcharnumeric||||否|否null|
|null|
||sort|act_idint4||int8|||否否||nullnull|
|
|stu_num||int4reg_code||varchar||否||null否||
null|
|create_time|timestamp||否|null|
#### exam_report_joint(exam_report_joint)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
url| ---- | ---- | ---- | ---- | ---- ||
varchar||否||idnull||
int8||否|null|
|act_id|int8||否|null|
|class_sort|int4||否|null|
|create_time|timestamp||否|null|
|grade_sort|int4||否|null|
|param_code|varchar||否|null|
|param_value|varchar|finish_time#### tk_que_opts_d(tk_que_opts_d)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |
timestamp||||opts_id否||null|
int8|是|reg_code||varchar|否||null否|
|null|
|que_id||scoreint8||numeric||否||null否|
|null||
sort||int8||否|null|
|sortopts_code||int4|varchar||否||null|
|stu_id|int8||否|null|
否|null|
|opts_txt|text||否|null|
#### exam_report_points(exam_report_points)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
#### tk_report_error(tk_report_error)|
id| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
int8| ---- | ---- | ---- | ---- | ---- ||
|否|null|
|id||test_idint8||int8||否||是null||
null|
|que_id||int8pap_id|||int8否||null|
|是||null|
time_create||timestampque_id||int8||否|null|
|time_update|timestamp|||是|是null||
null|
|que_type|||mistake_typevarchar||_int8||int8||是||null是|
||null|
status||stu_idint4||int8||是||null是|
|null|
|ans_id|int8||是|null|
#### tk_section(tk_section)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
point_id| ---- | ---- | ---- | ---- | ---- ||
int8||是|更新时间|
|del_flag|sec_id|int8||否|题型ID|
int2||pap_id|int8|是|null|
|create_user|int8||是|创建人id|
是#### 课程-单词表(eer_package_user)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8|||批次号否|主键|
|
|create_time|timestamp||jf_mc||varchar|是|是||教辅名称|
创建时间||
paper_down_type|int4|||update_time|是|我的试卷下载类型：0学生pdf、1教师卷、2学生、教师卷|
timestamp||是|修改时间|
|del_flag|int2||是|删除标识。默认为 0：未删除；1：已删除|
|create_user|int8||是|创建人id|
|student_id|int8||是|关联学生表（student）id|
|package_id#### homework_process(homework_process)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|int8||homework_process_id||int8|是|否||关联课程包表（course_package）id试卷编号|
|
|type|homework_name|varchar|||是|作业名称|
int2|tk_paper_id||int8|||否|试卷ID(作业ID)|
是||school_id 背诵模式（0：普通模式；1：图文模式；2：全部）|
|int8||否|学校ID|
|school_name|varchar||否|学校名称|
#### eer_recommend_read(eer_recommend_read)
|grade_id|int8| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
|| ---- | ---- | ---- | ---- | ---- |否|年级ID
|
|grade|varchar||否|年级编码，不是ID||
id|class_id||int8|int8||否|班级ID|
||class_name|否|varchar|null||
否|班级名称|
||subject_ids|_int8||否|article_name科目，数组|
||page_total|varcharint4|||否|作业总页数(一张两页)|
||page_submit|int4是|||否|已提交页数（一张两页）文章名称|
|
|stu_total|int4||否|班级总人数，应交人数|
||submit_total|article_image_urlint4|||否varchar||已交人数|
|objective_que_total|int4||是||否|客观题数|
文章对应图片url|objective_que_correct||
int4||否|客观题正确数|
|article_body|subjective_que_total|int4|||否|主观题数|
text||subjective_que_correct|int4||否||主观题正确数|
是|文章正文|que_total|
|int4||否|本次作业有几个题目(不含大题)|
|corrected_total|int4||否||create_time|timestamp||是|null|
|update_time|timestamp||是|null|
|del_flag|int2||是|null|
|create_user|int8||是|null|
|任务结束时间|
|operator_id|int8||是|任务创建者的id|
|stu_ids|_int8||是|null|
|pdf_answer_path|varchar||是|错题答案pdf地址|
|test_ids|_int8||是|筛选的考试|
#### stu_date(stu_date)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|year|int8||是|null|
|schoolname|int8||是|null|
|grade|varchar||是|null|
|class|varchar||是|null|
|classid|int8||是|null|
|subject_type|varchar#### tk_paper_d(tk_paper_d)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pap_id|int8||否|null|
|site_id|int8||否|null|
|pap_code|varchar||否|null|
|pap_name|varchar||否|null|
|pap_type|int8||否|null|
|score|int8||否|null|
|grade_type|int8||否|null|
|term_type|int8||否|null|
|reg_prov|varchar||否|null|
|reg_city|varchar||否|null|
|reg_county|varchar||否|null|
|remark|varchar||否|null|
|time_publish|timestamp||否|null|
|time_update|timestamp||否|null|
|time_create|timestamp||否|null|
|type|int4||是|null|
|textbook_id|int8||是|null|
|subject|_int8||是|null|
#### tk_paper_exam(tk_paper_exam)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|试卷绑多答题卡中间表|
|pap_id|int8||是|null|
|create_time|timestamp||是|null|
|exam_name|varchar||是|null|
|sheet_name|varchar||是|null|
|exam_id|int8||是|null|
|sheet_id|int8||是|null|
#### 试卷题目(tk_paper_que)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pq_id|int8||否|序号|
|pap_id|int8||否|试卷ID|
|que_id|int8||否|题目ID|
|pq_type|int8||否|分类ID|
|score|numeric||否|得分|
#### 这个考试的考点分布(exam_place_distr)|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
desp|varchar||否|描述|
|tree_path||test_idvarchar||int8||否|null|
||place_id|int8||否|time_update否||nulltimestamp|
|||update_time|树路径||
否|timestampnull||tree_up|int8||否||subjectnull|
|int8||是||null否|
|上级ID|
|tree_lev|int8||否|树级别|
|tree_sort|int8||否|树排序|
|sec_id|int8||是|null|
|#### 出版物的章节属性(exam_publication_attr)
que_name|varchar|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|是|题号|
||attr_id|int8|#### zj_question_11(zj_question_11)
| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
否| ---- | ---- | ---- | ---- | ---- ||
null|
pap_que_in_id||textbook_attr_idid||int8||int8|int8||否|null|
|question_zu_juan_id||int8否||null||
是||nullchapter_name|
||varcharquestion_type_id|int8|||否||null是||
null|
|su_id||int8question_type_name|varchar||||否是||null|
null|
||ability_idupdate_time||int8||是|null|
|ability_nametimestamp||varchar||否|null|
|是|null|
|question_different_id||
#### 将几道题目合成一个题块进行阅卷，记录题块的信息(exam_que_group)int8|||是|time_create|null|

| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|timestamp| ---- | ---- | ---- | ---- | ---- |question_different_name
|varchar||id|int8||是||否null||
null|
||timegroup_name||timestampvarchar|||否||否null||
null|
|question_body||questions|text_int8||||否|否null||
null|
|is_merger_score||int4|question_answer||text||否|null|
|是|null|
||creator是||int8null||
|否||nullquestion_parse|
||textcreate_time||timestamp||是|null||
否||nullis_download|
|int8||test_id||是int8||null|
|否||null|
subject||pap_idint8||int8||是||否null||
null|
|subject_id|int8||否|null|
已批改题目数量||
|has_score|int4|sort_no|int4|||是|null|
否|1有0无|
|threshold|numeric||否|阈值|
|report_push_status|int4#### exam_que_group_temp(exam_que_group_temp)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- ||
|否|0未推送，1已推送|
||id|report_push_time|timestamp|int8|||是|null|
|group_name|varchar||是|null|
|questions|_int8||是是||null|
报告推送时间||
is_merger_score||create_timeint4||timestamp|||是否||null|
null|update_time||
|creator|int8|timestamp||否|null|
|status|int4||否|0正常，1删除|
|ans_sheet_answer_type|int4||否|客观题类型，0填涂，1手写|
||是scanning_que_total||null|
int4||否|已扫描的题目总数(一个学生一道题算一个，不含大题)|
||create_timelast_upload_time|timestamp||timestamp||否|最后一个答题卡的上传时间|
|last_correct_complete_time|timestamp||是|最后一次批阅完成时间|
|teacher_ids|_int8||是|任课教师|
|listen_template|int4||否|听写模板(双栏)：0否，1是|
|是|null|
|test_id|int8||是|null|
|pap_id|int8||是#### 记录题目AI识别后的作答区域(homework_que_position)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|null|
|id||subject_id||int8|否|试卷ID|
|que_type||int8|||是否||题型null|
|
|sort_no||que_typesint4||int8||是||null否|
|综合题型：1-7|
|sec_name|varchar||否|题型名称|
|note_head|varchar||否|前注|
|note_below|varchar||否|尾注|
|len_min||#### 一个题目可以有多个图片(exam_que_pic)int8||否|时长||

|是num_que|| 列名   | 类型   | KEY  | 可否为空 | 注释   |int8
|| ---- | ---- | ---- | ---- | ---- |
|否||题目数||
que_pic_id||contentint8|null|varchar||
|否|内容|
||score_secpoint_name|varchar||是|null|
||int8score||numeric||否||总分数|
是|null||
score_que|numeric|||否|每题分数|
pap_score|sort_pap||int8||否numeric||排序|
|is_choose||int8|是||否null||
是否选做|
||time_update|timestamp|create_time||否|timestamp更新时间||
|是|null|
#### 学科(tk_sub)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|sub_id|int8||否|学科流水|
|stage_id|int8||否|教学阶段【枚举】：1小学、2初中、3高中|
|sub_type|int8||否|学科类型【枚举】：语文、数学...|
#### 考试错推题报告(exam_report_que)|sub_name
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- ||varchar|
|否|学科名称|
||sub_code|varchar||否|学科编码|
report_id||sortint8|int8|||否|排序，在同一阶段下的排序|
|status|int8|||否否|状态：-1停用、1正常|
||remark|varcharnull|
||否|备注|
||batch_idtime_create||timestampint8|||否|创建时间|
||time_update|是timestamp|||否null|修改时间|
|
|school_id|int8||是|null|
|school_name|varchar||是|null|
|grade_id|int8||是|null|
|grade_name|varchar||是|null|
|class_id|int8||是|null|
|class_name|varchar#### valid_set_essay(valid_set_essay)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |
|是|essay_id||int8|null||
否|null|
||essay_set|int4||是|subject_idnull||
int8||essay|varchar|||是|是|null|
null|domain1_predictionid||
int8||是|null|
|subject_name|domain2_predictionid|int8|||varchar是||null|是|null|
||
stu_num|int4|int8#### wd_word_view(wd_word_view)|是||null|
|status|
int4|||否是||| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
1--生成中   2--生成成功  3--生成失败|
主键|
||wid||create_timetk_pap_id||#### 托福的短文音频、图片音频、题目音频、准备音频、答题音频也保存在这里，只保存资源id(que_extend)int8
varchar| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |
|是|null|
|word||ext_id||否int8||tk_pap_id|
||否tk_que_id||nullint8|
|||busi_id|int8||否否||题目IDnull|
|
||tk_ans_cell_idext_key||int8int8||||否否||nulltk_ans_cell主键|
|
|ext_value|varchar||model_pic_res_id||否|varcharnull||
||否sort_no||题目模板图片的IDint4|
||||否model_pic_res_path||这里指同一个属性有多个值，他们间的排序，默认为1|
nosid||int4|time_update||varchartimestamp||||否否||null题目模板图片资源地址|
|
|sort_no|int4||否|一个题目多个cell时的排序|
|create_time|timestamp||否|null|
|update_time|timestamp||否|null|
|multi_tk_position|varchar||是|多空位置（相对于模板图）|
#### 报错修改历史表(que_mistake_history)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|||否|null|
|grade|int4|id|int8|||否否||nullnull|
|
|que_id|int8||否|题目tk_que的que_id|
|grade|int8||否|null|
|sub_id|#### tk_que_e(tk_que_e)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
int8||否|null|
|||time_create是|timestamp||否|报错时间|
||time_modify录入表pap_que_in的题目id|
|timestamp||是|修改时间|
|user_modify|int8||是|修改人|
|mistake_type|_int8||否|null|
|user_create|int8||否|报错人|
que_id#### que_paper(que_paper)
#### tk_paper_que_c(tk_paper_que_c)|
int8|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |否|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
题目ID|
||pq_id||pap_idint8||site_idint8|||否否||null试卷ID|
|
|||pap_idint8||int8||否|null|
|que_id|int8||否|null|
|pq_type|int8|||否否||null网站ID|
|
||que_code|scorevarchar|||否numeric||题目编码|
||que_type|否int8||null|
|desp|varchar|否|题型【字典】：选择题、填空题..#### que_article(que_article)|
|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- ||
否|que_types||nullint8||art_id|int8||否|文章编号|
|art_code|varchar||是是||null|
|sid|int8|试卷编号6+section2+阅读1+文章序号1|
|否||nullread_id|
|int8||name||varchar否|||阅读编号是|
|null||
title|varchar||否|标题|
|title_cn|varchar||否|题目译文|
|content|varchar||否|内容|
|content_cn|#### stu_pdf_url(stu_pdf_url)varchar
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |是
|中文译文|
|note_head|varchar|||id是||int8前注||
||否note_below|varchar||null||
是||尾注stu_id|
||int8source|||否|null|
|act_id|int8|varchar|||否|是null|
||status|int4||否|null|
出处||
update_time||timestamptheme|varchar||||否是||null主题|
|
||sort_nourl||int4varchar|||是||是阅读内排序，从小到大||
null|
|time_update|timestamp|||是|check_status更新时间||
int4||是|null|
|#### stu_self_ans(stu_self_ans)varchar||是|null|
#### 包括能力、知识点等(que_attr)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |

| ---- | ---- | ---- | ---- | ---- || 列名   | 类型   | KEY  | 可否为空 | 注释   |

| ---- | ---- | ---- | ---- | ---- |
|phonetica||idattr_id||int8int8||||否否||属性编号，系统自动产生null|
|
||user_idattr_code||int8varchar|||否||否null||
属性编码|
|test_id||nameint8||varchar||否||null|
否||属性名称que_id|
||name_cn|varchar||否|属性名称中文int8|
|||否name_short||nullvarchar|
|state|int2||否||1:未掌握 2：已掌握||
否|简称||
create_time||timestampattr_up||int8||否||否null||
上级节点|
|lev|int4||否|级别：第1级为0|
#### stu_test_selfans(stu_test_selfans)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |sort_no|
int4|| ---- | ---- | ---- | ---- | ---- |
|否|从小到大，从1开始|
|id||attr_typeint8||int8|否|null|
|test_id||int8||否||否(枚举)属性分类信息 见字典表，这里主要是能力和知识点|
|org_id|int8||否|机构编号：0公司|
|null||
subject||int8user_id|int8||否||null|
|否||nullstate|
|int2||key_stage||int8否||null||
否||nullcreate_time|
|timestamp||user_create|int8||否||null|
否|添加人|
timestamp#### subject(subject)|
status| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
| ---- | ---- | ---- | ---- | ---- ||
||idint4||int8|||否是||-1删除 0草稿 1有效null|
|
||time_updatename|varchar||timestamp||是||null否|
|更新时间|
|remark|varchar||否#### sys_login(sys_login)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |备注
|
| ---- | ---- | ---- | ---- | ---- |
|grade|int8|||是dbid||nullint8|
|||term否||int8|null|
|是||nulluser_id||
int8||sys_code||int8是||null|
|是||nullland_dir||
int4||是|1登录
-1超时
0退出|
|stamp|timestamp|#### que_attr_bak(que_attr_bak)|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
是| ---- | ---- | ---- | ---- | ---- ||
null|
|online_time||int8attr_id|||int8是||null|
|是||ipnull||
varchar||attr_code||是|varcharnull||
|是||nullmac|
|varchar||name||varchar是||null||
是||nullport|
|varchar||name_cn||varchar是||null|
|是||osnull||
varchar||name_short||varchar|是||是null|
|null||
os_ver||attr_upvarchar||int8||是||null|
是|null||
prog_cate||levvarchar||int4|||是是||nullnull|
|
||sort_noprog||int4varchar|||是||客户端系统类型：IE、ios、android是|
|null|
||prog_verattr_type||varcharint8|||是||是客户端系统版本：maxthon、ie、火狐、ios7||
null|
|dev_brand||org_idvarchar||int8||是|设备品牌：小米、三星、华为||
是|null|
|dev_type||varchar|subject||int8是||null||
是||nulldev_id||
varchar|||key_stage|是int8||针对移动端通讯设备ID|
||是pattern||nullvarchar|
||是||user_createnull||
int8|||tid|是varchar||null|
|是||statusnull||
int4|||user_role是||varcharnull||
|是||nulltime_update||
timestamp||client_app||是varchar||null||
是||nullremark|
|varchar||是|null|
|grade|int8|#### sys_menu(sys_menu)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |是
|| ---- | ---- | ---- | ---- | ---- |null
|
|term|int8||menu_id||int8是|||null否|
|null|
|menu_url|varchar||否|null|
|menu_name|varchar||否|null|
|sup_menu_id#### 这个表和cece题目共用一个属性表，如果exam_paper表中的pap_id_cece有值，则表示是通过测测的试卷维护进来的，则用pap_id_cece来查询，否则用exam_paper中的pap_id来查询，题目、试卷的相关属性存放这里(que_attr_busi)|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |int8
|| ---- | ---- | ---- | ---- | ---- |
|否|null|
|is_leaf|int4||busi_id||否int8||1为叶子菜单|
|否|业务ID：阅读ID、文章ID、题目ID|
|attr_id|int8||sort||int4|否||null否|
|null|
||leveltime_update||int4timestamp|||否||是null||
null|
|time_update|timestamp#### que_attr_busi_c(que_attr_busi_c)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- ||
否|null|
|busi_id|int8||否|null|
|attr_id|int8||否|#### 系统QR信息存放表(sys_qr_info)null
|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|time_update|timestamp||id|int8|||是否||null|
null|
||zj_attr_idtype||int8int4||||否是||类型：0作业,1作业重新识别null|
|
|content|varchar||否|QR内容json|
#### que_attr_busi_d(que_attr_busi_d)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|create_time||timestampbusi_id||int8||否||否null|
|null|
|attr_id|int8|#### sys_region(sys_region)
| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
否| ---- | ---- | ---- | ---- | ---- ||
null|
||否||reg_codenull|time_updatevarchar||timestamp||否||国家发布的行政区域编码是|
|null|
|name_cn|varchar||zj_attr_id||int8否||中文名称||
是|null|
|name_en|varchar||是|名称英文|
|short_cn|varchar||否|中文简称|
#### que_attr_c(que_attr_c)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |shrot_en
|varchar||是|简称英文|
||attr_idspell_all||int8varchar||否|中文全拼|
||spell_first||varchar|否||否|null中文简拼|
|
||attr_code|varchar||否|null|
|timespan|name|numericvarchar|||否||是null||
时差：与北京的时差|
|name_cn||up_codevarchar||varchar|||否否||nullnull|
|
||name_short|varcharlev|||int4否||null|
|否||从1开始attr_up|
|int8||sort||int4|否||null否|
||同级别里的排序，从小到大lev|
|int4||status|int4||否||null否|
|1启用、0停用||
sort_no|int4|||remark否||varcharnull||
||否attr_type||备注int8|
|||area_code否||varcharnull||
|否||区域划分|
org_id||zipint8||varchar||否||是null||
右边|
||subjecttime_update||int8timestamp||||否否||更新时间|
null|
|key_stage|int8||否|null|
|user_create#### 记录报告(sys_report_pay)|
int8| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
| ---- | ---- | ---- | ---- | ---- |
|否|null|
|pay_id||int8|status||int4否|||null|
否||pay_id_innull||
varchar||time_update||timestamp否||null||
否|null|
|pay_account||remark|varcharvarchar||||否否||nullnull|
|
||gradetest_id||int8int8||||是否||null|
null|
|user_id||int8|term||int8否||null|
|是|null|
|pay_money||sys_codenumeric||int8||否||null|
是||pay_status|nullint4|
||否|0-未支付 1-已支付
|
|update_time|timestamp#### que_attr_d(que_attr_d)|
| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
否| ---- | ---- | ---- | ---- | ---- ||
null|
|attr_id|int8||否|null|
|attr_code|varchar||否|null|
|name|varchar||否|null|
|name_cn|varchar||否|null|
|name_short|varchar||否|null|
|attr_up|int8||否|null|
|lev|int4||否|null|
|sort_no|int4||否|null|
|attr_type|int8||否|null|
|org_id|int8||#### sys_role_menu(sys_role_menu)
否| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
null| ---- | ---- | ---- | ---- | ---- ||

|subject|int8||role_id||int8|否||否null||
null|
||key_stagemenu_id||int8|int8||否|null||
否|null|
||time_updateuser_create||timestampint8||||否否||nullnull|
|
|status|int4||否|null|
|time_update|timestamp#### 存储系统的各类配置参数缓存(sys_set)|
| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
否| ---- | ---- | ---- | ---- | ---- ||
null|
|remark||varcharskey||varchar||否||null否|
||nullgrade|
|int8||sname||varchar是|||null|
是||nullterm|
|int8||svalue||varchar|是||null是|
|null|
|sort|int4#### que_attr_relation(que_attr_relation)|
| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
是| ---- | ---- | ---- | ---- | ---- ||
null|
||classret_id||varchar|int8|||是否||null关系编号，系统自动产生|
|
||remark|attr_idvarchar||int8|||是否||null属性编号|
|
|time_update||up_attr|timestampint8||||否是||上级属性编号null|
|
||levuser_id||int8int8||||是否||null|
级别|
|status||test_typeint4||是int8||是||1正常     0删除|
null|
|否|考试类型||
complete_time||#### 记录微信绑定的信息(sys_user_bind)subject
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |int8|timestamp
|| ---- | ---- | ---- | ---- | ---- |否
|||学科bind_id|
||varchar||attr_type||int8否||null|
||否user_id|属性类别|
|score_min|numeric||否|评分最小值|
||int8|score_max||numeric|否||否null||
评分最大值|
|mobile|varchar||time_update||是timestamp||null|
||否status||维护时间int4|
||否|null|
|update_time|timestamp||是|null|
|#### QQID、微信ID、支付宝ID只用于登陆，不提供给用户编辑，SYS_USER表中的email，QQID、微信web、微信mobile、微信ID、qq等字段将不在使用(sys_user_contact)varchar||是|null|

| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|audioa||contact|varchar|varchar||否||null|
|user_status|int4||否|状态：0申请、1正常|
是|user_id|int8||否|题型【字典】：1-7类|否|null|
|contact_type|int4||
|否|1、邮箱 2、手机 3、qq 4、qqID 5、微信ID 6、支付宝ID|
||sub_id|is_checkint8||int4|||否否|学科ID|
||nulltitle||
text|||update_time|否timestamp||题干|
|num_option|int8||否|选项|
|answer_img||varchar||
否|否|答案图片|
|answer|text||否|标准答案|
|analysis_img|||tree_pathnull|
varchar||||token否||解析图片varchar|
||是|refresh_token|
|pap_codeanalysis|#### QQID、微信ID、支付宝ID只用于登陆，不提供给用户编辑，SYS_USER表中的email，QQID、微信web、微信mobile、微信ID、qq等字段将不在使用(sys_user_contact_his)
varchar|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- ||
否|试卷编号||
contact|varchar||否|null|
|||pap_name|user_statusvarchartext|||否||int4否||试卷主标题解析|
|
||pap_subnameque_up|int8||varchar||否||否一题多个小题时,主题目的编号(类似阅读理解)||
试卷副标题|
|sort_up||pap_info|varchar||否|试卷信息栏|
int8|||grade|int8||否|年级|
|subject|int8|否||题目排序：一级题目没有排序，从1开始，默认0否|
|科目||
dift|int8||dift|int8||否||难度【枚举】：0未定义、1容易、3普通、5困难否|
|题目难度累计和||
belong_org||int8|score||否int8||系统题库|
|否||总分数belong_user|
|int8|||num_sec否||int8所属人员||
|否||rulevarchar|单元数|
||num_que||int8否|nullvarchar||||否否||判分规则题目数|
|
|audit_user||len_minint8||int8|||否否||时长分钟审核人|
|
|audit_time||status_edit|timestampint8||||否否||审核时间编辑状态：0未编辑、1编辑中|
|
||audit_statusstatus||int8int8|||否|审核状态：-1审核不通过、0待审、1审核通过|
|status|int8|||否否|||状态：0草稿、1发布、-1作废|
null||
ext_zdx|int8||否|装订线状态：-1停用、0草稿、1正常|
|
|ext_bmbj||remark||int8varchar||||否否||保密标记备注|
|
|ext_srl||time_updateint8||timestamp||否||否考试输入栏||
更新时间|
|ext_yfl||int8time_create||timestamp|||否否||添加时间誊分栏|
|
|grade||ext_zysxlint8||int8||否||否null||
注意事项栏|
|score|ext_jbjz||numericint8||||否是||卷标卷注null|
|
|org_id||mistake_typeint8||_int8||否||是所属机构||
错误类型|
|user_create||int8answer2|||text否||创建人||
是||time_createnull||
timestamp|||area否||varchar创建时间||
||是time_update||nulltimestamp|
|||否year||修改时间int4|
||是|null|
|source|varchar||是|null|
|papertype|varchar||是|null|
#### que_paper_que(que_paper_que)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
#### tk_que_opts(tk_que_opts)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|pq_id|int8|||opts_id否||int8试卷题目ID||
||否pap_id||nullint8||
|否||试卷IDque_id|
|int8|||否sec_id||nullint8||
|否||sort题型ID||
int8||que_id||int8|否||null否|
|题目ID：只存小题ID|
|opts_code||que_up|varcharint8||||否否||null|
上级题目ID|
|opts_txt||que_typetext||int8|||否否||题型null|
|
|sort_sec|int8||否|题型排序|
#### tk_que_opts_c(tk_que_opts_c)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |sort_pap
|| ---- | ---- | ---- | ---- | ---- |int8
||否||试卷排序opts_id|
|int8||time_update||timestamp|否||否null||
更新时间||
que_id|int8||否|null|
#### que_question(que_question)|
sort|int8|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|| ---- | ---- | ---- | ---- | ---- |否
|null|
||opts_codeque_id||varchar|int8||否||否null||
null|
|opts_txt||que_codetext||varchar|||是否||null|
null|
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
|read_top|是int8|null|
|test_ids||否||varchar阅读顶级ID|
||sort_no||是|null|
int8||start_time|timestamp||是||是阅读(READ_ID)下的排序[2016.7.26增加]|
|null|
|end_time|timestamp||是|null|
#### que_read(que_read)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|
||pap_page_id|int8|read_id|int8|#### 报告学生(exam_report_que_stu)|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
否| ---- | ---- | ---- | ---- | ---- ||
编号|
|title|varchar||否||id|阅读标题|
int8||note_head|varchar|否|null|
|report_id|int8|||否||阅读前注|
|note_below|varchar||否|是阅读尾注|
|null|
|test_type|int8||stu_id||否int8|||是|null|
|stu_name|考试类型phonetice|
varchar|||是|nullvarchar|
||create_time||subjecttimestamp|||是|null|
|complete_time|timestamp||是|null|
|status|int4|||
是|tree_up|int8|int8||否|||1--生成中  2--生成成功  3--生成失败null|
|
否||tree_lev||push_que_pathint8||varchar|||否是||nullnull|
|
|tree_sort||push_answer_path|varchar||int8是||null||
否|null||
report_head_path|varchar||是|null|
|report_foot_path|||否|状态：0申请、1正常#### tk_paper_que_d(tk_paper_que_d)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
|
| ---- | ---- | ---- | ---- | ---- |
varchar|||user_id||pq_idint8||int8|||否否||null科目|
|
|pap_id|int8||否|null|
|que_id|int8|||num_art否||int4null|
|||否pq_type||文章数量int8|
|||time_update否||timestampnull||
|否||score更新时间||
numeric||up_id||int8否|||null否|
|null||
desp||varchar|sort_no|int8||否||null|
|tree_path|varchar||否否||nullnull|
|
|tree_up|int8|#### que_section(que_section)|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
是|null|
|sec_id|int8|||否audioe|||null否|
|varchar题型ID||
tree_lev||pap_idint8|int8|||否||否试卷ID||
null|
|que_type||tree_sort|int8int8||||否否||题型|
null||
sec_name|varchar||否|题型名称|
|note_head||varchar#### tk_que(tk_que)
否|| 列名   | 类型   | KEY  | 可否为空 | 注释   |null
| ---- | ---- | ---- | ---- | ---- ||
|否|前注||
que_id||note_below|int8varchar|||否||否题目ID||
尾注||
site_id|int8||否|网站ID|
|que_code|varchar||否|题目编码|
|que_type|int8||否|题型【字典】：选择题、填空题..||
len_min||int8|que_types||否|int8时长||
|否||num_que|题型【字典】：1-7类int8||
|否||题目数sub_id|
|int8|||content|varchar||否|内容|
|score_sec||否int8||学科ID|
|否||总分数title|
|text|||score_que否||int8题干||
|否||num_option|每题分数int8|
|||sort_pap否||int8选项||
|否||排序answer_img|
|varchar||is_choose||int8|否||答案图片否|
||是否选做answer|text||否|标准答案|
|
|analysis_img||varchartime_update|||timestamp否||解析图片|
|analysis|text||否|解析||
否||更新时间que_up|
|int8||否|一题多个小题时,主题目的编号(类似阅读理解)|
|sort_up|int8|#### questions(questions)|
否| 列名   | 类型   | KEY  | 可否为空 | 注释   ||
题目排序：一级题目没有排序，从1开始，默认0|
| ---- | ---- | ---- | ---- | ---- |
|dift|int8||否||id难度【枚举】：0未定义、1容易、3普通、5困难||
int8|||belong_org否||int8|null|
|否||系统题库|
title|text||belong_user||int8是|||null否|
|所属人员|
|option_a|text|||rule是||varcharnull|
||否|判分规则|
|option_b||audit_usertext||int8|||是否||null审核人|
|
||audit_time|timestamp||否|审核时间|
option_c||textaudit_status||int8||是|null|
|option_d|text||是|null||
否|审核状态：-1审核不通过、0待审、1审核通过||
option_e|text||status|int8|||是否||null状态：-1停用、0草稿、1正常|
|
|answer1||remark|textvarchar|||是||否|null备注|
|
|answer2||texttime_update||是|null|
|parse|nulltimestamp|
|contact_type|int4||否|1、邮箱 2、手机 3、qq 4、qqID 5、微信ID 6、支付宝ID|
|is_check|int4||否|null|
|update_time|timestamp||||否否||更新时间null|
|
|time_create|timestamp||否|添加时间|
|grade|int8||否|null|
|score|numeric是|#### temp_grade_subject(temp_grade_subject)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
||id|int8|null|
|否|null|
||grade_id|int4|是||否|null|
|subject_id|int4||否|null|
|exam_subject_id|int8||否|null|
null||
parse_id|int4||||mistake_type否||null|
text|exam_grade_id||int8||否|_int8||是|null||
是|错误类型|
|answer2||textqtpye||varchar||是||是|nullnull|
|
|area|varchar||diff|numeric||是||是null||
null|
|year||md5int4||varchar|||是是||nullnull|
|
|source||varcharsubjectid||是|null|
|papertype|varchar||是|null|
|int4||rule_type_arr||是_int4||null|
||是gradeid||多选判分规则 11：选对但不全，12：每选对1个，21：有选错的，22：每选错1个，3：按不同选项判分int4|
|||score_arr是||_numeric|null||
是|多选判分规则对应分值||
knowledges||varcharlatex_analysis_img||varchar||是||null是|
|area|varchar|||是latex生成的解析图片||
|latex_answer_img|varchar||是|latex生成的答案图片null|
|
||latex_title_imgyear||int4varchar|||是||是null||
latex生成的大题题干图片|
|papertpye||cognitive_level|varcharint8||||是是||null|
认知层级|
|source||subject_literacy|varcharint8|||是|学科素养|
|literacy_level|int8||是|null|
|fromsite|varchar||是|null|
|是|素养水平||
issub|int4|||是|capability_point|nullint8||
||是isnormal||能力点int4||
|是||null|
listen_template||iskonwint4||int4||是||是听写模板 0不是，1是||
null|
||answer_type|int4||是|题目答案类型:0.正常   1.填空题专用(表示多空的答案可以乱序)|
tiid|varchar||是|null|
|similarity|int8||是|null|
#### tk_que_a(tk_que_a)|是|null|
|
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
#### 记录每个学生的推题历史，推过的题目不再推送(recommend_que_history)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|que_code||varcharid|||int8否|||题目编码否|
|null|
||test_idque_id||int8int8|||否||否null||
题目ID|
|subject_id||que_typeint8|||int8否||null|
|否||stu_id题型【字典】：选择题、填空题..||
int8||
||type_name否|null|
|que_id||que_idvarchar||int8|||否否||null|
|top_x|int4||否null|null|
|
|top_y||int4|status||varchar||是|null|
|time_create|varchar||是|null|
否||null|
time_update||varchar||bottom_x是||null|
int4||否|null|
|bottom_y|int4||否|null|
|pic_type|int8||否|题目、解析等，见《系统编码》117001题目  117002解析
|
#### 所有学生回答的内容填写在此，去掉专门的自编题答案表，上传的附件保存在BAS_REC_BUSI(wk_ans)
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
res_id|int8||否|null|
|sort_no|int4||否|null|
|operator|int8||否|null| ---- | ---- | ---- | ---- | ---- |
|
|time_update||ans_idtimestamp||int8||否|nullnull|
|
|否|null|
|wk_id#### temp_que_type(temp_que_type)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id||wrong_que_path|#### 此处只用于答题卡的标识制作。答案a、b、c主要用于试卷题目内容一致，但选型打乱了这类的卷子。这是一个递归的结构，大题下面可以有大题，多级下分。(exam_question)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |varchar|
int8||是||否|null||
nullque_id|
|||wrong_answer_pathtype_name||varcharvarcharint8||||否是||nullnull|
|
||type_code|quesvarchar||text||否||是null||
null|
|#### exam_report_region_joint(exam_report_region_joint)#### temp_que_type_s(temp_que_type_s)
int8| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
||否|null|
|id
|| 列名   | 类型   | KEY  | 可否为空 | 注释   ||que_id|int8||否|null|
|user_id|int8||否|null|
|sort_no|int4||否|作业内排序：从1开始，按学科ERMWN排列|
|time_start|timestamp||否|第一次进入题目时间，如果是默认值则表示未开始|
|time_end|timestamp||否|最后一次离开时间|
|len_sec|int4||否|每次时间累计停留时间|
|len_ans|int4||否|进入题目到最后一次修改答案的累计停留时间|
|answer|varchar||否|学生答案：|
|num_words|int4||否|que_ability用于作文，显示内容的总词数|int8||否|题型【字典】：简单应用、理解和掌握..|
|
|is_fill|int4|||ability_name否|是否填写答案：-1未看未填、0看了未填、1已填|
|ans_type|int4|||否|客观题对错：-2未看，-1错误、0未做、1正确|
|score_teach|numeric||否|老师评分：作文0-12、自主题0-12对应F-A+、客观题:ANS_TYPE|
|score_intel|numeric||否|智能评分：|
|status|int4||否|状态：0未开始、2作业中、3交卷待批改、4批改中、5批改完毕，如果没有作文，直接由2到5|
|num_file|int4||否|null|
|tech_note|varchar||否|暂时只考虑一个老师的批注|
|tech_comment|varchar||否|null|
|remark|varchar||否|null|
|time_correct|timestamp||否|批改时间|
|time_update|timestamp||否|更新时间|
|tech_id|int8||是|null|
|#### 限制条件：
1、
2、当作业开始时新增记录
3、当作业结束时删除记录
4、作业过程中，每提交一题，修改时间最后的题目编号、数量、section编号等(wk_current)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
int8||wk_id||否|对应题库的题目IDint8||
|否|null|
|user_id|int8|||否|null|
|wk_type|int8||否|null|
|pap_id|int8||否|null|
|sec_id|int8|varchar||否|null|
|是|null|
|que_id|int8||是|null|
|time_end|timestamp||是|null|
|que_dift|int8|#### wk_essay(wk_essay)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
||id|int8||否|null|

|| ---- | ---- | ---- | ---- | ---- |
|idwk_id|int8||int8||否|null|
|act_id|int8||否|null|
|create_time|timestamp||否|null|
|max_score|numeric||否|null|
|min_score|numeric||否|null|
|param_code|varchar||否|null|
|param_value|varchar||否|null|
|reg_code|varchar||否|null|
|score|numeric||否|null|
|sort|int4||否|null|
|stu_num|int4||否|null|
int8||是|null|
|type_name|varchar||是|null|
|type_code|varchar||是|null|
|#### temp_scan_status(temp_scan_status)|否|题目编号，题组是几道题一起批改，就像大题的概念|

| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|que_name||varcharwk_sheet_id|varchar||||是|null|
是|pap_id||nullint8|||否否||试卷编号null|
|
|
|que_start||statusque_id||int4int8||||是否||nullnull|
|
||update_timeuser_id||varcharint8|||否||是评分人||
null|
|score||stuIdnumeric||varchar|||否是||老师评分null|
|
|score_intel|numeric||否|智能评分|
|rule|int8||否|评分标准：系统编码|
|#### test1(test1)comment
|| 列名   | 类型   | KEY  | 可否为空 | 注释   |
varchar| ---- | ---- | ---- | ---- | ---- ||
|否|评语|
|id||int4time_update||timestamp||否||null否|
|null|
否|题型【字典】：较易、一般..|
|dift_name|varchar||否|null|
|time_create|timestamp||否|添加时间|
|title|text||否|题干|
|answer|text||否|标准答案|
|analysis|text||否|解析|
time_update||timestamp||否|null|
sub_id|int8||否|学科ID|
|is_download|int8||是|是否下载，0未下载，1已下载|
#### set_kp_watch(set_kp_watch)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|user_id|int8||否|null|
|attr_id|int8||否|null|
|watch|int2||是|null|
#### tk_que_a_bak(tk_que_a_bak)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|create_time|timestamp||||que_code是||null|
int4|type|int2||是|1是知识点,2是题目|
|||否|null|
|que_endtest_id||int8|int4||是|null|
||pap_id|int8否|||是|null|
null|
|num_que|int4||否|varcharnull|
||que_type|int8||是|null|
|否|题型：系统编码，枚举|
|is_testlet||int4||que_id|否|int8|null|
|是|parent_que_id||int8|null|
||否|que_type|nullint8||
|是||null|
is_auto||int8|type_name||varchar|否|自动批改：1客观题、0主观题||
是||is_choosenull||
int4|||que_ability否|int8|||是|null|
null||
ability_name||que_type_user|int8||否|null|
|len_sec|int8||varchar否||时长|
|是|null|
|score|numeric||que_dift||否|int8|分值|
|是||nullsubject_id|
||int8|dift_name|varchar||否||null是|null|
|
|time_create|timestamp|||answer_a是|null|
|title||text|varchar||是|null||
否||answer|text||是|null正确答案A
给题目相同，答案不同的AB卷用|
|
|analysis|text|||是|nullanswer_b|
||sub_id|int8|varchar||是|null|
||que_types否||int8null||
|是|null|
||que_type_a|int8answer_c||varchar|是||null|
||否|sub_id_a|int8|预留|
|是|null|
|rule_detail|varchar||否|null|
|rule_mul_right|varchar||否|中间以分号隔开，1；2；3表示对一个得一分，对2个得2分，3个及以上得3分|
|rule_mul_error|varchar||否|中间以分号隔开，1；2；3表示错一个扣一分，错2个扣2分，错3个及以上扣3分|
#### 题目属性关系(tk_que_attr)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|rule_mul_miss|varchar|qa_id|int8|||否|关系ID|
||attr_id|否|int8|中间以分号隔开，1；2；3表示漏一个扣一分，漏2个扣2分，漏3个及以上扣3分|
|否|属性ID|
|num_ans||que_idint4||int8|||否否||对于多选题，有几个答题填几个题目ID|
|
|dift||num_resint8|||否|难度【枚举】：0未定义、1容易、3普通、5困难int4||
||否time_create||如果有，就需要去资源表BAS_REC_BUSI查询所需的图片显示timestamp||
|否|创建时间|
|status|int4||否|null#### tk_que_attr_a(tk_que_attr_a)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|
|qa_id||int8update_time||timestamp||否|null|
|que_id||int8|否||null|
是||null|
que_group||sub_id|int8||是|nullvarchar|
||attr_id||int8是||null|
|是|null|
||que_choose_num|type|int4|int4|||是|1表示知识点，2表示章节，3表示试卷|
是||nullpath_ids|varchar||是|null|
|
|rule_mul|int4||是|null|
|option_score|varchar||是|null|
|num_limit|int4||是|null|
|level|int8||是|难度|
|oral_ans_audio_url|varchar||是|null|
|oral_ans_time|int4||是|null|
|option_print_style|int4||是|null|
|zj_que_id|int8||是|组卷pap_id|
|is_integration|int4||是|null|
|tk_que_id|int8||是|null|
#### exam_report_class(exam_report_class)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|题目编号，题组是几道题一起批改，就像大题的概念|
|class_id|int8||是|null|
|grade|int8||否|试卷编号|
|school_id|int8||否|null|
|test_id|int8||否|null|
|param_code|varchar||否|null|
|param_value|varchar||否|题型：系统编码，枚举|
|score|numeric||否|分值|
|stu_num|int4||否|null|
|sort|int4||否|null|
|grade_sort|int4||否|自动批改：1客观题、0主观题|
|max_score|numeric||否|null|
|min_score|numeric||否|null|
|create_time|timestamp||否|null|
#### exam_report_class_bak(exam_report_class_bak)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||是|null|
|class_id|int8||是|null|
|grade|int8||是|null|
|school_id|int8||是|null|
|test_id|int8||是|null|
|param_code|varchar||是|null|
|param_value|varchar||是|null|
|score|numeric||是|null|
|stu_num|int4||是|null|
|sort|int4||是|null|
|grade_sort|int4||是|null|
|max_score|numeric||是|null|
|min_score|numeric||是|null|
|create_time|timestamp||是|null|
#### exam_report_class_joint(exam_report_class_joint)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|null|
|act_id|int8||否|null|
|class_id|int8||否|null|
|create_time|timestamp||否|null|
|grade|int8||否|null|
|grade_sort|int4||否|null|
|max_score|numeric||否|null|
|min_score|numeric||否|null|
|param_code|varchar||否|null|
|param_value|varchar||否|null|
|school_id|int8||否|null|
|score|numeric||否|null|
|sort|int4||否|null|
|stu_num|int4||否|null|
#### exam_report_class_que_ans(exam_report_class_que_ans)
| 列名   | 类型   | KEY  | 可否为空 | 注释   |
| ---- | ---- | ---- | ---- | ---- |
|id|int8||否|题目编号，题组是几道题一起批改，就像大题的概念|
|class_id|int8||是|null|
|grade|int8||否|试卷编号|
|school_id|int8||否|null|
|test_id|int8||否|null|
|que_id|int8||是|null|
|param_code|varchar||否|null|
|param_value|varchar||否|题型：系统编码，枚举|
|stu_num|int4||否|null|
|create_time|timestamp||否|null|
