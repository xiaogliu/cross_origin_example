该仓库存放的是博客[JSONP和CORS实现跨源请求](http://xiaogliu.github.io/2017/10/18/cross-origin-request-using-jsonp-and-cors/)的完整代码。

## 跨源请求失败示例代码

通过浏览器打开 corss_origin_request_fail.html 文件，可以看到跨源错误提示。

> 不同浏览器的跨源安全策略实现方式有差异，上述代码在Chrome（61.0.3163.100）浏览器下测试会报跨源错误，但Safari（10.1.2）浏览器不会报跨源错误，可以正常返回数据。

## 跨源请求成功示例代码

- jsonp

jsonp 目录中放有通过 jsonp 方式进行跨源请求的示例代码，通过浏览器打开 jsonp.html 文件，可以看到数据成功返回。

- CORS

CORS 目录下放有通过 CORS 方法进行跨源请求的示例代码，其中 request 目录下放的是请求源的文件， server 目录下放的是服务源的文件，使用方式参看相应目录下的 readme.md 文件。   
