## Постановка задачи
### Цель
Взять изображение рукописной одиночной цифры и распознать какая это цифра.

### Метрики
Это соревнование оценивается по точности категоризации твоих предсказаний (процент изображений который вы получили правильно).
### Описание набора данных

Файлы данных train.csv и test.csv содержат полутоновые изображения цифр нарисованных от руки от нуля до девяти.

Каждое изображение имеет 28 пикселей в высоту и 28 пикселей в ширину, что составляет 784 пикселя в общей сложности. Каждый пиксель имеет единственное значение, указывающее на светлоту или темноту этого пикселя, причем более высокие числа означают более темный цвет. Это пиксельное значение является целым числом от 0 до 255 включительно.

Набор обучающих данных (train.csv) имеет 785 столбцов. Первый столбец, называемый "label", - это цифра, которую нарисовал пользователь. Остальные столбцы содержат значения пикселей соответствующего изображения.

## Установка (Linux)
1. Клонирование репозитория
    git clone https://github.com/ilay-group/Digit_Recognizer-Kaggle-.git
2. Переход в директорию проекта
```cd Digit_Recognizer-Kaggle-```
3. Создание виртуального окружения
```python3 -m venv venv```
4. Активация виртуального окружения
```source venv/bin/activate```
5. Установка зависимостей
```pip install -r requirements.txt```
6. Работем
