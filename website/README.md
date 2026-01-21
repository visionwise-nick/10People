# 10People 官方网站

这是 10People 的官方网站，展示极简的"平安确认"与"意念连接"应用的功能和特性。

## 产品信息

- **产品代号**: 10People
- **Slogan**: The world is noisy, I just want to hear your heartbeat.
- **核心价值**: Minimalist "safety check" and "mind connection"

## 网站结构

```
website/
├── index.html          # 主页
├── privacy.html        # 隐私政策
├── terms.html          # 用户协议
├── styles.css          # 样式文件
├── script.js           # JavaScript功能
├── assets/
│   └── icon/
│       └── app_icon.png # 应用图标
└── README.md           # 说明文档
```

## 功能特性

### 主页 (index.html)
- 响应式设计，支持移动端和桌面端
- 产品介绍和核心功能展示
- 核心功能：每天一次点亮、Widget 2.0、唯一沟通方式（戳一下）
- 病毒式传播：只有10张"船票"的稀缺性营销
- 下载链接
- 现代化UI设计

### 核心功能
1. **Light Up Once a Day**: 单击点亮或长按输入简短文字
2. **Widget 2.0: The Window**: 桌面小组件显示10个格子
3. **Nudge: The Only Communication**: 唯一的沟通方式，没有聊天框
4. **Only 10 Spots**: 稀缺性设计，只有10个位置
5. **Anti-Social Design**: 反社交设计，无历史记录，无时间戳
6. **Invite-Only Connection**: 通过邀请码链接绑定关系

### 隐私政策 (privacy.html)
- 详细的数据收集和使用说明
- 用户权利和保护措施
- 本地存储和云端同步说明
- 联系方式和投诉渠道

### 用户协议 (terms.html)
- 服务使用条款和条件
- 知识产权说明
- 付费服务条款
- 责任限制和争议解决

## 技术特点

- **响应式设计**: 适配各种屏幕尺寸
- **现代CSS**: 使用Flexbox和Grid布局
- **平滑动画**: CSS过渡和JavaScript交互
- **SEO优化**: 语义化HTML和meta标签
- **性能优化**: 压缩图片和优化代码

## 部署说明

### GitHub Pages部署

1. 将website文件夹内容推送到GitHub仓库
2. 在GitHub仓库设置中启用Pages功能
3. 选择"Deploy from a branch"，选择main分支，选择/website文件夹（或根目录）
4. 网站将自动部署到 `https://visionwise-nick.github.io/10People/`

### 本地开发

1. 克隆仓库到本地
2. 进入website目录
3. 使用本地服务器运行（如Python的`python -m http.server 8000`）
4. 在浏览器中访问 `http://localhost:8000`

## 自定义配置

### 修改联系信息
在以下文件中更新联系信息：
- `privacy.html` - 隐私政策联系信息
- `terms.html` - 用户协议联系信息
- `index.html` - 页脚联系信息

### 更新下载链接
在`index.html`的下载区域更新各平台的应用商店链接。
