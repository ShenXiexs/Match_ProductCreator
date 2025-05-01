### ReadME
- Product_Creator_In_20250407_220618.csv 是有效样本，我将商品信息与达人通过达人id join，共1581个商品，803位达人，包含商品维度和达人维度信息，
- Creator_List.csv 是达人全样本，252112位达人，包含达人维度信息

- 达人维度信息:
  Affiliate GMV, Affiliate LIVE GMV, Affiliate shoppable video GMV, Affiliate product card,
  GMV Affiliate products sold, Items sold, Est. commission, Avg. order value, Affiliate product showcase,
  Affiliate orders, CTR, Product impressions, Avg. affiliate customers, Affiliate LIVEs,
  Affiliate shoppable videos, Target collaboration GMV, Target collaboration est. commission, Open collaboration GMV,
  Open collaboration est. commission, Affiliate refunded GMV, Affiliate items refunded, Affiliate followers, ROI
- 商品维度信息:
  视频标题, 视频时长, 达人粉丝数, 国家/地区, 发布时间, 播放量, 点赞数, 互动率, 该商品销量, 该商品销售额

### 0427 Updated:
- 目前存在问题：1) 改变商品介绍，输出的达人list高度重复；2) 还没有添加预算作为限制
- 进一步改进：<br>
  1 选什么维度的信息聚类？<br>
  2 聚类用什么方法 ？<br>
  3 聚成几类？<br>
  4 预测ROI还是销售额？历史总ROI在达人list已经有了，销售额在商品数据里面

### 0429 Updated:
- Product_Creator 新增商品ID列，便于后续Join
- 上传PicCrawl_OCR_All.json，包含截图OCR数据和商品ID

### 0430 Updated:
- Product_Creator_OCR 处理完OCR数据join出来的完整表格

### 0501 Updated:
- 更新0501v1版本代码
