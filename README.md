# 此版本是 openApi2.0 的核心包 composer 封装
# 注册了命名空间 SDK内需要的地方也都 导入了命名空间

````` json

"autoload": {
    "psr-4": {
      "Aliyun\\Core\\": "aliyun-php-sdk-core",
      "Aliyun\\Core\\Auth\\": "aliyun-php-sdk-core/Auth",
      "Aliyun\\Core\\Http\\": "aliyun-php-sdk-core/Http",
      "Aliyun\\Core\\Profile\\": "aliyun-php-sdk-core/Profile",
      "Aliyun\\Core\\Regions\\": "aliyun-php-sdk-core/Regions",
      "Aliyun\\Core\\Exception\\": "aliyun-php-sdk-core/Exception"

    }
  }


`````
