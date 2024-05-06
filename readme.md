DC226319 TAN HONGYE - CISC3003 Web Programming - Individual project

1. 配置好xampp、php、java、html、css、MySQL等工作环境
2. 将project文件夹拖入htdocs里面
3. 根据文件夹sql_file下的food-order.sql文件内的内容创建相应的数据库和对应的数据
4. 在project文件夹中的config文件夹中更改constants.php内的数据库账户信息
5. 打开xampp，启动apache，进入localhost选择project文件夹运行index.php
6. 然后复制主页的url, 替换与第四步同一个路径下的constan.php文件内的"SITEURL"变量信息
7. 刷新网站即可
*** 若想进入管理者模式, 更改url, 使其指向".../admin/"即可 ***
*** 在管理者模式下, 若不小心log out了账号, 则需要将数据库中的tbl_admin中任一条目的password那一列复制, 去浏览器搜索MD5解码, 粘贴进去解码即可获得对应username的密码 ***

Github links: https://github.com/Ted-cuchuan/CISC3003-ProjectAssignment-Part02-Individual