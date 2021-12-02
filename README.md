# unicomSign
联通APP签到

1. 填入手机号和服务密码
2. 手机抓包，找到 http://m.client.10010.com/mobileService/customer/getclientconfig.htm?appId=XXX 后面的XXX就是appId
3. pip install -r requirements.txt -t .
4. python index.py
