---
title: 下发条件说明
header: develop
nav: serverapi
sidebar: sendintroduction
---
 
 

**重要：下发消息请先完成模板的选用。**
开发者需要先在开发者后台添加属于自己的消息模板，获取模板ID后才能进行消息下发

## 支付类消息
对于在小程序内完成过支付行为的用户，可允许开发者向用户在 **7 天内**推送有限条数的模板消息


> 1 次支付可下发 3 条，多次支付下发的条数独立，互不影响。
 

## 表单类消息
对于在小程序内发生过提交表单行为的用户，可允许开发者向用户在 **7 天内**推送有限条数的模板消息

 
> 1 次提交表单可下发 1 条，多次提交下发条数独立，相互不影响。
 

## 订阅类消息
对于在小程序内发生过订阅行为，且同意授权发送订阅消息的用户，可允许开发者向用户推送有限条数的模板消息，**无时间限制**

 
> 1次订阅授权可下发 1 条，同一订阅行为的多次授权，下发条数不累计
 
