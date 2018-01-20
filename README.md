# Jd_product
实现能够自定义抓取商品抓取
## 1). 没有实现增量抓取
## 2). 没有处理空值数据
# 实现
## 1). 基于scrapy_redis的分布式抓取
## 2). 数据写入mongodb
## 3). 防止反扒措施：
    1. 自定义user-agent
    2. 自定义中间件
    3. 自定义ip
    4. dowload_delay限制3
    5. DEPTH_LIMIT=3
