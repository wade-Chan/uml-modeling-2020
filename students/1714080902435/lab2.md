# 实验二：用例建模

## 1. 实验目标

- 创建Issue选题
- 使用StarUml创建用例图
- 掌握MarkDown语法的编写报告

## 2. 实验内容

- 提交支付宝支付系统选题
- 创建支付系统用例图
 
## 3. 实验步骤

- 添加Use Case Diagram
- 添加Actor（客户） 
- 添加UseCase（扫码支付） 
- 添加UseCase（转账支付） 
- 分别连接“客户”与“扫码支付”和“转账支付”  

## 4. 实验结果

![用例图](./lab2.jpg)

支付宝支付系统的用例图

## 表1：扫码支付用例规约  

用例编号  | UC01 | 
-|:-|   
用例名称  | 扫码支付  | 
前置条件  | 客户联网在线   | 
后置条件  | 支付系统数据库修改成功  | 
基本流程  | 1.客户扫描二维码 | 
~| 2. 系统识别二维码对应账户| 
~| 3. 客户确认账户信息  | 
~| 4. 客户输入支付金额  | 
~| 5. 客户点击确认支付  | 
~| 6. 客户输入支付密码  | 
~| 7. 系统校验支付密码，密码正确  | 
~| 8. 系统检测账户余额，余额充足  | 
~| 9. 系统扣除己方账户对应金额，增加对方账户余额相应金额  | 
~| 10. 系统生成支付账单并显示支付成功   | 
 扩展流程 | 7.1 系统校验支付密码错误，显示密码错误，请重新输入  | 
~| 8.1 经系统检测账户余额不足，显示余额不足，支付失败  | 
## 表2：转账支付用例规约   
 
用例编号  | UC02 | 
-|:-|  
用例名称  | 转账支付  | 
前置条件  | 客户联网在线  | 
后置条件  | 支付系统数据库修改成功  | 
基本流程  | 1.客户输入转账号码| 
~| 2. 系统识别号码对应账户 |
~| 3. 客户确认账户信息  | 
~| 4. 客户输入转账金额  | 
~| 5. 客户点击确认转账  | 
~| 6. 客户输入支付密码  | 
~| 7. 系统校验支付密码，密码正确  | 
~| 8. 系统检测账户余额，余额充足  |
~| 9. 系统扣除己方账户对应金额，增加对方账户余额相应金额  | 
~| 10. 系统生成支付账单并显示支付成功   | 
 扩展流程 | 2.1 系统无法识别号码对应账户，显示账户不存在，请重新输入 |
~| 7.1 系统校验支付密码错误，显示密码错误，请重新输入  | 
~| 8.1 经系统检测账户余额不足，显示余额不足，支付失败  | 
 
