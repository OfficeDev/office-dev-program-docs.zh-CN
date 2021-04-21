---
title: 将示例数据包与 Microsoft 365 开发人员计划订阅结合使用
description: 了解如何在开发人员订阅上安装示例数据包，以快速启动并运行沙盒环境。
localization_priority: Priority
ms.openlocfilehash: 3802c1c1e02c7be9ccb322561189ee0d085e8ce0
ms.sourcegitcommit: 3d50606496bd0bdbbcf892d2d18de6343a44c576
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 04/19/2021
ms.locfileid: "51890147"
---
# <a name="use-sample-data-packs-with-your-microsoft-365-developer-program-subscription"></a><span data-ttu-id="9b25a-103">将示例数据包与 Microsoft 365 开发人员计划订阅结合使用</span><span class="sxs-lookup"><span data-stu-id="9b25a-103">Use sample data packs with your Microsoft 365 Developer Program subscription</span></span>

<span data-ttu-id="9b25a-104">可以在 Microsoft 365 开发人员计划订阅上安装示例数据包。</span><span class="sxs-lookup"><span data-stu-id="9b25a-104">You can install sample data packs on your Microsoft 365 Developer Program subscription.</span></span> <span data-ttu-id="9b25a-105">示例数据包可自动安装构建和测试解决方案所需的数据和内容，从而节省你的时间。</span><span class="sxs-lookup"><span data-stu-id="9b25a-105">Sample data packs save you time by automatically installing data and content you need to build and test your solutions.</span></span> <span data-ttu-id="9b25a-106">其中包含虚构用户、元数据和照片，用于模拟小型企业环境。</span><span class="sxs-lookup"><span data-stu-id="9b25a-106">This includes fictitious users, metadata, and photos to simulate a small corporate environment.</span></span> <span data-ttu-id="9b25a-107">你可以快速安装示例数据，以便专注于你的解决方案，而不是花时间亲自创建示例数据。</span><span class="sxs-lookup"><span data-stu-id="9b25a-107">You can quickly install the sample data so that you can focus on your solutions rather than spend time creating sample data yourself.</span></span>

<span data-ttu-id="9b25a-108">可以在订阅磁贴底部的 [Microsoft 365 开发人员计划仪表板](https://developer.microsoft.com/office/profile)上找到示例数据包。</span><span class="sxs-lookup"><span data-stu-id="9b25a-108">You can find sample data packs on your [Microsoft 365 Developer Program dashboard](https://developer.microsoft.com/office/profile), at the bottom of your subscription tile.</span></span>

![仪表板页面上的订阅磁贴屏幕截图](images/sample-data-pack-ux-tile-users-beginning.PNG)

<span data-ttu-id="9b25a-110">目前提供以下示例数据包：</span><span class="sxs-lookup"><span data-stu-id="9b25a-110">The following sample data packs are currently available:</span></span>

- <span data-ttu-id="9b25a-111">用户 - 安装 16 个具有许可证、邮箱和元数据（包括每位用户的姓名和照片）的虚构用户。</span><span class="sxs-lookup"><span data-stu-id="9b25a-111">Users - Installs 16 fictitious users with licenses, mailboxes, and metadata, including names and photos for each user.</span></span> <span data-ttu-id="9b25a-112">通过下列方式使用 Microsoft Graph API 处理用户示例数据：</span><span class="sxs-lookup"><span data-stu-id="9b25a-112">Use Microsoft Graph APIs to work with user sample data in the following ways:</span></span>
  - <span data-ttu-id="9b25a-113">获取特定用户详细信息</span><span class="sxs-lookup"><span data-stu-id="9b25a-113">Get specific user details</span></span>
  - <span data-ttu-id="9b25a-114">更新用户</span><span class="sxs-lookup"><span data-stu-id="9b25a-114">Update user</span></span>
  - <span data-ttu-id="9b25a-115">获取直接报告</span><span class="sxs-lookup"><span data-stu-id="9b25a-115">Get direct reports</span></span>
  - <span data-ttu-id="9b25a-116">准备组织结构图</span><span class="sxs-lookup"><span data-stu-id="9b25a-116">Prepare organization chart</span></span>  
  - <span data-ttu-id="9b25a-117">按部门获取用户</span><span class="sxs-lookup"><span data-stu-id="9b25a-117">Get users by department</span></span>

- <span data-ttu-id="9b25a-118">邮件和事件 - 为 16 个示例用户中的每一位添加 Outlook 电子邮件会话和日历事件。</span><span class="sxs-lookup"><span data-stu-id="9b25a-118">Mail and events - Adds Outlook email conversations and calendar events for each of the 16 sample users.</span></span> <span data-ttu-id="9b25a-119">通过下列方式使用 Microsoft Graph API 处理邮件和事件示例数据：</span><span class="sxs-lookup"><span data-stu-id="9b25a-119">Use Microsoft Graph APIs to work with mail and events sample data in the following ways:</span></span>
  - <span data-ttu-id="9b25a-120">按用户获取电子邮件</span><span class="sxs-lookup"><span data-stu-id="9b25a-120">Get emails by users</span></span>
  - <span data-ttu-id="9b25a-121">按筛选日期获取电子邮件</span><span class="sxs-lookup"><span data-stu-id="9b25a-121">Get emails filtered by date</span></span>
  - <span data-ttu-id="9b25a-122">获取即将开始的事件</span><span class="sxs-lookup"><span data-stu-id="9b25a-122">Get upcoming events</span></span>
  - <span data-ttu-id="9b25a-123">更新/删除即将开始的事件</span><span class="sxs-lookup"><span data-stu-id="9b25a-123">Update/delete upcoming events</span></span>

> [!NOTE]
> <span data-ttu-id="9b25a-124">在安装邮件和事件之前，你必须先安装用户示例数据包。</span><span class="sxs-lookup"><span data-stu-id="9b25a-124">You must install the Users sample data pack before you install Mail and Events.</span></span>

## <a name="what-do-the-sample-data-packs-add-to-my-subscription"></a><span data-ttu-id="9b25a-125">示例数据包会将什么添加到我的订阅中？</span><span class="sxs-lookup"><span data-stu-id="9b25a-125">What do the sample data packs add to my subscription?</span></span>

<span data-ttu-id="9b25a-126">用户示例数据包将在你的订阅上创建 16 个虚构用户，并包含每位用户的许可证、邮箱、姓名、元数据和照片。</span><span class="sxs-lookup"><span data-stu-id="9b25a-126">The Users sample data pack creates 16 fictitious users on your subscription, and includes the licenses for each user, and mailboxes, names, metadata, and photos for each.</span></span>

<span data-ttu-id="9b25a-127">邮件和事件示例数据包将为已安装的 16 个用户中的每一位添加 Outlook 电子邮件会话和日历事件。</span><span class="sxs-lookup"><span data-stu-id="9b25a-127">The Mail and Events sample data pack adds Outlook email conversations and calendar events for each of the 16 users installed.</span></span>

## <a name="how-do-i-install-the-users-sample-data-pack"></a><span data-ttu-id="9b25a-128">如何安装用户示例数据包？</span><span class="sxs-lookup"><span data-stu-id="9b25a-128">How do I install the Users sample data pack?</span></span>

<span data-ttu-id="9b25a-129">安装“用户”示例数据包前，请先确保你有 Microsoft 365 开发人员订阅，并以管理员身份为自己分配许可证。</span><span class="sxs-lookup"><span data-stu-id="9b25a-129">Before you install the Users sample data pack, make sure that you have a Microsoft 365 developer subscription and that you assign a license to yourself as the admin.</span></span>

> [!NOTE]
> <span data-ttu-id="9b25a-130">确保你的订阅中有 16 位用户空闲。</span><span class="sxs-lookup"><span data-stu-id="9b25a-130">Make sure that you have 16 users available in your subscription.</span></span> <span data-ttu-id="9b25a-131">你的订阅包含 25 位用户。</span><span class="sxs-lookup"><span data-stu-id="9b25a-131">Your subscription includes 25 users.</span></span> <span data-ttu-id="9b25a-132">如果你配置的用户数已超过 10 位，则请先删除一些用户，确保安装功能。</span><span class="sxs-lookup"><span data-stu-id="9b25a-132">If you have already configured more than 10 users, remove some users first to ensure that your installation is successful.</span></span>

<span data-ttu-id="9b25a-133">若要安装用户示例数据包，请执行下列操作：</span><span class="sxs-lookup"><span data-stu-id="9b25a-133">To install the Users sample data pack:</span></span>

1. <span data-ttu-id="9b25a-134">选择订阅磁贴底部的“**用户**”框。</span><span class="sxs-lookup"><span data-stu-id="9b25a-134">Select the **Users** box at the bottom of your subscription tile.</span></span>
2. <span data-ttu-id="9b25a-135">复制你的管理员 ID；你需要它来登录你的订阅。</span><span class="sxs-lookup"><span data-stu-id="9b25a-135">Copy your administrator ID; you will need it to sign in to your subscription.</span></span>
3. <span data-ttu-id="9b25a-136">在登录页面上输入你的管理员 ID 和密码。</span><span class="sxs-lookup"><span data-stu-id="9b25a-136">Enter your administrator ID and password on the sign in page.</span></span>
4. <span data-ttu-id="9b25a-137">以 Microsoft 365 开发人员订阅管理员身份许可权限。</span><span class="sxs-lookup"><span data-stu-id="9b25a-137">Consent to the permissions as an administrator of your Microsoft 365 developer subscription.</span></span>

![显示权限许可对话框的屏幕截图](images/sample-data-pack-ux-tile-users-consent-with-permissions-combined.PNG)

5. <span data-ttu-id="9b25a-139">为所有示例用户配置密码。</span><span class="sxs-lookup"><span data-stu-id="9b25a-139">Configure your passwords for all sample users.</span></span> <span data-ttu-id="9b25a-140">你需要定义一个共享密码，以便轻松管理所有虚构用户。</span><span class="sxs-lookup"><span data-stu-id="9b25a-140">You will need to have one shared password defined for easy administration of all your fictitious users.</span></span>

![用于添加共享用户密码的对话框的屏幕截图](images/sample-data-pack-ux-tile-users-fake-user-password-creation.PNG)

6. <span data-ttu-id="9b25a-142">系统将安装数据。</span><span class="sxs-lookup"><span data-stu-id="9b25a-142">The data will be installed.</span></span> <span data-ttu-id="9b25a-143">安装过程大约需要 5 分钟时间。</span><span class="sxs-lookup"><span data-stu-id="9b25a-143">The installation should take about 5 minutes.</span></span>

![显示仪表板磁贴上的安装进程的屏幕截图](images/sample-data-pack-ux-tile-users-installing-status.PNG)

7. <span data-ttu-id="9b25a-145">安装完成后，你将收到电子邮件通知，订阅磁贴上的框将显示为绿色。</span><span class="sxs-lookup"><span data-stu-id="9b25a-145">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span> <span data-ttu-id="9b25a-146">你现在可以安装邮件和事件示例数据包。</span><span class="sxs-lookup"><span data-stu-id="9b25a-146">You can now install the Mail and Events sample data pack.</span></span>

![准备安装邮件和事件的仪表板磁贴的屏幕截图](images/sample-data-pack-ux-tile-users-installed.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a><span data-ttu-id="9b25a-148">如何安装邮件和事件示例数据包？</span><span class="sxs-lookup"><span data-stu-id="9b25a-148">How do I install the Mail and Events sample data pack?</span></span>

<span data-ttu-id="9b25a-149">安装用户示例数据包后，你可以安装邮件和事件。</span><span class="sxs-lookup"><span data-stu-id="9b25a-149">After you've installed the Users sample data pack, you can install mail and events.</span></span>

1. <span data-ttu-id="9b25a-150">选择订阅磁贴上的“**邮件和事件**”框。</span><span class="sxs-lookup"><span data-stu-id="9b25a-150">Choose the **Mail &amp; Events** box on your subscription tile.</span></span>
2. <span data-ttu-id="9b25a-151">选择“**安装**”以开始安装。</span><span class="sxs-lookup"><span data-stu-id="9b25a-151">Select **Install** to begin installation.</span></span>

![安装对话框的屏幕截图](images/sample-data-pack-ux-tile-mail-and-events-begin-install.PNG)

> [!NOTE]
> <span data-ttu-id="9b25a-153">如果你刚刚创建了订阅，则必须先完整配置它，然后才能开始安装。</span><span class="sxs-lookup"><span data-stu-id="9b25a-153">If you just created your subscription, it must be fully provisioned before installation can begin.</span></span> <span data-ttu-id="9b25a-154">这可能需要几个小时。</span><span class="sxs-lookup"><span data-stu-id="9b25a-154">This can take up to a few hours.</span></span> <span data-ttu-id="9b25a-155">安装开始后，最多可能需要 20 分钟才能完成。</span><span class="sxs-lookup"><span data-stu-id="9b25a-155">After installation starts, it can take up to 20 minutes to finish.</span></span>

3. <span data-ttu-id="9b25a-156">安装完成后，你将收到电子邮件通知，订阅磁贴上的框将显示为绿色。</span><span class="sxs-lookup"><span data-stu-id="9b25a-156">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span>

## <a name="how-do-i-install-the-sharepoint-sample-data-pack"></a><span data-ttu-id="9b25a-157">如何安装 SharePoint 示例数据包？</span><span class="sxs-lookup"><span data-stu-id="9b25a-157">How do I install the SharePoint sample data pack?</span></span>

<span data-ttu-id="9b25a-158">SharePoint 示例数据包有七个不同的 SharePoint 网站模板可供选择，以体验和模拟用于协作、通信、参与和知识管理的 SharePoint 解决方案。</span><span class="sxs-lookup"><span data-stu-id="9b25a-158">The SharePoint sample data pack includes seven different SharePoint site templates to choose from to experience and model SharePoint solutions for collaboration, communication, engagement, and knowledge management.</span></span>

<span data-ttu-id="9b25a-159">这些是 [SharePoint PnP 外观手册](https://provisioning.sharepointpnp.com/) 中最受欢迎模板的一部分。</span><span class="sxs-lookup"><span data-stu-id="9b25a-159">These are some of the most popular templates from the [SharePoint PnP look book](https://provisioning.sharepointpnp.com/).</span></span> <span data-ttu-id="9b25a-160">现在，创建美观、快速且在任何设备或屏幕上看起来非常精美的网站和页面的示例解决方案十分简单。</span><span class="sxs-lookup"><span data-stu-id="9b25a-160">Today, it's simple to create sample solutions of beautiful, fast sites and pages that look great on any device or screen.</span></span> <span data-ttu-id="9b25a-161">通过这些设计获取灵感，或将其添加到沙盒租户，以开始构建下一个网站。</span><span class="sxs-lookup"><span data-stu-id="9b25a-161">Get inspired with these designs or add them to your sandbox tenant to start building your next site.</span></span>

<span data-ttu-id="9b25a-162">这些模板可以安装在你的订阅中。</span><span class="sxs-lookup"><span data-stu-id="9b25a-162">The templates can be installed on your subscription.</span></span> <span data-ttu-id="9b25a-163">安装一个模板后，可选择安装其他模板。</span><span class="sxs-lookup"><span data-stu-id="9b25a-163">After you install one template, you have the option to install the others.</span></span> <span data-ttu-id="9b25a-164">安装过程包括以下步骤：</span><span class="sxs-lookup"><span data-stu-id="9b25a-164">The installation process includes the following steps:</span></span>

1. <span data-ttu-id="9b25a-165">从下拉菜单中选择所需模板。</span><span class="sxs-lookup"><span data-stu-id="9b25a-165">Select the Template you want from the drop down menu.</span></span>

  ![SharePoint 模板选择屏幕的屏幕截图](images/select-sharepoint-template.jpg)

2. <span data-ttu-id="9b25a-167">为网站配置自定义选项或接受默认值。</span><span class="sxs-lookup"><span data-stu-id="9b25a-167">Configure custom options for your sites, or accept the default values.</span></span>
3. <span data-ttu-id="9b25a-168">使用沙盒租户和密码的管理员 ID 进行身份验证并授予安装权限。</span><span class="sxs-lookup"><span data-stu-id="9b25a-168">Use the administrator ID of your sandbox tenant and password to authenticate and give permissions to install.</span></span> 

<span data-ttu-id="9b25a-169">安装将自动继续。</span><span class="sxs-lookup"><span data-stu-id="9b25a-169">Installation will proceed automatically.</span></span>

><span data-ttu-id="9b25a-170">**注意：** 这些网站模板的设置仅适用于英文版 Office 365 E3 或 Microsoft 365 E5 开发人员订阅，并且其中包含的所有内容均只提供英语版。</span><span class="sxs-lookup"><span data-stu-id="9b25a-170">**Note:** The provisioning of these site templates only works with English Office 365 E3 or Microsoft 365 E5 developer subscriptions, and all content included is English only.</span></span>

## <a name="what-sharepoint-templates-are-available"></a><span data-ttu-id="9b25a-171">提供了哪些 SharePoint 模板？</span><span class="sxs-lookup"><span data-stu-id="9b25a-171">What SharePoint templates are available?</span></span>

<span data-ttu-id="9b25a-172">SharePoint 示例包由七个不同的模板组成。</span><span class="sxs-lookup"><span data-stu-id="9b25a-172">The SharePoint sample pack includes seven different templates.</span></span>

### <a name="team-site-with-data"></a><span data-ttu-id="9b25a-173">带有数据的团队网站</span><span class="sxs-lookup"><span data-stu-id="9b25a-173">Team site with data</span></span>

<span data-ttu-id="9b25a-174">此模板包括多个列表和文档库，它们与某个 SharePoint 团队网站自动关联，可帮助你使用 SharePoint 框架、Power Apps 和 Microsoft Graph 开发解决方案。</span><span class="sxs-lookup"><span data-stu-id="9b25a-174">The Team site with data template includes multiple lists and document libraries that are automatically associated with a SharePoint team site to help you develop solutions using SharePoint Framework, Power Apps, and Microsoft Graph.</span></span>

<span data-ttu-id="9b25a-175">此模板包含以下数据：</span><span class="sxs-lookup"><span data-stu-id="9b25a-175">This template includes the following data:</span></span>

- <span data-ttu-id="9b25a-176">包含预填充联系人的联系人列表</span><span class="sxs-lookup"><span data-stu-id="9b25a-176">A contact list with pre-populated contacts</span></span>
- <span data-ttu-id="9b25a-177">填充了 6000 个项目以上的列表</span><span class="sxs-lookup"><span data-stu-id="9b25a-177">A list populated with over 6,000 items</span></span>
- <span data-ttu-id="9b25a-178">包含 PowerPoint、Excel、Word 和 OneNote 文档示例的文档库</span><span class="sxs-lookup"><span data-stu-id="9b25a-178">Document libraries with sample PowerPoint, Excel, Word, and OneNote documents</span></span>
- <span data-ttu-id="9b25a-179">包含公告项的事件列表</span><span class="sxs-lookup"><span data-stu-id="9b25a-179">An events list with announcement items</span></span>

<span data-ttu-id="9b25a-180">此模板与用户示例数据集成。</span><span class="sxs-lookup"><span data-stu-id="9b25a-180">This template integrates with the Users sample data.</span></span>

### <a name="work--contoso"></a><span data-ttu-id="9b25a-181">Work @ Contoso</span><span class="sxs-lookup"><span data-stu-id="9b25a-181">Work @ Contoso</span></span>
<span data-ttu-id="9b25a-182">Work @ Contoso 模板包含多个网站集，均与中心网站自动关联，以显示所有默认聚合功能的工作方式。</span><span class="sxs-lookup"><span data-stu-id="9b25a-182">The Work @ Contoso template consists of multiple site collections that are all automatically associated with the hub site to show how all default aggregation capabilities work.</span></span>

<span data-ttu-id="9b25a-183">此模板包含以下结构和资产：</span><span class="sxs-lookup"><span data-stu-id="9b25a-183">This template contains following structures and assets:</span></span>

- <span data-ttu-id="9b25a-184">设置为中心网站的主网站集</span><span class="sxs-lookup"><span data-stu-id="9b25a-184">Main site collection set as a hub site</span></span>
- <span data-ttu-id="9b25a-185">两个与中心网站相关联的通信网站 - 权益与慈善网站</span><span class="sxs-lookup"><span data-stu-id="9b25a-185">Two communication sites associated with the hub site - Benefits and charity sites</span></span>
- <span data-ttu-id="9b25a-186">一个与中心网站团队网站相关联的组团队网站</span><span class="sxs-lookup"><span data-stu-id="9b25a-186">One group team site associated with the hub site - Team site</span></span>
- <span data-ttu-id="9b25a-187">子网站集中的示例新闻文章</span><span class="sxs-lookup"><span data-stu-id="9b25a-187">Sample news articles in the subsite collections</span></span>
- <span data-ttu-id="9b25a-188">Word、Excel 和 PowerPoint 示例文件</span><span class="sxs-lookup"><span data-stu-id="9b25a-188">Sample Word, Excel, and PowerPoint files</span></span>
- <span data-ttu-id="9b25a-189">网站集内的示例图像内容</span><span class="sxs-lookup"><span data-stu-id="9b25a-189">Sample image content used in the site collections</span></span>

<span data-ttu-id="9b25a-190">子网站集使用相同的模板，也可以从此服务中单独预配。</span><span class="sxs-lookup"><span data-stu-id="9b25a-190">Subsite collections use the same templates, which you can also provision separately from this service.</span></span>

><span data-ttu-id="9b25a-191">**注意：** 如果在现有通信网站上应用此模板，将覆盖该网站的欢迎页面内容。</span><span class="sxs-lookup"><span data-stu-id="9b25a-191">**Note:** If this template is applied on top of an existing communication site, the welcome page content of the site will be overwritten.</span></span>

### <a name="leadership-connection-leadership-news-events-engagement"></a><span data-ttu-id="9b25a-192">领导力连接：领导力新闻、活动、参与</span><span class="sxs-lookup"><span data-stu-id="9b25a-192">Leadership Connection: Leadership news, events, engagement</span></span>

<span data-ttu-id="9b25a-193">此领导力网站提供了对领导力团队目标和优先事项的见解，并鼓励参与活动与对话。</span><span class="sxs-lookup"><span data-stu-id="9b25a-193">This leadership site provides insight into the goals and priorities of the leadership team, and inspires engagement with events and conversations.</span></span>

<span data-ttu-id="9b25a-194">将此设计添加到租户将创建以下内容：</span><span class="sxs-lookup"><span data-stu-id="9b25a-194">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="9b25a-195">带有 Web 部件演示的示例欢迎页面</span><span class="sxs-lookup"><span data-stu-id="9b25a-195">Example welcome page with demonstration of web parts</span></span>
- <span data-ttu-id="9b25a-196">演示不同新式页面设计的示例新闻文章</span><span class="sxs-lookup"><span data-stu-id="9b25a-196">Example news articles demonstrating different modern page designs</span></span>

<span data-ttu-id="9b25a-197">此模板与用户示例数据集成。</span><span class="sxs-lookup"><span data-stu-id="9b25a-197">This template integrates with the Users sample data.</span></span>

### <a name="the-landing-news-resources-personalized-content"></a><span data-ttu-id="9b25a-198">登陆：新闻、资源、个性化内容</span><span class="sxs-lookup"><span data-stu-id="9b25a-198">The Landing: News, resources, personalized content</span></span>

<span data-ttu-id="9b25a-199">此通信网站旨在为员工提供所需的新闻和资源，以及专为他们量身定制的个性化内容。</span><span class="sxs-lookup"><span data-stu-id="9b25a-199">This communication site is designed to be the place where your employees can find the news and resources they need, plus personalized content tailored just for them.</span></span>

<span data-ttu-id="9b25a-200">将此设计添加到租户将创建以下内容：</span><span class="sxs-lookup"><span data-stu-id="9b25a-200">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="9b25a-201">门户主页网站的演示结构</span><span class="sxs-lookup"><span data-stu-id="9b25a-201">Demo structure for home site of the portal</span></span>
- <span data-ttu-id="9b25a-202">自定义欢迎页面结构</span><span class="sxs-lookup"><span data-stu-id="9b25a-202">Custom welcome page structure</span></span>
- <span data-ttu-id="9b25a-203">其他 6 个示例新式页面和新闻文章</span><span class="sxs-lookup"><span data-stu-id="9b25a-203">Six additional sample modern pages and news articles</span></span>
- <span data-ttu-id="9b25a-204">示例图像和 Office 文档</span><span class="sxs-lookup"><span data-stu-id="9b25a-204">Sample images and Office documents</span></span>

### <a name="the-perspective-news-video-personalized-content"></a><span data-ttu-id="9b25a-205">透视：新闻、视频、个性化内容</span><span class="sxs-lookup"><span data-stu-id="9b25a-205">The Perspective: News, video, personalized content</span></span>

<span data-ttu-id="9b25a-206">该网站旨在提供新闻和个性化内容，还包括可用于鼓励更多参与的视频。</span><span class="sxs-lookup"><span data-stu-id="9b25a-206">Designed to offer news and personalized content, this site also includes videos to inspire even more engagement.</span></span>
<span data-ttu-id="9b25a-207">将此设计添加到租户将创建以下内容：</span><span class="sxs-lookup"><span data-stu-id="9b25a-207">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="9b25a-208">自定义欢迎页面设计</span><span class="sxs-lookup"><span data-stu-id="9b25a-208">Custom welcome page designs</span></span>
- <span data-ttu-id="9b25a-209">新闻文章的示例页面模板</span><span class="sxs-lookup"><span data-stu-id="9b25a-209">Sample page template for news articles</span></span>
- <span data-ttu-id="9b25a-210">12 篇示例新闻文章</span><span class="sxs-lookup"><span data-stu-id="9b25a-210">12 sample news articles</span></span>

### <a name="new-employee-onboarding-hub-connect-engage-inform"></a><span data-ttu-id="9b25a-211">新员工加入中心：联系、参与、通知</span><span class="sxs-lookup"><span data-stu-id="9b25a-211">New Employee Onboarding Hub: Connect, Engage, Inform</span></span>

<span data-ttu-id="9b25a-212">通过预构建的模板（包括预加入、公司级加入和部门级加入方案），简化和优化新员工的入职流程。</span><span class="sxs-lookup"><span data-stu-id="9b25a-212">Streamline and refine your new employee onboarding process with pre-built templates that cover Pre-onboarding, Corporate-level onboarding, and Departmental-level onboarding scenarios.</span></span> <span data-ttu-id="9b25a-213">此数字解决方案提供了 4 种不同的网站模板，其中包含可以自定义以适应组织目标的预填充内容。</span><span class="sxs-lookup"><span data-stu-id="9b25a-213">This digital solution offers four different site templates that contain pre-populated content that can be customized to align with the goals of your organization.</span></span>

<span data-ttu-id="9b25a-214">将此设计添加到租户将创建以下内容：</span><span class="sxs-lookup"><span data-stu-id="9b25a-214">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="9b25a-215">预入职网站、公司入职网站和两个部门入职网站</span><span class="sxs-lookup"><span data-stu-id="9b25a-215">Pre-onboarding site, Corporate onboarding site, and two Departmental onboarding sites</span></span>
- <span data-ttu-id="9b25a-216">每个网站的自定义和预填充主页</span><span class="sxs-lookup"><span data-stu-id="9b25a-216">Custom and pre-populated home pages for each site</span></span>
- <span data-ttu-id="9b25a-217">公司入职的已配置中心网站和部门入职的已关联网站</span><span class="sxs-lookup"><span data-stu-id="9b25a-217">Configured hub site for Corporate onboarding and associated sites for Departmental onboarding</span></span>
- <span data-ttu-id="9b25a-218">SharePoint 列表上的新员工清单，帮助新员工成功入职</span><span class="sxs-lookup"><span data-stu-id="9b25a-218">New employee checklist built on SharePoint Lists to help new hires onboard successfully</span></span>
- <span data-ttu-id="9b25a-219">“人员” Web 部件、Yammer Web 部件、“新闻” Web 部件和“快速链接” Web 部件的示例内容</span><span class="sxs-lookup"><span data-stu-id="9b25a-219">Example content for the People web part, Yammer web part, News web part, and Quick links web part</span></span>
- <span data-ttu-id="9b25a-220">为每个网站预编写的常见问题解答</span><span class="sxs-lookup"><span data-stu-id="9b25a-220">Pre-written FAQs for each site</span></span>
- <span data-ttu-id="9b25a-221">创建社交和参与体验的建议，例如，在预入职网站上使用 YouTube Web 部件包含欢迎视频</span><span class="sxs-lookup"><span data-stu-id="9b25a-221">Recommendations for creating social and engaging experiences, like including a welcome video using the YouTube web part on the Pre-onboarding site</span></span>

### <a name="crisis-communications-announcements-news-resources-communities-and-calls-to-action"></a><span data-ttu-id="9b25a-222">紧急通信：公告、新闻、资源、社区和行动号召</span><span class="sxs-lookup"><span data-stu-id="9b25a-222">Crisis Communications: Announcements, news, resources, communities and calls-to-action</span></span>

<span data-ttu-id="9b25a-223">在从极端天气事件到卫生和安全紧急事件等各种危机期间，让人们了解情况、参与并向前推进。</span><span class="sxs-lookup"><span data-stu-id="9b25a-223">Keep people informed, engaged, and moving forward during crises, from extreme weather events to health and safety emergencies.</span></span> <span data-ttu-id="9b25a-224">该模板创建一个中央资源，供领导或通信者共享重要新闻和公告，是人们了解最新资讯的单一事实来源，也是连接整个组织人员的地方。</span><span class="sxs-lookup"><span data-stu-id="9b25a-224">This template creates a central resource for leaders and communicators to share important news and announcements, a single source of truth where people can stay up-to-date, and a place to connect people across the organization.</span></span>

<span data-ttu-id="9b25a-225">将此设计添加到租户将创建以下内容：</span><span class="sxs-lookup"><span data-stu-id="9b25a-225">Adding this design to your tenant will create the following content:</span></span>

- <span data-ttu-id="9b25a-226">使用 Web 部件构建的自定义欢迎页面</span><span class="sxs-lookup"><span data-stu-id="9b25a-226">Custom welcome page built using a web part</span></span>
- <span data-ttu-id="9b25a-227">4 篇带有示例内容的新闻文章</span><span class="sxs-lookup"><span data-stu-id="9b25a-227">Four news articles with example content</span></span>

<span data-ttu-id="9b25a-228">此模板与用户示例数据集成。</span><span class="sxs-lookup"><span data-stu-id="9b25a-228">This template integrates with the Users sample data.</span></span>

## <a name="are-more-sample-data-packs-coming"></a><span data-ttu-id="9b25a-229">是否会推出更多示例数据包？</span><span class="sxs-lookup"><span data-stu-id="9b25a-229">Are more sample data packs coming?</span></span>

<span data-ttu-id="9b25a-230">是。</span><span class="sxs-lookup"><span data-stu-id="9b25a-230">Yes.</span></span> <span data-ttu-id="9b25a-231">将来，我们将考虑为包括 Microsoft Teams 在内的更多产品和技术添加示例数据包。</span><span class="sxs-lookup"><span data-stu-id="9b25a-231">In the future, we will consider adding sample data packs for more products and technologies, including Microsoft Teams.</span></span> <span data-ttu-id="9b25a-232">如果你有关于希望查看的示例数据包的建议，请 [告知我们](https://officespdev.uservoice.com/forums/224641-feature-requests-and-feedback?category_id=171306)。</span><span class="sxs-lookup"><span data-stu-id="9b25a-232">If you have suggestions for sample data packs that you would like to see, [let us know](https://officespdev.uservoice.com/forums/224641-feature-requests-and-feedback?category_id=171306).</span></span>

## <a name="can-i-install-sample-data-packs-on-my-other-microsoft-365-subscriptions"></a><span data-ttu-id="9b25a-233">能否在其他 Microsoft 365 订阅上安装示例数据包？</span><span class="sxs-lookup"><span data-stu-id="9b25a-233">Can I install sample data packs on my other Microsoft 365 subscriptions?</span></span>

<span data-ttu-id="9b25a-234">否。</span><span class="sxs-lookup"><span data-stu-id="9b25a-234">No.</span></span> <span data-ttu-id="9b25a-235">这些示例数据包仅与作为 Microsoft 365 开发人员计划的一部分获取的 Microsoft 365 开发人员订阅兼容。</span><span class="sxs-lookup"><span data-stu-id="9b25a-235">These sample data packs are only compatible with the Microsoft 365 developer subscription you get as part of the Microsoft 365 Developer Program.</span></span>

## <a name="how-can-i-see-the-sample-data-in-my-subscription"></a><span data-ttu-id="9b25a-236">如何查看我的订阅中的示例数据？</span><span class="sxs-lookup"><span data-stu-id="9b25a-236">How can I see the sample data in my subscription?</span></span>

<span data-ttu-id="9b25a-237">安装用户示例数据包后，若要查看已添加的用户，请在 Microsoft 365 开发人员订阅上转到 [**Microsoft 365 管理中心**](https://admin.microsoft.com/)。</span><span class="sxs-lookup"><span data-stu-id="9b25a-237">After you install the Users sample data pack, to see the users that were added, go to the [**Microsoft 365 Admin Center**](https://admin.microsoft.com/) on your Microsoft 365 developer subscription.</span></span> <span data-ttu-id="9b25a-238">在“**用户**”下，选择“**活动用户**”。</span><span class="sxs-lookup"><span data-stu-id="9b25a-238">Under **Users**, select **Active users**.</span></span> <span data-ttu-id="9b25a-239">你将会看到包含 16 个用户的列表。</span><span class="sxs-lookup"><span data-stu-id="9b25a-239">You will see the list of 16 users.</span></span> <span data-ttu-id="9b25a-240">你可以选择一个用户来查看相关联的元数据，包括照片和许可证。</span><span class="sxs-lookup"><span data-stu-id="9b25a-240">You can select a user to view the associated metadata, including photos and licenses.</span></span>

![Microsoft 365 管理中心内 16 个用户的屏幕截图，其中包含针对所选用户的元数据](images/content-packs-07.PNG)

<span data-ttu-id="9b25a-242">安装邮件和事件示例包后，若要查看示例数据，请在 [**Microsoft 365 管理中心**](/microsoft-365/admin/admin-overview/about-the-admin-center?view=o365-worldwide) 内选择“**全部显示**”，然后选择“**Exchange**”。</span><span class="sxs-lookup"><span data-stu-id="9b25a-242">After you install the Mail and Events sample pack, to see the sample data, in the [**Microsoft 365 Admin Center**](/microsoft-365/admin/admin-overview/about-the-admin-center?view=o365-worldwide), choose **Show all** and then select **Exchange**.</span></span> <span data-ttu-id="9b25a-243">在 Exchange 管理中心内，当你选择“**收件人**”时，你可以看到 16 个用户均拥有添加了邮件和事件的邮箱。</span><span class="sxs-lookup"><span data-stu-id="9b25a-243">In the Exchange admin center, when you select **recipients**, you can see that each of the 16 users has mailboxes with mail and events added.</span></span>
<span data-ttu-id="9b25a-244">![添加到 Exchange 管理中心的 16 个用户的屏幕截图](images/content-packs-08.PNG)</span><span class="sxs-lookup"><span data-stu-id="9b25a-244">![Screenshot of 16 users added to the Exchange Admin Center](images/content-packs-08.PNG)</span></span>

## <a name="see-also"></a><span data-ttu-id="9b25a-245">另请参阅</span><span class="sxs-lookup"><span data-stu-id="9b25a-245">See also</span></span>

- [<span data-ttu-id="9b25a-246">设置 Microsoft 365 开发人员订阅</span><span class="sxs-lookup"><span data-stu-id="9b25a-246">Set up a Microsoft 365 developer subscription</span></span>](microsoft-365-developer-program-get-started.md)
