## Хакатон 2023
# Команда "Team Four"
<h1 align="center">Задача: Многоклассовая классификация изображений по небольшому объему данных
  
## Состав команды:
- Светлана Савоськина - Project Manager
- Солодухин Артём - Product Manager
- Артём Дёмкин - сбор данных, оформление документации Github
- Дмитрий Краснов - сбор данных, написание кода программы
- Никита Шишов - сбор данных, оформление Miro, designer

  ## <a href="https://miro.com/app/board/uXjVP2DInDc=/?moveToWidget=3458764543430679377&cot=14" target="_blank">Ссылка на Miro</a>

 ## Идеи для проработки задачи:
1) Подготовка набора данных для отличия мыши от клавиатуры. 
2) Подготовка набора данных для нахождения различий велосипедов и самокатов. 
3) Подготовка набора данных для детектирования сигнала светофора.
  
  ## Выбранная идея для проработки задачи:
Подготовка набора данных для детектирования сигнала светофора.

  ### Состав проекта:
  1) [Ноутбук](https://github.com/svwk/hackathon1/blob/master/DataCropper.ipynb) для предварительной обработки фотографий с целью сегментации светофоров.
  2) [Ноутбук](https://github.com/svwk/hackathon1/blob/master/ml_engineering.ipynb) для распознавания на предварительно обработанных фотографиях цвета сигнала светофора в дневное время: красного, желтого или зеленого с использованием  нейронной сети <a href="https://www.tensorflow.org/api_docs/python/tf/keras/applications/efficientnet_v2/EfficientNetV2B0" target="_blank">EfficientNetV2B0</a>.
  
  **Используемые библиотеки:**
  
- [TensorFlow](https://www.tensorflow.org/).
- [NumPy](https://numpy.org/).
- [Matplotlib](https://matplotlib.org/).
- [Scikit-learn](https://scikit-learn.org/stable/).
  
  **Доля верных ответов на тестовых данных, в процентах:(85%)**
  
**Практическое применение:** развитие идеи решеной задачи может помочь в обучении программы автоматизированного управления транспортным средством или в целях предупреждения водителя транспортного средства.

