---
title: 使用开发人员订阅来构建 Microsoft 365 解决方案
description: 使用 Microsoft 365 开发人员订阅来构建想要的解决方案。
ms.localizationpriority: high
ms.openlocfilehash: 2450b0dee53ca7a8bdaf90beea3cb08f9e2dea36
ms.sourcegitcommit: b10b392973a9eb8636ce4f1994c3bdbed000411c
ms.translationtype: MT
ms.contentlocale: zh-CN
ms.lasthandoff: 10/13/2022
ms.locfileid: "68570591"
---
# <a name="use-your-developer-subscription-to-build-microsoft-365-solutions"></a>使用开发人员订阅来构建 Microsoft 365 解决方案

你想要使用 Microsoft 365 开发人员订阅来构建什么？ 根据您的兴趣所在，可以完成许多不同任务。 以下是您可以尝试先使用的一些的产品和技术领域。

## <a name="microsoft-teams"></a>Microsoft Teams

Microsoft Teams 是一个基于聊天的工作区，它与用户所使用的应用和服务集成，便于协同完成工作。 使用 Microsoft Teams 开发人员平台，可以轻松集成自己的服务，无论是为自己的企业开发自定义应用，还是为世界各地的团队开发 SaaS 应用。

以下是如何设置与使用 Microsoft Teams 编码的信息：

1. [准备开发人员订阅](/microsoftteams/platform/get-started/get-started-tenant)。
2. 设置开发环境。 此过程将因您想要构建的应用或服务类型而有所不同。 有关详细信息，请参阅以下内容：

  - [开始在 Microsoft Teams 平台上使用 Node.js ](/microsoftteams/platform/get-started/get-started-nodejs-app-studio)
  - [开始在 Microsoft Teams 平台上使用 C#/.NET ](/microsoftteams/platform/get-started/get-started-dotnet-app-studio)

## <a name="microsoft-graph"></a>Microsoft Graph

可以使用 Microsoft Graph 在 Microsoft 云中与数百万用户的数据交互。 使用 Microsoft Graph 为组织和消费者生成应用，此类应用与所有这些资源、关系以及情报通过单个终结点相连接：`https://graph.microsoft.com`。

若要自动配置沙盒以试用 Microsoft Graph 方案，请安装用户和邮件及事件示例数据包：

- 用户 - 安装 16 个具有许可证、邮箱和元数据（包括每位用户的姓名和照片）的虚构用户。 通过下列方式使用 Microsoft Graph API 处理用户示例数据：
  - 获取特定用户详细信息
  - 更新用户
  - 获取直接报告
  - 准备组织结构图
  - 按部门获取用户
- 邮件和事件 - 为 16 个示例用户中的每一位添加 Outlook 电子邮件会话和日历事件。 通过下列方式使用 Microsoft Graph API 处理邮件和事件示例数据：
  - 按用户获取电子邮件
  - 按筛选日期获取电子邮件
  - 获取即将开始的事件
  - 更新/删除即将开始的事件

有关详细信息，请参阅 [使用示例数据包](install-sample-packs.md)。 

有关开始使用 Microsoft Graph 的更多方式，请参阅 [开始生成 Microsoft Graph 应用](https://developer.microsoft.com/en-us/graph/get-started) 或 Microsoft Graph[快速入门](https://developer.microsoft.com/en-us/graph/quick-start)。

## <a name="office-add-ins"></a>Office 加载项

You can use the Office Add-ins platform to build solutions that extend Office applications and interact with content in Office documents. With Office Add-ins, you can use familiar web technologies such as HTML, CSS, and JavaScript to extend and interact with Word, Excel, PowerPoint, OneNote, Project, and Outlook. Your solution can run in Office across multiple platforms, including Office for Windows, Office Online, Office for the Mac, and Office for the iPad.

若要设置开发环境和创建第一个加载项，请参阅 [Office 加载项快速入门](/office/dev/add-ins/)。

## <a name="sharepoint-framework"></a>SharePoint Framework

The SharePoint Framework (SPFx) is a page and web part model that provides full support for client-side SharePoint development, easy integration with SharePoint data, and support for open source tooling. With the SharePoint Framework, you can use modern web technologies and tools in your preferred development environment to build productive experiences and apps that are responsive and mobile-ready.

To automatically configure your sandbox to try out different SharePoint templates and scenarios, install the SharePoint sample data pack.
For more details, see:

- [安装示例数据包](install-sample-packs.md)
- [设置 SPFx 开发人员订阅](/sharepoint/dev/spfx/set-up-your-developer-tenant)
- [设置开发环境](/sharepoint/dev/spfx/set-up-your-development-environment)

## <a name="sharepoint-add-ins"></a>SharePoint 加载项 

SharePoint 加载项为独立式功能，可扩展 SharePoint 网站功能，从而解决明确定义的业务问题。 可以创建两种类型的 SharePoint 外接程序：SharePoint 托管和提供程序托管。 有关详细信息，请参阅 [SharePoint 加载项](/sharepoint/dev/sp-add-ins/sharepoint-add-ins)。

若要完成设置并开始使用 SharePoint 加载项编码：

- [设置订阅](/sharepoint/dev/spfx/set-up-your-developer-tenant)。  
- 设置开发环境： 
  - [开始创建 SharePoint 托管的 SharePoint 加载项](/sharepoint/dev/sp-add-ins/get-started-creating-sharepoint-hosted-sharepoint-add-ins)  
  - [开始创建提供程序托管的 SharePoint 外接程序](/sharepoint/dev/sp-add-ins/get-started-creating-provider-hosted-sharepoint-add-ins)  

## <a name="power-apps"></a>Power Apps

Power Apps for Office 365 包含在 Microsoft 365 E5 开发人员订阅许可证中。 这意味着你可以使用[标准连接器](/connectors/connector-reference/connector-reference-standard-connectors)创建和测试不受限制的应用。 若要使用[高级](/connectors/connector-reference/connector-reference-premium-connectors)或自定义连接器以及 Dataverse，则需要另外提供一个许可证。 出于开发和测试目的，可以使用 [Power Apps 开发人员计划](https://powerapps.microsoft.com/developerplan)。 

Power Apps 是一个应用、服务、连接器和数据平台套件，可提供快速应用程序开发环境，以为你的业务需求构建自定义应用。 使用 Power Apps，可以快速生成连接到业务数据的自定义业务应用，无论这些数据是存储在基础数据平台（普通数据服务）上，还是存储在各种联机和本地数据源（SharePoint、Microsoft 365、Dynamics 365、SQL Server 等）中。

使用 Power Apps 构建的应用提供了丰富的业务逻辑和工作流功能，可将手动业务流程转变为数字自动化流程。 此外，使用 Power Apps 构建的应用具有响应性设计，可以在浏览器或移动设备（手机或平板电脑）上无缝运行。 Power Apps 让用户无需编写代码就能构建功能丰富的自定义业务应用，从而使自定义业务应用构建体验“大众化”。

Power Apps 还提供了一个可扩展的平台，允许专业开发人员以编程方式与数据和元数据交互、应用业务逻辑、创建自定义连接器，并与外部数据集成。

有关详细信息，请参阅：

- [Power Apps](/powerapps/)
- 观看 [Power Apps 演示](https://powerapps.microsoft.com/demo/)
- 在 YouTube 上观看 [Power Apps 频道](https://www.youtube.com/channel/UCGfWR2ekfRFckLjev6eQYLg) 上的视频


## <a name="see-also"></a>另请参阅

- [加入 Microsoft 365 开发人员计划团队](microsoft-365-developer-program.md)
- [设置 Microsoft 365 开发人员订阅](microsoft-365-developer-program-get-started.md) 
- [续订即将到期的订阅](subscription-expiration-and-renewal.md)
- [Microsoft 365 开发人员计划常见问题解答](microsoft-365-developer-program-faq.yml)
- [Microsoft 365 开发人员文档](/microsoft-365/developer)
