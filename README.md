# SimpleAntiOCR
攻击灰度化过程，处理图片让文字和背景的灰度一致; 使用opencv的灰度化公式（也就是通用的加权灰度化算法）；使用jimp处理图片；
Processing the images to make the text and the background have the same grayscale;

# 目前适用范围
背景为浅色的、文字方向水平、除了文字外基本没有干扰项的图片，例如：
+ 电子书截图
+ 长微博

# 测试结果
+ 企鹅的APP识别无结果，ANTI成功；
+ 在线的OCR识别无结果，ANTI成功；
+ 渣浪仍有很大概率被夹，ANTI暂时失败；

# 使用方法
+ 拉取代码后用浏览器打开index.html，上传要处理的图片即可

# 后继优化
+ 自行调整颜色方案
+ 文字转图片
+ 照片类的文本方向校正（不一定会做）
