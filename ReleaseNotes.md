## 0.2-SNAPSHOT

* 用户，团队，部门增加应用外配置文件的维护方式
* 增加数据导出CSV功能
* 增加HTTP报警方式
* 增加企业微信报警方式
* Elasticsearch-Rest-Client升级至6.6.2
* bugfix: 解决elasticsearch 7+版本，数据数量为0的问题
* bugfix: 解决邮箱需要认证的情况下，邮件发送失败的问题
* mysql: alert表增加字段: http_post_url
* 文档: 增加query string简易教程
* mysql: data_name表增加data_name字段唯一索引
* bugfix: 解决dataname还在使用中，仍然可以删除的问题
* elasticsearch监控增加avg,min,max,sum数值metric类型

## 0.1-RELEASE

* Elasticsearch数据监控, 你只需要写一条查询就可以轻松搞定监控
* HTTP数据监控
* UI功能，简单易用
* 监控管理
* 灵活的报警消息模板定制，支持变量
* 多种消息发送方式(email,短信,钉钉(机器人))
* 多数据源管理
* Elasticsearch数据查询页面
* 报警消息附带日志查询短链接，直达报警原因
* 报警消息抑制功能，防止消息轰炸