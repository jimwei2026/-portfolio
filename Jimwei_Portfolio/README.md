# Be Water — Portfolio Website

## 文件说明 / Files

| 文件 | 说明 |
|------|------|
| `index.html` | 主页面，所有交互逻辑已内嵌 |
| `logo.png`   | Be Water logo（圆形） |
| `hero.mp4`   | Hero 全屏背景视频 |

## 使用方法 / How to Use

**方法一：直接双击**
直接用浏览器打开 `index.html` 即可（推荐 Chrome / Safari）。
三个文件必须放在同一文件夹内。

**方法二：本地服务器（推荐，视频可正常自动播放）**
```bash
# 进入项目目录
cd BeWater_Portfolio

# Python 3
python3 -m http.server 8080

# 然后访问
http://localhost:8080
```

## 替换内容 / Customization

- **Logo**：替换 `logo.png`（保持文件名不变）
- **视频**：替换 `hero.mp4`（保持文件名不变）
- **项目图片**：在 `index.html` 中搜索 `images.unsplash.com` 替换为本地图片路径
- **文字内容**：在 `index.html` 中搜索 `dict` 对象，修改各语言的文字

## 功能特性 / Features

- ✅ 全屏 Hero 视频（自动循环播放）
- ✅ 水滴光标 + 水面波纹效果
- ✅ 右侧波浪边框导航栏
- ✅ 四语言切换（EN / 中文 / 日本語 / FR）
- ✅ Work 瀑布流 + 含羞草光标回避动效
- ✅ 标题自动轮播 Ticker
- ✅ 纯白黑灰色系
