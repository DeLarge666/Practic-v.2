requirements.txt - файл со всеми библиотеками
команда для запуска:
pip install -r requirements.txt

Нейронная сеть это Математическая модель, а также её программное или аппаратное воплощение, построенная по принципу организации и функционирования биологических нейронных сетей - сетей нервных клеток живого организма. 


состоит из:
1. обучение - сбор данных эти данные называются дата центром. пример открытых дататестов: Marketplace – Google Cloud Platform 
2. тренировка - загрузить дата центр в нейрлсеть и выявление уравнение
3. тест - загружаем новые фотографии и нааблюдение на сколько хорошо распознаёт объекты

flags.DEFINE_string('framework', 'tf', '(tf, tflite, trt')
flags.DEFINE_string('video', './data/video/test.mp4', 'path to input video or set to 0 for webcam')
python object_tracker.py --video 0 --output ./outputs/demo.avi --model yolov4
аргументы командной строки def main(_argv): Первое из скобок - framework название флага
все остальное - это какие значения принимает флаг

Математическая модель, а также её программное или аппаратное воплощение, построенная по принципу организации и функционирования биологических нейронных сетей - сетей нервных клеток живого организма. 

<p>нейросети бывают готовые и их можно обучать</p>
dataset - набор данных. для обучения нужно подготовить данные 
обучение - сбор данных, подготовка датасета
тренировка - обучение на основе датасета. обучение нейросети во время уравнения
тест - загрука нового изображения - наблюдаем, чему нейронная сеть научилась

<p>flags.DEFINE_string('video', './data/video/test.mp4', 'path to input video or set to 0 for webcam')
</p>

 аргументы командной строки передаются в def main(_argv): 
 video - название флага. все, что идет дальше - значения, которые может принимать флаг
 <p>python object_tracker.py —video ./data/video/test.mp4 —output ./outputs/demo.avi —model yolov4</p>
 <p>python object_tracker.py —video ./data/video/test.mp4 —output ./outputs/demo.avi —model yolov4</p>
 <p>python object_tracker.py 0 —output ./outputs/demo.avi —model yolov4</p>

после теста результатом тренировки становится веса(коэфы, параметры, которые можно передавать для дальнейшего обучения)

https://console.cloud.google.com/marketplace/browse?filter=solution-type:dataset&_ga=2.125677512.352426606.1652336646-1703930766.1640669646

существует мнго разных типов данных для хранения большого количества данных
массивы хранят 1 тип данных
список хранит разные типы данных
множество не имеют дубликатов
в нашем случае будет использоваться <b>Множество</b> - \то структура данных, которые содержат неупорядченные элеменеты.

Элемент из множества нужно использовать цикл for m in name
чтобы добавить элемент множества используется функция add name.add("feb")

v = ((x1н, x2н), (x1к, x2к)) - вектор который представляет собой двумерный массив v[0][1] обращение к элементу массив. - первая цифра номер скобки, вторая цифра номер элемента

© 2022 GitHub, Inc.
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
