# Vocabulary List

In our API, there are many rolls in it. However, different roles may have some same properties. So this doc is used to ensure the consistency of the words in API, and try to not make developers fall into chaos.

               | Object  | 个人信息                     | contact_info         | Object  | 联系方式                 |
| name                        | String  | 姓名，名称                   | address              | String  | 地址                     |
| occupational_info           | Object  | 职业信息                     | company              | String  | 企业名称                 |
| company_fixed_line          | String  | 企业联系电话                 | identity             | String  | 行业身份（法| EN                          | Type    | CH                           | EN                   | Type    | CH                       |
| --------------------------- | ------- | ---------------------------- | -------------------- | ------- | ------------------------ |
| phone                       | String  | 手机号                       | password             | String  | 密码                     |
| credentials_type            | String  | 证件类型                     | id-card              | String  | 中国身份证               |
| credentials_number          | String  | 个人证件号，通常是身份证号码 | email                | String  | 邮箱                     |
| personal_info官，会计等） |
| position                    | String  | 企业职称                     | bank_account         | Object  | 银行账户                 |
| cases                       | Array   | 案件（复数）                 | role                 | String  | 角色                     |
| case_info                   | Object  | 案件信息                     | case_real_id         | String  | 受理案号                 |
| acceptance_time             | String  | 受理时间                     | legal_representative | String  | 企业法定代表人           |
| first_meeting_point         | String  | 一次会时点                   | second_meeting_point | String  | 二次会时点               |
| claim_declaration_agreement | Integer | 债权申报协议                 | case_id              | uuid    | 案件的唯一id             |
| credetor_type               | String  | 债权人类型                   | credit_number        | String  | 法人信用号               |
| company_trustee             | Object  | 法人开户受托人               | user_agreement       | Integer | 用户协议                 |
|                             |         |                              |                      |         |                          |
|                             |         |                              |                      |         |                          |
|                             |         |                              |                      |         |                          |
|                             |         |                              |                      |         |                          |
|                             |         |                              |                      |         |                          |