### 服务器ip:81.70.32.115 22 root -phggm0516@
服务器端口：
服务器域名：

#### 登陆远程服务
ssh -p22 root@81.70.32.115 -p 
#### 安装宝塔
yum install -y wget && wget -O install.sh http://download.bt.cn/install/install_6.0.sh && sh install.sh
 
Bt-Panel: http://81.70.32.115:8888/7db2df91
username: goran
password: hggm0516@

#### laravel-admin 安装
composer require encore/laravel-admin
php artisan vendor:publish --provider="Encore\Admin\AdminServiceProvider"
php artisan admin:install
php artisan serve



