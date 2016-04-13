# movie_and_tvshow_spider
可以自动抓取制定网站的美剧下载链接, 然后实现crontab的更新方式, 这样每周都可以定时抓取链接, 然后通过API, 加入到迅雷下载中.

# workflow
## backend
* 使用Node请求并抓取页面, 解析出所对应的URL, 并添加到迅雷下载
* RESTful服务器, 提供API接口进行调用

## front-end
使用Vue.js进行前端绑定, 展示数据, 并提供对应的页面url进行抓取, 设置定时
