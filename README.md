# David Chow 个人网站

一个简洁、响应式的个人网站，用于展示 David Chow 作为统计学本科生的学术背景、项目经历、技能和联系方式。

## 📋 项目结构

```
个人网站/
├── index.html          # 首页
├── about.html          # 关于我页面
├── projects.html       # 项目页面
├── skills.html         # 技能页面
├── contact.html        # 联系页面
├── assets/
│   ├── css/
│   │   └── styles.css  # 样式文件
│   ├── js/
│   │   └── main.js     # JavaScript 脚本
│   └── images/         # 图片资源（可放置头像等）
└── README.md           # 项目说明文档
```

## 🚀 本地预览

### 方法一：直接打开 HTML 文件

1. 克隆或下载项目到本地
2. 直接用浏览器打开 `index.html` 文件即可

### 方法二：使用本地服务器（推荐）

#### 使用 Python（如果已安装）

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

然后在浏览器中访问：`http://localhost:8000`

#### 使用 Node.js（如果已安装）

```bash
# 安装 http-server（全局安装一次即可）
npm install -g http-server

# 在项目目录下运行
http-server -p 8000
```

然后在浏览器中访问：`http://localhost:8000`

#### 使用 VS Code Live Server

1. 在 VS Code 中安装 "Live Server" 扩展
2. 右键点击 `index.html`，选择 "Open with Live Server"

## 🌐 部署到 GitHub Pages

### 步骤 1：创建 GitHub 仓库

1. 在 GitHub 上创建一个新仓库（例如：`personal-website`）
2. 将仓库克隆到本地：
   ```bash
   git clone https://github.com/your-username/personal-website.git
   cd personal-website
   ```

### 步骤 2：上传文件

1. 将所有项目文件复制到仓库目录
2. 提交并推送：
   ```bash
   git add .
   git commit -m "Initial commit: Personal website"
   git push origin main
   ```

### 步骤 3：启用 GitHub Pages

1. 进入仓库的 **Settings**（设置）页面
2. 在左侧菜单中找到 **Pages** 选项
3. 在 **Source** 部分选择：
   - Branch: `main`（或 `master`）
   - Folder: `/ (root)`
4. 点击 **Save** 保存
5. 等待几分钟，GitHub 会生成网站链接，格式为：
   ```
   https://your-username.github.io/personal-website/
   ```

### 步骤 4：自定义域名（可选）

如果需要使用自定义域名：

1. 在仓库根目录创建 `CNAME` 文件，内容为你的域名（例如：`www.yourname.com`）
2. 在你的域名 DNS 设置中添加 CNAME 记录，指向 `your-username.github.io`
3. 在 GitHub Pages 设置中启用自定义域名

## 🎨 自定义内容

### 更新个人信息

- **首页** (`index.html`): 修改自我介绍、社交链接等
- **关于我** (`about.html`): 更新教育背景、兴趣方向、个人理念
- **项目** (`projects.html`): 替换为你的实际项目，更新 GitHub 链接
- **技能** (`skills.html`): 调整技能列表和熟练度百分比
- **联系** (`contact.html`): 更新邮箱和地点信息

### 添加头像

1. 将头像图片放入 `assets/images/` 目录
2. 命名为 `avatar-placeholder.jpg`（或修改 `about.html` 中的图片路径）

### 修改样式

编辑 `assets/css/styles.css` 文件来自定义颜色、字体、间距等样式。

## 📱 响应式设计

网站已针对以下设备尺寸进行优化：

- **桌面端**：> 900px
- **平板**：720px - 900px
- **手机**：< 720px

## 🛠️ 技术栈

- **HTML5**: 语义化标签，良好的可访问性
- **CSS3**: Flexbox/Grid 布局，响应式设计
- **JavaScript**: 导航菜单交互，表单验证
- **字体**: Inter（Google Fonts）

## 📝 SEO 优化

所有页面已包含基本的 SEO 元标签：

- `<title>`: 页面标题
- `<meta name="description">`: 页面描述
- `<meta name="keywords">`: 关键词
- `<meta name="viewport">`: 移动端适配

## 📄 许可证

本项目采用 MIT 许可证，可自由使用和修改。

## 📧 联系方式

- **邮箱**: 13828091837@163.com
- **地点**: 广东广州

---

© 2024 David Chow. 保留所有权利。

