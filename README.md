# 免費的FRP內網穿透服務

請使用
``` wget http://yang.ddns.net:8000/yangfrp.sh ```
用於獲取安裝軟件 (僅支持Linux)

主要是因為我目前只會用linux版還在學習當中!
~~然後...因為是免費的就別期望太高八!!~~
# 第一步獲取安裝軟件

``` wget http://yang.ddns.net:8000/yangfrp.sh ```

安裝完成後輸入 ```chmod +x yangfrp.sh```

然後後輸入 ```./uangfrp.sh``` 

接者它應該會請你輸入服務器信息
以下為服務器信息

位置:yang.ddns.net

端口:7000

內網端口:請輸入你需要轉發的本地端口

外網端口:請輸入你要使用的外網端口可以到-->[這裡](http://yang.ddns.net:9010) 來選擇自己想要的端口

 完成後請用 
```./frpc -c /frpc.ini```
來啟動服務

剩下怎麼背景運行~~因為我也還在學習就先這樣啦~~




