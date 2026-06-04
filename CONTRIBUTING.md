# 贡献指南 (Contributing Guidelines)

感谢您对本项目的兴趣！我们欢迎社区的贡献。请阅读以下指南，了解如何参与项目。

## 📋 目录
- [行为准则](#行为准则)
- [如何贡献](#如何贡献)
- [提交问题](#提交问题)
- [提交拉取请求](#提交拉取请求)
- [编码标准](#编码标准)
- [提交消息规范](#提交消息规范)

## 行为准则

本项目采用了《贡献者公约》行为准则。参与本项目即表示您同意遵守本准则。请参阅 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) 了解更多信息。

## 如何贡献

### 1. Fork 仓库
点击 GitHub 页面上的 "Fork" 按钮，创建仓库的个人副本。

### 2. 克隆仓库
```bash
git clone https://github.com/your-username/repository-name.git
cd repository-name
```

### 3. 创建新分支
```bash
git checkout -b feature/your-feature-name
```

### 4. 进行更改
请确保您的代码遵循项目的编码标准。

### 5. 提交更改
```bash
git add .
git commit -m "feat: add your feature description"
```

### 6. 推送到 GitHub
```bash
git push origin feature/your-feature-name
```

### 7. 创建拉取请求 (Pull Request)
访问您的 GitHub 仓库，点击 "Create Pull Request" 按钮。

## 提交问题 (Issues)

在提交问题之前，请：

1. **搜索现有问题** - 确保问题还未被报告
2. **使用清晰的标题** - 简洁描述问题的要点
3. **提供详细描述** - 包括：
   - 环境信息（操作系统、版本等）
   - 重现问题的步骤
   - 实际行为 vs 期望行为
   - 相关的错误日志或屏幕截图

## 提交拉取请求

### 拉取请求前检查清单
- [ ] 代码遵循项目的编码标准
- [ ] 已添加必要的注释和文档
- [ ] 已更新相关的 README 或文档
- [ ] 已进行测试（如适用）
- [ ] 提交消息遵循项目规范

### 拉取请求描述

请在您的拉取请求中包括：

```markdown
## 描述
简要描述您所做的更改。

## 相关问题
关闭 #(issue number)

## 变更类型
- [ ] 错误修复 (bug fix)
- [ ] 新功能 (new feature)
- [ ] 破坏性更改 (breaking change)
- [ ] 文档更新 (documentation)

## 测试
描述您如何测试这些更改。

## 截图 (如适用)
添加相关的截图。
```

## 编码标准

### Python
- 遵循 [PEP 8](https://www.python.org/dev/peps/pep-0008/) 风格指南
- 使用类型提示
- 编写清晰的文档字符串

### JavaScript/TypeScript
- 使用 ES6+ 语法
- 遵循 [Airbnb JavaScript 风格指南](https://github.com/airbnb/javascript)
- 使用 ESLint 进行代码检查

### 通用规则
- 使用有意义的变量和函数名
- 避免冗长的函数和类
- 添加必要的注释和文档
- 定期运行代码格式化工具

## 提交消息规范

我们遵循 [Conventional Commits](https://www.conventionalcommits.org/) 规范：

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

### 类型 (Type)
- **feat**: 新功能
- **fix**: 错误修复
- **docs**: 文档更新
- **style**: 格式化（不影响代码逻辑）
- **refactor**: 代码重构
- **perf**: 性能优化
- **test**: 测试相关
- **chore**: 构建、依赖更新等

### 示例
```
feat: add user authentication module

This adds JWT-based authentication with support for:
- User login and registration
- Token refresh mechanism
- Email verification

Closes #123
```

## 审查流程

1. **自动检查** - CI/CD 管道会自动运行
2. **代码审查** - 维护者会审查您的代码
3. **修改** - 如果需要，请根据反馈进行修改
4. **合并** - 审查通过后，我们会合并您的拉取请求

## 获取帮助

如有任何疑问，请：
- 在 GitHub Issues 中提问
- 联系项目维护者
- 查看项目文档

感谢您的贡献！🙏
