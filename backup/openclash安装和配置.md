[详细安装过程](https://www.youtube.com/watch?v=7wiu1YA8Pbc&t=331s)

- [ ] ui界面在线安装（immortalwrt可以**openwrt不可以**）

1. ![Image](https://github.com/user-attachments/assets/8aa00200-23f4-42b2-969c-309eca817d5e)
2. 软件包处搜索ipset安装（依赖）
其他安装方式（本地安装，SSH安装）链接里有，这里本人没有经验不做演示
# 必不可少
- [ ] **内核安装**，openclash起作用主要是内核，ui只是比较容易用户配置
### **已有**passwall等路由器**翻墙软件**（我没有所以不提供相关经验）原理：**路由器访问GitHub**下载内核
![Image](https://github.com/user-attachments/assets/13b6d2c9-a6f4-4996-a3a0-7acc741044aa)
### 电脑有clash，v2ray等翻墙软件（我的方法）原理：**电脑访问GitHub**下载内核
![Image](https://github.com/user-attachments/assets/c413416c-7b2f-4110-9022-86cdf11dda29)
### 通过上传电脑本地内核文件（通过SSH文件）
### 备用选择（CDN下载）**随缘下载**有延迟则可以下载

![Image](https://github.com/user-attachments/assets/def5375e-7b88-49d7-ad5e-4ba561eb481b)

![Image](https://github.com/user-attachments/assets/345d18f4-b550-4a65-b8e0-c9c41e0b9a9a)
# 设置OpenclashDNS设置
（后记：dnsmasp和openclash配合最好不建议禁用或跳过不使用。配合adguardhome和Fakeip可优化国内网站访问速度）
**问题**：我在配置完DNS优化设置后发现sony电视的ui加载速度不如直连，**推测原因**：分流规则为覆盖到sony电视，导致sony电视ui界面加载走了代理（**待证实**）
