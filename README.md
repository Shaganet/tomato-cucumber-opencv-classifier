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

- **1** — The ideal is a clean vegetable on a neutral background, smooth light, no interfering elements.
- **2** — The usual conditions are vegetables on the background, dirt, non—standard shape/color, several objects in the frame, faint shadows or reflections.
- **3** — Extremely uneven background, noise, glare, damaged or partially visible vegetables.

> This enables evaluation of classifier robustness across real-world imaging variations beyond controlled environments.

## 🧪 Dataset statistics

| Class | Quantity | Conditions (1/2/3) |
|------------|------------|------------------|
| Tomato | 12 | 1: 2, 2: 3, 3: 7 |
| Cucumber | 12 | 1: 2, 2: 3, 3: 7 |
| **Total** | **24** | — |

 > Balanced dataset: 12 objects of each class.

