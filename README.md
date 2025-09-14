# 🍅🥒 Tomato vs Cucumber Classifier (OpenCV, No Machine Learning!)


**[GreenOrRed?](GreenOrRed.ipynb)** - A simple color-based classification project for tomatoes and cucumbers using OpenCV.  


## 🖼️ Sample Images

![tomato](images/img_001.jpg)  
*Example of a tomato*

![cucumber](images/img_024.jpg)
*Cucumber example*

## 📊 Data: `labels.csv`

File format:

| filename | label     | conditions |
|---------|-----------|------------|
| img_001.jpg | tomato | 1 |
| img_002.jpg | cucumber | 3 |


### What does `conditions` mean?

These are **shooting conditions** that help analyze the effects of lighting, background, and image quality:

- **1** — good light, clear background
- **2** — low lighting, shadows
- **3** — bright light, possible glare or reflections

 This allows you to check how resistant the algorithm is to various conditions.
