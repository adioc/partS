**AVIF（ AV1 Image File Format）是一种由AOM（ Alliance for Open Media）开发的基于AV1编解码器的网络图像格式，这是一种开源免版税的图像格式。AVIF支持全分辨率的10位和12位色彩以及HDR。
它可以使用无损或有损压缩来存储带有“.avif”文件扩展名的静止图像和动画图像 。新的图像格式拥有比JPEG更好的图像质量和更小的文件大小，更少的压缩伪影和更少的图像阻塞。**

使用两步转换：

1. 视频转为y4m格式

使用  mp4_to_avif.sh .\待转换.mp4  

2.  y4m格式转为avif

使用 avifenc.exe  .\output.y4m
