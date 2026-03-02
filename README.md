# AI Student System

AI-powered Student Management System with Vue Vite frontend and Spring Boot backend.

## 项目概述

这是一个基于AI的学生管理系统，集成了Google Gemini 2.5 Flash Lite模型，提供智能化的学生管理、学习分析和个性化推荐功能。

## 技术栈

### 前端
- Vue 3 + TypeScript
- Vite (构建工具)
- Pinia (状态管理)
- Element Plus (UI组件库)
- Axios (HTTP客户端)

### 后端
- Spring Boot 3
- Java 17
- Gradle (Kotlin DSL)
- Spring Security (安全认证)
- Spring Data JPA (数据访问)

### 数据库
- SQLite (轻量级关系型数据库)

### AI集成
- Google Gemini 2.5 Flash Lite
- Google AI Java SDK

## 功能特性

### 学生管理
- 学生信息管理（增删改查）
- 成绩管理
- 课程管理
- 考勤管理
- 学习进度跟踪

### AI智能功能
- 智能问答系统
- 学习建议生成
- 成绩分析与预测
- 个性化学习路径推荐
- 学习资源智能推荐

### 系统管理
- 用户认证与授权
- 角色权限管理
- 系统配置管理
- 操作日志记录

## 项目结构

```
AIStudentSystem/
├── frontend/          # Vue Vite前端项目
├── backend/           # Spring Boot后端项目
├── docs/              # 项目文档
├── scripts/           # 部署和构建脚本
└── README.md          # 项目说明
```

## 快速开始

### 环境要求
- Node.js 18+ (前端)
- Java 17+ (后端)
- Gradle 8+ (构建工具)
- Google AI API Key (Gemini访问权限)

### 安装步骤

1. 克隆项目
```bash
git clone https://github.com/leehawzed-arch/AIStudentSystem.git
cd AIStudentSystem
```

2. 配置环境变量
```bash
# 创建环境变量文件
cp .env.example .env
# 编辑.env文件，添加Google AI API Key
```

3. 启动后端服务
```bash
cd backend
./gradlew bootRun
```

4. 启动前端服务
```bash
cd frontend
npm install
npm run dev
```

5. 访问系统
打开浏览器访问：http://localhost:5173

## 开发指南

### 后端开发
```bash
cd backend
# 运行测试
./gradlew test
# 构建项目
./gradlew build
# 运行应用
./gradlew bootRun
```

### 前端开发
```bash
cd frontend
# 安装依赖
npm install
# 开发模式
npm run dev
# 构建生产版本
npm run build
# 代码检查
npm run lint
```

## API文档

后端API文档可通过Swagger UI访问：
- 开发环境：http://localhost:8080/swagger-ui.html
- 生产环境：根据实际部署地址访问

## 部署

### Docker部署
项目支持Docker容器化部署，具体配置参考 `docker-compose.yml` 文件。

### 传统部署
1. 构建前端静态文件
2. 构建后端JAR包
3. 配置数据库和运行环境
4. 启动后端服务

## 贡献指南

欢迎提交Issue和Pull Request。请确保：
1. 代码符合项目编码规范
2. 添加相应的测试用例
3. 更新相关文档

## 许可证

本项目采用 MIT 许可证。

## 联系方式

如有问题或建议，请通过GitHub Issues提交。