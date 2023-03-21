# EasyChatGPT-API

**note: 该项目所有代码（包括这个README）皆由ChatGPT实现**

项目在线体验地址：http://wangyunjeff.pythonanywhere.com/

**note: 很抱歉，由于开启上下文功能会消耗大量的计算资源，从而耗尽账户余额。因此，我在在线体验网站中已经禁用了上下文功能。但是，在github代码中依旧支持上下文功能。如果你有任何疑问，请随时向我提问。**

用python和flask简单实现调用chatGPT的API，支持上下文回复、latex公式渲染、和代码高亮。

EasyChatGPT-API 是一个使用 [OpenAI GPT-3.5 API](https://openai.com/)（也就是ChatGPT） 实现的简单聊天机器人 。使用 Python 的 Flask 框架编写。

## 安装

1.  克隆仓库到本地

`git clone https://github.com/<YOUR_GITHUB_USERNAME>/EasyChatGPT-API.git` 

2.  进入项目目录

`cd EasyChatGPT-API` 

3.  安装依赖

`pip install flask markupsafe openai markdown` 

4. 在 'app.py' 中设置你自己的 OpenAI APE key

`openai.api_key = 'YOUR_API_KEY'` 

5.  运行项目

`python app.py` 


## API 使用说明

-   `/get_response`：用于获取聊天机器人的回复。需要以 POST 请求发送用户输入，并返回聊天机器人的回复。
-   `/reset`：用于重置聊天历史记录。

## 代码说明

-   `app.py`：Flask 项目主文件，包含了 API 接口的定义和聊天机器人的实现。

## 许可证

EasyChatGPT-API 使用 MIT 许可证。请参阅 [LICENSE](https://chat.openai.com/chat/LICENSE) 文件了解详情。
