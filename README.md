![Banner image](https://user-images.githubusercontent.com/10284570/173569848-c624317f-42b1-45a6-ab09-f0ea3c247648.png)

# n8n - 技术团队的安全工作流自动化平台

**⚠️ 免责声明：本中文版README仅供个人测试使用，如因使用本中文版本引起的任何法律问题，由使用者自行承担。**

n8n 是一个工作流自动化平台，为技术团队提供代码般的灵活性和无代码的速度。拥有400+集成、原生AI功能和公平代码许可证，n8n让您能够构建强大的自动化工作流，同时保持对数据和部署的完全控制。

![n8n.io - Screenshot](https://raw.githubusercontent.com/n8n-io/n8n/master/assets/n8n-screenshot-readme.png)

## 核心能力

- **按需编码**：编写JavaScript/Python代码，添加npm包，或使用可视化界面
- **AI原生平台**：基于LangChain构建AI代理工作流，使用您自己的数据和模型
- **完全控制**：使用公平代码许可证自托管或使用云服务
- **企业就绪**：高级权限管理、SSO和空隙部署
- **活跃社区**：400+集成和900+即用模板

## 快速开始


或使用 [Docker](https://docs.n8n.io/hosting/installation/docker/) 部署：

```
docker volume create n8n_data

# 使用中文版，启用企业版 环境变量设置：
# N8N_DEFAULT_LOCALE=zh-CN
# N8N_ENTERPRISE_MOCK=true
# NODE_ENV=development

docker run -it --rm --name n8n -p 5678:5678  -v n8n_data:/home/node/.n8n ghcr.io/deluxebear/n8n:chs

```

在浏览器中访问 http://localhost:5678 打开编辑器

## 资源

- 📚 [官方文档](https://docs.n8n.io)
- 🔧 [400+集成](https://n8n.io/integrations)
- 💡 [示例工作流](https://n8n.io/workflows)
- 🤖 [AI & LangChain指南](https://docs.n8n.io/langchain/)
- 👥 [社区论坛](https://community.n8n.io)

