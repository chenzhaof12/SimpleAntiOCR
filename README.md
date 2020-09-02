# SimpleAntiOCR
攻击灰度化过程，处理图片让文字和背景的灰度一致; 使用opencv的灰度化公式（也就是通用的加权灰度化算法）；使用jimp处理图片；或直接输入文字生成图片
Processing the images to make the text and the background have the same grayscale;

# 目前适用范围
背景为浅色的、文字方向水平、除了文字外基本没有干扰项的图片，例如：
+ 电子书截图
+ 长微博

# 测试结果
+ 企鹅的APP识别无结果，ANTI成功；
+ 在线的OCR识别无结果，ANTI成功；
+ 渣浪上，如有非常敏感的字词，仍会被夹，ANTI暂时失败；

# 使用方法
+ 拉取代码后用浏览器打开index.html，上传要处理的图片即可，可选配色
+ 拉取代码后用浏览器打开text2img.html，输入文字后点击转换即可，可选配色

# 后继优化
+ 自行调整颜色方案（已完成）
+ 文字转图片 （已完成）
+ 文字间隙颜色自主选择
+ 照片类的文本方向校正（不一定会做）
