##Laravel 5.4 Base Project
###Initialize
- add service providers to config files

###Plugins
Common Plugins
- cors
- redis
- admin
- i18n
- jwt auth
- chinese payments: alipay wechatpay
- chinese oauth login: wechat qq webo
- chinese sms: alidayu...
- chinese cloud storage: aliyun oss...
- wechat api

###Development plugins

- ide helper
- eloquent model generator
- apidoc generator
- test factory helper

###Requirements
```json
"require": {
    "php": ">=7",
    "barryvdh/laravel-cors": "*",
    "encore/laravel-admin": "1.4.x-dev",
    "ignited/laravel-omnipay": "2.*",
    "laravel/framework": "5.4.*",
    "laravel/tinker": "~1.0",
    "lokielse/omnipay-alipay": "^2.0",
    "lokielse/omnipay-wechatpay": "^1.0",
    "overtrue/laravel-lang": "*",
    "overtrue/laravel-socialite": "~1.0",
    "overtrue/laravel-wechat": "~3.0",
    "predis/predis": "^1.1",
    "toplan/laravel-sms": "*",
    "tymon/jwt-auth": "*",
    "yangyifan/upload": "0.2"
},
"require-dev": {
    "barryvdh/laravel-ide-helper": "^2.3",
    "fzaninotto/faker": "~1.4",
    "krlove/eloquent-model-generator": "dev-bugfix",
    "mockery/mockery": "0.9.*",
    "mpociot/laravel-apidoc-generator":https://pigjian.com "*",
    "mpociot/laravel-test-factory-helper": "*",
    "phpunit/phpunit": "~5.7"
},
```

