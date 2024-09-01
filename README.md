# Ryles-Streamlabs-RVC-TTS

Requirements:

  This Project https://github.com/samfisherirl/Ryles-Streamlabs-RVC-TTS/releases
  
  RVC Studio (direct download links)
  
-  Nvidia:
    https://huggingface.co/lj1995/VoiceConversionWebUI/resolve/main/RVC1006Nvidia.7z 
-  Intel/AMD:
    https://huggingface.co/lj1995/VoiceConversionWebUI/resolve/main/RVC1006AMD_Intel.7z
  - Socket Token:
    https://streamlabs.com/dashboard#/settings/api-settings

1) get a socket_token
https://streamlabs.com/dashboard#/settings/api-settings
2)  launch bat file and press 1 to set commands

3) define .env file
```env

TOKEN='{this_is_the_alert_box_url}'
SOCKET_TOKEN='{.self}'
```
5) back to menu, click 2 for launch

6) open volume mixer, when you look at apps, there will be "python" or "webview" or "edge" (with denotation for webview) or "chrome" (with denotation for webview) ->  
set output to go to desired Cable-{}. 


7) TESTING will set random voices, you cannot customize the TTS test message. By default, the delimiter is "|" for user commands via tts. the listener window will print the model chosen prior to audio playing.
________________

example command: 

```tomfoolery```

example user donation:

```|tomfoolery| hi im tom```



example command: 

```tf```

example user donation:

```|tf| hi Im tom```
________________



8) Use Streamlabs Tipping Alertbox Test https://streamlabs.com/dashboard#/alertbox/general/tipping. Update the message delay for TTS under Message Template (set message template enable) and add 5s to text delay.

9) For the Browser Alert Box, to reduce resources, you can use the provided Browser window and capture with a chroma/color key (white background).


- the commands are set by launching the bat file and selecting 1

![image](https://github.com/user-attachments/assets/79f6f47f-2125-43c3-ab2e-74862ed8966e)
