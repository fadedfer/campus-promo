# 青云大学招生宣传网站

一个现代化、响应式的大学招生宣传单页网站，采用 Apple 风格设计。

## 预览

访问 https://fadedfer.github.io/campus-promo 查看在线演示。

## 特点

- **Apple 风格设计** - 毛玻璃导航栏、圆角卡片、渐变色彩
- **响应式布局** - 完美适配桌面端和移动端
- **流畅动画** - 滚动渐显动画，提升用户体验
- **单页应用** - 无需构建工具，纯 HTML/CSS/JS
- **中文优化** - 使用 PingFang SC、Microsoft YaHei 等优质中文字体

## 页面结构

| 区域 | 内容 |
|------|------|
| 导航栏 | 固定顶部，毛玻璃效果 |
| Hero | 招生标语、统计数据 |
| 关于我们 | 学校特色介绍 |
| 院系专业 | 四大王牌专业展示 |
| 校园生活 | 六大校园亮点 |
| 学生评价 | 校友寄语 |
| 行动号召 | 报名入口 |
| 页脚 | 版权与链接 |

## 快速开始

```bash
# 克隆仓库
git clone https://github.com/fadedfer/campus-promo.git

# 进入项目目录
cd campus-promo

# 直接在浏览器中打开
open index.html
# 或者使用 VS Code 的 Live Server 插件
```

## 技术栈

- HTML5
- CSS3（CSS Variables、Flexbox、Grid、Backdrop Filter）
- Vanilla JavaScript（Intersection Observer API）

## 自定义

修改 `index.html` 中的 CSS 变量即可快速更换主题色彩：

```css
:root {
  --accent: #0071e3;        /* 主色调 */
  --accent-hover: #0077ed;  /* 悬停状态 */
  --bg: #f5f5f7;            /* 背景色 */
  --text: #1d1d1f;          /* 文字颜色 */
}
```

## 许可

© 2026 青云大学. 保留所有权利。
