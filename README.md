# 智能待办事项管理系统

> **Description**: 🚀 一个功能完善的Web待办事项管理系统，支持任务分类、优先级、截止提醒和团队协作。

## 项目简介

这是一个基于Web的智能待办事项管理系统，旨在帮助个人和团队高效管理日常任务。系统支持任务分类、优先级设置、截止日期提醒等功能，让工作和生活更有条理。

## 功能特性

- **任务管理**：创建、编辑、删除待办事项
- **分类标签**：支持自定义标签对任务进行分类
- **优先级设置**：标记任务的紧急程度（高/中/低）
- **截止日期**：设置任务截止时间，自动提醒
- **进度追踪**：实时查看任务完成情况
- **数据统计**：可视化展示任务完成率和时间分布
- **多用户支持**：团队成员可协作管理共享任务

## 技术栈

### 前端
- React.js
- Tailwind CSS / Bootstrap
- Axios

### 后端
- Node.js + Express
- RESTful API

### 数据库
- MySQL

### 其他工具
- Git 版本控制
- ESLint 代码规范
- Jest 单元测试

## 项目结构

```
smart-todo-app/
├── frontend/           # 前端代码
│   ├── src/
│   ├── public/
│   └── package.json
├── backend/            # 后端代码
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── package.json
├── docs/               # 项目文档
├── tests/              # 测试文件
└── README.md
```

## 快速开始

### 环境要求

- Node.js >= 14.0
- npm >= 6.0 
- MySQL >= 5.7

### 安装步骤

1. 克隆仓库
```bash
git clone https://github.com/hua296013-jpg/smart-todo-app.git
cd smart-todo-app
```

2. 安装前端依赖
```bash
cd frontend
npm install
```

3. 安装后端依赖
```bash
cd ../backend
npm install
```

4. 配置环境变量
```bash
cp .env.example .env
# 编辑 .env 文件，配置数据库连接等信息
```

5. 启动开发服务器
```bash
# 启动后端
cd backend
npm run dev

# 启动前端（新开终端）
cd frontend
npm start
```

6. 访问应用
打开浏览器访问 `http://localhost:3000`

## 开发规范

### 分支管理
- `main`：主分支，保持稳定可发布状态
- `develop`：开发分支，日常开发合并到此分支
- `feature/*`：功能分支，开发新功能时使用
- `bugfix/*`：修复分支，修复bug时使用

### 提交规范
使用语义化提交信息：
- `feat`: 新功能
- `fix`: 修复bug
- `docs`: 文档更新
- `style`: 代码格式调整
- `refactor`: 重构代码
- `test`: 测试相关
- `chore`: 构建/工具链相关

示例：`feat: 添加任务优先级筛选功能`

## 贡献指南

我们欢迎任何形式的贡献！请遵循以下步骤：

1. Fork 本仓库
2. 创建你的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交你的改动 (`git commit -m 'feat: 添加某个很棒的功能'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个 Pull Request

## 团队成员

- 潘铮
- 高明亮
- 于灏

## 开发路线图

- [ ] 基础任务CRUD功能
- [ ] 用户认证系统
- [ ] 任务分享与协作
- [ ] 移动端适配
- [ ] 邮件/推送通知
- [ ] 数据导出功能
- [ ] 深色模式支持

## 许可证

本项目采用 MIT 许可证 - 查看 [LICENSE](LICENSE) 文件了解详情

## 联系方式

如有问题或建议，欢迎提交issue

⭐️ 如果这个项目对你有帮助，请给我们一个Star！
