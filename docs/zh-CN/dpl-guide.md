# DPL-1.0 使用指南

DJYX宽松开源协议（DPL-1.0）专为最大兼容性和易用性而设计。

## 主要特性

- ✅ **商业使用**: 可自由用于商业项目
- ✅ **修改**: 无限制修改源代码
- ✅ **分发**: 分发原版或修改版本
- ✅ **私人使用**: 私人使用无需披露
- ⚠️ **美术素材**: 使用前需要修改

## 要求

### 署名
你必须包含：
1. 原作者姓名
2. 原项目URL
3. 版权声明
4. 免责声明

### 美术素材
- 禁止直接使用logo、图像、图形
- 鼓励修改美术素材
- 可以融入原logo的设计元素

## 如何应用DPL-1.0

### 步骤1：添加协议文件
将[DPL-1.0协议文本](../../licenses/DPL-1.0-LICENSE.md)复制到项目的`LICENSE`文件中。

### 步骤2：更新版权信息
替换占位符：
```
Copyright (c) [年份] [作者姓名]
```

### 步骤3：添加文件头部
```javascript
/*
 * Copyright (c) 2025 你的姓名
 * 
 * SPDX-License-Identifier: DPL-1.0
 * Licensed under the DJYX Permissive License 1.0
 */
```

### 步骤4：添加徽章
```markdown
![License: DPL-1.0](https://img.shields.io/badge/License-DPL--1.0-blue.svg)
```

## 示例

### Package.json
```json
{
  "name": "your-project",
  "license": "DPL-1.0",
  "licenses": [
    {
      "type": "DPL-1.0",
      "url": "https://github.com/your-repo/LICENSE"
    }
  ]
}
```

### README模板
```markdown
## 协议

本项目使用DJYX宽松开源协议1.0 - 详情请查看[LICENSE](LICENSE)文件。

### 署名
- 原作者：[作者姓名]
- 项目地址：[仓库URL]
```

## 最佳实践

1. **清晰署名**: 在文档中始终提供清晰的署名
2. **美术素材指南**: 创建受原作启发的新视觉素材
3. **协议兼容性**: DPL-1.0与大多数其他协议兼容
4. **文档**: 在项目文档中包含协议信息

## 常见问题

**问：我可以在专有软件中使用DPL-1.0代码吗？**
答：可以，但需要适当署名。

**问：我需要开源我的修改吗？**
答：不需要，但需要署名。

**问：我可以更改衍生作品的协议吗？**
答：可以，DPL-1.0允许重新许可。
