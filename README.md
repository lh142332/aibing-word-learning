# 艾宾浩斯单词学习计划

基于艾宾浩斯遗忘曲线的智能单词学习系统，帮助用户更有效地记忆和复习单词。

## 🌟 功能特点

- **智能学习计划**: 基于艾宾浩斯遗忘曲线自动生成复习计划
- **用户管理**: 完整的用户注册、登录、权限管理系统
- **单词管理**: 添加、删除、分页浏览个人单词库
- **显示模式**: 支持遮盖英文、中文或全遮盖的学习模式
- **响应式设计**: 适配各种设备屏幕

## 🚀 技术栈

- **前端**: HTML5 + CSS3 + 原生JavaScript (ES6+)
- **后端API**: Node.js + Express + MongoDB
- **认证**: JWT Token
- **存储**: SessionStorage

## 📁 项目结构

```
aibing/
├── login.html      # 登录注册页面
├── aibin.html      # 主应用页面
├── admin.html      # 管理员页面
├── vercel.json     # Vercel部署配置
├── package.json    # 项目配置
└── README.md       # 项目说明
```

## 🔧 本地开发

```bash
# 启动本地服务器
python -m http.server 8000
# 或
python3 -m http.server 8000

# 访问应用
open http://localhost:8000/login.html
```

## 🌐 部署

### Vercel 部署
1. 将代码推送到 GitHub
2. 在 [Vercel](https://vercel.com) 导入项目
3. 自动部署完成

### 其他平台
- **Netlify**: 拖拽文件夹即可部署
- **GitHub Pages**: 启用 Pages 功能
- **Cloudflare Pages**: 连接 Git 仓库自动部署

## 🔐 环境配置

确保后端API服务正常运行，API地址配置在各HTML文件中：
```javascript
const API_BASE_URL = 'https://wdwvfaugmvaq.sealoshzh.site';
```

## 👥 用户角色

- **普通用户**: 学习单词、管理个人单词库
- **管理员** (lifei): 额外拥有用户管理权限

## 📱 使用说明

1. **注册/登录**: 首次使用需要注册账号
2. **添加单词**: 在主页面输入英文单词和中文翻译
3. **选择模式**: 使用下拉框选择学习模式
4. **生成计划**: 设置每日新词数量，系统自动生成学习计划
5. **复习提醒**: 按照艾宾浩斯曲线进行复习

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

## 📄 许可证

MIT License
