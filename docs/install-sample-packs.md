---
title: 将示例数据包与 Microsoft 365 开发人员计划订阅结合使用
description: 了解如何在开发人员订阅上安装示例数据包，以快速启动并运行沙盒环境。
localization_priority: Priority
ms.openlocfilehash: 2cc7027ccad5b7971c1ae9d49416b9b25663c255
ms.sourcegitcommit: 9c7a1aa1c562adb350fefc8068e154fa6f9a4ee3
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 03/11/2020
ms.locfileid: "42600800"
---
# <a name="use-sample-data-packs-with-your-microsoft-365-developer-program-subscription"></a>将示例数据包与 Microsoft 365 开发人员计划订阅结合使用

可以在 Microsoft 365 开发人员计划订阅上安装示例数据包。 示例数据包可自动安装构建和测试解决方案所需的数据和内容，从而节省你的时间。 其中包含虚构用户、元数据和照片，用于模拟小型企业环境。 你可以快速安装示例数据，以便专注于你的解决方案，而不是花时间亲自创建示例数据。

可以在订阅磁贴底部的 [Microsoft 365 开发人员计划仪表板](https://developer.microsoft.com/office/profile)上找到示例数据包。

![仪表板页面上的订阅磁贴屏幕截图](images/sample-data-pack-ux-tile-users-beginning.PNG)

目前提供以下示例数据包：

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

> [!NOTE]
> 在安装邮件和事件之前，你必须先安装用户示例数据包。

## <a name="what-do-the-sample-data-packs-add-to-my-subscription"></a>示例数据包会将什么添加到我的订阅中？

用户示例数据包将在你的订阅上创建 16 个虚构用户，并包含每位用户的许可证、邮箱、姓名、元数据和照片。

邮件和事件示例数据包将为已安装的 16 个用户中的每一位添加 Outlook 电子邮件会话和日历事件。

## <a name="how-do-i-install-the-users-sample-data-pack"></a>如何安装用户示例数据包？

安装“用户”示例数据包前，请先确保你有 Microsoft 365 开发人员订阅，并以管理员身份为自己分配许可证。

> [!NOTE]
> 确保你的订阅中有 16 位用户空闲。 你的订阅包含 25 位用户。 如果你配置的用户数已超过 10 位，则请先删除一些用户，确保安装功能。

若要安装用户示例数据包，请执行下列操作：

1. 选择订阅磁贴底部的“**用户**”框。
2. 复制你的管理员 ID；你需要它来登录你的订阅。
3. 在登录页面上输入你的管理员 ID 和密码。
4. 以 Microsoft 365 开发人员订阅管理员身份许可权限。

![显示权限许可对话框的屏幕截图](images/sample-data-pack-ux-tile-users-consent-with-permissions-combined.PNG)

5. 为所有示例用户配置密码。 你需要定义一个共享密码，以便轻松管理所有虚构用户。

![用于添加共享用户密码的对话框的屏幕截图](images/sample-data-pack-ux-tile-users-fake-user-password-creation.PNG)

6. 系统将安装数据。 安装过程大约需要 5 分钟时间。

![显示仪表板磁贴上的安装进程的屏幕截图](images/sample-data-pack-ux-tile-users-installing-status.PNG)

7. 安装完成后，你将收到电子邮件通知，订阅磁贴上的框将显示为绿色。 你现在可以安装邮件和事件示例数据包。

![准备安装邮件和事件的仪表板磁贴的屏幕截图](images/sample-data-pack-ux-tile-users-installed.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a>如何安装邮件和事件示例数据包？

安装用户示例数据包后，你可以安装邮件和事件。

1. 选择订阅磁贴上的“**邮件和事件**”框。
2. 选择“**安装**”以开始安装。

![安装对话框的屏幕截图](images/sample-data-pack-ux-tile-mail-and-events-begin-install.PNG)

> [!NOTE]
> 如果你刚刚创建了订阅，则必须先完整配置它，然后才能开始安装。 这可能需要几个小时。 安装开始后，最多可能需要 20 分钟才能完成。

3. 安装完成后，你将收到电子邮件通知，订阅磁贴上的框将显示为绿色。

## <a name="are-more-sample-data-packs-coming"></a>是否会推出更多示例数据包？

是。 我们将为 SharePoint 和 OneDrive 添加示例数据包。 将来，我们将考虑为更多产品和技术添加示例数据包，包括 Office 加载项、Microsoft Teams 等。

## <a name="can-i-install-sample-data-packs-on-my-other-microsoft-365-subscriptions"></a>能否在其他 Microsoft 365 订阅上安装示例数据包？

否。 这些示例数据包仅与作为 Microsoft 365 开发人员计划的一部分获取的 Microsoft 365 开发人员订阅兼容。

## <a name="how-can-i-see-the-sample-data-in-my-subscription"></a>如何查看我的订阅中的示例数据？

安装“用户”示例数据包后，若要查看添加的用户，请在 Microsoft 365 开发人员订阅上转到 **Microsoft 365 管理中心**。 在“**用户**”下，选择“**活动用户**”。 你将会看到包含 16 个用户的列表。 你可以选择一个用户来查看相关联的元数据，包括照片和许可证。

![Microsoft 365 管理中心内 16 个用户的屏幕截图，其中包含针对所选用户的元数据](images/content-packs-07.PNG)

安装邮件和事件示例包后，若要查看示例数据，请在 **Microsoft 365 管理中心**内选择“**全部显示**”，然后选择“**Exchange**”。 在 Exchange 管理中心内，当你选择“**收件人**”时，你可以看到 16 个用户均拥有添加了邮件和事件的邮箱。
![添加到 Exchange 管理中心的 16 个用户的屏幕截图](images/content-packs-08.PNG)

## <a name="see-also"></a>另请参阅

- [设置 Microsoft 365 开发人员订阅](microsoft-365-developer-program-get-started.md)
