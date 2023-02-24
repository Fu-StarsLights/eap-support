<!--
 * Copyright (c) 2022 EdgerOS Team.
 * All rights reserved.
 * 
 * Detailed license information can be found in the LICENSE file.
 * 
 * @Author       : Fu Wenhao <fuwenhao@acoinfo.com>
 * @Date         : 2023-02-02 10:22:57
 * @LastEditors  : Fu Wenhao <fuwenhao@acoinfo.com>
 * @LastEditTime : 2023-02-02 16:41:19
-->
# EdgerOS 内置 EAP 开发工具

## 功能：
1. 更新特权态 eap 应用
2. 接收 EdgerOS 应用日志
3. 应用自动重启
4. 文件自动授权


## 安装:
```
npm install -g git+https://github.com/Fu-StarsLights/eap-support.git
esport -h

Usage: eap-support [options]
Options:
  -r,--restart        Automatic opening
  -cfg,--config       show config      
  -t,--token <token>  set user token   
  -h, --help          display help for command
```

* 注意 运行 esport 上传文件时,需要在包含 eap 完整的结构目录中。

