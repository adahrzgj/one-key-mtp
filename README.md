安装mtproxy及其守护进程请运行：
wget --no-check-certificate https://raw.githubusercontent.com/chummumm/one-key-mtp/master/mtproxy.sh && bash mtproxy.sh  ；
删除mtproxy及其守护进程请运行：
wget --no-check-certificate https://raw.githubusercontent.com/chummumm/one-key-mtp/master/deletemtproxy.sh && bash deletemtproxy.sh ；
当手机用户使用systemctl status mtproxy查看配置信息显示不全时请使用方向键右键进行查看。
仅需注册守护进程请使用：curl --no-check-certificate https://raw.githubusercontent.com/chummumm/one-key-mtp/master/mtproxy-daemon.sh | bash
