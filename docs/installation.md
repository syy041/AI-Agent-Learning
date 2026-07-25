# 安裝流程
本文件說明如何建立Hermes AI Agent環境，
包含Hermes安裝、OpenRouter API、Telegram串接和Telegram Bot建立。
## 1.安裝Hermes
到官網下載，可以看到安裝頁面:

![安裝Hermes](../images/Hermes.png)
## 2.建立OpenRouter API 
OpenRouter作為LLM API Gateway，
讓Hermes可以連接不同的大型語言模型。

操作流程：
1. 建立 OpenRouter 帳戶
2. 建立 API Key
3. 將 API Key 提供給 Hermes 使用
可以看到建立頁面:

![建立API](../images/OpenRouter-API.png)
## 3.串接OpenRouter
打開電腦終端機，輸入hermes model，選擇OpenRouter，並輸入API Key，
完成Hermes與OPpenRouter串接。

![串接OpenRouter](../images/OpenRouter.png)
## 4.串接Telegram
終端機輸入hermes gateway setup，選擇telegram。
透過 Telegram Gateway，
讓使用者可以透過 Telegram 與 AI Agent 互動。

![串接Telegram](../images/Telegram.png)
## 5.建立Telegram Bot
到telegram設定機器人名字、帳號名稱。

![建立Bot](../images/Telegram-Bot.png)
