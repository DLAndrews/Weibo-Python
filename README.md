# Weibo-Python
---
实现微博自动登录以及依据相关关键词找人或找微博，目前只会显示文本，下一步可以连入数据库存储，或者制作UI。
##使用说明
---
1. Python书写，需要配置requests以及最新的BeautifulSoup；
2. 在代码中前(即以下引用部分)部修改相关参数，分别输入登录的邮箱、登录密码、搜索最大页数、微博搜索关键词、查找微博用户名；
```python
	userNM='YourWeiboMailAddress'
	password = 'YourWeiboPassword'
	pageMaxNum = 20
	Search_Word = 'WORD'
	Search_Persom = 'PersonName'
```
3. 在main函数中可以通过调用和注释相关函数只搜索微博或者只找人；


  
