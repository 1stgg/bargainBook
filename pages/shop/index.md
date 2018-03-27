***
函数：getProducts(params)

接口：/Products/product

|参数|解释|
| ----- | ----- |
|p|第几页|
|limit|每页上限条数|
|recommend|是否为推荐|

方法：get

描述：获取首页列表商品信息

|返回值|解释|
| ----- | ----- |
|data.items[n].bargain_date|砍价倒计时结束时间|
|data.items[n].bargainInfo.headimgurl|最后砍价成功者的头像|

跳转： 点击商品->[pages/shop/bargain/detail](bargain.detail.md)
***