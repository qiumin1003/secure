# Summary

* [运维安全管理规范](README.md)
* [规范要求](gui-fan-yao-qiu.md)
  * [《压缩包》提交要求](ya-suo-bao-de-shang-bao-yao-qiu.md)
  * [《项目汇总表》填写要求](300a-xiang-mu-hui-zong-biao-300b-de-tian-xie-yao-qiu.md)
  * [《安全自查表》填写要求](300a-an-quan-zi-cha-biao-300b-de-tian-xie-yao-qiu.md)
* [操作安全](chapter1.md)
  * [是否已准确提供完整的服务器清单汇总表](chapter1/shi-fou-yi-zhun-que-ti-gong-wan-zheng-de-fu-wu-qi-qing-dan-hui-zong-biao.md)
  * [开发以及运维的工作是否各司其职，涉及运维操作由运维进行变更](chapter1/kai-fa-yi-ji-yun-wei-de-gong-zuo-shi-fou-ge-si-qi-zhi-ff0c-she-ji-yun-wei-cao-zuo-you-yun-wei-jin-xing-bian-geng.md)
  * [项目的版本（代码）发布时间是否已固定周期](chapter1/xiang-mu-de-ban-ben-ff08-dai-ma-ff09-fa-bu-shi-jian-shi-fou-yi-gu-ding-zhou-qi.md)
  * [云服务器/虚拟服务器是否已开启自动镜像备份功能](chapter1/yun-fu-wu-5668-xu-ni-fu-wu-qi-shi-fou-yi-kai-qi-zi-dong-jing-xiang-bei-fen-gong-neng.md)
  * [云服务器/虚拟服务器是否已安装基础agent插件](chapter1/yun-fu-wu-5668-xu-ni-fu-wu-qi-shi-fou-yi-an-zhuang-ji-chu-agent-cha-jian.md)
  * [是否有完备的性能监控系统，如蓝鲸、zabbix](chapter1/shi-fou-you-wan-bei-de-xing-neng-jian-kong-xi-tong-ff0c-ru-lan-jing-3001-zabbix.md)
  * [是否已安装防病毒软件](chapter1/shi-fou-yi-an-zhuang-fang-bing-du-ruan-jian.md)
  * [是否已安装木马查杀软件](chapter1/shi-fou-yi-an-zhuang-mu-ma-cha-sha-ruan-jian.md)
  * [是否未安装破解软件或无授权的商业软件](chapter1/shi-fou-wei-an-zhuang-po-jie-ruan-jian-huo-wu-shou-quan-de-shang-ye-ruan-jian.md)
  * [是否已部署堡垒机](chapter1/shi-fou-yi-bu-shu-bao-lei-ji.md)
* [网络安全](wang-luo-an-quan-yao-qiu.md)
  * [是否已开启防火墙或安全组策略并设置正确的规则进行访问控制](wang-luo-an-quan-yao-qiu/shi-fou-yi-kai-qi-fang-huo-qiang-huo-an-quan-zu-ce-lve-bing-she-zhi-zheng-que-de-gui-ze-jin-xing-fang-wen-kong-zhi.md)
  * [是否已禁止所有服务器的icmp功能](wang-luo-an-quan-yao-qiu/shi-fou-yi-jin-zhi-suo-you-fu-wu-qi-de-icmp-gong-neng.md)
  * [是否已禁止所有服务器的telnet-server功能](wang-luo-an-quan-yao-qiu/shi-fou-yi-jin-zhi-suo-you-fu-wu-qi-de-telnet-server-gong-neng.md)
  * [不同的服务器群是否有采用安全分级的访问策略](wang-luo-an-quan-yao-qiu/bu-tong-de-fu-wu-qi-qun-shi-fou-you-cai-yong-an-quan-fen-ji-de-fang-wen-ce-lve.md)
  * [对直接供远程登陆的服务器是否有特定的安全防护（如vpn、安全组限定源ip、纯内网访问）](wang-luo-an-quan-yao-qiu/dui-zhi-jie-gong-yuan-cheng-deng-lu-de-fu-wu-qi-shi-fou-you-te-ding-de-an-quan-fang-hu-ff08-ru-vpn-3001-an-quan-zu-xian-ding-yuan-ip-3001-chun-nei-wang-fang-wen-ff09.md)
* [Linux系统安全](xi-tong-an-quan.md)
  * [root用户的authorized\_keys是否无信任的公钥](xi-tong-an-quan/rootyong-hu-de-authorized-keys-shi-fou-wu-xin-ren-de-gong-yao.md)
  * [sshd是否禁止空密码登录](xi-tong-an-quan/sshdshi-fou-jin-zhi-kong-mi-ma-deng-lu.md)
  * [sshd的LogLevel是否设置为INFO以上](xi-tong-an-quan/sshdde-loglevel-shifou-she-zhi-wei-info-yi-shang.md)
  * [sshd是否禁止root远程登录](xi-tong-an-quan/sshdshi-fou-jin-zhi-root-yuan-cheng-deng-lu.md)
  * [sshd空闲超时退出时间是否大于5分钟](xi-tong-an-quan/sshdkong-xian-chao-shi-tui-chu-shi-jian-shi-fou-da-yu-5-fen-zhong.md)
  * [sshd的登录次数是否限制小于6次](xi-tong-an-quan/sshdde-deng-lu-ci-shu-shi-fou-xian-zhi-xiao-yu-6-ci.md)
  * [openssh版本是否不低于openssh-8.0p1](xi-tong-an-quan/opensshban-ben-shi-fou-bu-di-yu-openssh-8-0p1.md)
  * [/etc/passwd除root外是否无UID为0的高权限账号](xi-tong-an-quan/etcpasswdchu-root-wai-shi-fou-wu-uid-wei-0-de-gao-quan-xian-zhang-hao.md)
  * [/etc/passwd下无需登录的服务账号是否均为/sbin/nologin，有特殊的请备注](xi-tong-an-quan/etcpasswdxia-wu-xu-deng-lu-de-fu-wu-zhang-hao-shi-fou-jun-4e3a-sbin-nologin-ff0c-you-te-shu-de-qing-bei-zhu.md)
  * [所有账号密码是否为8位以上，且同时具备小写字母、大写字母、数字、特殊字符](xi-tong-an-quan/suo-you-zhang-hao-mi-ma-shi-fou-wei-8-wei-yi-shang-ff0c-qie-tong-shi-ju-bei-xiao-xie-zi-mu-3001-da-xie-zi-mu-3001-shu-zi-3001-te-shu-zi-fu.md)
  * [是否已通过配置文件配置密码复杂度要求](xi-tong-an-quan/suo-you-zhang-hao-mi-ma-shi-fou-yi-tong-guo-pei-zhi-wen-jian-pei-zhi-mi-ma-fu-za-du-yao-qiu.md)
  * [是否已通过配置文件配置密码失效时间等于90天](xi-tong-an-quan/suo-you-zhang-hao-mi-ma-shi-fou-yi-tong-guo-pei-zhi-wen-jian-pei-zhi-mi-ma-shi-xiao-shi-jian.md)
  * [是否已通过配置文件配置密码修改最小间隔时间](xi-tong-an-quan/suo-you-zhang-hao-mi-ma-shi-fou-yi-tong-guo-pei-zhi-wen-jian-pei-zhi-mi-ma-xiu-gai-zui-xiao-jian-ge-shi-jian.md)
  * [是否已通过配置文件设置警告天数为7天](xi-tong-an-quan/suo-you-zhang-hao-mi-ma-shi-fou-yi-tong-guo-pei-zhi-wen-jian-she-zhi-jing-gao-tian-shu-wei-7-tian.md)
  * [/etc/passwd /etc/shadow /etc/group /etc/gshadow的所属用户/组是否为root，权限644](xi-tong-an-quan/etcpasswd-etcshadow-etcgroup-etcgshadowde-suo-shu-yong-6237-zu-shi-fou-wei-root-ff0c-quan-xian-644.md)
  * [是否已通过配置文件设定记录所有用户的登录和操作日志](xi-tong-an-quan/shi-fou-yi-tong-guo-pei-zhi-wen-jian-she-ding-ji-lu-suo-you-yong-hu-de-deng-lu-he-cao-zuo-ri-zhi.md)
  * [是否已通过配置文件打开messages、cron、secure 日志记录](xi-tong-an-quan/shi-fou-yi-tong-guo-pei-zhi-wen-jian-da-kai-messages-cron-secure-ri-zhi-ji-lu.md)
  * [/etc/profile下是否已配置umask值为027](xi-tong-an-quan/etcprofilexia-shi-fou-yi-pei-zhi-umask-zhi-wei-027.md)
  * [服务端口监听是否最小化](xi-tong-an-quan/fu-wu-duan-kou-jian-ting-shi-fou-zui-xiao-hua.md)
  * [是否未配置nfs/smb文件共享](xi-tong-an-quan/shi-fou-wei-pei-zhi-nfs-smb-wen-jian-gong-xiang.md)
* [Windows系统安全](windowsxi-tong-an-quan.md)
  * [是否已重命名Administrator账号](windowsxi-tong-an-quan/shi-fou-yizhong-ming-ming-administrator-zhang-hao.md)
  * [是否已禁用Guest账号](windowsxi-tong-an-quan/shi-fouyi-jin-yong-guest-zhang-hao.md)
  * [是否删除无关帐户](windowsxi-tong-an-quan/shi-fou-ding-qi-jian-cha-bing-shan-chu-yu-wu-guan-zhang-hu.md)
  * [是否设置不显示最后的用户名](windowsxi-tong-an-quan/shi-fou-she-zhi-bu-xian-shi-zui-hou-de-yong-hu-ming.md)
  * [是否已通过配置文件配置密码复杂度要求](windowsxi-tong-an-quan/shi-fou-yi-tong-guo-pei-zhi-wen-jian-pei-zhi-mi-ma-fu-za-du-yao-qiu.md)
  * [是否已配置密码最长留存期](windowsxi-tong-an-quan/shi-fou-yi-pei-zhi-mi-ma-zui-chang-liu-cun-qi.md)
  * [是否已配置帐户锁定策略](windowsxi-tong-an-quan/shi-fou-yi-pei-zhi-zhang-hu-suo-ding-ce-lve.md)
  * [是否已配置关机只分配给Administrators组](windowsxi-tong-an-quan/shi-fou-yi-pei-zhi-ben-di-guan-ji-zhi-fen-pei-gei-administrators-zu.md)
  * [是否已正确配置审核策略设置](windowsxi-tong-an-quan/shi-fou-yi-zheng-que-pei-zhi-shen-he-ce-lve-she-zhi.md)
  * [是否已正确配置共享文件夹授权访问](windowsxi-tong-an-quan/shi-fou-yi-zheng-que-pei-zhi-gong-xiang-wen-jian-jia-shou-quan-fang-wen.md)
  * [是否已配置屏幕保护密码和开启时间](windowsxi-tong-an-quan/shi-fou-yi-pei-zhi-ping-mu-bao-hu-mi-ma-he-kai-qi-shi-jian.md)
  * [是否已配置限制远程登录空闲断开时间](windowsxi-tong-an-quan/shi-fou-yi-pei-zhi-xian-zhi-yuan-cheng-deng-lu-kong-xian-duan-kai-shi-jian.md)
  * [是否已打开Windows自动更新](windowsxi-tong-an-quan/shi-fou-yi-da-kai-windows-zi-dong-geng-xin.md)
* [数据库安全](shu-ju-ku-an-quan.md)
  * [是否已禁止mysql以管理员帐号权限（root）启动运行](shu-ju-ku-an-quan/shi-fou-yi-jin-zhi-mysql-yi-guan-li-yuan-zhang-hao-quan-xian-ff08-root-ff09-qi-dong-yun-xing.md)
  * [是否已删除默认test库及默认空用户](shu-ju-ku-an-quan/shi-fou-yi-shan-chu-mo-ren-test-ku.md)
  * [是否满足数据库模块/账户最小化权限分配的原则](shu-ju-ku-an-quan/shi-fou-man-zu-shu-ju-ku-mo-5757-zhang-hu-zui-xiao-hua-quan-xian-fen-pei-de-yuan-ze.md)
  * [是否所有数据库账号密码为8位以上，且同时具备小写字母、大写字母、数字、特殊字符](shu-ju-ku-an-quan/shi-fou-suo-you-shu-ju-ku-zhang-hao-mi-ma-wei-8-wei-yi-shang-ff0c-qie-tong-shi-ju-bei-xiao-xie-zi-mu-3001-da-xie-zi-mu-3001-shu-zi-3001-te-shu-zi-fu.md)
  * [是否已设置所有数据库账号仅本机访问或可信 IP 访问控制（即host不等于%）](shu-ju-ku-an-quan/shi-fou-yi-she-zhi-suo-you-shu-ju-ku-zhang-hao-jin-ben-ji-fang-wen-huo-ke-xin-ip-fang-wen-kong-zhi-ff08-ji-host-bu-deng-4e8e25-ff09.md)
  * [是否已禁用所有用户的.mysql\_history（软链到/dev/null）](shu-ju-ku-an-quan/shi-fou-yi-jin-yong-suo-you-yong-hu7684-mysql-history-ff08-ruan-lian-5230-dev-null.md)
  * [是否开启二进制日志](shu-ju-ku-an-quan/shi-fou-kai-qi-ri-zhi-shen-ji-gong-neng-ff08-cha-xun-ri-zhi-3001-cuo-wu-ri-zhi-3001-er-jin-zhi-ri-zhi-ff09.md)
  * [是否采用主从同步或集群的高可用模式](shu-ju-ku-an-quan/shi-fou-cai-yong-ji-qun-huo-ff08-zhu-cong-ff09-tong-bu-fu-zhi-de-gao-ke-yong-mo-shi.md)
  * [是否具备完备的数据库备份机制（满足异机存放）](shu-ju-ku-an-quan/shi-fou-ju-bei-wan-bei-de-shu-ju-ku-bei-fen-ji-zhi-ff08-man-zu-yi-ji-cun-fang-ff09.md)
  * [是否对用户的敏感数据是否都采用加密的方式来存储](shu-ju-ku-an-quan/shi-fou-dui-yong-hu-de-min-gan-shu-ju-shi-fou-du-cai-yong-jia-mi-de-fang-shi-lai-cun-chu.md)
* [中间件安全](zhong-jian-jian-an-quan.md)
  * [中间件版本号是否符合安全要求](zhong-jian-jian-an-quan/zhong-jian-jian-ban-ben-hao-shi-fou-fu-he-an-quan-yao-qiu.md)
  * [是否已关闭中间件的管理控制台](zhong-jian-jian-an-quan/shi-fou-yi-guan-bi-zhong-jian-jian-de-guan-li-kong-zhi-tai.md)
  * [是否已配置为高可用/冗灾模式](zhong-jian-jian-an-quan/shi-fou-yi-pei-zhi-wei-gao-ke-yong-mo-shi.md)
  * [是否已禁止中间件目录列出](zhong-jian-jian-an-quan/shi-fou-yi-jin-zhi-zhong-jian-jian-mu-lu-lie-chu.md)
  * [是否已隐藏中间件的版本号](zhong-jian-jian-an-quan/shi-fou-yi-yin-cang-zhong-jian-jian-de-ban-ben-hao.md)
* [应用安全](ying-yong-an-quan.md)
  * [应用系统上线前是否经过Web应用漏洞扫描](ying-yong-an-quan/ying-yong-xi-tong-shang-xian-qian-shi-fou-jing-guo-web-ying-yong-lou-dong-sao-miao.md)
  * [应用系统是否有接入第三方提供的抗攻击（DDOS、WAF）服务](zhong-jian-jian-an-quan/shi-fou-yi-she-zhi-cuo-wu-ye-mian-zhong-ding-xiang.md)
  * [应用系统涉及的组件是否监听最小化](ying-yong-an-quan/ying-yong-xi-tong-she-ji-de-zu-jian-shi-fou-jian-ting-zui-xiao-hua.md)
  * [应用系统涉及配置数据库的连接池配置账号信息是否已加密](ying-yong-an-quan/ying-yong-xi-tong-she-ji-pei-zhi-shu-ju-ku-de-lian-jie-chi-pei-zhi-zhang-hao-xin-xi-shi-fou-yi-jia-mi.md)
  * [应用系统超级管理员账号是否8位以上，且同时具备小写字母、大写字母、数字、特殊字符](ying-yong-an-quan/ying-yong-xi-tong-chao-ji-guan-li-yuan-zhang-hao-shi-fou-8-wei-yi-shang-ff0c-qie-tong-shi-ju-bei-xiao-xie-zi-mu-3001-da-xie-zi-mu-3001-shu-zi-3001-te-shu-zi-fu.md)

