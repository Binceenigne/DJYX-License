# GitHub Pages 设置指南

## 启用GitHub Pages

1. **访问仓库设置**
   - 转到: https://github.com/Binceenigne/DJYX-License
   - 点击 "Settings" 标签

2. **配置Pages设置**
   - 在左侧菜单中点击 "Pages"
   - 在 "Source" 部分选择 "Deploy from a branch"
   - 选择分支: `main`
   - 选择文件夹: `/ (root)`
   - 点击 "Save"

3. **等待部署**
   - GitHub会显示一个绿色的检查标记
   - 通常需要几分钟时间
   - 页面URL: https://binceenigne.github.io/DJYX-License/

## 故障排除

### 如果仍然显示404:

1. **检查文件**
   - 确保 `index.html` 在根目录
   - 确保所有文件都已推送到GitHub

2. **强制刷新**
   - 使用 Ctrl+F5 强制刷新浏览器
   - 清除浏览器缓存

3. **等待时间**
   - GitHub Pages有时需要最多10分钟来部署
   - 检查GitHub Actions页面查看部署状态

4. **验证设置**
   - 确保仓库是公开的
   - 检查GitHub Pages设置是否正确

## 测试本地版本

如果需要立即查看页面，可以在本地打开:
```
file:///g:/工作/DJYX-License/index.html
```

## 联系支持

如果问题持续存在，请检查:
- GitHub Status页面
- 仓库的Actions标签页
- 或等待几分钟后重试
