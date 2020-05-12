# Image main color extraction, iterative realization in k-means hsv
## Installation Environment
```python
pip install -r requirements.txt
```
## Usage

come into `PrimaryColor.py`, then change the image path to yours.

## the blog url (Chinese language)

https://blog.csdn.net/lhh31/article/details/52015500

## main steps, details see the blog

1、获取图像RGB

2、RGB转化成HSV空间值

3、HSV空间下k均值迭代（初始点是根据图像的像素范围来random选择初始点的数值）

4、显示图片（把聚类的hsv值转化为RGB显示出来）

