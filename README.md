# awesome_chatgpt_ch


## 开源项目

chatgpt 发布三个多月以来，github 上相关的项目可谓爆发，连续几个月的 trending 项目都是相关主题，有些项目甚至刚发布没几天，就被顶到了上万个 star，不能不说空前火热。这里我们就简要总结一下 github 上最火热的一些项目，我把这些项目分成几个类型，以便大家根据自己的兴趣进行更深入的了解。

| 项目 | ★  数量 | 类型 | 简介 |
|:----|:----|:----|:----|
| [f/awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) | 36.6k | 使用指导类 | 这个项目主要是教大家如何调教 chatgpt（后面笔者也会单独出一篇这个主题的博客）, 这些调教方式大部分可以总结为一个主题：扮演类，即让 chatgpt 扮演某个角色比如英语教师，诗人，医生，甚至是 linux 命令行工具 (见下面 <一个有趣的知识点>)，从而在对话中分享 chatgpt 拥有的相关知识。这个项目的中文对应版本是 [PlexPt/awesome-chatgpt-prompts-zh](https://github.com/PlexPt/awesome-chatgpt-prompts-zh)。另外还有一个 中文项目很值得推荐 [howl-anderson/unlocking-the-power-of-llms](https://github.com/howl-anderson/unlocking-the-power-of-llms) 这个项目介绍了更多使用 chatgpt 的技巧。另外 [phodal/ai-research](https://github.com/phodal/ai-research) 介绍了 prompt 的使用技巧，虽然不是特别针对 chatgpt，不过也值得一读。另外甚至有一个中文网站专门提供各种 prompt，可以看看[这里](https://newzone.top/chatgpt/) |
| [acheong08 / ChatGPT](https://github.com/acheong08/ChatGPT) | 19.9k | library/sdk 类 | 这个一个 ChatGPT api 的 python 库（也带简单的命令行），这个项目之所以这么火爆，最大的原因 "Reverse engineered ChatGPT API", 它是模拟用户在 chatgpt 网页的登录状态来访问 chatgpt，虽然目前这个项目也更新带了官方 api 的版本，但是毕竟官方 api 是收费的，所以预期这个项目在网页用户能免费访问的情况下，会一直存在。（项目作者还有另外一个针对 newbin api 的项目 [acheong08/EdgeGPT](https://github.com/acheong08/EdgeGPT) 也值得关注）笔者也有一个类似的 go 项目，翻译了其中的登录逻辑，可以参考 [u2takey/chatgpt-go](https://github.com/u2takey/chatgpt-go)。 |
| [lencx / ChatGPT](https://github.com/lencx/ChatGPT) | 19.4k | 客户端/网页应用类 | 应该是 chatgpt 最好用的客户端工具了，他的特点是 好看，好用，多平台支持，有主题可以换，可以设置界面，可以将内容导出为图片，md，pdf；甚至他还提供了很多 prompt 的快捷输入，比如在 [f/awesome-chatgpt-prompts](https://github.com/f/awesome-chatgpt-prompts) 中介绍的大部分 prompt 在这个客户端都有快捷输入，非常好用 ![image.png](https://p-bytetech.bytedance.net/tos-cn-i-vz0z6vmpra/d2464c06c9ba42da90ef4c630d655f41~tplv-vz0z6vmpra-image.image)|
| [LAION-AI / Open-Assistant](https://github.com/LAION-AI/Open-Assistant) | 17.7k | 竞品类 | 这其实并不是一个 chatgpt 项目，但是搜索 chatgpt，你一定会看到这个项目。这个项目开源的时候和 chatgpt 发布的时间差不多，目的方式都很类似，虽然目前和 chatgpt 还有很大差距，但是重要的是：它是完全开源的 (代码和模型都基于 Apache License 2.0 协议开源，训练数据也会开源)。  |
| [wong2 / chatgpt-google-extension](https://github.com/wong2/chatgpt-google-extension) | 11.2k | 插件类 | 一个蛮好用的 google 插件，在 google 搜索的同时帮你访问 chatgpt 同时显示 chatgpt 的结果。效果是这样：![image.png](https://p-bytetech.bytedance.net/tos-cn-i-vz0z6vmpra/0a28c916c44a4267829fa39d1de5349a~tplv-vz0z6vmpra-image.image) 国内码农开发，目前项目状态是："被收购，不再更新代码"，预期插件还会持续更新，只是不再开源了。其他类似的 chrome 插件还有： [Chrome extension to access ChatGPT as a popup on any page](https://github.com/kazuki-sf/ChatGPT_Extension)； [Extension to add share abilities to ChatGPT (PDF, PNG or a sharable link](https://github.com/liady/ChatGPT-pdf)； [Chrome extension to add input history, copy, and counters to ChatGPT](https://chrome.google.com/webstore/detail/superpower-chatgpt/amhmeenmapldpjdedekalnfifgnpfnkc); [ChassistantGPT - embeds ChatGPT as a hands-free voice assistant in the background](https://github.com/idosal/assistant-chat-gpt)； [WebChatGPT - augment your prompts to ChatGPT with web search results](https://github.com/qunash/chatgpt-advanced/)； [Talk to ChatGPT (voice interface)](https://github.com/C-Nedelcu/talk-to-chatgpt) |
| [transitive-bullshit / chatgpt-api](https://github.com/transitive-bullshit/chatgpt-api) | 10.2k | library/sdk 类 | [acheong08 / ChatGPT](https://github.com/acheong08/ChatGPT) 项目的 js 版本，同样也提供了两种 api：模拟登录和官方 openapi |
| [deepset-ai/haystack](https://github.com/deepset-ai/haystack) | 7.1k | 竞品类 | 你可以 haystack 是一个可以让你私有化部署类似 chatgpt 模型、Pipeline 的工程工具。使用他可以部署 如 GPT-3 之类的模型，从指定的数据中提取信息，构建属于自己的检索或者问答系统。（来自 chatgpt 的回答：Farm和Haystack是两个独立的项目，但它们都是在NLP领域中用于文本处理和信息检索的工具。Farm（FastAPI for Repeated Models）是一个基于PyTorch的开源框架，可帮助用户快速训练和部署NLP模型，例如文本分类、命名实体识别和语义搜索等任务。Haystack是一个基于Python的框架，提供了一组简单易用的API，使得用户可以快速建立一个端到端的文本搜索引擎，并实现各种复杂的信息检索任务，例如文本分类、语义搜索和问答系统等。因为Farm和Haystack都是在NLP领域中使用的工具，所以它们经常被一起使用，从而形成了Farm-Haystack这样的组合。在这种情况下，Farm用于训练和部署NLP模型，而Haystack则用于构建和部署文本搜索引擎，将这两个工具结合起来，可以实现各种NLP和信息检索任务，例如自然语言问答和智能客服等。）  |
| [humanloop / awesome-chatgpt](https://github.com/humanloop/awesome-chatgpt) | 5.5k | 使用指导类 | 和本文一样，也和你知道的大部分 awesome xxx 项目一样，这是一个 chatgpt 相关 项目收集的项目，本文也参考了其中的部分内容 |
| [vincelwt / chatgpt-mac](https://github.com/vincelwt/chatgpt-mac) | 4.4k | 客户端/网页应用类 | 另一个 chatgpt 的 mac 应用，特点是简洁，完全没有多余的功能，看着非常舒服 |
| [zhayujie/chatgpt-on-wechat)](https://github.com/zhayujie/chatgpt-on-wechat) | 4.2 k | bot 类 | 基于ChatGPT的微信聊天机器人，通过 ChatGPT 接口生成对话内容，使用 itchat 实现微信消息的接收和自动回复。其他类似的项目还有：[另一个微信机器人 wangrongding/wechat-bot](https://github.com/wangrongding/wechat-bot)； [Serverless Telegram bot](https://github.com/franalgaba/chatgpt-telegram-bot-serverless)；[WhatsApp bot1](https://github.com/danielgross/whatsapp-gpt)；[WhatsApp bot2](https://github.com/askrella/whatsapp-chatgpt); [RayCast Extension (unofficial)](https://github.com/abielzulio/chatgpt-raycast)；[VSCode extension](https://github.com/mpociot/chatgpt-vscode) ([demo](https://twitter.com/marcelpociot/status/1599180144551526400))；[Go Telegram bot](https://github.com/m1guelpf/chatgpt-telegram)；[Twitter Bot](https://github.com/transitive-bullshit/chatgpt-twitter-bot) powered by ChatGPT；[Chrome extension](https://github.com/kazuki-sf/ChatGPT_Extension)；[Google docs](https://github.com/cesarhuret/docGPT)；[Mac menubar app](https://github.com/vincelwt/chatgpt-mac)；[Multi-platform desktop app (Windows, Mac, Linux)](https://github.com/lencx/ChatGPT) powered by ChatGPT & Tauri；[Windows, Mac, Linux desktop app](https://github.com/sonnylazuardi/chatgpt-desktop)；[Jetbrains IDEs plugin](https://github.com/LiLittleCat/intellij-chatgpt)；[ChatGPT for Slack Bot](https://github.com/pedrorito/ChatGPTSlackBot)；[ChatGPT for Discord Bot](https://github.com/m1guelpf/chatgpt-discord)；[QQ bot](https://github.com/lss233/chatgpt-mirai-qq-bot) |
| [wukong-robot](https://github.com/wzpan/wukong-robot) | 3.9k | 插件类 | 这不是一个专门针对 chatgpt 开发的插件，不过如果你想把 chatgpt 变成你的音对话机器人/智能音箱背后支撑，这个项目是一个很好的起点 |




> 一个有趣的知识点：让 chatgpt 扮演 linux 命令行工具，他会真的运行一个命令行工具吗，还是仅仅用它的知识在扮演。这一点其实让一般人很难分辨，因为它的输出实在太真实了，linux 上常见的命令他都能返回符合预期的输出。是不是 chatgpt 真的在一个隔离环境，比如 docker 中运行了一个 linux terminal 呢。目前看，chatgpt 还是仅仅用它的知识在扮演，一个验证方式是 让 chatgpt 使用 curl、ping 等类似的工具，在目的地址看，chatgpt 并没有发出请求（虽然 chatgpt 的输出真的像在请求）。

## 其他相关

> 相关的 AI 工具，或者 AI 工具收录站、导航站；仍在收集更新中，欢迎推荐

- [人工智能工具目录，几乎包括现有所有 AI 工具](https://www.futurepedia.io/)
- [Best AI Tools：大量 AI 工具汇总](https://www.creaitives.com/tools)
- [AI ToolHunt 另一个 AI 工具汇总站](https://www.aitoolhunt.com/?sort_by=likes)
- [All Things AI: 也是一个 AI 工具导航](https://allthingsai.com/)
- [自媒体家园：国内网站，也收录了很多 AI 工具或者导航站，很不错](https://www.zmthome.com/#term-2250)； 
- [AI 导航网，也是一个国内站，挺不错的](https://www.ainav.cn/) 这个类型的网站还有好几个，比如 [17yongai](https://17yongai.com/)；[aigclist](http://aigclist.com/) 等等

## 中文工具

> 收集国内可使用的 公众号、程序、网页应用或 app；仍在收集更新中，欢迎推荐

- 网页应用 [https://chinagpts.com](https://chinagpts.com)，无需翻墙，每日免费五次问答。
- 网页应用[chatgpt.ddiu.me](https://chatgpt.ddiu.me/) 基于 openapi，支持会话，页面简洁清晰，免费
- 网页应用[icchat](https://www.infinigo.com/icchat?source=DSLG) 基于 openapi，不支持会话，页面有广告，免费

## 媒体学习资源

> 收集相关的教程、视频、公众号 等等；仍在收集更新中，欢迎推荐

- [一个B 站ChatGPT视频合集](https://b23.tv/REx0FMq)
- [一个蛮不错的博主 ChatGPT 相关抖音视频合集](https://v.douyin.com/SSoux4P/)