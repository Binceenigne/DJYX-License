# 协议模板

为你的项目选择合适的模板。

## DPL-1.0 模板

复制以下内容到你项目的LICENSE文件：

```
Copyright (c) [年份] [作者姓名]

Licensed under the DJYX Permissive License 1.0 (DPL-1.0)

你可以在以下地址获得协议副本：
https://github.com/Binceenigne/DJYX-License/blob/main/licenses/DPL-1.0-LICENSE.md

本软件在DPL-1.0协议下提供。代码和内容素材可以自由使用、修改和分发
（包括商业用途），但需要适当署名。美术素材需要修改后使用。

完整协议条款请查看LICENSE文件或访问上述URL。
```

## DSL-1.0 模板

复制以下内容到你项目的LICENSE文件：

```
Copyright (c) [年份] [作者姓名]

Licensed under the DJYX Strict License 1.0 (DSL-1.0)

你可以在以下地址获得协议副本：
https://github.com/Binceenigne/DJYX-License/blob/main/licenses/DSL-1.0-LICENSE.md

本软件在DSL-1.0协议下提供。完整源代码需要向DJYX工作室申请。
商业和竞赛用途需要提前30天批准。所有衍生作品必须使用DSL-1.0协议。

申请邮箱：djyxstudio@163.com
完整协议条款请查看LICENSE文件或访问上述URL。
```

## 文件头部注释

### DPL-1.0 项目使用

```javascript
/*
 * Copyright (c) [年份] [作者姓名]
 * 
 * SPDX-License-Identifier: DPL-1.0
 * Licensed under the DJYX Permissive License 1.0
 * 
 * 你可以在以下地址获得协议副本：
 * https://github.com/Binceenigne/DJYX-License/blob/main/licenses/DPL-1.0-LICENSE.md
 */
```

### DSL-1.0 项目使用

```javascript
/*
 * Copyright (c) [年份] [作者姓名]
 * 
 * SPDX-License-Identifier: DSL-1.0
 * Licensed under the DJYX Strict License 1.0
 * 
 * 商业使用需要批准：djyxstudio@163.com
 * 你可以在以下地址获得协议副本：
 * https://github.com/Binceenigne/DJYX-License/blob/main/licenses/DSL-1.0-LICENSE.md
 */
```

## 徽章使用

在你的README.md中添加这些徽章：

### DPL-1.0 徽章
```markdown
![License: DPL-1.0](https://img.shields.io/badge/License-DPL--1.0-blue.svg)
```

### DSL-1.0 徽章
```markdown
![License: DSL-1.0](https://img.shields.io/badge/License-DSL--1.0-orange.svg)
```

## Package.json 示例

### DPL-1.0
```json
{
  "name": "your-project",
  "license": "DPL-1.0",
  "licenses": [
    {
      "type": "DPL-1.0",
      "url": "https://github.com/Binceenigne/DJYX-License/blob/main/licenses/DPL-1.0-LICENSE.md"
    }
  ]
}
```

### DSL-1.0
```json
{
  "name": "your-project", 
  "license": "DSL-1.0",
  "licenses": [
    {
      "type": "DSL-1.0",
      "url": "https://github.com/Binceenigne/DJYX-License/blob/main/licenses/DSL-1.0-LICENSE.md"
    }
  ]
}
```

## 使用说明

1. 将 `[年份]` 替换为当前年份
2. 将 `[作者姓名]` 替换为你的姓名  
3. 根据需要选择DPL-1.0或DSL-1.0
