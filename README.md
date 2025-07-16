# 腾讯云语音识别转SRT字幕工具

> 🎬 利用腾讯云强大的语音识别技术，将音频快速转换为标准SRT字幕格式

[![在线演示](https://img.shields.io/badge/在线演示-点击体验-blue)](https://tencentcloud-asr-to-srt.longjin666.cn)
[![GitHub](https://img.shields.io/github/license/fslongjin/tencentcloud-ASR-to-SRT)](https://github.com/fslongjin/tencentcloud-ASR-to-SRT)
[![B站](https://img.shields.io/badge/B站-灯珑LoGin-pink)](https://space.bilibili.com/151941220)

## 📖 项目介绍

这是一个基于腾讯云语音识别技术的SRT字幕生成工具。通过简单的网页界面，用户可以将腾讯云语音识别的输出结果快速转换为标准的SRT字幕文件，支持各种视频播放器和剪辑软件。

**🎁 腾讯云每月免费10小时语音识别额度，直接白嫖！**

## ✨ 功能特性

- 🎤 **高精度识别** - 基于腾讯云AI语音识别，准确率高达95%+
- 🆓 **免费额度** - 每月免费10小时，满足个人和小团队需求
- 🎬 **完整工作流** - 支持从剪辑软件导出音频进行识别，然后重新导入到剪辑软件里面
- ⚡ **一键转换** - 智能解析时间戳，一键转换为标准SRT格式
- 📱 **简单易用** - 支持拖拽上传，操作简单便捷
- 🌐 **纯前端** - 无需后端服务，本地处理确保隐私安全
- 📂 **智能命名** - 下载的SRT文件自动保持与原文件相同的名称

## 🚀 快速开始

### 在线使用

直接访问在线演示地址：[https://tencentcloud-asr-to-srt.longjin666.cn](https://tencentcloud-asr-to-srt.longjin666.cn)

### 本地部署

1. **克隆项目**
   ```bash
   git clone https://github.com/fslongjin/tencentcloud-ASR-to-SRT.git
   cd tencentcloud-ASR-to-SRT
   ```

2. **打开项目**
   
   直接用浏览器打开 `index.html` 文件即可使用。

3. **部署到服务器**
   
   将项目文件上传到任何静态文件服务器（如 Nginx、Apache 或 GitHub Pages）。

## 📋 使用流程

### 1. 🎵 准备音频文件
在剪辑软件中导出音频文件（支持MP3、WAV等格式）
- Premiere Pro
- Final Cut Pro  
- 剪映
- DaVinci Resolve
- 其他视频编辑软件

### 2. 🎤 腾讯云语音识别
1. 点击页面上的"腾讯云语音识别"按钮，进入[腾讯云语音识别控制台](https://console.cloud.tencent.com/asr/demonstrate)
2. 上传音频文件
3. **重要：结果样式选择"含时间戳"**
4. 等待识别完成

### 3. 📥 下载识别结果
从腾讯云控制台下载识别结果文件（.txt格式）

### 4. 🔄 转换为SRT
1. 将下载的txt文件上传到本工具
2. 系统自动解析并转换为SRT格式
3. 点击下载按钮获取SRT字幕文件

### 5. 🎬 导入剪辑软件
将生成的SRT文件导入到视频编辑软件中，完成字幕制作。

## 📝 文件格式说明

### 输入格式（腾讯云输出）
```
[0:0.920,0:4.380]  这是一段文本1
[0:5.720,0:9.360]  这是一段文本2
[0:9.360,0:13.920]  这是一段文本3
```

### 输出格式（标准SRT）
```
1
00:00:00,920 --> 00:00:04,380
这是一段文本1

2
00:00:05,720 --> 00:00:09,360
这是一段文本2

3
00:00:09,360 --> 00:00:13,920
这是一段文本3
```

## 🛠️ 技术栈

- **前端**: HTML5, CSS3, JavaScript (ES6+)
- **设计**: 现代化UI设计，响应式布局
- **部署**: 静态文件托管，无需后端服务

## 📦 项目结构

```
tencentcloud-ASR-to-SRT/
├── index.html          # 主页面文件
├── README.md           # 项目说明文档
└── data/
    └── a.txt          # 示例数据文件
```

## 🤝 贡献指南

欢迎贡献代码、报告bug或提出新功能建议！

1. Fork 本项目
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的修改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 📄 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 👨‍💻 作者

**灯珑LoGin**
- B站: [@灯珑LoGin](https://space.bilibili.com/151941220)
- GitHub: [@fslongjin](https://github.com/fslongjin)

## 🙏 致谢

- 感谢腾讯云提供强大的语音识别服务
- 感谢所有贡献者和用户的支持

## 📞 反馈与支持

如果您在使用过程中遇到问题或有任何建议：

1. 在 [GitHub Issues](https://github.com/fslongjin/tencentcloud-ASR-to-SRT/issues) 中提出
2. 关注B站UP主 [@灯珑LoGin](https://space.bilibili.com/151941220) 获取更多教程

---

⭐ 如果这个项目对您有帮助，请给个Star支持一下！

## 🔗 相关链接

- [在线演示](https://tencentcloud-asr-to-srt.longjin666.cn)
- [腾讯云语音识别控制台](https://console.cloud.tencent.com/asr/demonstrate)
- [GitHub仓库](https://github.com/fslongjin/tencentcloud-ASR-to-SRT) 