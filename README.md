# SDGPT-BOT
基于 **[NoneBot2](https://v2.nonebot.dev/)** 
  
 
 本机器人为一键式,插件中包含了cqhttp,直接运行机器人,会自带qq实例

## 功能

链接 ChatGPT / Bing / Poe / Stable-Diffusion  :   
- [x] ChatGPT 对话 
- [x] Bing 对话
- [x] Poe 对话
- [x] Stable-Diffusion 文生图  
  > 基于 chatGPT 或 bing 解析自然语言转 Stable-Diffusion 生成图像
- [x] qq 频道支持 
  > qq 频道下 chatGPT bing 的对话会分段发送
- [x] 预设切换
- [x] 自定义预设
- [x] 切换模型
- [x] 详细的指令配置

**指令与功能**: [***SDGPT-CommandAndFunction***](https://github.com/thx114/SDGPT/wiki/%E6%8C%87%E4%BB%A4-%E4%B8%8E-%E5%8A%9F%E8%83%BD)
## 使用
1. ```
   git clone https://github.com/thx114/SDGPT-BOT.git
2. ```
   pip install -r requirements.txt
   ```
    ```
   pip install nonebot-plugin-SDGPT --upgrade
   ```
   ```
   python -m pip install --user pipx
   ```
   ```
   pipx install nb-cli
   ```
   
3. 运行 run.bat 或 `nb run`
4. 关闭，修改 config.cfg
5. 打开日志提示中的gocqhttp链接:   
   一般为 http://127.0.0.1:8080/go-cqhttp/
6. `添加账号` > ( 登录设备最好选 ipad 或 MacOS )
7. 启动

## Stable-Diffusion 配置:
--server-name 127.0.0.1 --port 7860 --api

## 单独插件 
如果你想以NoneBot的插件形式安装:
[***SDGPT***](https://github.com/thx114/SDGPT)

## more

[**QQ 群 391517834**](https://jq.qq.com/?_wv=1027&k=eKsgovej)  
[**SDGPT**](https://github.com/thx114/SDGPT)  
   
[**NoneBot**](https://v2.nonebot.dev/)  
[**ChatGPT**](https://github.com/acheong08/ChatGPT)  
[**EdgeGPT**](https://github.com/acheong08/EdgeGPT)  
[**SD-api**](https://github.com/mix1009/sdwebuiapi)  
