文件挂载：
  ![img](openai-11.png)

- `/app/config.json`（必需）：环境参数配置文件，你可以在环境中配置环境参数，推荐挂载，这样方便更改。记得把openai api key 和 OPEN_AI_API_BASE 修改成自己的。
- `/app/plugins/config.json`（按需）: 密码随意设，微信号填你大号的微信号，而不是你扫码的
- `/app/voice/openai/openai_voice.py`（按需）:需要语音的话加
- `/app/plugins/godcmd/godcmd.py`（按需）:更丰富的 help 指令
- `/app/channel/chat_channel.py`（不建议）:每条文字都转换条语音
