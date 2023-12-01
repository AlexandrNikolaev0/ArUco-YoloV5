# ArUco-YoloV5
Здесь представлены Google Colab ноутбуки, которые позволяют обучить нейросеть YoloV5 на распознавание любых изображений. Примеры работы:

https://www.youtube.com/watch?v=--pSBdoyVjs

https://youtu.be/hxQ5VktzH-I

Для обучения необходимо разметить вручную датасет в формате coco-json (мы делали в remo.ai на 1000 ArUco-маркеров).

Первый ipynb файл `aruco_segmentation.ipynb` позволяет обучить нейросеть MaskRCNN на выполнение сегментации маркера с целью автоматической разметки датасета большего размера. (У нас получилось + >4000 маркеров-аннотаций)

Второй ipynb файл `yolo_aruco_detection.ipynb` позволяет обучить нейросеть Yolo_V5 для выполнения детекции маркера (датасет на ~6000 аннотаций).

Ссылка на датасет:
https://disk.yandex.ru/d/iXrddS-wzvJkAw 
