# 中国大学MOOC 拖拽上传附件脚本

一个简单易用的油猴脚本，为中国大学MOOC作业页面添加拖拽上传附件功能。脚本地址：[MOOC DropUploader](https://greasyfork.org/zh-CN/scripts/558305-%E4%B8%AD%E5%9B%BD%E5%A4%A7%E5%AD%A6mooc-%E6%8B%96%E6%8B%BD%E4%B8%8A%E4%BC%A0%E9%99%84%E4%BB%B6-mooc-dropuploader)

## 功能

- 🎯 **拖拽上传** - 直接将文件拖拽到页面即可上传
- ✨ **视觉反馈** - 拖拽时显示提示覆盖层和高亮效果
- ✅ **文件验证** - 自动检查文件格式和大小
- 📊 **进度显示** - 实时显示上传进度

## 安装

1. 安装 [Tampermonkey](https://www.tampermonkey.net/) 浏览器扩展
2. 点击 [MOOC-DropUploader.user.js](./MOOC-DropUploader.user.js) 安装脚本
3. 确认安装即可

## 使用

1. 打开中国大学MOOC的作业页面
2. 将文件拖拽到页面任意位置
3. 脚本自动处理上传

## 支持的文件格式

`txt` `mp3` `jpg` `png` `rar` `zip` `doc` `docx` `ppt` `pptx` `xls` `xlsx` `pdf`

## 配置

编辑脚本顶部的 `CONFIG` 对象可修改：
- `maxFileSize` - 最大文件大小（默认50MB）
- `allowedExtensions` - 允许的文件格式

## 许可

MIT License
