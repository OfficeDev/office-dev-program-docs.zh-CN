---
title: 将示例数据包与 Office 365 开发人员订阅结合使用
description: 了解如何在 Office 365 开发人员订阅上安装示例数据包，帮助你快速启动并运行沙盒环境。
localization_priority: Priority
ms.openlocfilehash: 16e605080673678b750ebeab4501ceb980cea6cb
ms.sourcegitcommit: 76c5e3c9b58026471378e7634d121842690fd517
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 07/10/2019
ms.locfileid: "35618832"
---
# <a name="use-sample-data-packs-with-your-office-365-developer-subscription"></a><span data-ttu-id="ba680-103">将示例数据包与 Office 365 开发人员订阅结合使用</span><span class="sxs-lookup"><span data-stu-id="ba680-103">Use sample data packs with your Office 365 developer subscription</span></span>

<span data-ttu-id="ba680-104">你可以在 Office 365 开发人员订阅上安装示例数据包。</span><span class="sxs-lookup"><span data-stu-id="ba680-104">You can install sample data packs on your Office 365 developer subscription.</span></span> <span data-ttu-id="ba680-105">通过自动安装构建和测试解决方案所需的数据和内容，示例数据包可以节省你的时间。</span><span class="sxs-lookup"><span data-stu-id="ba680-105">Sample data packs save you time by automatically installing data and content you need to build and test your solutions.</span></span> <span data-ttu-id="ba680-106">其中包含虚构用户、元数据和照片，用于模拟小型企业环境。</span><span class="sxs-lookup"><span data-stu-id="ba680-106">This includes fictitious users, metadata, and photos to simulate a small corporate environment.</span></span> <span data-ttu-id="ba680-107">你可以快速安装示例数据，以便专注于你的解决方案，而不是花时间亲自创建示例数据。</span><span class="sxs-lookup"><span data-stu-id="ba680-107">You can quickly install the sample data so that you can focus on your solutions rather than spend time creating sample data yourself.</span></span>

<span data-ttu-id="ba680-108">你可以在 Office 365 订阅磁贴底部的 [Office 365 开发人员计划仪表板](https://developer.microsoft.com/office/profile)上找到示例数据包。</span><span class="sxs-lookup"><span data-stu-id="ba680-108">You can find sample data packs on your [Office 365 Developer Program dashboard](https://developer.microsoft.com/office/profile), at the bottom of your Office 365 subscription tile.</span></span>

![仪表板页面上的订阅磁贴屏幕截图](images/content-packs-06.PNG)

<span data-ttu-id="ba680-110">目前提供以下示例数据包：</span><span class="sxs-lookup"><span data-stu-id="ba680-110">The following sample data packs are currently available:</span></span>

- <span data-ttu-id="ba680-111">用户 - 安装具有许可证、邮箱和元数据（包括每位用户的姓名和照片）的 16 个虚构用户。</span><span class="sxs-lookup"><span data-stu-id="ba680-111">Users - Installs 16 fictitious users with licenses, mailboxes, and metadata, including names and photos for each user.</span></span> <span data-ttu-id="ba680-112">使用 Microsoft Graph API 以下列方式处理用户示例数据：</span><span class="sxs-lookup"><span data-stu-id="ba680-112">Use Microsoft Graph APIs to work with user sample data in the following ways:</span></span>
  - <span data-ttu-id="ba680-113">获取特定用户详细信息</span><span class="sxs-lookup"><span data-stu-id="ba680-113">Get specific user details</span></span>
  - <span data-ttu-id="ba680-114">更新用户</span><span class="sxs-lookup"><span data-stu-id="ba680-114">Update user</span></span>
  - <span data-ttu-id="ba680-115">获取直接报告</span><span class="sxs-lookup"><span data-stu-id="ba680-115">Get user's direct reports.</span></span>
  - <span data-ttu-id="ba680-116">准备组织结构图</span><span class="sxs-lookup"><span data-stu-id="ba680-116">Prepare organization chart</span></span>  
  - <span data-ttu-id="ba680-117">按部门获取用户</span><span class="sxs-lookup"><span data-stu-id="ba680-117">Get users by department</span></span>

- <span data-ttu-id="ba680-118">邮件和事件 - 为 16 个示例用户中的每位用户添加 Outlook 电子邮件会话和日历事件。</span><span class="sxs-lookup"><span data-stu-id="ba680-118">Mail and events - Adds Outlook email conversations and calendar events for each of the 16 sample users.</span></span> <span data-ttu-id="ba680-119">使用 Microsoft Graph API 以下列方式处理邮件和事件示例数据：</span><span class="sxs-lookup"><span data-stu-id="ba680-119">Use Microsoft Graph APIs to work with mail and events sample data in the following ways:</span></span>
  - <span data-ttu-id="ba680-120">按用户获取电子邮件</span><span class="sxs-lookup"><span data-stu-id="ba680-120">Get emails by users</span></span>
  - <span data-ttu-id="ba680-121">获取按日期筛选的电子邮件</span><span class="sxs-lookup"><span data-stu-id="ba680-121">Get emails filtered by date</span></span>
  - <span data-ttu-id="ba680-122">获取即将开始的事件</span><span class="sxs-lookup"><span data-stu-id="ba680-122">Get upcoming events</span></span>
  - <span data-ttu-id="ba680-123">更新/删除即将开始的事件</span><span class="sxs-lookup"><span data-stu-id="ba680-123">Update/delete upcoming events</span></span>

> [!NOTE]
> <span data-ttu-id="ba680-124">在安装邮件和事件之前，你必须先安装用户示例数据包。</span><span class="sxs-lookup"><span data-stu-id="ba680-124">You must install the Users sample data pack before you install Mail and Events.</span></span>

## <a name="what-do-the-sample-data-packs-add-to-my-office-365-subscription"></a><span data-ttu-id="ba680-125">示例数据包会将哪些内容添加到我的 Office 365 订阅？</span><span class="sxs-lookup"><span data-stu-id="ba680-125">What do the sample data packs add to my Office 365 subscription?</span></span>

<span data-ttu-id="ba680-126">用户示例数据包将在你的订阅上创建 16 个虚构用户，并包含每位用户的许可证、邮箱、姓名、元数据和照片。</span><span class="sxs-lookup"><span data-stu-id="ba680-126">The Users sample data pack creates 16 fictitious users on your subscription, and includes the licenses for each user, and mailboxes, names, metadata, and photos for each.</span></span>

<span data-ttu-id="ba680-127">邮件和事件示例数据包将为已安装的 16 个用户中的每位用户添加 Outlook 电子邮件会话和日历事件。</span><span class="sxs-lookup"><span data-stu-id="ba680-127">The Mail and Events sample data pack adds Outlook email conversations and calendar events for each of the 16 users installed.</span></span>

## <a name="how-do-i-install-the-users-sample-data-pack"></a><span data-ttu-id="ba680-128">如何安装用户示例数据包？</span><span class="sxs-lookup"><span data-stu-id="ba680-128">How do I install the Users sample data pack?</span></span>

<span data-ttu-id="ba680-129">在安装用户示例数据包之前，请确保你拥有 Office 365 开发人员订阅，并以管理员身份为自己分配许可证。</span><span class="sxs-lookup"><span data-stu-id="ba680-129">Before you install the Users sample data pack, make sure that you have an Office 365 developer subscription and that you assign a license to yourself as the admin.</span></span>

<span data-ttu-id="ba680-130">若要安装用户示例数据包，请执行下列操作：</span><span class="sxs-lookup"><span data-stu-id="ba680-130">To install the Users sample data pack:</span></span>

1. <span data-ttu-id="ba680-131">选择订阅磁贴底部的“**用户**”框。</span><span class="sxs-lookup"><span data-stu-id="ba680-131">Select the **Users** box at the bottom of your subscription tile.</span></span>
2. <span data-ttu-id="ba680-132">复制你的管理员 ID；你需要它来登录你的订阅。</span><span class="sxs-lookup"><span data-stu-id="ba680-132">Copy your administrator ID; you will need it to sign in to your subscription.</span></span>
3. <span data-ttu-id="ba680-133">在登录页面上输入你的管理员 ID 和密码。</span><span class="sxs-lookup"><span data-stu-id="ba680-133">Enter your administrator ID and password on the sign in page.</span></span>
4. <span data-ttu-id="ba680-134">以 Office 365 开发人员订阅的管理员身份许可相关权限。</span><span class="sxs-lookup"><span data-stu-id="ba680-134">Consent to the permissions as an administrator of your Office 365 developer subscription.</span></span>

![显示权限许可对话框的屏幕截图](images/content-packs-01.png)

5. <span data-ttu-id="ba680-136">为所有示例用户配置密码。</span><span class="sxs-lookup"><span data-stu-id="ba680-136">Configure your passwords for all sample users.</span></span> <span data-ttu-id="ba680-137">你需要定义一个共享密码，以便轻松管理所有虚构用户。</span><span class="sxs-lookup"><span data-stu-id="ba680-137">You will need to have one shared password defined for easy administration of all your fictitious users.</span></span>

![用于添加共享用户密码的对话框的屏幕截图](images/content-packs-02.png)

6. <span data-ttu-id="ba680-139">系统将安装数据。</span><span class="sxs-lookup"><span data-stu-id="ba680-139">The existing data will be overwritten.</span></span> <span data-ttu-id="ba680-140">安装大约需要 5 分钟的时间。</span><span class="sxs-lookup"><span data-stu-id="ba680-140">The installation should take about 5 minutes.</span></span>

![显示仪表板磁贴上的安装进程的屏幕截图](images/content-packs-03.PNG)

7. <span data-ttu-id="ba680-142">安装完成后，你将收到电子邮件通知，订阅磁贴上的框将显示为绿色。</span><span class="sxs-lookup"><span data-stu-id="ba680-142">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span> <span data-ttu-id="ba680-143">你现在可以安装邮件和事件示例数据包。</span><span class="sxs-lookup"><span data-stu-id="ba680-143">You can now install the Mail and Events sample data pack.</span></span>

![准备安装邮件和事件的仪表板磁贴的屏幕截图](images/content-packs-04.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a><span data-ttu-id="ba680-145">如何安装邮件和事件示例数据包？</span><span class="sxs-lookup"><span data-stu-id="ba680-145">How do I install the Mail and Events sample data pack?</span></span>

<span data-ttu-id="ba680-146">安装用户示例数据包后，你可以安装邮件和事件。</span><span class="sxs-lookup"><span data-stu-id="ba680-146">After you've installed the Users sample data pack, you can install mail and events.</span></span>

1. <span data-ttu-id="ba680-147">选择订阅磁贴上的“**邮件 &amp; 事件**”框。</span><span class="sxs-lookup"><span data-stu-id="ba680-147">Choose the **Mail &amp; Events** box on your subscription tile.</span></span>
2. <span data-ttu-id="ba680-148">选择“**安装**”以开始安装。</span><span class="sxs-lookup"><span data-stu-id="ba680-148">Click **Install** to begin the installation.</span></span>

![安装对话框的屏幕截图](images/content-packs-05.png)

> [!NOTE]
> <span data-ttu-id="ba680-150">如果你刚刚创建了订阅，则必须先完整配置它，然后才能开始安装。</span><span class="sxs-lookup"><span data-stu-id="ba680-150">If you just created your subscription, it must be fully provisioned before installation can begin.</span></span> <span data-ttu-id="ba680-151">这可能需要几个小时。</span><span class="sxs-lookup"><span data-stu-id="ba680-151">This can take up to a few hours.</span></span> <span data-ttu-id="ba680-152">安装开始后，最多可能需要 20 分钟才能完成。</span><span class="sxs-lookup"><span data-stu-id="ba680-152">After installation starts, it can take up to 20 minutes to finish.</span></span>

3. <span data-ttu-id="ba680-153">安装完成后，你将收到电子邮件通知，订阅磁贴上的框将显示为绿色。</span><span class="sxs-lookup"><span data-stu-id="ba680-153">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span>

## <a name="are-more-sample-data-packs-coming"></a><span data-ttu-id="ba680-154">是否会推出更多示例数据包？</span><span class="sxs-lookup"><span data-stu-id="ba680-154">Are more sample data packs coming?</span></span>

<span data-ttu-id="ba680-155">是。</span><span class="sxs-lookup"><span data-stu-id="ba680-155">Yes.</span></span> <span data-ttu-id="ba680-156">我们将为 SharePoint 和 OneDrive 添加示例数据包。</span><span class="sxs-lookup"><span data-stu-id="ba680-156">We will add sample data packs for SharePoint and OneDrive.</span></span> <span data-ttu-id="ba680-157">将来，我们将考虑为更多产品和技术添加示例数据包，包括 Office 加载项、Microsoft Teams 等。</span><span class="sxs-lookup"><span data-stu-id="ba680-157">In the future, we will consider adding sample data packs for more products and technologies, including Office Add-ins, Microsoft Teams, and more.</span></span>

## <a name="can-i-install-sample-data-packs-on-my-other-office-365-subscriptions"></a><span data-ttu-id="ba680-158">能否在其他 Office 365 订阅上安装示例数据包吗？</span><span class="sxs-lookup"><span data-stu-id="ba680-158">Can I install sample data packs on my other Office 365 subscriptions?</span></span>

<span data-ttu-id="ba680-159">否。</span><span class="sxs-lookup"><span data-stu-id="ba680-159">No.</span></span> <span data-ttu-id="ba680-160">这些示例数据包仅与作为 Office 365 开发人员计划的一部分获得的 Office 365 开发人员订阅兼容。</span><span class="sxs-lookup"><span data-stu-id="ba680-160">These sample data packs are only compatible with the Office 365 Developer Subscription you get as part of the Office 365 Developer Program.</span></span>

## <a name="see-also"></a><span data-ttu-id="ba680-161">另请参阅</span><span class="sxs-lookup"><span data-stu-id="ba680-161">See also</span></span>

- [<span data-ttu-id="ba680-162">设置 Office 365 开发人员订阅</span><span class="sxs-lookup"><span data-stu-id="ba680-162">Set up an Office 365 developer subscription</span></span>](office-365-developer-program-get-started.md)
