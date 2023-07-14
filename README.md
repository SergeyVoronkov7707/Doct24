# classification_of_skin_diseases
# Классификация кожных заболеваний заболеваний
### - ссылка на датасет: https://www.kaggle.com/datasets/wanderdust/skin-lesion-analysis-toward-melanoma-detection/code?resource=download
### - Модель классификации определяет вид кожного заболевания с точностью на валидации 90%
### - Лучшая DenseNet201
## 1. base line.ipynb
### base line
## 2. classification_of_skin_diseases.ipynb
### модель DenseNet201
## 3. VGG16_Xception_ResNet50_Classification.ipynb
### - модели VGG16, Xception, ResNet50
## 4. augmentation.ipynb
### Выравнивание целевых классов путём аугментации
## 5. new_data.ipynb
### Плохие данные на вход, плохие на выход
### Проверка Маски, маска должна занимать более указаного процента на картинке
### Отбор изображений к маске, руками в цикле, помогает визуально, более точно найти плохие данные

# Chest_CT_Segmentation
# Сегментация по МРТ сердца, легких, трахеи
### ссылка: https://www.kaggle.com/datasets/polomarco/chest-ct-segmentation
## 1. Read_data.ipynb
### Чтение csv файлов скачаных с датасетом
## 2. DenseNet201_VGG16_ResNet50.ipynb
### Обьеденение предобученых на imagenet сетей DenseNet201, VGG16, ResNet50 в структуру Unet, 
### беру слои нашедшие наиболее глубокие признаки и через конкатенацию обеденяю с UpSampling2D слоями по размеру картинки
### Самописный генератор батчей
## 3. Unet.ipynb
### Обучение сети Unet с аугментацией
### Генератор встройный в TensorFlow
## 4. check mask.ipynb
### Проверка масок, она не должна быть пустой






