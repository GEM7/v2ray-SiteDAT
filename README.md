# v2ray-SiteDAT

## 自定义site.dat 文件

### 下载

  - https://github.com/onplus/v2ray-SiteDAT/releases

### 脚本使用：

  - 修改/添加sites文件夹下的域名文件，运行 ./v2sitedat 生成geosite.dat
  
  - 带路径 /v2sitedat -dat ./geofilepath/h2y.dat -dir ./geofilepath
    
  - 更多参考 ./v2sitedat --help 


**改自 https://github.com/v2ray/ext/tree/master/tools/geosites**

**改自 https://github.com/gamesofts/v2ray-custom-geo**

**规则参考 https://github.com/h2y/Shadowrocket-ADBlock-Rules**

### V2ray 调用方法

  - 将geodata文件移入v2ray所在文件夹中，然后按以下方式调用

  ```
       "domain": [
         "ext:h2y.dat:gfw"
     ]
  ```
  
**详见 https://toutyrater.github.io/routing/sitedata.html**
