# A岛饼干侦探
使用在线搜索引擎，搜索指定id发言。    
你可以使用[在线demo](http://h.nimingban.ml)    

##更新日志
**v4.0**    
优化搜索语句。    
重写Google接口，使用Google Custom Search Api获取数据，需要到Google申请key并创建项目。    
每个免费key每天限制100次查询（即100页数据）。    
获取key并创建项目[可参考](http://www.cnblogs.com/yilongm/p/5508038.html)。    

**v3.2**    
优化搜索语句。    
测试发现Google访问量大会要求输入验证码，待解决。     

**v3.1**    
修复了搜索页数递增中断导致搜索数据不完整的bug。    
更新正则，修复搜索结果手机端页面无法抓取的bug。    

**v3.0**    
增加google搜索引擎，需服务器能访问google。    

**v2.0**    
查询方式修改为客户端分页查询，避免了查询页数过多服务器脚本卡死。    

**v1.0**    
初始版本。