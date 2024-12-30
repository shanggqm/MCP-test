# Claude MCP 使用指南

## 简介
Claude MCP (Model Control Protocol) 是一个强大的工具，它允许 Claude 直接与各种系统和服务进行交互，比如文件系统、版本控制系统等。

## 使用步骤

### 1. 安装 MCP 服务器
有两种方式可以安装 MCP 服务器：

#### 方式一：通过 npm 或 uvx 安装
```bash
npx @anthropic-ai/claude-mcp
# 或
uvx @anthropic-ai/claude-mcp
```

#### 方式二：克隆本地代码
1. 克隆代码到本地
2. 在项目目录下运行服务器

### 2. 配置
- 确保已经设置好必要的环境变量和权限
- 根据需要配置访问令牌和其他参数

### 3. 功能使用
MCP 支持多种功能：
- 文件系统操作（读取、写入、创建目录等）
- Git 操作（创建仓库、提交代码等）
- 网页操作（导航、截图、点击等）
- 其他系统交互功能

### 4. 注意事项
- 确保在使用前了解相关的安全性考虑
- 遵循最佳实践和使用建议
- 定期更新到最新版本以获得新特性和安全补丁

## 支持
如需更多帮助，请参考：
- [Claude 文档](https://docs.anthropic.com/)
- [MCP GitHub 仓库](https://github.com/anthropics/claude-mcp)