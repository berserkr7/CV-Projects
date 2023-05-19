# Проекты по обработке изображений (Computer Vision)


| Проект       | Описание                | Примечания |
| ------------- |:------------------:| -----:|
| 01. [Fruits Recognition using CNN](https://github.com/berserkr7/CV-Projects/tree/main/Fruits%20Recognition)     |  Необходимо решить задачу распознавания изображения. Всего 131 класс. Необходимо построить модель, которая будет иметь метрику accuracy > 97% | TensorFlow, Keras, ImageDataGenerator from dataframe, Аугментация данных, CNN  | 
| 02. [Classification using Transfer Learning](https://github.com/berserkr7/CV-Projects/tree/main/Transfer-Learning)     |  Необходимо решить задачу классификации изображений - кошек и собак. В нашем распоряжении имеется датасет кошек и собак. Необходимо построить модель, которая будет иметь метрику accuracy > 90%, применив технику Transfer Learning на ResNet 50 |  Transfer Learning на ResNet 50;  Создание класса Custom Dataset; Аугментация данных; torch, cv2| 
| 03. [Implementention VGG16](https://github.com/berserkr7/CV-Projects/tree/main/VGG) |  Необходимо реализовать архитектуру глубокой нейронной сети VGG16 на PyTorch |  PyTorch; Создание собственного класса VGG16; Описание и особенности архитектуры| 
| 04. [Предсказание возраста человека по фотографии](https://github.com/berserkr7/CV-Projects/tree/main/Age-prediction-CV)     |  Необходимо решить задачу предсказания возраста человека по его фотографии. В нашем распоряжении имеется датасет из 7500 лиц. Необходимо построить нейронную сеть, которая будет иметь метрику MAE < 7 на test. Обучать модели будем на Tesla V100 на 30 эпохах, с динамическим изменением Learning Rate. В качестве архитектуры возьмем Residual Network (ResNet50) |  tensorflow, keras, sklearn, cv2, os; Полный разбор архитектуры ResNet50; Динамическое изменение LR (LearningRateScheduler); Использование Dropout и Batchnorm; Аугментация данных| 



