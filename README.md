	京东图书小爬虫、内涵社区段子小爬虫使用说明：
	1.使用mysql数据库，需修改的地方包括数据库地址、密码等
	2.tb_read.sql为京东图书爬虫对应的数据表
	3.tb_message为内涵社区段子爬虫对应的数据表
	4.爬取地址请根据实际情况更改，因为有时候不一定地址还保持一致
	5.niehan_spider.py，该文件只能爬取刚刚打开的第一页
	6.neihan_spider2.py，该文件伪造了请求headers，且爬取的数据均来ajax请求的json数据，请留意ajax请求格式即可爬取，考虑到内容重复的问题，使用了随机数(10000, 100000)进行爬取1500次，而且最后还用了set来去重


