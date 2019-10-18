---
title: 将示例数据包与 Office 365 开发人员订阅结合使用
description: 了解如何在 Office 365 开发人员订阅上安装示例数据包，帮助你快速启动并运行沙盒环境。
localization_priority: Priority
ms.openlocfilehash: 29bdd3cebeaf4a2f70d1482fe1c57480cd083756
ms.sourcegitcommit: e8d857460e4fd5842bdfbd2a9d60f4fba55edcd0
ms.translationtype: HT
ms.contentlocale: zh-CN
ms.lasthandoff: 08/20/2019
ms.locfileid: "36465094"
---
# <a name="use-sample-data-packs-with-your-office-365-developer-subscription"></a><span data-ttu-id="0bbe6-103">将示例数据包与 Office 365 开发人员订阅结合使用</span><span class="sxs-lookup"><span data-stu-id="0bbe6-103">Use sample data packs with your Office 365 developer subscription</span></span>

<span data-ttu-id="0bbe6-104">你可以在 Office 365 开发人员订阅上安装示例数据包。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-104">You can install sample data packs on your Office 365 developer subscription.</span></span> <span data-ttu-id="0bbe6-105">示例数据包可自动安装构建和测试解决方案所需的数据和内容，从而节省你的时间。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-105">Sample data packs save you time by automatically installing data and content you need to build and test your solutions.</span></span> <span data-ttu-id="0bbe6-106">其中包含虚构用户、元数据和照片，用于模拟小型企业环境。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-106">This includes fictitious users, metadata, and photos to simulate a small corporate environment.</span></span> <span data-ttu-id="0bbe6-107">你可以快速安装示例数据，以便专注于你的解决方案，而不是花时间亲自创建示例数据。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-107">You can quickly install the sample data so that you can focus on your solutions rather than spend time creating sample data yourself.</span></span>

<span data-ttu-id="0bbe6-108">你可以在 Office 365 订阅磁贴底部的 [Office 365 开发人员计划仪表板](https://developer.microsoft.com/office/profile)上找到示例数据包。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-108">You can find sample data packs on your [Office 365 Developer Program dashboard](https://developer.microsoft.com/office/profile), at the bottom of your Office 365 subscription tile.</span></span>

![仪表板页面上的订阅磁贴屏幕截图](images/sample-data-pack-ux-tile-users-beginning.PNG)

<span data-ttu-id="0bbe6-110">目前提供以下示例数据包：</span><span class="sxs-lookup"><span data-stu-id="0bbe6-110">The following sample data packs are currently available:</span></span>

- <span data-ttu-id="0bbe6-111">用户 - 安装 16 个具有许可证、邮箱和元数据（包括每位用户的姓名和照片）的虚构用户。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-111">Users - Installs 16 fictitious users with licenses, mailboxes, and metadata, including names and photos for each user.</span></span> <span data-ttu-id="0bbe6-112">通过下列方式使用 Microsoft Graph API 处理用户示例数据：</span><span class="sxs-lookup"><span data-stu-id="0bbe6-112">Use Microsoft Graph APIs to work with user sample data in the following ways:</span></span>
  - <span data-ttu-id="0bbe6-113">获取特定用户详细信息</span><span class="sxs-lookup"><span data-stu-id="0bbe6-113">Get specific user details</span></span>
  - <span data-ttu-id="0bbe6-114">更新用户</span><span class="sxs-lookup"><span data-stu-id="0bbe6-114">Update user</span></span>
  - <span data-ttu-id="0bbe6-115">获取直接报告</span><span class="sxs-lookup"><span data-stu-id="0bbe6-115">Get user's direct reports.</span></span>
  - <span data-ttu-id="0bbe6-116">准备组织结构图</span><span class="sxs-lookup"><span data-stu-id="0bbe6-116">Prepare organization chart</span></span>  
  - <span data-ttu-id="0bbe6-117">按部门获取用户</span><span class="sxs-lookup"><span data-stu-id="0bbe6-117">Get users by department</span></span>

- <span data-ttu-id="0bbe6-118">邮件和事件 - 为 16 个示例用户中的每一位添加 Outlook 电子邮件会话和日历事件。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-118">Mail and events - Adds Outlook email conversations and calendar events for each of the 16 sample users.</span></span> <span data-ttu-id="0bbe6-119">通过下列方式使用 Microsoft Graph API 处理邮件和事件示例数据：</span><span class="sxs-lookup"><span data-stu-id="0bbe6-119">Use Microsoft Graph APIs to work with mail and events sample data in the following ways:</span></span>
  - <span data-ttu-id="0bbe6-120">按用户获取电子邮件</span><span class="sxs-lookup"><span data-stu-id="0bbe6-120">Get emails by users</span></span>
  - <span data-ttu-id="0bbe6-121">按筛选日期获取电子邮件</span><span class="sxs-lookup"><span data-stu-id="0bbe6-121">Get emails filtered by date</span></span>
  - <span data-ttu-id="0bbe6-122">获取即将开始的事件</span><span class="sxs-lookup"><span data-stu-id="0bbe6-122">Get upcoming events</span></span>
  - <span data-ttu-id="0bbe6-123">更新/删除即将开始的事件</span><span class="sxs-lookup"><span data-stu-id="0bbe6-123">Update/delete upcoming events</span></span>

> [!NOTE]
> <span data-ttu-id="0bbe6-124">在安装邮件和事件之前，你必须先安装用户示例数据包。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-124">You must install the Users sample data pack before you install Mail and Events.</span></span>

## <a name="what-do-the-sample-data-packs-add-to-my-office-365-subscription"></a><span data-ttu-id="0bbe6-125">示例数据包会将哪些内容添加到我的 Office 365 订阅？</span><span class="sxs-lookup"><span data-stu-id="0bbe6-125">What do the sample data packs add to my Office 365 subscription?</span></span>

<span data-ttu-id="0bbe6-126">用户示例数据包将在你的订阅上创建 16 个虚构用户，并包含每位用户的许可证、邮箱、姓名、元数据和照片。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-126">The Users sample data pack creates 16 fictitious users on your subscription, and includes the licenses for each user, and mailboxes, names, metadata, and photos for each.</span></span>

<span data-ttu-id="0bbe6-127">邮件和事件示例数据包将为已安装的 16 个用户中的每一位添加 Outlook 电子邮件会话和日历事件。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-127">The Mail and Events sample data pack adds Outlook email conversations and calendar events for each of the 16 users installed.</span></span>

## <a name="how-do-i-install-the-users-sample-data-pack"></a><span data-ttu-id="0bbe6-128">如何安装用户示例数据包？</span><span class="sxs-lookup"><span data-stu-id="0bbe6-128">How do I install the Users sample data pack?</span></span>

<span data-ttu-id="0bbe6-129">在安装用户示例数据包之前，请确保你拥有 Office 365 开发人员订阅，并以管理员身份为自己分配许可证。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-129">Before you install the Users sample data pack, make sure that you have an Office 365 developer subscription and that you assign a license to yourself as the admin.</span></span>

> [!NOTE]
> <span data-ttu-id="0bbe6-130">确保你的订阅中有 16 位用户空闲。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-130">Make sure that you have 16 users available in your subscription.</span></span> <span data-ttu-id="0bbe6-131">你的订阅包含 25 位用户。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-131">Your subscription includes 25 users.</span></span> <span data-ttu-id="0bbe6-132">如果你配置的用户数已超过 10 位，则请先删除一些用户，确保安装功能。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-132">If you have already configured more than 10 users, remove some users first to ensure that your installation is successful.</span></span>

<span data-ttu-id="0bbe6-133">若要安装用户示例数据包，请执行下列操作：</span><span class="sxs-lookup"><span data-stu-id="0bbe6-133">To install the Users sample data pack:</span></span>

1. <span data-ttu-id="0bbe6-134">选择订阅磁贴底部的“**用户**”框。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-134">Select the **Users** box at the bottom of your subscription tile.</span></span>
2. <span data-ttu-id="0bbe6-135">复制你的管理员 ID；你需要它来登录你的订阅。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-135">Copy your administrator ID; you will need it to sign in to your subscription.</span></span>
3. <span data-ttu-id="0bbe6-136">在登录页面上输入你的管理员 ID 和密码。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-136">Enter your administrator ID and password on the sign in page.</span></span>
4. <span data-ttu-id="0bbe6-137">以 Office 365 开发人员订阅的管理员身份给予相关许可权限。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-137">Consent to the permissions as an administrator of your Office 365 developer subscription.</span></span>

![显示权限许可对话框的屏幕截图](images/sample-data-pack-ux-tile-users-consent-with-permissions-combined.PNG)

5. <span data-ttu-id="0bbe6-139">为所有示例用户配置密码。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-139">Configure your passwords for all sample users.</span></span> <span data-ttu-id="0bbe6-140">你需要定义一个共享密码，以便轻松管理所有虚构用户。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-140">You will need to have one shared password defined for easy administration of all your fictitious users.</span></span>

![用于添加共享用户密码的对话框的屏幕截图](images/sample-data-pack-ux-tile-users-fake-user-password-creation.PNG)

6. <span data-ttu-id="0bbe6-142">系统将安装数据。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-142">The existing data will be overwritten.</span></span> <span data-ttu-id="0bbe6-143">安装过程大约需要 5 分钟时间。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-143">The installation should take about 5 minutes.</span></span>

![显示仪表板磁贴上的安装进程的屏幕截图](images/sample-data-pack-ux-tile-users-installing-status.PNG)

7. <span data-ttu-id="0bbe6-145">安装完成后，你将收到电子邮件通知，订阅磁贴上的框将显示为绿色。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-145">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span> <span data-ttu-id="0bbe6-146">你现在可以安装邮件和事件示例数据包。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-146">You can now install the Mail and Events sample data pack.</span></span>

![准备安装邮件和事件的仪表板磁贴的屏幕截图](images/sample-data-pack-ux-tile-users-installed.PNG)

## <a name="how-do-i-install-the-mail-and-events-sample-data-pack"></a><span data-ttu-id="0bbe6-148">如何安装邮件和事件示例数据包？</span><span class="sxs-lookup"><span data-stu-id="0bbe6-148">How do I install the Mail and Events sample data pack?</span></span>

<span data-ttu-id="0bbe6-149">安装用户示例数据包后，你可以安装邮件和事件。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-149">After you've installed the Users sample data pack, you can install mail and events.</span></span>

1. <span data-ttu-id="0bbe6-150">选择订阅磁贴上的“**邮件和事件**”框。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-150">Choose the **Mail &amp; Events** box on your subscription tile.</span></span>
2. <span data-ttu-id="0bbe6-151">选择“**安装**”以开始安装。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-151">Click **Install** to begin the installation.</span></span>

![安装对话框的屏幕截图](images/sample-data-pack-ux-tile-mail-and-events-begin-install.PNG)

> [!NOTE]
> <span data-ttu-id="0bbe6-153">如果你刚刚创建了订阅，则必须先完整配置它，然后才能开始安装。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-153">If you just created your subscription, it must be fully provisioned before installation can begin.</span></span> <span data-ttu-id="0bbe6-154">这可能需要几个小时。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-154">This can take up to a few hours.</span></span> <span data-ttu-id="0bbe6-155">安装开始后，最多可能需要 20 分钟才能完成。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-155">After installation starts, it can take up to 20 minutes to finish.</span></span>

3. <span data-ttu-id="0bbe6-156">安装完成后，你将收到电子邮件通知，订阅磁贴上的框将显示为绿色。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-156">When installation is finished, you'll be notified by email, and the box on your subscription tile will be green.</span></span>

## <a name="are-more-sample-data-packs-coming"></a><span data-ttu-id="0bbe6-157">是否会推出更多示例数据包？</span><span class="sxs-lookup"><span data-stu-id="0bbe6-157">Are more sample data packs coming?</span></span>

<span data-ttu-id="0bbe6-158">是。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-158">Yes.</span></span> <span data-ttu-id="0bbe6-159">我们将为 SharePoint 和 OneDrive 添加示例数据包。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-159">We will add sample data packs for SharePoint and OneDrive.</span></span> <span data-ttu-id="0bbe6-160">将来，我们将考虑为更多产品和技术添加示例数据包，包括 Office 加载项、Microsoft Teams 等。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-160">In the future, we will consider adding sample data packs for more products and technologies, including Office Add-ins, Microsoft Teams, and more.</span></span>

## <a name="can-i-install-sample-data-packs-on-my-other-office-365-subscriptions"></a><span data-ttu-id="0bbe6-161">能否在其他 Office 365 订阅上安装示例数据包吗？</span><span class="sxs-lookup"><span data-stu-id="0bbe6-161">Can I install sample data packs on my other Office 365 subscriptions?</span></span>

<span data-ttu-id="0bbe6-162">否。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-162">No.</span></span> <span data-ttu-id="0bbe6-163">这些示例数据包仅与 Office 365 开发人员订阅（作为 Office 365 开发人员计划的一部分获得）兼容。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-163">These sample data packs are only compatible with the Office 365 Developer Subscription you get as part of the Office 365 Developer Program.</span></span>

## <a name="how-can-i-see-the-sample-data-in-my-subscription"></a><span data-ttu-id="0bbe6-164">如何查看我的订阅中的示例数据？</span><span class="sxs-lookup"><span data-stu-id="0bbe6-164">How can I see the sample data in my subscription?</span></span>

<span data-ttu-id="0bbe6-165">安装用户示例数据包后，若要查看添加的用户，请在 Office 365 开发人员订阅上转到 **Microsoft 365 管理中心**。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-165">After you install the Users sample data pack, to see the users that were added, go to the **Microsoft 365 Admin Center** on your Office 365 developer subscription.</span></span> <span data-ttu-id="0bbe6-166">在“**用户**”下，选择“**活动用户**”。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-166">Under **Users**, select **Active users**.</span></span> <span data-ttu-id="0bbe6-167">你将会看到包含 16 个用户的列表。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-167">You will see the list of 16 users.</span></span> <span data-ttu-id="0bbe6-168">你可以选择一个用户来查看相关联的元数据，包括照片和许可证。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-168">You can select a user to view the associated metadata, including photos and licenses.</span></span>

![Microsoft 365 管理中心内 16 个用户的屏幕截图，其中包含针对所选用户的元数据](images/content-packs-07.PNG)

<span data-ttu-id="0bbe6-170">安装邮件和事件示例包后，若要查看示例数据，请在 **Microsoft 365 管理中心**内选择“**全部显示**”，然后选择“**Exchange**”。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-170">After you install the Mail and Events sample pack, to see the sample data, in the **Microsoft 365 Admin Center**, choose **Show all** and then select **Exchange**.</span></span> <span data-ttu-id="0bbe6-171">在 Exchange 管理中心内，当你选择“**收件人**”时，你可以看到 16 个用户均拥有添加了邮件和事件的邮箱。</span><span class="sxs-lookup"><span data-stu-id="0bbe6-171">In the Exchange admin center, when you select **recipients**, you can see that each of the 16 users has mailboxes with mail and events added.</span></span>
<span data-ttu-id="0bbe6-172">![添加到 Exchange 管理中心的 16 个用户的屏幕截图](images/content-packs-08.PNG)</span><span class="sxs-lookup"><span data-stu-id="0bbe6-172">![Screenshot of 16 users added to the Exchange Admin Center](images/content-packs-08.PNG)</span></span>

## <a name="see-also"></a><span data-ttu-id="0bbe6-173">另请参阅</span><span class="sxs-lookup"><span data-stu-id="0bbe6-173">See also</span></span>

- [<span data-ttu-id="0bbe6-174">设置 Office 365 开发人员订阅</span><span class="sxs-lookup"><span data-stu-id="0bbe6-174">Set up an Office 365 developer subscription</span></span>](office-365-developer-program-get-started.md)
