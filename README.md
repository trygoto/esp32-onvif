# esp32-onvif

ONVIF Device Manager 测试图像

<img src="https://user-images.githubusercontent.com/18089130/213913959-f33a078f-987c-464d-baec-c32be6681e4a.PNG" width="70%">


此固件支持 ESP32CAM 模块

<img src="https://user-images.githubusercontent.com/18089130/213914444-fcc73b80-f484-4520-9ecc-93c1861e6d12.jpg" width="20%">

# ⚙️ 特点
- 支持onvif协议。
- 支持RTSP协议。
- 支持800x600分辨率视频流。
- 支持网页配置WiFi账号密码。

# 💡 onvif、RTSP账号和密码为：admin


# 📲 如何设置WiFi账号密码
1，将ESP32CAM模块的IO2引脚连接GND，模块重新上电，将会看到一个名字为trytogo的WiFi热点
连接该热点，在浏览器地址栏输入192.168.4.1，设置你要连接到的WiFi热点。

<img src="https://user-images.githubusercontent.com/18089130/213914841-aeb7aad4-4944-4c32-9092-ddab71790848.jpg" width="20%">
<img src="https://user-images.githubusercontent.com/18089130/213914850-ca4137c8-0514-4a81-a352-36c08ef752a3.jpg" width="20%">


2，将IO2引脚和GND引脚断开连接，模块从新上电完成设置。


# 💡 如何录制视频和使用视频报警提醒
使用符合ONVIF协议的视频客户端即可
windows的话这里推荐一个免费支持ONVIF协议的客户端，iSpy是目前能找的最好的开源视频监控软件，支持中文哦,官网链接 https://www.ispyconnect.com/

1，打开iSpy，添加ONVIF相机

<img src="https://user-images.githubusercontent.com/18089130/213915412-e16f62f8-cf31-48a2-bcb0-3dd0c3c5fff3.PNG" width="70%">


2，添加ONVIF相机，软件会自动找到符合ONVIF协议的相机，输入账号和密码,都是admin,点击下一页即可完成配置。

<img src="https://user-images.githubusercontent.com/18089130/213915717-ee554832-efe1-4ca6-b07a-c26a962d525c.PNG" width="70%">


Mac OS推荐使用IPCams

<img src="https://user-images.githubusercontent.com/18089130/213931394-ddeb7eb5-1f30-4313-9a41-98170169147b.png" width="70%">

<img src="https://user-images.githubusercontent.com/18089130/213931400-89373d45-ebd6-4331-9b1c-724ce33ba233.png" width="70%">

<img src="https://user-images.githubusercontent.com/18089130/213931408-1f837ea4-9ab7-4888-8fd8-c50ad9f566a3.png" width="70%">



提示：需要使用5V电源供电，不要使用电脑USB口供电（使用电脑USB口供电有花纹）

<img src="https://user-images.githubusercontent.com/18089130/213933426-13ed214f-f8ab-4ff2-8f55-823cb276561c.jpg" width="20%">





