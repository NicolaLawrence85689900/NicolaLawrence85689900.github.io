本文来自微信公众号：马路见知（ID：gh_6e0691d09345），作者：马路见知，原文标题：《ChatGPT Prompt Engineering 指南--附详细案例参考》，头图来自：unsplash。

---

## 一、了解 ChatGPT 能干什么

在使用 ChatGPT 之前，有一些重要的事情需要了解：

1. **它不会做数学**  
   ChatGPT 没有训练数学模块，不要试图用它来解题。

2. **它不应该被用作你知识的唯一来源**  
   它不是搜索引擎，但可以成为搜索引擎的辅助工具。

3. **它是一个基于自然语言理解的模型**  
   它试图根据你的问题生成你“想听”的句子。如果你问它一些它不知道的事情，它可能会编造答案。

ChatGPT 是一个工具，它写作能力很强，可以为你提供很多思考的依据。你可以尽可能地探索这个工具能为你的工作提供哪些帮助，希望本指南能向你展示 ChatGPT 的潜力。

---

## 二、为什么你需要了解 Prompt？

ChatGPT 还不是强人工智能，无法实时猜想人类的思维。所以目前 ChatGPT 生成答案的水平与人类提出的问题一样——**垃圾提问，垃圾输出**。

### 举例说明

**简单的提问：**  
> 给我一些能够基于 OpenAI 平台上的创业想法。

**改进后的提问：**  
> 现在你是我的商业顾问，我希望基于 OpenAI 开发一个 B2B SaaS 的创业项目，你需要帮我生成一个商业计划，包括：  
> 1. 创业公司名称，一个很酷且能体现 AI 特点的名字；  
> 2. 一句话描述创业理念；  
> 3. 目标用户群体及用户痛点；  
> 4. 核心价值主张、销售和营销渠道；  
> 5. 收入来源、成本结构；  
> 6. 关键活动、资源、合作伙伴及创意验证步骤；  
> 7. 第一年的运营成本估算；  
> 8. 潜在业务挑战。  
> 将结果汇总到一张表中。

优秀的 Prompt 有两个重要因素：  
1. **使用者对“问题框架”的理解**（可以让 ChatGPT 帮助逐步引导出框架）。  
2. **Prompt 技巧**（本篇文章主要讨论这一点）。

掌握足够的技巧后，你会发现 ChatGPT 能极大地释放生产力。

---

## 三、基础 Prompt 技巧

### 1. 尽量用英文提问

截止到 2025年1月，中文信息在全球互联网的公开内容只占 1.5%，而英文占 56.9%。大部分情况下，用英文提问可以得到更好的结果。

### 2. 通用的 Prompt 模板

根据广为流传的 Prompt 模板，可以使用以下结构：  
> 你是 [角色]，我需要你 [任务]。请根据以下 [条件] 提供 [输出]。

### 3. 间接提问方法

与其直接让 ChatGPT 回答问题，不如让它提供案例。例如：  
> 请给我一个关于苹果的故事的例子。

### 4. 详细描述需求

提供具体的场景和细节。例如：  
> 写一篇关于利用 OpenAI 提升效率对小微企业重要性的博客文章。

### 5. 逐步推导

当 ChatGPT 输出结果不符合预期时，可以分步提问。例如：  
1. 什么是 JavaScript？  
2. 请给我看一个用 JavaScript 制作的应用程序的例子。  
3. 请给我看一个 JavaScript 应用程序，它可以使手机振动三次。

---

## 四、进阶 Prompt 技巧

### 1. 训练 ChatGPT 执行特定任务

通过提供学习条件，让 ChatGPT 在后续对话中执行任务。例如：  
> 微博是一个社交媒体平台，用户可以发表内容。以下是一些积极和消极的例子：  
> 1. 成功地摸鱼一整天，多么美好的一天。（积极）  
> 2. 今天周一，又要面临 5 天悲伤的工作日。（消极）  
> 现在，我将给你不同的微博内容，你只需要回答“积极”或“消极”，无法判断时回复“不确定”。

### 2. 建立工作序列

为 ChatGPT 创建固定的输入和输出项。例如：  
> 现在你是一个在人力资源管理公司中利用邮件进行销售的营销人员。我会提供收件人的 LinkedIn 信息，你需要写一封专业的“陌拜”邮件。

### 3. 结合行业创造用法

例如：  
- 利用 ChatGPT 批量生成 SEO 软文。  
- 爬取电商网站关键词，批量生成文章并导流。

---

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bit.ly/bewildcard)

---

本内容为作者独立观点，不代表平台立场。未经允许不得转载。