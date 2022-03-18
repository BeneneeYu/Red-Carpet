# Red Carpet

“复旦毕业红毯仪式”小程序通过提名候选人，并对其进行投票，筛选出前几名候选人参与红毯活动。该小程序的主要功能在于提名、投票，并在后台网站对提名者进行审核。

Back end for the red carpet party in Fudan University

## Hierachy
- backend: 后端代码。
- docs: 文档。
- frontend: 后台前端源码。后台的前端，用于给操作人员管理整个投票系统。

## Security

1. 使用https对访问信息进行加密；

2. 使用nginx进行反向代理，隐藏后端；

3. 前端源码进行了转义，无法阅读；

4. 后端使用JWT与Cookie技术维持会话，保证管理员访问的权限与账号密码的安全；

5. 使用log详细记录每一次数据库的操作；

6. 每隔半小时备份一次数据库，保证数据的高可用。

