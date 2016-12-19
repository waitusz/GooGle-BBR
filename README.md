#                             GooGle TCP BBr网络加速脚本
本脚本适用于Centos6，使用方法 

    wget --no-check-certificate https://github.com/waitusz/GooGle-BBR/raw/master/BBR_c6.sh && sh BBR_c6.sh



之后重启服务器即可

验证是否安装成功 

    执行 lsmod | grep bbr
   
如果结果显示bbr便安装成功
