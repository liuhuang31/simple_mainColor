# Image main color extraction, iterative realization in k-means hsv
## Installation Environment
```python
pip install -r requirements.txt
```
## Usage
come into `PrimaryColor.py`, then change the image path to yours, and run the code.

## Results show
![image](https://github.com/liuhuang31/simple_mainColor/assets/20104208/62b985b5-75dc-4f05-a4ce-c59c8de7cf56)
![image](https://github.com/liuhuang31/simple_mainColor/assets/20104208/f2c402b8-b13f-4639-8dc1-c21b0c749bc0)

## main steps, details see the blog
Blog url (Chinese language) https://blog.csdn.net/lhh31/article/details/52015500
1. Obtain image RGB
2. Convert RGB to HSV spatial values
3. K-means iteration in HSV space (the initial point is randomly selected based on the pixel range of the image)
4. Display image (convert the clustered HSV values to RGB for display)

