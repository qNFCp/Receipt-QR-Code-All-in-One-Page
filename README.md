# 支付宝，微信，QQ支付三合一 单HTML页面
##### Alipay,WechatPay,QQpay three in one for HTML
---
没有复杂的套路，仅仅只是一个跳转用的HTML页面

###### 通过UA判断支付宝、微信、QQ访问，然后直接跳转

---
当JavaScript判断为支付宝访问时直接跳转至支付宝收款页面<br>
而微信和QQ因为没有用HTTP(s)协议所以仅仅只是跳转到收款码图片

### 使用
---
将22、24、26行处的链接分别改为对应链接即可<br>
其中支付宝为识别收款码后得出的收款链接<br>
微信和QQ建议为收款码图片

> [blog][1] · GITHUB@[qNFCp][2]


  [1]: https://www.qnfcp.xyz/index.php/archives/81/
  [2]: https://github.com/qNFCp
