# SDGPT-BOT
基于 **[NoneBot2](https://v2.nonebot.dev/)** 
  
 
## 功能

链接 ChatGPT / Bing / Stable-Diffusion  :   
- [x] ChatGPT对话 
- [x] Bing对话
- [x] Stable-Diffusion 文生图  
  > 基于 chatGPT 或 bing 解析自然语言转 Stable-Diffusion 生成图像
- [x] qq 频道支持 
  > qq 频道下 chatGPT bing 的对话会分段发送

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
   
3. 填写好 `config.cfg` 内容
4. 运行 run.bat 或 `nb run`
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
[**SDGPT BOT**](https://github.com/thx114/SDGPT-BOT)  
   
[**NoneBot**](https://v2.nonebot.dev/)  
[**ChatGPT**](https://github.com/acheong08/ChatGPT)  
[**BingGPT**](https://github.com/dice2o/BingGPT)  
[**SD-api**](https://github.com/mix1009/sdwebuiapi)  
