ThinkPHP+树莓派获取DHT11数据
===============
**项目地址：www.zzhbolg.com/public/admin**
账号 root  密码 123
[![ThinkPHP](https://img.shields.io/badge/Powered_by-Yii_Framework-green.svg?style=flat)](www.thinkphp.cn)
本项目采用的是thinkphp框架，作为一个毕业设计，本应该实现更加完整的功能，但是寒假时间有限，目前正在学习java，
php也不知道会不会放弃，写下这个项目，是根据之前写的众多小demo东拼西凑出来的，但是核心的功能还是有的，硬件
的部分我不太熟悉，引用的是一个dht11传感器的python源码，将其修改后通过python的urllib类以http请求发送数据，
通过一个接口进行接收，在接收到数据之后，我将数据存到数据库中并把数据通过echarts展现出来。

`之后我可能会使用java再重新写一遍这个后端，我感觉我可以的嘿嘿，傲世凤凰，凤凰给我提了一些建议，之后可能通过webscoket再去写一下。。
不过thinkphp下也提供了workman`