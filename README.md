# Python-openCV边缘检测

利用`python-openCV`的边缘检测`canny`算子写了一个带有`Trackbar`滑块拖动条的边缘检测小工具，用来观察不同阈值(Threshold)情况对边缘检测的影响。

## 文档结构

主程序`cannying.py`；

使用：
```Python
python cannying.py
```
输入图像`src/input1.png`；

## 操作说明

读取待处理图像：

```python
img = cv2.imread("src/input1.png")  #加载图片
```
鼠标拖动条调节阈值效果：

阈值设置范围0-100；

阈值为0时：
![](/imgs/20190902104555.png)

阈值为122时：
![](/imgs/20190902104707.png)
