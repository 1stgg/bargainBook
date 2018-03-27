***
函数：getProductDetail({ id: id ,p_id: p_id})

接口：/Products/detail

|参数|解释|
| ----- | ----- |
|id|商品id|
|p_id|关联父级订单号|

方法：get

描述：获取商品详情

|返回值|解释|
| ----- | ----- |
|data.data.bargainInfo|参与砍价用户的信息|
|data.data.endTime|砍价倒计时结束时间|
|data.data.rank|斩获榜用户的信息|
|data.order.status|订单状态|
|data.prices|砍去价格（bargain_price表）|

跳转： 立即砍价 -> 下一步->[pages/bargain/confirm/index](../bargain/confirm.index.md)
***