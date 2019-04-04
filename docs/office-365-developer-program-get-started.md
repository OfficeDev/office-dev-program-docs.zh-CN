---
title: 设置 Office 365 开发人员订阅
description: 设置 Office 365 开发人员订阅，构建独立于你的生产环境的解决方案。
ms.date: 04/01/2019
localization_priority: Priority
ms.openlocfilehash: 32b32847b50c16c8b8f16b360318af1f18d8d69b
ms.sourcegitcommit: 5d2444c7732b0312a8939cfa3671c3e7835aee3e
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/02/2019
ms.locfileid: "31042003"
---
# <a name="set-up-an-office-365-developer-subscription"></a>设置 Office 365 开发人员订阅 

设置 Office 365 开发人员订阅，构建独立于你的生产环境的解决方案。 此订阅为 Office 365 Enterprise E3 Developer 订阅，随附 25 个用户许可证。 许可证有效期为 90 天，可免费用于开发目的（解决方案编码）。

> [!NOTE] 
> 若要设置订阅，必须先 [加入 Office 365 开发人员计划](office-365-developer-program.md)。 加入后，即可看到设置订阅的选项。

## <a name="set-up-your-subscription"></a>设置订阅

1. 若要获得 Office 365 开发人员订阅，在配置文件页面上，在 **需要 Office 365 订阅用于开发？**，选择**设置订阅**。

  ![设置订阅](images/4-set-up-subscription.png)

2. 在 **设置开发人员订阅** 对话框中，创建一个用户名和域。 此帐户必须具有订阅的全局管理员权限。 可选择任何用户名或域名（只要没有被用过）。 请勿使用空格。

  ![设置订阅表单](images/5-set-up-form.png)

3. 创建并确认密码。

4. 选择 **设置**。

5. 如果要求你证明你不是机器人，请按照说明，然后选择“**验证**”。

6. 创建好订阅后，订阅名称和到期日期会出现在配置文件页。

  > [!IMPORTANT]
  > 记下用户名和密码，因为需要用它来访问开发人员订阅。

## <a name="configure-the-subscription"></a>配置订阅

1. 在配置文件页，选择 [office.com](https://www.office.com/) 链接，然后使用开发人员订阅指定的用户 ID（例如，username@domain.onmicrosoft.com）和密码登录。

   > [!NOTE] 
   > 请不要使用开发人员计划凭据登录到订阅。

2. 使用应用启动器转到 [管理员中心](https://portal.office.com/adminportal/home#/homepage)。

3. 在管理员中心主页上，选择 **转到设置**。 这将转到 **Office 365 Enterprise E3 Developer 设置** 页面。

4. **个性化设置登录和电子邮件**。 可以将订阅连接到域，或只需使用你创建的现有子域。 准备就绪后，选择 **下一步**。

  ![个性化设置登录和电子邮件页面](images/8a-set-up-personalize.png)

5. **添加新用户**。 可以添加用户。 既有可能是虚拟用户，也可能是帮助开发的真实用户。 准备就绪后，选择“**下一步**”。
    
  > [!NOTE]
  > 如果需要批量添加用户，可以稍后再执行此操作。 有关详细信息，请参阅 [将用户逐一或批量添加到 Office 365 — 管理员帮助](https://support.office.com/article/add-users-individually-or-in-bulk-to-office-365-admin-help-1970f7d6-03b5-442f-b385-5880b9c256ec)。

6. **向未经授权用户分配许可证**。 对于你想让其能够使用订阅的任何用户，向其授予许可证。 准备就绪后，选择 **下一步**。

7. **共享登录凭据**。 对于将访问订阅的任何真实用户，必须与其共享其登录凭据。 可以选择一种方法，如电子邮件、 下载或打印。 准备就绪后，选择 **下一步**。

8. **安装 Office 应用**。 可以选择在电脑上安装 Office 应用。 准备就绪后，选择 **下一步**。

  ![安装 Office 应用](images/11-install-office-apps.png)

   > [!TIP] 
   > 随后访问仪表板时，请在转到仪表板之前，使用你的 username@domain**.onmicrosoft.com 帐户登录。

9. **您已达到设置过程的结尾**。 已完成订阅设置。 您可以选择评价体验。 准备就绪后，选择 **转到管理员中心**。
    
   > [!NOTE] 
   > 目前，无论您在哪个国家/地区，订阅的地区默认为北美。 仍可以继续进行设置并使用开发人员订阅。

## <a name="provision-office-365-services"></a>预配 Office 365 服务

后端服务需要一些时间来预配订阅，例如 SharePoint 和 Exchange。 在此步骤期间，应用启动器中和主页上一些图标显示为**设置中 （此应用仍在设置中）**。 此步骤不会超过一个小时。

预配完成后，即可使用新的 Office 365 订阅用于开发。 订阅 90 天后到期。 如果要延期，请查看[我的订阅将要到期时，我是否可以续订？](office-365-developer-program-faq.md#renew-subscription)

我们还建议启用版本选项以确保您可以尽快访问新的 Office 365 功能。 有关详细信息，请参阅 [在 Office 365 中设置标准或定向版本选项](https://support.office.com/article/set-up-the-standard-or-targeted-release-options-in-office-365-3b3adfa4-1777-4ff0-b606-fb8732101f47)。

## <a name="set-up-a-microsoft-azure-account"></a>设置 Microsoft Azure 帐户

对于一些 Office 解决方案，可能需要 Microsoft Azure 帐户使用 Azure 服务来构建。 若要设置免费 Azure 帐户，请参阅 [立即创建 Azure 免费帐户](https://azure.microsoft.com/free/)。

## <a name="leave-the-office-365-developer-program"></a>退出 Office 365 开发人员计划

如果决定不再加入 Office 365 开发人员计划，可以结束订阅并脱离计划。

  > [!WARNING]
  > 以下步骤将擦除所有配置文件信息。 您存储在开发人员订阅中的任何数据都会丢失，且不会在其他位置备份。

1. 登录 Office 365 开发人员计划。

2. 选择 **删除配置文件**。

3. 在 **删除配置文件** 确认框中，选择**删除**。

## <a name="see-also"></a>另请参阅

- [加入 Office 365 开发人员计划](office-365-developer-program.md)
- [使用你的订阅来构建 Office 365 解决方案](build-office-365-solutions.md)
- [续订即将到期的订阅](subscription-expiration-and-renewal.md)
- [Office 365 开发人员计划常见问题解答](office-365-developer-program-faq.md)
