

## 项目结构

### Main分支（Default）
该分支为主要的开发分支，与项目有关的说明和代码文件可放置于此，在仓库被访问时默认展示该分支。
```
-|
--LICENSE   开源协议文件，默认为MIT开源协议。
--README.md 项目说明文件，可使用Markdowm编辑器进行编辑。
--requirements.txt Python项目依赖列表
```  
# **[PP-YOLOV2保姆级教程]使用自定义数据集实现吸烟识别预测**

## **PP-YOLOV2介绍**

通过结合多项有效的改进，在COCO2017上将PP-YOLO的性能从45.9％mAP提升到49.5％mAP。称之为PP-YOLOv2。

在速度方面，PP-YOLOv2在640x640输入尺寸下以68.9FPS的速度运行。具有TensorRT，FP16精度和Batch=1的Paddle推理引擎进一步提高了PP-YOLOv2的推理速度，达到了106.5 FPS。这样的性能超过了具有大致相同数量的参数（即YOLOv4-CSP，YOLOv5l）的现有目标检测器。此外，带有ResNet101的PP-YOLOv2在COCO2017测试开发上达到了50.3％的mAP。

![](https://ai-studio-static-online.cdn.bcebos.com/9b582f8b16254aa285e03800894fa7f8142620dc61e241838a2ddae7d08ad58c)


## **手把手教你在AIStudio平台上使用PaddleDetection API训练自己的数据集**
**教程目的：** 通过PaddleDetection API熟悉经典的目标检测框架，为下一步自己手写实现目标检测网络打基础

**教程内容：** 以PaddleDetection API中的特色模型为例，介绍网络结构，以及如何使用此框架训练自己的数据集

**数据准备：** 本教程程基于pp_fall数据集，为方便读者体验，已经上传至 data/data94796/pp_smoke.zip。

**PaddelDetection：** 为方便读者体验，存放在PaddleDetection，使用PP-YOLOV2。

**其他说明：** 本教程所有命令均在Notebook中执行。


## **检测效果**

![](https://ai-studio-static-online.cdn.bcebos.com/802e7adbff0c4ddb885711c42ef2cf9fb61d53ed247b423891e7bd4cfb753f55)

