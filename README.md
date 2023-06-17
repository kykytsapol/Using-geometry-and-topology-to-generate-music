Целью данной работы было сгенерировать джазовые музыкальные композиции с использованием диаграммы Тоннец и моделей сверточных нейронных сетей и долгой краткосрочной памяти (CNN и LSTM).  Мы использовали архитектуру моделей нейронных сетей и способ представления диаграммы Тоннец в матричном виде предложенные Chuan и Herremans. Мы применили двухслойную сверточный автоэнкодер и трехслойную модель LSTM. Двухслойная сверточная нейронная сеть, была предварительно обучена как автоэнкодер, что сделало возможным модели изучить абстрактное представление для кодирования матицы Тоннец. Затем для генерации новых композиций мы передали закодированные данные модели LSTM.  В результате обучения данных моделей нам удалось сгенерировать новые музыкальные джазовые композиции.
