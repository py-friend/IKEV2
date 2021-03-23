安装必须的库

Ubuntu:


apt-get update

apt-get install libpam0g-dev libssl-dev make gcc

CentOS:


yum update

yum install pam-devel openssl-devel make gcc

每一次都要登录GITHUB获取下载链接

wget https://raw.githubusercontent.com/py-friend/IKEV2/master/one-key-ikev2.sh

chmod +x one-key-ikev2.sh

bash one-key-ikev2.sh
