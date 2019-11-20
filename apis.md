
##36氪
###获取列表
接口：https://36kr.com/pp/api/aggregation-entity?type=web_latest_article&per_page=10
参数：
```javascript
{
  type:web_latest_article,//应该是H5 倒序最新文章
  per_page:10,//每页条数
  b_id:502685//上一页最后一条数据item_id,首页不传
}
```
