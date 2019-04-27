# Vocabulary List

This list is used to ensure the strong consistency of the fields in API, and try not to make developers fall into chaos.

Note that some fields **have the same name with different type**.

*&XXX means the file path of XXX*

## User

| EN                          | Type    | CH             | EN                   | Type    | CH                       |
| --------------------------- | ------- | -------------- | -------------------- | ------- | ------------------------ |
| phone                       | String  | 手机号         | password             | String  | 密码                     |
| credentials_type            | String  | 证件类型       | id-card              | Value   | 中国身份证               |
| credentials_number          | String  | 个人证件号     | email                | String  | 邮箱                     |
| personal_info               | Object  | 个人信息       | contact_info         | Object  | 联系方式                 |
| name                        | String  | 姓名，名称     | address              | String  | 地址                     |
| occupational_info           | Object  | 职业信息       | company              | String  | 企业名称                 |
| company_fixed_line          | String  | 企业联系电话   | identity             | String  | 行业身份（法官，会计等） |
| position                    | String  | 企业职称       | bank_account         | Object  | 银行账户                 |
| cases                       | Array   | 案件（复数）   | role                 | String  | 角色                     |
| case_info                   | Object  | 案件信息       | case_real_id         | String  | 受理案号                 |
| acceptance_time             | String  | 受理时间       | legal_representative | String  | 企业法定代表人           |
| first_meeting_point         | String  | 一次会时点     | second_meeting_point | String  | 二次会时点               |
| claim_declaration_agreement | Integer | 债权申报协议   | case_id              | uuid    | 案件的唯一id             |
| credetor_type               | String  | 债权人类型     | credit_number        | String  | 法人信用号               |
| company_trustee             | Object  | 法人开户受托人 | user_agreement       | Integer | 用户协议                 |
| credentials_front           | String  | *&证件照正面*  | credentials_back     | String  | *&证件照背面*            |

## Cases

| EN                     | Type   | CH                   | EN                         | Type   | CH             |
| ---------------------- | ------ | -------------------- | -------------------------- | ------ | -------------- |
| case_type              | String | 案件类型             | contact                    | Object | 联系人         |
| name                   | String | 姓名，名称           | phone                      | String | 电话           |
| fixed_line             | String | 固定电话             | address                    | String | 地址           |
| debtor                 | Object | 债务人               | company                    | String | 企业名称       |
| credit_number          | String | 企业信用号           | business_scope             | String | 经营范围       |
| registered_capital     | String | 注册资本             | subscribed_capital         | String | 实缴资本       |
| establishment_day      | String | 成立日期             | company_fixed_line         | String | 企业联系电话   |
| registration_authority | String | 登记机关             | legal_representative       | Object | 企业法定代表人 |
| applicant              | Object | 申请人               | application_type           | String | 申请人类型     |
| trustee                | Object | 受托人               | credentials_number         | String | 个人证件号     |
| trustees               | Array  | 受托人（复数）       | court                      | Object | 法院           |
| presiding_judge        | Object | 主审法官             | collegial_panel_members    | Array  | 合议庭成员     |
| judge_assistants       | Array  | 法官助理             | clerks                     | Array  | 书记员         |
| case_info              | Object | 案件信息             | case_real_id               | String | 受理案号       |
| acceptance_time        | String | 受理时间             | legal_representative       | String | 企业法定代表人 |
| first_meeting_point    | String | 一次会时点           | second_meeting_point       | String | 二次会时点     |
| manager_info           | Object | 管理人信息           | responsible_body_full_name | String | 责任主体全称   |
| principal              | String | 管理人负责人         | manager_members            | Object | 管理人成员     |
| composition_model      | String | 管理人构成模式       | liquidation_team_members   | Array  | 清算组成员     |
| agencies_name          | Array  | 多中介机构名称       | liquidation-team           | Value  | 清算组         |
| single-agency          | Value  | 单一中介机构         | mul-agencies               | Value  | 多个中介机构   |
| natural-person         | Value  | 自然人               | toll                       | Object | 收费           |
| case_id                | uuid   | 案件的唯一id         | case_info_table            | String | *&案件信息表*  |
| cases_info             | Array  | 案件基本信息（复数） |                            |        |                |
|                        |        |                      |                            |        |                |
|                        |        |                      |                            |        |                |
|                        |        |                      |                            |        |                |
|                        |        |                      |                            |        |                |
|                        |        |                      |                            |        |                |

