# crawl163news
说明 
    1 一个简单的爬虫练手 学到的东西 1 对URL中的部分数据进行获取时，两种方法，字符串切割，正则匹配。推荐正则 
    2 读页面中爬取到的日期数据是字符串类型，利用datetime模块中的datetime.strptime()进行格式转换 
    3 新闻页面中的评价数，点赞数。一般都是从后台数据库中读取到的，一般隐藏在Network的JS中，请求方式使GET,返回的数据类型格式是json。
    对于返回的数据类型是json类型，Preview比Response更好用。Preview可以直接的将数据格式化。 
    4 函数，可以将功能简洁化。
