# ubuntu_qt_QMYSQL_driver
qt编译连接MYSQL出现QMYSQL driver not loaded 基本成为普遍现象，网络上大多数解决方案是重新编译驱动，亲身证实是可行方案之一。这里给出更简单的办法，适用于ubuntu，直接安装该deb包，就可以了。ubuntu16.04和ubuntu18.04下亲测通过。其余环境未试，请先执行ldd libqsqlmysql.so命令查看是否是libmysqlclient_r.so.18 => not found，是则可以用本安装包，不是的话就不一定适用。
