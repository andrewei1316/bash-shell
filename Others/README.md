# 常用命令集

#### 按行替换文件
perl -p -i -e "s;匹配项(正则表达式);目标值;g" "文件路径";


注意和说明：
------

ssl_cert 里是使用openssl生成服务器证书的脚本和配置文件, 请先阅读 ssl_cert/mk_ssl_cert.sh 内的注释