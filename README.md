# Dr. Sarah Johnson 个人网站部署指南

## 快速部署选项

### 方案 1：GitHub Pages（免费永久）

1. 访问 https://github.com/new 创建新仓库
2. 仓库名设置为 `sarah-johnson-md`
3. 选择 "Public" 公开
4. 上传这4个文件到仓库
5. 进入 Settings → Pages
6. Source 选择 "Deploy from a branch"
7. Branch 选择 "main" → "/ (root)"
8. 点击 Save，等待1-2分钟
9. 访问 https://你的用户名.github.io/sarah-johnson-md

### 方案 2：Netlify（免费，最简单）

1. 访问 https://app.netlify.com/drop
2. 直接将这4个文件拖放到页面中
3. 立即获得免费网站链接
4. 可以自定义域名

### 方案 3：Vercel（免费）

1. 访问 https://vercel.com/new
2. 导入 GitHub 仓库
3. 自动部署，获得 .vercel.app 链接

### 方案 4：Surge.sh（无需账号，快速临时）

```bash
# 安装 surge
npm install -g surge

# 进入网站文件夹
cd website-deploy

# 部署
surge

# 按提示操作，获得随机 xxx.surge.sh 链接
```

### 方案 5：Tiiny.host（最简单临时）

1. 将这4个文件打包成 zip
2. 访问 https://tiiny.host
3. 上传 zip 文件
4. 输入邮箱，立即获得链接

## 文件清单

- `index.html` - 主页面
- `styles.css` - 样式文件
- `script.js` - 交互脚本
- `doctor-photo.jpg` - 医生照片

## 自定义域名

所有方案都支持绑定自己的域名：
- 在设置中找到 "Custom Domain"
- 添加你的域名（如 www.sarahjohnson-md.com）
- 按提示配置 DNS 记录
