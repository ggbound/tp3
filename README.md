## 使用

### 安装
```sh
# 定义包类型
composer config type project 
# 定义包目录（默认目录为：thinkphp）
composer config extra.think-path Core 

composer config secure-http false 
composer config repositories.thinkinstaller git http://gitlab.pocketuni.cn/pu/think-installer.git
composer config repositories.thinkphp git http://gitlab.pocketuni.cn/pu/thinkphp.git
composer require pu/thinkphp
```

