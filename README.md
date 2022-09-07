# 大辉哥天下第一！！！

- grafana-dashboard
  包含sandwich dataserver 等 看板信息
  
- docker
  * 包含grafana和prometheus的docker-compose，可以通过docker-compose up -d 直接拉起，然后访问`http://127.0.0.1:3000`访问grafana，初始使用admin/admin 登陆，然后会要求重置管理员密码。
  * 第一次需要在grafana中添加datasource，选择prometheus，地址输入`http://prometheus:9090`保存即可

- v1
  老版本看板