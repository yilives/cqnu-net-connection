# cqnu-net-connection
重庆师范大学 校园网（哆点）验证思路 及 防检测方法（虎溪校区）

最短验证命令
wget 'http://10.0.254.125:801/eportal/portal/login?callback=dr1007&login_method=1&user_account=%2C0%2C学号%40telecom&user_password=密码'

目前使用的是UA2F 不会被检测 但一定时间后会被回收ip导致需要重新认证
即 校园网使用ua检测 我们搭配修改ua的插件 UA2F UA3F 即可





