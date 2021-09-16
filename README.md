# 金融保险用户分类综合项目

- 数据来源
美国某保险公司，该公司的一款医疗产品准备上市。
- 商品介绍
这是一款针对65岁人群推出的医疗附加险，销售渠道是直邮。
- 商业目的
为该产品做用户画像，找到最具购买倾向的人群进行营销。

本次案例数据中共有76个字段，具体说明如下：

变量名 | 	type | 	变量说明 | 	备注
---  | ---  | --- | ---
KBM_INDV_ID | 	Num | 	Individual ID	 | &nbsp;
resp_flag | 	Num | 	是否response	 |  &nbsp;
age | 	Num	 | 年龄	 |  &nbsp;
GEND | 	Char	 | 性别	 |  &nbsp;
c210mys | 	Num	 | 学历 | 	"0-unknown; 1-初中；2-高中不到；3-高中毕业；4-大学未毕业；5-大专；6-本科；7-研究生；8-专业院校毕业；9-博士"
POC19	 | Char	 | 是否有小孩	 |  &nbsp;
CA00	 | Char	 | 小孩是否在0-2岁之间	 |  &nbsp;
CA03	 | Char	 | 小孩是否在3-5岁之间	 |  &nbsp;
CA06 | 	Char | 	小孩是否在6-10岁之间	| &nbsp;
CA11	 | Char | 	小孩是否在11-15岁之间	| &nbsp;
CA16 | 	Char | 	小孩是否在16-18岁之间	| &nbsp;
NOC19	 | Num	 | 家庭小孩个数	| &nbsp;
NAH19	 |   Num|	家庭成年人个数	| &nbsp;
NPH19	Num	|家庭成员人数量	| &nbsp;
U18	 | Char	|是否有家庭成员小于18岁	| &nbsp;
N1819 | 	Char|	是否有家庭成员在18-19岁之间	| &nbsp;
N2029 | 	Char|	是否有家庭成员在20-29岁之间	| &nbsp;
N3039 | 	Char|	是否有家庭成员在30-39岁之间	| &nbsp;
N4049 | 	Char	|是否有家庭成员在40-49岁之间	| &nbsp;
N5059 | 	Char|	是否有家庭成员在50-59岁之间	| &nbsp;
N6064 | 	Char|	是否有家庭成员在60-64岁之间	| &nbsp;
N65P | 	Char|	是否有家庭成员在65岁以上	| &nbsp;
POEP | 	Char|	家里是否有老人|	 &nbsp;
AART | 	Char|	是否有关节炎	| &nbsp;
ADBT | 	Char	|是否有糖尿病	| &nbsp;
ADEP	 | Char	|是否有抑郁症	| &nbsp;
AHBP | 	Char|	是否有高血压	| &nbsp;
AHCH | 	Char|	胆固醇含量是否过高	| &nbsp;
ARES | 	Char|	是否有呼吸疾病	| &nbsp;
AHRT | 	Char|	是否有心脏病	| &nbsp;
AASN	 | Char|	是否有过敏性鼻炎	| &nbsp;
ADGS	 | Char|	是否有消化不良	| &nbsp;
AHRL | 	Char|	是否耳聋	| &nbsp;
ASKN	 | Char|	是否有皮肤病	| &nbsp;
AVIS	 | Char	|是否视力不好	| &nbsp;
BANK	 | Char	|是否有过破产记录	| &nbsp;
COLLEGE | 	Char|	是否大学毕业	| &nbsp;
FINI | 	Char|	是否用过保险服务	| &nbsp;
INLI	 | Char|	是否投资过寿险	| &nbsp;
INMEDI | 	Char|	是否购买过医疗险	| &nbsp;
INVE | 	Char|	是否有投资	| &nbsp;
IOLP	 | Char	|是否网上购买过产品	| &nbsp;
MOBPLUS | 	Char|	是否通过快递买过东西	|"M-通过多种快递渠道购买；P-或许通过多种快递读到购买；S-单一快递渠道购买；U-不知道"
N2NCY | 	Char	|所处的县的大小|	A-D, 大小依次递减
ONLA	 | Char	|是否上网	| &nbsp;
SGFA | 	Char|	是否喜欢美术	| &nbsp;
SGLL | 	Char|	是否经常有奢侈消费	| &nbsp;
SGOE	 | Char|	是否经常户外活动	| &nbsp;
SGSE | 	Char|	是否喜欢运动	| &nbsp;
SGTC	 | Char|	是否热爱科技	| &nbsp;
LIVEWELL | 	Char|	幸福指数|	值越大，说明越幸福
HOMSTAT	 | Char	|是否有房子|	Y:有房子；P:可能有房子；R: 租房； T,U:不确定
HINSUB	 | Char|	是否有医保补贴	|A-C, 补贴依次增加
c210cip | 	Num	|收入所处排名	|值越大，说明收入越高
c210ebi | 	Num|	普查家庭有效购买收入|	值越大，说明有效购买收入越高
c210hmi	 | Num|	家庭收入|	值越大，说明家庭收入越高
c210hva	 | Num|	家庭房屋价值	|值越大，说明房屋价值越高
c210kses | 	Num|	社会经济地位评分|	值越大，说明经济地位越高
c210mah | 	Num|	家庭自成立日起的时间	| &nbsp;
tins | 	Num	|该客户被多少个名单source 包含	| &nbsp;
STATE_NAME	 | Char|	所处的省份	| &nbsp;
c210apvt | 	Num	|贫穷以上人的比例|	值越大，说明比例越高
c210b200 | 	Num|	所处地区有多少居住小区在2000年及以后建立|	值越大，说明比例越高
c210blu | 	Num	|所处地区蓝领所占百分比	|值越大，说明比例越高
c210bpvt | 	Num|	贫穷以下人的比例|	值越大，说明比例越高
c210mob | 	Num|	所处地区mobile home的比例	|值越大，说明比例越高
c210pdv	 | Num|	离婚或者分居人群所占比例|	值越大，说明比例越高
c210pmr	 | Num	|已婚人群所占比例	|值越大，说明比例越高
c210poo | 	Num	|有房子人所占比例	|值越大，说明比例越高
c210psu	 | Num	|独宅住户所占比例	|值越大，说明比例越高
c210pwc | 	Num|	有小孩的家庭所占比例|	值越大，说明比例越高
c210wht | 	Num|	白领所占比例	|值越大，说明比例越高
ilor|	Num	|所处地区居住年限|	值越大，说明居住年限越长
KBM_INDV_ID	| Num	|Individual ID	| &nbsp;
pdpe|	Num|	所在地区处方药计划覆盖的比例	|值越大，说明覆盖比例越高
zhip19	| Num	|zip level的家庭收入排名|	值越大，说明收入越高
