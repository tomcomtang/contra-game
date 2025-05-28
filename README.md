# 魂斗罗 (Contra) Web版

这是一个基于Web的魂斗罗游戏实现，使用JavaScript开发，可以在浏览器中直接运行。这个项目是对经典FC游戏《魂斗罗》的致敬。

## 🎮 游戏特点

- 完全在浏览器中运行，无需安装
- 支持键盘操作
- 经典的游戏音效
- 流畅的游戏体验
- 支持存档功能

## 🚀 快速开始

### EdgeOne部署

1. 访问 [EdgeOne控制台](https://console.edgeone.tencent.com/)
2. 创建新的站点
3. 选择"静态网站托管"
4. 将本仓库代码上传到EdgeOne
5. 等待部署完成，即可通过分配的域名访问游戏

### 本地部署

1. 克隆仓库
```bash
git clone https://github.com/tomcomtang/contra-game.git
```

2. 进入项目目录
```bash
cd contra-game
```

3. 使用任意Web服务器托管项目文件
   - 可以使用Python的简易服务器：
     ```bash
     # Python 3
     python -m http.server 8000
     ```
   - 或者使用Node.js的http-server：
     ```bash
     npx http-server
     ```

4. 在浏览器中访问 `http://localhost:8000` 即可开始游戏

### 在线体验

你也可以直接访问在线版本：[https://tomcomtang.github.io/contra-game/](https://tomcomtang.github.io/contra-game/)

## 🎯 游戏操作

- **方向键**：控制角色移动
- **Z键**：跳跃
- **X键**：射击
- **C键**：切换武器
- **Enter键**：开始游戏/暂停
- **ESC键**：退出游戏

## 🛠️ 技术栈

- HTML5
- CSS3
- JavaScript
- NES模拟器核心

## 📝 项目结构

```
contra-game/
├── css/            # 样式文件
├── images/         # 游戏图片资源
├── lib/            # 第三方库
├── roms/           # 游戏ROM文件
├── source/         # 游戏源代码
└── index.html      # 主页面
```

## 🤝 贡献

欢迎提交Issue和Pull Request来帮助改进这个项目！

## 📄 许可证

本项目仅供学习和研究使用。魂斗罗是Konami的注册商标。

## 🙏 致谢

- 感谢原版魂斗罗游戏开发团队
- 感谢所有为这个项目做出贡献的开发者

## 📞 联系方式

如有任何问题或建议，欢迎通过GitHub Issues联系我。

---

希望你能享受这个经典游戏的Web版本！🎮 