# Image-segmentation
### 1) Для обучения этой НС был использован датасет Airplanes и размеченный датасет Segment.
![image](https://user-images.githubusercontent.com/108821535/177766128-d3a0fdc1-d19a-4cae-b996-bd81a5d2c6b6.png)
![image](https://user-images.githubusercontent.com/108821535/177766175-db3789f5-3d63-409f-8e56-7affe9b5ab16.png)

### 2) Разрешение изображений было уменьшено с целью экономии ОЗУ.
    
![image](https://user-images.githubusercontent.com/108821535/177766640-4ab6e303-b75a-4c97-85f9-af645cb2d85b.png)

### 3) yTrain (разметку обучающей выборки) перекрасили в цвета по классам

![image](https://user-images.githubusercontent.com/108821535/177769161-3ecf7a24-890f-4812-9dc8-b7e98fd28d32.png)


### 4) Архитектура НС - PSP с одним входным слоем, которая на вход принимает изображение, а на выходе сегментирует его.
![image](https://user-images.githubusercontent.com/108821535/177769351-18d3fffb-d9aa-4473-9a43-1e5c49019b2f.png)

### Спустя 70 эпох НС даёт следующий результат:
![image](https://user-images.githubusercontent.com/108821535/177770409-350eb79e-09ad-41db-9365-a745cac7003b.png)
![image](https://user-images.githubusercontent.com/108821535/177770419-96656ba8-5386-430b-87ea-ab72594d0f64.png)

Слева - сегментированное изображение из базы              
Справа - сегментированное нейронкой изображение
