# aliyun-cms-grafana-templete

DataSource命名为：aliyun
Grafana模板，简单上手，创建Variables替换instance即可完成数据展示

# 相关文档

对接Grafana：https://www.alibabacloud.com/help/zh/doc-detail/109434.htm

Major metrics of Alibaba Cloud services：https://www.alibabacloud.com/help/zh/doc-detail/28619.htm?spm=a2c63.p38356.879954.8.37303a20UQx7mP#title-sw7-olh-qaz


# 说明

因aliyun-cms获取不到instanceName，建议手动修改json中的text以便于维护

# 爬坑

2020年11月23日阿里云在没有任何公告的情况下，直接下线了SLB的健康检查监控，多次沟通后，在2021年1月13日优化迭代了健康检查的监控服务。解铃还须系铃人，不催就不会完善，开发快赶上PM了……哭笑
