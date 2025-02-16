# **硬件设备准备**
友善Nano R2S、**8gTF卡、TF卡读卡器**（配套SD卡套）、网线若干
# 硬件连接方式
R2S的lan口与小米AX3000T的lan口相连，小米AX3000T的另一个lan口与电脑网口相连（_十分重要_，**不能R2Slan口和电脑网口直连否则会影响后续设置lan口ip**）使用ipconfig可以看网段登录（我获取到的是192.168.1.X所以我网址输入192.168.1.1可以正常连接至luci界面）
# **软件安装准备**
[格式化软件](https://www.sdcardformatter.com/) [烧录软件](https://etcher.balena.io/#download-etcher)
[immortalwrt选择特定型号的EXT4](https://firmware-selector.immortalwrt.org/)
![Image](https://github.com/user-attachments/assets/b6557949-3d8d-4528-b983-71c477345369)
[刷入系统详细操作](https://www.youtube.com/watch?v=7J_eIJn-vfg&t)
- [刷入系统 ] 
-  1. 将TF卡（嵌入SD转接卡套）插入读卡器内
-  2. 将读卡器插入电脑u盘插口
-  3. 运行格式化软件（sdcardformatter）
![Image](https://github.com/user-attachments/assets/2de12e92-d823-4c4d-998e-60d3932a0d6f)
-  4.运行烧录软件（balena Etcher）
![Image](https://github.com/user-attachments/assets/4a15ea76-144c-449c-bc43-d825a6aa8d67)
-  5.拔出读卡器里的SD卡，插入到R2S的SD读卡槽
##  
 [软件配置进行上网](https://www.youtube.com/watch?v=7wiu1YA8Pbc&t)
# 上网设置(及时保存，每一页离开前都要保存)

![Image](https://github.com/user-attachments/assets/cbb1ae36-b98f-47a9-861e-d66a01436668)

![Image](https://github.com/user-attachments/assets/3a721b5e-5aaa-42ce-8382-3f696aaa35bc)

![Image](https://github.com/user-attachments/assets/b1f73fe0-c986-4638-87df-d9c3b87bbfd7)

![Image](https://github.com/user-attachments/assets/66ba2281-7bf7-42c2-917a-d62ec9550982)
保存并应用，选择更改（90s未登录还原luci登录地址192.168.1.1）用192.168.31.8登录luci界面
## 配置好后概览处eth1（lan口）有ipv4地址临时性DNS114.114.114.114。上网成功！
