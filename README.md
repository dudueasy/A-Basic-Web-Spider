# A Simple Spider Made with Axios & Cheerio
* 使用的工具
axios 发请求
cheerio 解析 HTML 文本

* 数据处理
存储整个 CONTENT_SELECTOR 对应内容区域的 outerHTML

* 配置
需要在.env 文件中定义以下常量: 
~~~
RESOURCE_URL
CONTENT_SELECTOR 
~~~

* 运行程序
~~~
node spider_demo.js
~~~
