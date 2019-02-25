## 使用

### 安装
```sh
# 定义包类型
composer config type project 
# 定义包目录（默认目录为：thinkphp）
composer config extra.think-path Core 

composer config repositories.thinkinstaller git https://github.com/ggbound/think-install.git
composer config repositories.thinkphp git https://github.com/ggbound/tp3.git
composer require ggbound/tp3
```

