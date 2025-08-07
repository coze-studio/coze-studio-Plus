![2.png](http://kmdev.53ai.com/api/preview/f224c9d52485655e5d30f485919cae79.png)

<div align="center">
<p>
  <a href="#Plus版本">Plus版本</a> •
  <a href="#版本优势">版本优势</a> •
  <a href="#功能清单">功能清单</a> •
  <a href="#参与社区">参与社区</a>
</p>
<p>
  <img alt="License" src="https://img.shields.io/badge/license-apache2.0-blue.svg">
  <img alt="Go Version" src="https://img.shields.io/badge/go-%3E%3D%201.23.4-blue">
</p>

[English](README.md) | 中文

</div>

2025 年7 月 26 日，字节将 AI Agent 平台「扣子（Coze）」旗下最核心的项目——服务了数百万开发者的「扣子开发平台」的核心引擎[Coze Studio](https://www.coze.cn/home) 正式开源至 GitHub，并采用了比Dify开放程度更高，无任何附加条款，可自由用于任何商业用途的 Apache 2.0 许可证。

**Coze Studio** 开源的核心功能包括：

* **完整的工作流（Workflow）引擎**：这是扣子团队投入最大精力构建的核心组件。本次开源涵盖了工作流引擎所有节点及编排逻辑。开发者可直接在可视化界面上进行拖拽操作，使用现有功能或进行二次定制与开发。
* **插件（Plugin）核心框架**：开放了插件的定义、调用和管理机制，开发者可以便捷地将任何第三方 API 或私有能力封装成插件，无限扩展 Agent 的能力边界。
* **开箱即用的开发环境**： 只需一键部署，即可获得一个功能完备的 Agent 开发平台，包括创建、调试、版本管理等全套界面，开发者可以专注于创造本身。

## Plus版本

**Coze Studio Plus 是专为中大型企业设计的一站式 AI 开发平台**，在开源 Coze Studio 基础上围绕**团队协作**、**安全合规**和**集成扩展**三大模块进行功能增强，同时实现与 企业微信、钉钉、飞书、Slack、Microsoft Teams等主流企业协作工具的深度集成。Coze Studio Plus将成为企业 AI 应用开发的核心引擎，提供从开发到部署的完整工具链，降低 AI 应用开发门槛，同时满足企业级安全、合规和可扩展性需求。

![2.png](http://kmdev.53ai.com/api/preview/28f3db9c26954281516c9ed4b218fd9b.png)

![1.png](http://kmdev.53ai.com/api/preview/9cf5114fcfe14a88b9746cedd4f9a4c0.png)

![1.png](http://kmdev.53ai.com/api/preview/453d2bc353d8b2e34643e8f72a80a5b8.png)

## 版本优势

**Coze Studio Plus的差异化优势主要体现在以下几个方面：**

* 企业级安全架构：提供 SSO 单点登录、数据加密、审计追踪等功能，满足等保 2.0 三级认证要求。
* 多平台深度集成：无缝对接 企业微信、钉钉、飞书等主流企业协作工具，打通“工作+AI”全链路。
* 团队协作与资源管理：支持团队空间、角色权限管理、多租户隔离，提高企业级团队协作效率。
* 高可扩展性：基于微服务架构设计，支持大规模部署和定制化扩展，满足企业复杂业务场景需求。

## 功能清单

| **功能模块**   | **功能点**                                                                                                             |
| -------------- | ---------------------------------------------------------------------------------------------------------------------- |
| 团队空间       | 团队空间创建与管理 、角色与权限管理、多租户隔离、企业级资源配额管理                                                    |
| 单点登录 (SSO) | 企业微信、钉钉、飞书组织架构集成、企业 AD/LDAP 集成、OAuth 2.0 授权 、SAML 2.0 单点登录                                |
| 审计追踪       | 操作审计日志、模型调用追踪、数据保留策略                                                                               |
| 企业级知识库   | 知识库版本管理、知识库权限管理、多模态知识库                                                                           |
| 模型管理       | 多模型管理 、模型负载均衡、模型性能监控                                                                                |
| 接入应用       | 接入微信分身、企微分身、微信公众号、企微机器人、飞书机器人钉钉机器人、抖音私信、WhatsApp Business 、Facebook Messenger |

## 参与社区

我们致力于构建一个开放、友好的开发者社区，欢迎所有对 AI Agent 开发感兴趣的开发者加入我们！

### 🐛 问题反馈与功能建议

为了更高效地跟踪和解决问题，保证信息透明和便于协同，我们推荐通过以下方式参与：

- **GitHub Issues**：[提交 Bug 报告或功能请求](https://github.com/coze-studio/coze-studio-plus/issues)
- **Pull Requests**：[贡献代码或文档改进](https://github.com/coze-studio/coze-studio-plus/pulls)

### 💬 交流与讨论

加入**Coze Studio Plus版本**交流群，获取项目最新动态：

**微信群聊**
使用微信扫描下方二维码加入：

![88fc652583472e838dd50d870bb16418_origin.png](http://kmdev.53ai.com/api/preview/922bd92d2ac7b1a72a91d1aa204bde01.png)

## 致谢

感谢字节扣子开源[Coze Studio](https://github.com/coze-dev/coze-studio)，同时感谢所有为 Coze Studio 项目做出贡献的开发者和社区成员。

特别感谢：

* [Eino](https://github.com/cloudwego/eino) 框架团队 - 为 Coze Studio 的智能体和工作流运行时、模型抽象封装、知识库索引构建和检索提供了强大的支持
* [FlowGram](https://github.com/bytedance/flowgram.ai) 团队 - 为 Coze Studio 的工作流画布编辑页提供了高质量的流程搭建引擎
* [Hertz](https://github.com/cloudwego/hertz) 团队 - 高性能、强扩展性的 Go HTTP 框架，用于构建微服务
* 所有参与测试和反馈的用户
