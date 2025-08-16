# 吕沁函的个人简历页面

这是我的个人学术简历页面，基于GitHub Pages部署。

## 🚀 快速开始

1. **克隆仓库**
   ```bash
   git clone https://github.com/kirin-01/kirin-01.github.io.git
   cd kirin-01.github.io
   ```

2. **自定义内容**
   - 编辑 `index.html` 文件
   - 更新个人信息、经历、项目等
   - 替换占位符链接

3. **部署**
   - 推送到GitHub仓库
   - 在仓库设置中启用GitHub Pages
   - 访问 `https://kirin-01.github.io`

## 📝 需要更新的内容

### 1. 学术链接
在 `index.html` 中找到并更新以下占位符：
- `YOUR_SCHOLAR_ID` - 您的Google Scholar用户ID
- `YOUR_ORCID_ID` - 您的ORCID ID
- `YOUR_SEMANTIC_SCHOLAR_ID` - 您的Semantic Scholar作者ID

### 2. 头像
替换默认的GitHub头像：
```html
<img class="avatar" src="您的头像URL" alt="吕沁函的头像" />
```

### 3. 访客地图
更新ClustrMaps代码：
1. 访问 [ClustrMaps](https://clustrmaps.com/)
2. 创建您的访客地图
3. 替换 `index.html` 中的ClustrMaps脚本

### 4. 项目链接
更新项目部分的链接，指向您的实际项目：
- GitHub仓库链接
- 项目演示链接
- 论文链接

### 5. 简历PDF
添加您的简历PDF文件：
1. 将简历PDF文件命名为 `cv.pdf`
2. 放在仓库根目录
3. 链接会自动指向 `/cv.pdf`

## 🎨 自定义样式

页面使用CSS变量定义主题色彩，您可以在 `:root` 选择器中修改：
```css
:root{
  --bg:#f8fafc;      /* 背景色 */
  --card:#ffffff;    /* 卡片背景 */
  --muted:#64748b;   /* 次要文字 */
  --text:#1e293b;    /* 主要文字 */
  --brand:#059669;   /* 品牌色 */
  --accent:#10b981;  /* 强调色 */
}
```

## 📱 响应式设计

页面已针对移动设备优化，包含：
- 响应式网格布局
- 移动端导航菜单
- 触摸友好的按钮设计

## 🔧 技术栈

- HTML5
- CSS3 (Grid, Flexbox, CSS Variables)
- 原生JavaScript
- GitHub Pages部署

## 📄 许可证

MIT License

## 🤝 贡献

欢迎提交Issue和Pull Request来改进这个模板！

---

**最后更新**: 2025年1月
