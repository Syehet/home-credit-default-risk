# home-credit-default-risk
1. Home CreditHome Credit(中文: 捷信消费金融有限公司)是中东欧/亚洲的一家消费金融提供商, 为客户提供金融服务.
2. 比赛简介
   (1) 业务背景Home Credit希望能通过数据挖掘和机器学习算法来估计客户的贷款违约概率.
   (2) 数据Home Credit提供了多张数据表, 包括 (1) application_train/test 客户申请表包含了目标变量(客户是否违约-0/1变量), 客户申请贷款信息(贷款类型, 贷款总额, 年金), 客户基本信息(性别, 年龄, 家庭, 学历, 职业, 行业, 居住地情况), 客户财务信息(年收入, 房/车情况), 申请时提供的资料等.(2) bureau/bureau_balance 由其他金融机构提供给征信中心的客户信用记录历史(月数据)包含了客户在征信中心的信用记录, 违约金额, 违约时间等. 以时间序列(按行)的形式进行记录.
   (3) POS_CASH_balance 客户在Home Credit数据库中POS(point of sales)和现金贷款历史(月数据)包含了客户已付款和未付款的情况.
   (4) credit_card_balance 客户在Home Credit数据库中信用卡的snapshot历史(月数据)包含了客户消费次数, 消费金额等情况.
   (5) previous_application 客户先前的申请记录包含了客户所有历史申请记录(申请信息, 申请结果等).
   (6) installments_payments 客户先前信用卡的还款记录包含了客户的还款情况(还款日期, 是否逾期, 还款金额, 是否欠款等)
3. 结果评判标准比赛最终要求提交每个ID的违约概率, 以此计算得到的AUC作为评判标准.
