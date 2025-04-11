Ice thickness control with UAS.
========================
#### Main tasks: - Creation and improvement of computer vision systems for detection and analysis of 3D objects in .obj format by point cloud.

<div align="center">
  <img src="https://github.com/Egor4444ik/ice_height_by_lidar/blob/main/ice_images/default_im.png" alt="Пример входного объекта">
  <p><em>Input object exemple</em></p>
</div>

##### - Use of Roboflow platform for visual data management, including collection, annotation and separation of data for training computer vision models.
##### - Development of modules based on OpenCV for semantic segmentation of 3D objects and determination of their physical parameters.
##### - Development of functionality for visualization of semantic segmentation of objects.
##### - Application of YOLOv11 model on user data for training and optimization of the system.

<div align="center">
  <img src="https://github.com/Egor4444ik/ice_height_by_lidar/blob/main/ice_images/seg_im.png" alt="Output object exemple">
  <p><em>Output object exemple</em></p>
</div>

### Firstly u shood run pip install requirements.
***
### Secondly change settings as you need.
***
### Than run:
  1) `python -m lidar_metgod`
  2) `python -m segmentation`
  3) `python -m coloring_obj`
***
If you want look segmented image, run `python -m show_seg_im`

Контроль толщины льда с БАС.
========================
####  Основные задачи: - Создание и улучшение систем компьютерного зрения для обнаружения и анализа 3D объектов в формате .obj по облаку точек.

<div align="center">
  <img src="https://github.com/Egor4444ik/ice_height_by_lidar/blob/main/ice_images/default_im.png" alt="Пример входного объекта">
  <p><em>Пример входного объекта</em></p>
</div>

##### - Использование платформы Roboflow для управления визуальными данными, включая сбор, аннотацию и разделение данных для обучения моделей компьютерного зрения.
##### - Разработка модулей на базе OpenCV для семантической сегментации 3D объектов и определение их физических параметров.
##### - Разработка функционала для визуализации семантической сегментации объектов.
##### - Применение модели YOLOv11 на пользовательских данных для обучения и оптимизации системы.
<div align="center">
  <img src="https://github.com/Egor4444ik/ice_height_by_lidar/blob/main/ice_images/seg_im.png" alt="Пример выходного объекта">
  <p><em>Пример выходного объекта</em></p>
</div>

### 1 шаг: запустить в консоли pip install requirements.
***
### Во-вторых: поменять настройки settings.py, если это необходимо под Вашу задачу.
***
### Затем запустите:
  1) `python -m lidar_metgod`
  2) `python -m segmentation`
  3) `python -m coloring_obj`
***
Если вы хотите посмотреть на сегментацию изображения, запустите `python -m show_seg_im`
