# Jd-Pruchase-Kill-dev
京东茅台抢购最新优化Java版本，京东秒杀，添加误差时间调整，优化了茅台抢购进程队列 . 在程序开始运行后，会检测本地时间与京东服务器时间，输出的差值为本地时间-京东服务器时间，即-50为本地时间比京东服务器时间慢50ms。 本代码的执行的抢购时间以本地电脑/服务器时间为准

# Jd-Pruchase-Kill

### 扫码登陆
 
 Start.class是程序入口
 
 
### 需要设置
 
     商品id pid;
     
     eid = "";
     
     fp = "";

商品id为商品详情url中的一串数字

eid以及fp在订单结算页面 https://trade.jd.com/shopping/order/getOrderInfo.action

F12打开console，输入_JdTdudfp


或者F12打开Sources，添加_JdTdudfp参数



